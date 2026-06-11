# 🤖 AI Prompt Engineering Pack

**50+ Curated Prompts for Coding, Business, Writing, AI & Crypto**

---

## 📖 How to Use This Pack

Each prompt is designed to be **copy-paste ready**. Just replace the `[PLACEHOLDERS]` with your specific details and send it to ChatGPT, Claude, or any AI assistant.

### Quick Start
1. Pick a category that matches your need
2. Find a prompt that fits your task
3. Replace `[BRACKETS]` with your details
4. Copy → Paste → Get results

### Difficulty Levels
- 🟢 **Beginner** — Just fill in the basics
- 🟡 **Intermediate** — Requires some domain knowledge
- 🔴 **Advanced** — Needs specific technical input

---

## 💻 Coding & Development

### code-001: Full-Stack App Generator
**Difficulty:** 🔴 Advanced

Generate a complete full-stack application with best practices.

**When to use:** Starting a new project from scratch.

```
You are a senior full-stack developer. Build a complete [APP_TYPE] application with:
- Frontend: [FRAMEWORK] with responsive design
- Backend: [BACKEND_FRAMEWORK] with REST API
- Database: [DATABASE] with proper schema
- Authentication: JWT with refresh tokens
- Error handling, validation, and logging
- Docker setup for deployment
- Unit tests with >80% coverage

Provide the complete project structure, all source files, and deployment instructions. Follow clean architecture principles and SOLID design patterns.
```

---

### code-002: Bug Hunter & Fixer
**Difficulty:** 🟡 Intermediate

Analyze code for bugs, security vulnerabilities, and performance issues.

**When to use:** Code review, debugging, or pre-deployment check.

```
You are an expert debug agent. Analyze the following code for bugs, security vulnerabilities, performance issues, and code smells:

```
[PASTE CODE HERE]
```

For each issue found:
1. Category (bug/security/performance/code-smell)
2. Severity (critical/high/medium/low)
3. Explanation of the issue
4. Fixed code snippet
5. Prevention tips

Also suggest refactoring opportunities to improve maintainability.
```

---

### code-003: API Documentation Writer
**Difficulty:** 🟡 Intermediate

Generate comprehensive API documentation.

**When to use:** Documenting APIs for developers.

```
You are a technical writer specializing in API documentation. Create comprehensive documentation for the following API endpoints:

[PASTE ENDPOINTS/SPEC HERE]

Include:
1. Overview and authentication guide
2. Each endpoint with: method, URL, headers, request body, response examples (success + error)
3. Rate limiting info
4. SDK examples in Python, JavaScript, and cURL
5. Changelog format
6. OpenAPI 3.0 spec

Write in clear, developer-friendly language. Use consistent formatting throughout.
```

---

### code-004: Database Schema Designer
**Difficulty:** 🔴 Advanced

Design optimized database schemas.

**When to use:** Planning a new database or redesigning an existing one.

```
You are a database architect. Design an optimized database schema for [PROJECT_DESCRIPTION] with the following requirements:
- [REQUIREMENT_1]
- [REQUIREMENT_2]
- [REQUIREMENT_N]

Provide:
1. ERD (Entity Relationship Diagram) in Mermaid.js format
2. Complete SQL CREATE TABLE statements with proper constraints, indexes, and foreign keys
3. Migration scripts (up + down) for [FRAMEWORK]
4. Seed data script with realistic sample data
5. Query optimization notes for the most common operations
6. Estimated table sizes and partitioning strategy if needed

Optimize for: read-heavy workload, ACID compliance, and future scalability.
```

---

### code-005: Code Refactor Pro
**Difficulty:** 🟡 Intermediate

Refactor messy code into clean, maintainable code.

**When to use:** Cleaning up legacy code or improving code quality.

```
You are a code refactoring specialist. Take the following code and refactor it following best practices:

```
[PASTE CODE HERE]
```

Apply these principles:
1. SOLID design principles
2. DRY (Don't Repeat Yourself)
3. Meaningful naming conventions
4. Proper error handling
5. Type safety (add TypeScript types if JS)
6. Extract reusable utilities
7. Add JSDoc/docstrings
8. Reduce cognitive complexity

Show the before/after comparison and explain each refactoring decision. Ensure the refactored code maintains the same functionality while being more maintainable and testable.
```

---

### code-006: Test Suite Generator
**Difficulty:** 🟡 Intermediate

Generate comprehensive test suites.

**When to use:** Writing tests for existing code.

```
You are a QA engineer specializing in test automation. Generate a comprehensive test suite for the following code:

```
[PASTE CODE HERE]
```

Create tests using [TESTING_FRAMEWORK] that cover:
1. Unit tests for all functions/methods (happy path + edge cases)
2. Integration tests for API endpoints
3. Error handling tests (invalid inputs, network failures, timeouts)
4. Boundary value analysis
5. Security tests (SQL injection, XSS, CSRF)
6. Performance benchmarks

Follow AAA pattern (Arrange, Act, Assert). Use descriptive test names. Aim for >90% code coverage. Include setup/teardown helpers and mock factories.
```

---

### code-007: DevOps Pipeline Builder
**Difficulty:** 🔴 Advanced

Create CI/CD pipelines and infrastructure configs.

**When to use:** Setting up deployment automation.

```
You are a DevOps engineer. Create a complete CI/CD pipeline and infrastructure setup for [PROJECT_TYPE] using [CLOUD_PROVIDER]:

1. CI/CD Pipeline (GitHub Actions / GitLab CI)
   - Build stage with caching
   - Test stage with parallel jobs
   - Security scanning (SAST + dependency check)
   - Deploy to staging/production
   - Rollback strategy

2. Infrastructure as Code (Terraform)
   - VPC, subnets, security groups
   - Compute (containers/VMs)
   - Database with replication
   - CDN and load balancer

3. Monitoring & Alerting (Prometheus + Grafana)
4. Secrets management
5. Cost estimation

Include all config files and README with setup instructions.
```

---

### code-008: Security Audit Checklist
**Difficulty:** 🔴 Advanced

Comprehensive security review for any codebase.

**When to use:** Security audit, penetration test prep, or compliance review.

```
You are a cybersecurity auditor. Perform a thorough security audit of the following codebase/config:

```
[PASTE CODE/CONFIG HERE]
```

Check against OWASP Top 10 and CWE Top 25:
1. Injection vulnerabilities (SQL, NoSQL, Command, LDAP)
2. Broken Authentication & Session Management
3. Sensitive Data Exposure
4. XML External Entities (XXE)
5. Broken Access Control
6. Security Misconfiguration
7. Cross-Site Scripting (XSS)
8. Insecure Deserialization
9. Using Components with Known Vulnerabilities
10. Insufficient Logging & Monitoring

For each finding: severity, description, proof of concept, remediation, and reference links.

Provide a risk score (1-10) and prioritized fix list.
```

---

### code-009: Regex Master Builder
**Difficulty:** 🟢 Beginner

Build and explain complex regex patterns.

**When to use:** When you need a regex for validation, parsing, or extraction.

```
You are a regex expert. Create a regular expression pattern for [MATCH_DESCRIPTION] with these requirements:
- Must match: [EXAMPLES_OF_VALID]
- Must NOT match: [EXAMPLES_OF_INVALID]
- Edge cases: [EDGE_CASES]

Provide:
1. The regex pattern (with flags if needed)
2. Step-by-step explanation of each part
3. Visual breakdown (regex101 style)
4. Test cases (10 valid + 10 invalid)
5. Performance considerations (catastrophic backtracking check)
6. Optimized version if applicable
7. Implementation in Python, JavaScript, and Go
8. Common pitfalls to avoid
```

---

### code-010: TypeScript Type Wizard
**Difficulty:** 🟡 Intermediate

Convert JavaScript to TypeScript with proper types.

**When to use:** Migrating JS projects to TypeScript.

```
You are a TypeScript expert. Convert the following JavaScript code to TypeScript with maximum type safety:

```javascript
[PASTE JS CODE HERE]
```

Apply:
1. Strict type annotations for all variables, parameters, and returns
2. Generic types where appropriate
3. Discriminated unions for state management
4. Utility types (Partial, Required, Pick, Omit) where useful
5. Type guards and type narrowing
6. Interface definitions for all data structures
7. Enum types for constants
8. Branded types for domain primitives
9. Proper module declarations
10. tsconfig.json with strict mode

Explain each type decision. Ensure zero `any` types. Add JSDoc comments for public APIs.
```

---

## 📊 Business & Strategy

### biz-001: Business Model Canvas Generator
**Difficulty:** 🟡 Intermediate

Create a complete business model canvas for any idea.

```
You are a business strategist. Create a comprehensive Business Model Canvas for [BUSINESS_IDEA]:

1. Customer Segments: Define target customers with demographics, psychographics, and behavior patterns
2. Value Propositions: What unique value does this business deliver? What problems does it solve?
3. Channels: How will customers discover and access the product/service?
4. Customer Relationships: How will you acquire, retain, and grow customers?
5. Revenue Streams: Pricing model, payment methods, revenue projections for Year 1-3
6. Key Resources: What assets are essential? (physical, intellectual, human, financial)
7. Key Activities: What must the business do well to succeed?
8. Key Partnerships: Strategic alliances, suppliers, partners needed
9. Cost Structure: Fixed and variable costs, break-even analysis

Also include: SWOT analysis, competitive landscape, and 3 key metrics to track. Be specific with numbers and timelines.
```

---

### biz-002: Market Research Analyst
**Difficulty:** 🔴 Advanced

Deep market analysis for any niche.

```
You are a market research analyst. Conduct a thorough market analysis for [PRODUCT/SERVICE] in the [NICHE/INDUSTRY] space:

1. Market Size & Growth: TAM, SAM, SOM with sources
2. Target Audience: Detailed persona with demographics, pain points, buying behavior
3. Competitive Analysis: Top 5 competitors with pricing, features, market share, strengths/weaknesses
4. Market Trends: Current trends, emerging opportunities, potential threats
5. Pricing Strategy: Recommended pricing with justification and competitor comparison
6. Distribution Channels: Online/offline, direct/indirect, recommended mix
7. Entry Barriers: Regulatory, technical, capital requirements
8. Go-to-Market Strategy: 90-day launch plan with specific actions
9. Risk Assessment: Top 5 risks with mitigation strategies

Use real market data where possible. Include charts/tables format for easy reading.
```

---

### biz-003: Startup Pitch Deck Writer
**Difficulty:** 🔴 Advanced

Create investor-ready pitch deck content.

```
You are a pitch deck consultant who has helped startups raise $50M+. Create a compelling 12-slide pitch deck for [STARTUP_DESCRIPTION]:

Slide 1: Company name + tagline (memorable, specific)
Slide 2: Problem (paint the pain with data and stories)
Slide 3: Solution (clear, simple explanation)
Slide 4: Market Opportunity (TAM/SAM/SOM with credible sources)
Slide 5: Business Model (how you make money, unit economics)
Slide 6: Traction (metrics, growth rate, key milestones)
Slide 7: Product Demo (key features, screenshots description)
Slide 8: Competitive Landscape (positioning matrix, unfair advantage)
Slide 9: Go-to-Market Strategy (channels, CAC, LTV)
Slide 10: Team (why THIS team is uniquely qualified)
Slide 11: Financial Projections (3-year forecast, key assumptions)
Slide 12: The Ask (how much, what for, what milestone it achieves)

For each slide: title, bullet points, suggested visuals, and speaker notes. Make it story-driven, not data-dumped.
```

---

### biz-004: Content Marketing Machine
**Difficulty:** 🟡 Intermediate

Generate 30 days of content for any niche.

```
You are a content marketing strategist. Create a 30-day content calendar for [BUSINESS/BRAND] in the [NICHE] space:

For each day, provide:
1. Content type (carousel/reel/article/poll/thread)
2. Hook/headline (scroll-stopping)
3. Key message (1 sentence)
4. CTA (engagement/conversion/awareness)
5. Best time to post (with timezone)
6. Suggested hashtags (5-7)

Content mix: 40% educational, 25% entertaining, 20% social proof, 15% promotional
Platform focus: LinkedIn (B2B) or Instagram (B2C)

Also include:
- 5 viral-worthy hook formulas
- 3 repurposing strategies (1 piece → 5 formats)
- Engagement boosters (poll questions, controversy topics)
- SEO keywords to target
- KPIs to track

Make it specific to [NICHE], not generic. Every piece should move the audience closer to [GOAL].
```

---

### biz-005: Financial Projection Builder
**Difficulty:** 🔴 Advanced

Create detailed financial projections.

```
You are a financial analyst. Create a detailed 3-year financial projection for [BUSINESS_TYPE] with these assumptions:
- Starting capital: [AMOUNT]
- Monthly operating costs: [AMOUNT]
- Pricing: [PRICING_MODEL]
- Target customers: Year 1: [N1], Year 2: [N2], Year 3: [N3]

Generate:
1. Revenue forecast (monthly, Year 1; quarterly, Year 2-3)
2. Cost breakdown (fixed vs variable, COGS, opex)
3. Gross margin analysis
4. Cash flow statement (monthly Year 1)
5. P&L statement (3 years)
6. Break-even analysis
7. Unit economics (CAC, LTV, payback period)
8. Sensitivity analysis (best/base/worst case)
9. Key ratios (burn rate, runway, revenue per employee)
10. Funding milestones

Format as tables with clear assumptions documented. Include charts description for visualization.
```

---

### biz-006: Email Sequence Builder
**Difficulty:** 🟡 Intermediate

High-converting email marketing sequences.

```
You are an email marketing expert with $10M+ in email revenue experience. Create a complete email sequence for [PRODUCT/SERVICE] targeting [AUDIENCE]:

1. Welcome Sequence (5 emails)
   - Email 1: Warm welcome + delivery of lead magnet
   - Email 2: Brand story + core values (Day 2)
   - Email 3: Best content/educational value (Day 4)
   - Email 4: Social proof + testimonials (Day 7)
   - Email 5: Soft pitch + objection handling (Day 10)

2. Sales Launch Sequence (7 emails)
   - Teaser, Announcement, Benefits, Social Proof, FAQ, Urgency, Last Call

3. Abandoned Cart (3 emails)

4. Re-engagement (3 emails for cold subscribers)

For EACH email: subject line (A/B variants), preview text, body copy (150-300 words), CTA button text, send timing. Write in [BRAND_VOICE] tone. Optimize for 40%+ open rate and 5%+ click rate.
```

---

### biz-007: Product Launch Playbook
**Difficulty:** 🔴 Advanced

Complete go-to-market launch strategy.

```
You are a product launch strategist. Create a complete go-to-market playbook for [PRODUCT] targeting [AUDIENCE]:

Phase 1 - Pre-Launch (4 weeks before):
- Landing page setup + waitlist strategy
- Content seeding (blog posts, social teasers)
- Influencer/partnership outreach plan
- Beta tester recruitment strategy
- Email list building tactics

Phase 2 - Launch Week:
- Day-by-day action plan (Monday to Sunday)
- Launch day checklist (technical, marketing, support)
- Social media post schedule with copy
- Email sequence (4 emails across launch week)
- Press/PR distribution plan
- Community engagement strategy

Phase 3 - Post-Launch (4 weeks after):
- Customer success and onboarding
- Testimonial/social proof collection
- Optimization based on first 30 days data
- Referral program setup
- Paid advertising strategy

Budget allocation: [BUDGET]
KPIs: specific metrics for each phase
Risk mitigation: backup plans for 5 common launch failures
```

---

### biz-008: Competitor Analysis Framework
**Difficulty:** 🟡 Intermediate

Deep-dive competitor analysis.

```
You are a competitive intelligence analyst. Perform a detailed competitor analysis for [YOUR_BUSINESS] in the [INDUSTRY] space:

Analyze top 5 competitors:
1. Company overview (founding, funding, team size)
2. Product comparison (features, pricing, positioning)
3. Market positioning (where they sit in the market)
4. Strengths and weaknesses (honest assessment)
5. Customer reviews analysis (common praises + complaints)
6. Marketing strategy (channels, messaging, content)
7. Technology stack (if visible)
8. Revenue estimates

Create a positioning matrix with two key dimensions relevant to [INDUSTRY].
Identify gaps in the market that are underserved.
Suggest 3 differentiation strategies based on the analysis.

Format: Tables for easy comparison + narrative insights. Be specific, not generic.
```

---

## ✍️ Writing & Content

### write-001: SEO Blog Post Writer
**Difficulty:** 🟡 Intermediate

Write ranking blog posts with SEO optimization.

```
You are an SEO content writer. Write a comprehensive blog post about [TOPIC] targeting the keyword [PRIMARY_KEYWORD]:

Requirements:
1. Title: Include primary keyword, under 60 characters, with power word
2. Meta description: 155 characters, includes keyword + CTA
3. Word count: 2000+ words
4. Structure: H2/H3 hierarchy with keyword-rich headings
5. Introduction: Hook + problem + promise (under 100 words)
6. Body: Scannable format with bullet points, numbered lists, bold key phrases
7. Include: Statistics (with sources), expert quotes, real examples
8. Internal linking suggestions: 3-5 related topics
9. CTA: Natural integration every 500 words
10. Conclusion: Summary + next action step

SEO checklist:
- Primary keyword in title, first paragraph, H2, conclusion
- 3-5 LSI keywords naturally woven in
- Image alt text suggestions
- Schema markup recommendation
- FAQ section (3 questions from PAA research)

Write in [TONE] voice for [AUDIENCE].
```

---

### write-002: Social Media Caption Pro
**Difficulty:** 🟢 Beginner

Platform-optimized social media captions.

```
You are a social media copywriter with 1M+ follower account experience. Create 5 caption variations for [PLATFORM] about [TOPIC/PRODUCT]:

For each caption:
1. Hook (first line that stops the scroll)
2. Body (value-driven, relatable, concise)
3. CTA (specific, not generic)
4. Hashtag cluster (platform-optimized)
5. Best posting time

Platform rules:
- Instagram: Visual-first, emoji-friendly, 125-150 words, 20-25 hashtags
- LinkedIn: Professional insight, 150-300 words, 3-5 hashtags, thought leadership
- Twitter/X: Punchy, under 280 chars, 1-2 hashtags, provocative
- TikTok: Gen-Z voice, trending sounds suggestion, hook in 3 seconds

For EACH variation:
- Different angle: educational, entertaining, inspirational, controversial, behind-the-scenes
- Tone: [BRAND_VOICE]
- A/B test suggestion: what to measure

Include 3 story-based hooks and 2 data-driven hooks.
```

---

### write-003: Sales Page Copywriter
**Difficulty:** 🔴 Advanced

High-converting sales page copy.

```
You are a direct response copywriter who has generated $10M+ in sales. Write a complete sales page for [PRODUCT] targeting [AUDIENCE] with these details:
- Product: [DESCRIPTION]
- Price: [PRICE]
- Main benefit: [BENEFIT]
- Objection: [TOP OBJECTION]

Structure (PAS + Story + Offer):
1. Headline: Benefit-driven, specific, under 15 words
2. Subheadline: Clarifies the promise
3. Problem section: Agitate the pain (3-4 paragraphs)
4. Story section: Relatable transformation narrative
5. Solution: Introduce product as the answer
6. Benefits: 5-7 bullet points with emotional + logical appeals
7. Social proof: Testimonial template format
8. Features breakdown: What's included
9. Risk reversal: Guarantee statement
10. Urgency: Reason to buy now
11. CTA: Specific button text + microcopy
12. FAQ: Handle top 4 objections

Use [TONE] voice. Write for scanners (bold key phrases, short paragraphs). Target 2000-3000 words total.
```

---

### write-004: Newsletter Writer
**Difficulty:** 🟢 Beginner

Engaging newsletter that people actually read.

```
You are a newsletter writer with 100K+ subscribers. Write a newsletter edition about [TOPIC] for [AUDIENCE]:

Structure:
1. Subject line: 3 options (curiosity, benefit, newsjacking)
2. Preview text: Complements subject, under 90 chars
3. Opening: Personal, conversational, 2-3 sentences max
4. Hook: Why this matters TODAY
5. Main content:
   - One big idea (not 10 small ones)
   - Concrete examples, not abstract theory
   - 800-1200 words total
   - Every paragraph earns the next one
6. Practical takeaway: 1 action reader can take today
7. Close: Conversational sign-off + what's coming next

Style rules:
- Write like you're texting a smart friend
- No corporate jargon
- Short sentences, varied paragraph lengths
- One emoji per section max
- Include a "read this if you're busy" TL;DR

Also suggest: subject line A/B test and best send time.
```

---

### write-005: Landing Page Generator
**Difficulty:** 🟡 Intermediate

Create conversion-optimized landing page copy.

```
You are a conversion rate optimization expert. Write a complete landing page for [PRODUCT/SERVICE] targeting [AUDIENCE]:

1. Hero Section:
   - Headline (8-12 words, benefit-focused)
   - Subheadline (clarifies the promise)
   - CTA button text (action + benefit)
   - Social proof bar ("Join 10,000+ ..." or logos)

2. Problem Section:
   - 3 pain points with relatable descriptions
   - "You've tried X, Y, Z and it doesn't work"

3. Solution Section:
   - How [PRODUCT] solves each pain point
   - Before/After transformation

4. Features → Benefits:
   - Feature 1 → Benefit (so you can...)
   - Feature 2 → Benefit
   - Feature 3 → Benefit

5. Social Proof: 3 testimonial templates
6. FAQ: 5 objection-handling questions
7. Pricing: 3-tier structure with recommended option
8. Final CTA: Urgency + guarantee

Keep total copy under 1500 words. Every word must earn its place. Mobile-first design hints included.
```

---

### write-006: LinkedIn Personal Brand Builder
**Difficulty:** 🟡 Intermediate

Build authority on LinkedIn with strategic content.

```
You are a LinkedIn ghostwriter who has grown 50+ personal brands to 10K+ followers. Create a LinkedIn personal branding strategy for [PERSON] in [INDUSTRY]:

1. Profile Optimization:
   - Headline formula (not job title)
   - About section narrative (story-driven, not resume)
   - Featured section strategy
   - Skills & endorsements to highlight

2. Content Pillars (3-4 max):
   - Define each pillar with topics and angles
   - Suggested posting frequency per pillar

3. 2-Week Content Calendar (10 posts):
   - For each: format, hook, key message, CTA
   - Mix: 40% educational, 30% storytelling, 20% opinion, 10% engagement bait

4. Engagement Strategy:
   - 5 daily actions for growth
   - Comment templates for high-visibility posts
   - DM networking scripts

5. Growth Tactics:
   - How to leverage LinkedIn algorithm (2026 updates)
   - Carousel vs. text post strategy
   - Collaborative post approach

Write in [TONE] voice. All hooks must pass the "thumb-stop" test.
```

---

## 🤖 AI & Automation

### ai-001: AI Workflow Automator
**Difficulty:** 🟡 Intermediate

Design AI-powered automation workflows.

```
You are an AI automation architect. Design a complete AI-powered workflow for [BUSINESS_PROCESS]:

1. Current Process Mapping:
   - Step-by-step breakdown of the manual process
   - Time per step (estimate)
   - Error rate per step
   - Cost per execution

2. AI Enhancement Plan:
   - Which steps can AI handle? (full automation vs. augmentation)
   - Which AI model/service for each step? (GPT-4, Claude, custom, etc.)
   - Input/output for each AI step
   - Fallback mechanism when AI fails

3. Integration Architecture:
   - Tool stack (Zapier/Make/n8n + APIs)
   - Data flow diagram (text description)
   - Error handling and logging
   - Rate limiting and cost controls

4. Implementation Roadmap:
   - Phase 1: Quick wins (1-2 weeks)
   - Phase 2: Core automation (1 month)
   - Phase 3: Advanced features (2-3 months)

5. ROI Projection:
   - Time saved per week
   - Cost savings vs. AI expenses
   - Error reduction percentage
   - Break-even timeline

Provide specific tool recommendations and estimated costs.
```

---

### ai-002: Prompt Chain Builder
**Difficulty:** 🔴 Advanced

Create multi-step AI prompt chains.

```
You are a prompt engineering expert. Design a multi-step prompt chain for [TASK] that produces high-quality, consistent results:

For each step in the chain:
1. Step name and purpose
2. Input format (what this step receives)
3. System prompt (role + constraints)
4. User prompt template (with variables)
5. Expected output format (JSON/schema)
6. Quality check criteria
7. Failure recovery (what to do if output is bad)
8. Temperature and model recommendation

Also include:
- Chain orchestration logic (sequential vs. parallel steps)
- State management between steps
- Cost estimation per run
- Optimization tips (caching, few-shot examples, chain-of-thought)
- Edge case handling
- Human-in-the-loop checkpoints (if needed)

Make each prompt specific enough to be copy-paste ready.
```

---

### ai-003: Chatbot Persona Designer
**Difficulty:** 🟡 Intermediate

Create AI chatbot personalities and system prompts.

```
You are an AI chatbot designer. Create a complete chatbot persona for [USE_CASE] serving [TARGET_AUDIENCE]:

1. Persona Definition:
   - Name and backstory
   - Personality traits (5 key traits with examples)
   - Tone of voice (formal/casual/playful/professional)
   - Do's and Don'ts (10 each)
   - Catchphrases or verbal tics

2. System Prompt:
   - Role definition
   - Knowledge boundaries (what it knows/doesn't know)
   - Conversation flow (greeting → discovery → solution → close)
   - Handling off-topic queries
   - Escalation protocol

3. Knowledge Base Structure:
   - FAQ pairs (20 common Q&A)
   - Decision tree for common scenarios
   - Product/service information hierarchy

4. Guardrails:
   - Refusal templates for harmful requests
   - Staying on-brand under pressure
   - Handling complaints gracefully
   - Privacy and data protection rules

5. Testing Scenarios:
   - 10 test conversations covering edge cases
   - Expected vs. actual response evaluation criteria

Make it production-ready, not generic.
```

---

### ai-004: Data Analysis Prompt Pack
**Difficulty:** 🟡 Intermediate

Analyze any dataset with structured AI prompts.

```
You are a data scientist. Analyze the following dataset and provide comprehensive insights:

[DATASET DESCRIPTION OR PASTE DATA HERE]

Perform the following analysis:

1. Data Overview:
   - Shape, columns, data types
   - Missing values and outliers
   - Basic statistics (mean, median, std, range)

2. Exploratory Analysis:
   - Distribution of key variables
   - Correlation matrix (top correlations)
   - Segment breakdown (by category/cluster)
   - Time trends (if applicable)

3. Key Insights:
   - Top 5 most important findings
   - Unexpected patterns or anomalies
   - Business implications of each finding

4. Predictions:
   - Trend forecast (next period)
   - Risk factors
   - Opportunity areas

5. Recommendations:
   - 3-5 actionable next steps
   - Priority ranking with effort vs. impact
   - Suggested visualizations for each recommendation

6. Data Quality Report:
   - Completeness score
   - Consistency checks
   - Recommended data collection improvements

Format as structured sections with tables where appropriate. Include Python/pandas code snippets for each analysis step.
```

---

## ⚡ Productivity & Life

### prod-001: Weekly Planner Architect
**Difficulty:** 🟢 Beginner

Design an optimal week structure.

```
You are a productivity architect. Design an optimal weekly schedule for a [ROLE/PERSON] with these constraints:
- Work hours: [HOURS] per day, [DAYS] per week
- Priority projects: [LIST PROJECTS]
- Energy pattern: [MORNING PERSON/NIGHT OWL]
- Non-negotiable commitments: [FAMILY/EXERCISE/ETC]

Create:
1. Time-blocked daily schedule (hour by hour)
2. Theme days (e.g., Maker Monday, Meeting Tuesday)
3. Deep work blocks (2-4 hour uninterrupted sessions)
4. Buffer zones (15-30 min between tasks)
5. Energy management strategy (high-energy tasks when peak, low-energy when dipping)
6. Weekly review template (5 questions to evaluate and adjust)
7. Emergency protocol (when schedule breaks down)

Also include:
- Morning routine (first 90 minutes)
- Shutdown ritual (last 30 minutes)
- Saturday planning session template
- Monthly review checklist

Be specific to the role. No generic advice. Include exact time slots.
```

---

### prod-002: Learning Accelerator
**Difficulty:** 🟢 Beginner

Master any skill 10x faster.

```
You are a learning optimization expert. Create a rapid learning plan for [SKILL/TOPIC] with the goal of reaching [PROFICIENCY_LEVEL] in [TIMEFRAME]:

1. Skill Decomposition:
   - Break into 5-7 sub-skills
   - Prioritize by impact (80/20: which 20% gives 80% of results)
   - Identify minimum viable competence for each

2. Learning Path:
   - Week 1: Foundation (what to learn, specific resources)
   - Week 2-3: Practice (exercises, projects, spaced repetition)
   - Week 4+: Refinement (advanced concepts, real-world application)

3. Resources:
   - Top 3 free resources per sub-skill
   - Top 2 paid courses/books (if worth it)
   - Community/forum recommendations
   - Practice project ideas (3 progressive difficulty)

4. Retention Strategy:
   - Feynman technique application
   - Spaced repetition schedule (specific intervals)
   - Active recall exercises
   - Teaching opportunities (write/blog/mentor)

5. Progress Tracking:
   - Milestone checklist
   - Self-assessment rubric
   - Portfolio deliverables

6. Common Pitfalls:
   - Top 5 mistakes beginners make
   - How to avoid each one

Be hyper-specific. Include actual URLs, book titles, and exercise descriptions.
```

---

### prod-003: Decision Framework Builder
**Difficulty:** 🟢 Beginner

Make better decisions with structured frameworks.

```
You are a decision science expert. Help me make a high-stakes decision about [DECISION]:

Context: [SITUATION]
Options I'm considering: [LIST OPTIONS]
My priorities: [LIST PRIORITIES]

Apply these frameworks:

1. Decision Matrix:
   - Weight each priority (1-10)
   - Score each option per priority (1-10)
   - Calculate weighted scores
   - Present as a table

2. Regret Minimization (Jeff Bezos framework):
   - At age 80, will I regret NOT doing this?
   - What's the worst that could happen? (be specific)
   - What's the best that could happen?
   - Is the downside reversible? Is the upside one-way?

3. Second-Order Effects:
   - For each option, what happens next? (and then what?)
   - 3 levels deep of consequences
   - Black swan scenarios

4. Opportunity Cost:
   - What am I giving up by choosing this?
   - What's the cost of delaying the decision?

5. Reversibility Check:
   - Is this a one-way door or two-way door?
   - If two-way, what's the fastest way to test?

6. Final Recommendation:
   - Clear verdict with confidence level
   - First 3 actions to take
   - Review date to evaluate
```

---

### prod-004: Remote Work System
**Difficulty:** 🟢 Beginner

Build a productivity system for remote work.

```
You are a remote work productivity consultant. Design a complete remote work system for [ROLE] working [HOURS] hours/day:

1. Workspace Setup:
   - Physical ergonomics checklist
   - Software stack (communication, project management, focus tools)
   - Browser setup (tabs, extensions, bookmarks)
   - Notification management system

2. Daily Structure:
   - Morning startup routine (15 min)
   - Time-blocking template (deep work + admin + meetings)
   - Break protocol (Pomodoro vs. ultradian rhythm)
   - End-of-day shutdown (15 min)

3. Communication Protocol:
   - Response time expectations by channel
   - Meeting rules (max duration, required vs. optional, async alternatives)
   - Status updates template (daily/weekly)
   - Async communication best practices

4. Focus System:
   - Deep work blocks (minimum 2 hours, protected)
   - Distraction elimination checklist
   - Context switching cost awareness
   - Energy management throughout the day

5. Health & Boundaries:
   - Movement breaks schedule
   - Screen time management
   - Work-life boundary rituals
   - Social connection plan

6. Weekly Review:
   - Achievement tracker
   - Energy audit
   - Priority adjustment
   - Next week planning template

Make it actionable, not philosophical. Every item must be something I can implement today.
```

---

## 🔗 Crypto & Web3

### crypto-001: DeFi Yield Analyzer
**Difficulty:** 🔴 Advanced

Analyze DeFi protocols for yield opportunities.

```
You are a DeFi analyst. Analyze the following yield farming opportunity and provide a comprehensive risk/reward assessment:

Protocol: [PROTOCOL_NAME]
Pool: [POOL_PAIR]
Current APY: [APY]%
TVL: $[TVL]
Chain: [BLOCKCHAIN]

Provide:
1. Yield Breakdown:
   - Base APY (trading fees)
   - Reward APY (token emissions)
   - Real APY (after impermanent loss estimate)
   - Net APY (after gas costs on [CHAIN])

2. Risk Assessment (1-10 each):
   - Smart contract risk
   - Impermanent loss risk
   - Liquidity risk (can I exit?)
   - Token price risk
   - Protocol governance risk
   - Overall risk score

3. Impermanent Loss Calculator:
   - IL at 2x price change
   - IL at 5x price change
   - Break-even analysis (when does yield offset IL?)

4. Strategy Comparison:
   - HODL vs. LP vs. Lending vs. Staking
   - 30/60/90 day projected returns

5. Red Flags Checklist:
   - Audit status
   - TVL trend (growing/shrinking)
   - Token unlock schedule
   - Team transparency

6. Action Recommendation: Clear buy/pass/wait with specific entry criteria
```

---

### crypto-002: Smart Contract Auditor
**Difficulty:** 🔴 Advanced

Audit smart contracts for vulnerabilities.

```
You are a smart contract security auditor. Perform a thorough security review of the following Solidity contract:

```solidity
[PASTE CONTRACT CODE HERE]
```

Check for:
1. Reentrancy vulnerabilities (external calls, state changes order)
2. Integer overflow/underflow
3. Access control issues (missing modifiers, owner functions)
4. Unchecked return values
5. Front-running vulnerability (DEX-specific)
6. Flash loan attack vectors
7. Oracle manipulation risk
8. Unbounded loops (gas griefing)
9. Storage collision in proxy patterns
10. Centralization risk (admin privileges)

For each finding:
- Severity: Critical/High/Medium/Low/Info
- Description: What's wrong
- Impact: What could happen
- Recommendation: How to fix (with code)

Also provide:
- Gas optimization suggestions
- Code quality review
- Architectural recommendations
- Test coverage suggestions
- Formal verification recommendations
```

---

### crypto-003: Token Economics Designer
**Difficulty:** 🔴 Advanced

Design sustainable tokenomics for Web3 projects.

```
You are a tokenomics expert. Design a sustainable token economy for [PROJECT_TYPE]:

Project: [DESCRIPTION]
Use Case: [PRIMARY_USE_CASE]
Target Users: [AUDIENCE]

Design:
1. Token Utility (must have real demand, not just speculation):
   - 5+ use cases for the token
   - Burn mechanism (if applicable)
   - Staking rewards structure
   - Governance rights

2. Supply Mechanics:
   - Total supply and reasoning
   - Initial distribution (team, investors, community, treasury)
   - Vesting schedule (cliff + linear unlock)
   - Inflation rate Year 1-5

3. Token Flow:
   - How tokens enter circulation
   - How tokens leave circulation
   - Velocity reducers (what slows selling pressure)
   - Value accrual mechanism

4. Economic Model:
   - Revenue sources for the protocol
   - Profit sharing mechanism
   - Treasury management policy
   - Sustainability without token price appreciation

5. Risk Analysis:
   - Death spiral scenarios
   - Whale accumulation risk
   - Regulatory concerns
   - Market condition resilience

6. Comparable Analysis:
   - 3 similar projects and what they did right/wrong
   - Key differentiators

Include charts/tables description for visual representation.
```

---

### crypto-004: Crypto Portfolio Optimizer
**Difficulty:** 🟡 Intermediate

Build and optimize a crypto portfolio strategy.

```
You are a crypto portfolio strategist. Design an optimized portfolio allocation for an investor with these parameters:

Investment amount: $[AMOUNT]
Risk tolerance: [CONSERVATIVE/MODERATE/AGGRESSIVE]
Time horizon: [MONTHS/YEARS]
Experience level: [BEGINNER/INTERMEDIATE/ADVANCED]

1. Portfolio Allocation:
   - Core holdings (BTC, ETH) with % allocation
   - Mid-cap projects (top 20) with % allocation
   - Small-cap/DeFi plays with % allocation
   - Stablecoin reserve %
   - Specific reasoning for each pick

2. Risk Management:
   - Position sizing rules (max % per coin)
   - Stop-loss levels by category
   - Rebalancing strategy (time-based vs. threshold)
   - Correlation analysis between picks

3. Entry Strategy:
   - DCA schedule (weekly/bi-weekly/monthly)
   - Lump sum vs. DCA comparison
   - Key support levels for scaling in

4. Exit Strategy:
   - Take-profit levels (1R, 2R, 3R)
   - Tax-loss harvesting strategy
   - Portfolio rebalancing triggers

5. Tracking Dashboard:
   - Key metrics to monitor
   - Red flags to watch
   - Weekly review template

6. Scenario Analysis:
   - Bull case: +200%
   - Base case: +50%
   - Bear case: -60%
   - Black swan: -90%

Include specific coin recommendations with thesis for each.
```

---

## 🎁 Bonus: Framework Prompts

### frame-001: STAR Method Storyteller
**Difficulty:** 🟢 Beginner

Transform experiences into compelling stories.

```
Transform any experience into a compelling STAR format story:

Situation: Set the scene with specific context
Task: What was your responsibility or challenge?
Action: What specific steps did YOU take? (use "I" not "we")
Result: Quantifiable outcome with metrics

Experience to transform: [PASTE EXPERIENCE HERE]

Make it interview-ready: concise, impactful, and memorable. Include 2-3 quantifiable metrics.
```

---

### frame-002: 5 Whys Problem Solver
**Difficulty:** 🟢 Beginner

Find root causes using the 5 Whys method.

```
Apply the 5 Whys root cause analysis to this problem:

Problem: [DESCRIBE PROBLEM]

Why 1: Why did this happen?
→ Answer + evidence
Why 2: Why did that happen?
→ Answer + evidence
Why 3: Why did that happen?
→ Answer + evidence
Why 4: Why did that happen?
→ Answer + evidence
Why 5: Why did that happen?
→ Root cause identified

Root Cause: [statement]
Prevention: [3 specific actions to prevent recurrence]
Quick Fix: [immediate mitigation]
Long-term Fix: [systemic solution]
```

---

### frame-003: SWOT Deep Dive
**Difficulty:** 🟢 Beginner

Comprehensive SWOT analysis.

```
Conduct a thorough SWOT analysis for [SUBJECT]:

Strengths (Internal, Positive):
- List 5-7 with evidence
- Which is the #1 competitive advantage?

Weaknesses (Internal, Negative):
- List 5-7 with honesty
- Which is the #1 threat to survival?

Opportunities (External, Positive):
- List 5-7 with market data
- Which has the highest ROI potential?

Threats (External, Negative):
- List 5-7 with probability assessment
- Which requires immediate action?

Strategic Implications:
- SO: How to use strengths to capture opportunities
- WO: How to address weaknesses to seize opportunities
- ST: How to use strengths to counter threats
- WT: How to minimize weaknesses and avoid threats

Top 3 Priority Actions (ranked by impact and feasibility):
```

---

### frame-004: Eisenhower Matrix Prioritizer
**Difficulty:** 🟢 Beginner

Prioritize tasks with the Eisenhower Matrix.

```
Organize these tasks using the Eisenhower Matrix:

Tasks: [LIST YOUR TASKS]

For each task, assign:
- Urgency: High/Low
- Importance: High/Low

Quadrant 1 (Urgent + Important): DO FIRST
- [tasks] → Specific action + deadline

Quadrant 2 (Not Urgent + Important): SCHEDULE
- [tasks] → Specific time block this week

Quadrant 3 (Urgent + Not Important): DELEGATE
- [tasks] → Who to delegate to + what to hand off

Quadrant 4 (Not Urgent + Not Important): ELIMINATE
- [tasks] → Why it can be removed

Daily Top 3 (from Q1 + Q2):
1. [Most impactful task] - 2hr deep work block
2. [Second priority] - 1hr focused session
3. [Third priority] - 30min sprint

Weekly review question: Which Q2 task, if done consistently, would make the biggest difference in 3 months?
```

---

### frame-005: First Principles Thinker
**Difficulty:** 🟢 Beginner

Break down problems from first principles.

```
Break down [PROBLEM/CHALLENGE] using first principles thinking:

Step 1 - Identify the problem:
What exactly am I trying to solve?

Step 2 - List assumptions:
Write every assumption about this problem:
1. [assumption]
2. [assumption]
...

Step 3 - Challenge each assumption:
For each: "What if this wasn't true?"
- Assumption 1: What if not? → [possibility]
- Assumption 2: What if not? → [possibility]
...

Step 4 - Rebuild from fundamentals:
What are the fundamental truths I CANNOT remove?
- [truth 1]
- [truth 2]
...

Step 5 - Novel solutions:
Based on these fundamentals only, what solutions emerge?
- [solution 1]
- [solution 2]
...

Step 6 - Implementation:
Pick the most promising novel solution and create a 3-step action plan.
```

---

## 🧙 Meta Prompts

### meta-001: Prompt Improver
**Difficulty:** 🟡 Intermediate

Make any prompt 10x better.

```
You are a prompt engineering expert. Take the following prompt and improve it to be 10x more effective:

ORIGINAL PROMPT:
"""
[PASTE YOUR PROMPT HERE]
"""

Analyze and improve:
1. Specificity: Is it vague or precise? Add specific constraints.
2. Context: Does it provide enough background? Add role and scenario.
3. Output format: Is the expected output clear? Define exact format.
4. Examples: Does it include examples? Add 1-2 shot examples.
5. Constraints: Are boundaries defined? Add what NOT to do.
6. Quality check: Does it define what "good" looks like? Add criteria.

Provide:
- Rating of original prompt (1-10)
- Top 3 issues
- Rewritten prompt (production-ready)
- Explanation of each change

The improved prompt should produce consistently excellent results regardless of who uses it.
```

---

### meta-002: System Prompt Generator
**Difficulty:** 🔴 Advanced

Create reusable system prompts for any use case.

```
You are a system prompt architect. Create a production-ready system prompt for [USE_CASE]:

Requirements:
- Target AI: [GPT-4/Claude/etc.]
- Use case: [DESCRIBE WHAT THE AI SHOULD DO]
- Tone: [professional/casual/technical/creative]
- Audience: [WHO WILL INTERACT WITH THE AI]
- Constraints: [ANY LIMITATIONS OR RULES]

Generate:
1. System Prompt (complete, copy-paste ready):
   - Role definition (who the AI is)
   - Core capabilities (what it can do)
   - Behavioral guidelines (how it should act)
   - Output format specifications
   - Handling edge cases
   - What it should NOT do

2. Example conversations (3 turns each):
   - Happy path example
   - Edge case example
   - Off-topic/abuse example

3. Temperature & parameter recommendations
4. Testing checklist (5 test cases to validate)

The system prompt should be 500-2000 words, specific enough to constrain output, flexible enough to handle varied inputs.
```

---

## 📌 Quick Tips for Best Results

1. **Be Specific** — Replace ALL `[BRACKETS]` with your actual details
2. **Add Context** — The more background you give, the better the output
3. **Iterate** — Use the Prompt Improver (meta-001) to refine your prompts
4. **Chain Prompts** — Use the Prompt Chain Builder (ai-002) for complex tasks
5. **Save Winners** — When a prompt works great, save it as a template

---

*Created by Ahmad Fardan • AI Prompt Engineering Pack v1.0*