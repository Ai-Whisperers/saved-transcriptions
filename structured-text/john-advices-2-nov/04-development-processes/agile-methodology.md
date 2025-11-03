# Development Process & Agile Methodology

## Agile Development Fundamentals

### What is Agile?

**Core Concept:**
> "Agile is you plan first like features and you go through steps."

**Agile vs Waterfall:**

**Waterfall (Old Way):**
- Define everything in advance
- Work through entire plan
- Changes are costly
- NASA's approach: design everything front to start
- Changes have ripple effects throughout

**Agile (Modern Way):**
> "While you're working, you're figuring out how it should be. So you're much more easy to adjust on changing circumstances while things are happening."

**Key Advantage:**
- Adapt to changes easily
- Figure out details as you go
- Respond to discoveries
- Iterate quickly

### Agile Structure

#### Program Increment (PI)
**Duration:** 2-3 months
**Purpose:** Overall project timeline
- Usually 4-6 sprints
- Complete feature sets
- Major milestones

#### Sprints
**Duration:** 2-3 weeks
**Purpose:** Work iterations

**Key Rule:**
> "All tickets are there. And I say there's nothing changing anymore during the two to three weeks. So you can concentrate focus working on those tickets."

**Loading:**
- Load 2-3 weeks of work per sprint
- No changes during sprint
- Focus on completion

#### Features
**Definition:** Major functionality to be added
**Breakdown:** Features → Stories/Tickets

**Example:**
- Feature: "Add dark mode"
- Stories: Design system, Toggle component, State management, etc.

#### Stories (Tickets)
**Duration:** Half a day to one week (traditionally)

**Current Reality:**
> "The thing is, is that half a day is now half an hour and one week is now half a day."

**AI Impact:** Everything is dramatically faster

### The Critical Agile Principle: Risk First

> "You're moving the risk to the front. You first do the critical parts, the most complicated parts you put to the front."

#### The Right Way
1. **Identify highest risk/complexity**
2. **Tackle those FIRST**
3. **Prove it can be done**
4. **Then do the easy stuff**

**Example: SpaceX**
> "Can we fly and then land? Yes. Can we launch and then land? Yes. Can we catch them? Yes. All those checkboxes, now all the difficult checkboxes are done. Now set up your production line. Now it's time to go fast."

#### The Wrong Way (What Companies Do)
> "What many companies do, they go with always the easy features. This one, that one, mainly UI and whatsoever."

**The Failure Pattern:**
1. Spend time on easy things
2. Feel productive (lots of visible progress)
3. Run out of time
4. Difficult parts remain
5. **Project fails**

**Lesson:**
> "That is the failure of the project. They spend a lot of time on the easy things. And then there's no time anymore for the difficult."

## Quality Assurance Strategy

### The QA Problem

**Traditional Approach:**
> "There was a girl when I was at Energy 21 that came to me, 'There is this error. This is always wrong. I am not allowed to fix this because it would change the behavior of the code that passed QA.'"

**The Trap:**
> "That QA effort is so high in many companies that they don't dare to change anything."

### The AI-Powered Solution

**Paradigm Shift:**
> "Once that QA effort is next to zero and you can test everything else, you have a paradigm shift."

**What Changes:**
- Can test changes easily
- Quality actually improves
- Safe to fix things
- Iterate faster

**Automation Opportunity:**
> "Go through it, annotate everything, document everything. Find inconsistencies. These are easy questions."

**QA as Market Segment:**
> "The QA side, you can improve a lot because of automation of QA and actually fulfilling to QA standards that in the past they didn't do."

### Test-Driven Development (TDD)

**Origin:**
> "They don't want to write the documentation, so they write the test documentation. Instead of writing documentation, they write unit tests to lock in the design."

**Modern Approach with AI:**
1. Write feature
2. AI generates unit tests
3. Review and adjust tests
4. Tests document behavior
5. Safe to refactor

**Important:**
> "Before you commit, all unit tests that exist should have run."

## Working with Customers

### The Fundamental Truth

> "The customer doesn't know what it wants. If you think the customer knows what it wants, they don't know what they want."

**Reality:**
- Customers have a problem
- They think they know the solution
- Often their solution isn't optimal
- Your job: Understand problem, provide better solution

### Managing Scope Creep

**Common Pattern:**
> "The customer was like: 'Upload XLS' → 'Files are this big' → 'Now we need parquet' → 'Files up to this line'"

**Problem:**
> "Couldn't you fucking tell us that from the beginning? If we knew that in the beginning, we could go directly to parquet."

**Why It Happens:**
- Customers don't know all requirements
- They discover needs as they go
- They assume you understand context
- They don't think to mention "obvious" things

### The Prototype Approach

**Strategy:**
1. **Start with Prototype**
   - Quick proof of concept
   - Shows possibilities
   - Gets feedback
   - Builds trust

2. **Gather All Feedback**
   - What works?
   - What's missing?
   - What's the real scale?
   - What are constraints?

3. **Define Project Scope**
   > "Let's work this one out. Let's get this to market first and accept it. Anything else afterwards, let's talk about that one."

4. **Set Boundaries**
   - Clear deliverables
   - Agreed pricing
   - Change process defined
   - Timeline expectations

### Negotiation Timing

> "You should negotiate in advance and not in the end."

**Why:**
- Avoid uncomfortable conversations later
- Set expectations early
- Protect your interests
- Professional relationship

**Current Client Example:**
> "The thing is, we want it to be finished before we talk."
> "Exactly. I also would not know how to approach that one."

**Better Approach:**
- Checkpoint meetings during development
- Incremental delivery and payment
- Scope changes trigger pricing discussion
- Keep communication open

### Selling the Solution

**When Customer Questions Your Approach:**

**Template Response:**
> "That was a brilliant idea that inspired you to do something even better because of [reasons]. You're not telling they were bad. It was just inspired you to make something even better."

**Psychology:**
- Acknowledge their input
- Make them feel heard
- Position your solution as evolution
- They feel ownership

## The Learning Culture

### Failure as Learning

**Core Principle:**
> "Failure is not an option. That is the worst thing that you can have."

**Correct Mindset:**
> "Failure is always an option. If something doesn't work out, it doesn't matter. If you learn something from it, that's the most important part."

**Implementation:**
> "I let you fail as much as I could. So you would learn a lot from it."

### Current Reality: Learning on the Job

**Project Pricing:**
> "You are learning on the fly, learning on the job. That is how all the companies work. The student that is helping out, they are willing also, they're not giving that one for free."

**Acceptance:**
- Everyone learns while working
- This is normal
- Charge for your work anyway
- Experience is valuable

### Speed of Learning with AI

**Time Compression:**
> "It takes companies 10 years to learn the same lessons."

**Your Advantage:**
- Learning faster with AI
- Making mistakes faster
- Iterating faster
- Compressing years into months

**Projection:**
> "Imagine yourself in like two months further, where you have your workflow much more automated. The time to go from idea to final product, five days, one week, done."

## Time Estimation

### The Challenge

**Example:**
> "Verdoen was like, 'yeah, we can make that easily' and now it's been like a week."

**Reality Check:**
> "The changes to make it work for a bazillion light-years, as you asked, was way more complex than we initially thought."

### Estimation with Time Tracking

**Current Good Practice:**
> "It's good that you keep track of time."

**Purpose:**
> "In two or three months you can start using that information to start to learn... You have a much better sense of actual time spent."

**Overhead Factor:**
> "If you have time registry of like 80% of the time, then you know that you need actually to ask for 20% of the time. Because although it was not spent on it, it was spent on overhead."

### The New Reality

**Old Thinking:**
> "It always costs more time than you initially thought."

**New Reality:**
> "Now we are in a time where it's always taking less than what you initially thought it would take."

**But:**
> "Our problem is that we think that it's going to be done so easily, but then again... you were like, 'yeah, adjusting the things...' It will be easy. It's been like a week or a little bit more."

**Lesson:** Even with AI, complexity can surprise you

## Task Prioritization

### The Matrix Approach

> "All the different things that need to be done, short term, mid term, long term, you should just record them. Then you start categorizing them."

**Categories:**
- **Timeline:** Short/Mid/Long term
- **Type:** Production vs PR vs Internal
- **Impact:** High/Medium/Low
- **Effort:** Small/Medium/Large

**Purpose:**
> "That creates like a certain type of matrix and you want to be like the middle."

**From Energy 21:**
> "It's a methodology that they use in business to get focused on the tasks to do."

### Benefits of Organized Backlog

**Current State:**
> "Now you're making spaghetti, but now at some moment you start creating focus."

**With Organization:**
- Clear priorities
- Focused effort
- Better decisions
- Less scattered work

**Strategic Thinking:**
> "If we do this, this and this, we're studying anytime, we start practicing, we have some workflow, let's put up this internal workflow that we're going to need anyway."

## Development Workflow

### The "Do Three Things" Principle

> "Always do things that is not doing one thing, it's not doing two things, but in the meantime, it's like doing three things."

**Example: Learning N8N**
1. **Learn the tool** (skill development)
2. **Automate company process** (internal value)
3. **Create sellable product** (revenue opportunity)

**Another Example: Feedback Tool**
1. **Solve customer problem** (revenue)
2. **Learn data processing** (skills)
3. **Create reusable service** (product)
4. **Entry point for upselling** (sales)

### Daily Scrum

**Purpose:**
> "Every day you're sitting together. OK, what everybody working on. OK, everybody knows what this is. Do any questions, any unclear, whatever. No, OK, go."

**Origin:**
> "That's the scrum. That's what it's coming from. The football when they are all..."

**Benefits:**
- Everyone aligned
- Blockers identified
- Help offered
- Quick sync

### Iterative Quality Improvement

**The Cycle:**
> "Iterations. You start fast. You pass the iterator, the quality goes up."

**Process:**
1. Get something working
2. Make it better
3. Add tests
4. Improve documentation
5. Refactor
6. Repeat

**AI Assistance:**
> "I went through like six cycles of telling the AI: look at the project, what should you fix, look at the project, what should you add, add more CI/CD, add more tests, add more CI/CD, improve the tests, abstract the tests, add more CI/CD."

## Working as a Team

### Collaborative Learning

> "You're not at school anymore and having to do everything yourself."

**Practice:**
> "You're learning, you should pass information to Ivan and Jonathan. You're learning as a team. If you know something, you pass it along."

**Show, Don't Just Tell:**
> "Hey this works. Show people how it works."

### Specialization & Collaboration

**Example from Discussion:**
> "There are things that for you is a problem, for Ivan it's not a problem. Actually, you should work together on those things."

**Division of Focus:**
- **Kirian:** Business side of N8N, market research, workflow applications
- **Ivan:** Technical deep dive, complex implementations, API integrations

**But Collaborate:**
- Share knowledge
- Help with blockers
- Review each other's work
- Learn from each other

## Security in Development

### Basic Principles

**Be Proactive:**
> "Be careful not to introduce security vulnerabilities such as command injection, XSS, SQL injection, and other OWASP top 10 vulnerabilities."

**If You Notice:**
> "If you notice that you wrote insecure code, immediately fix it."

### Don't Ship Secrets

**Warning:**
> "Do not commit files that likely contain secrets (.env, credentials.json, etc). Warn the user if they specifically request to commit those files."

**Practice:**
- Use .gitignore
- Environment variables
- Secret management tools
- Never hardcode credentials

## Documentation Strategy

### Auto-Documentation

**Philosophy:**
> "How do you say, you should... how do you say, you should automatically document from your projects."

**Trigger-Based:**
> "Something that is triggered by GitHub commit triggers something and it starts an agentic repository that will automatically do something for you."

**What to Automate:**
- Code documentation
- API documentation
- Architecture diagrams
- Changelog generation
- Release notes

### Sharing Knowledge

**Internal vs External:**
> "There are things that you don't want to show. There are things that you do want to show. There are things that you want to give for free. But you don't want to have linked to the company."

**Strategy:**
- Some knowledge free (builds reputation)
- Some knowledge paid (products)
- Some knowledge internal (competitive advantage)
- Always branded (marketing)

## Dealing with Technical Debt

### QA Debt Example

**The Problem:**
> "I am not allowed to fix this because it would change the behavior of the code that passed QA."

**Solution with AI:**
- Easy to test changes
- Quick to verify behavior
- Safe to refactor
- Can fix technical debt

### When to Address Debt

**Not Now:**
> "It's okay to experiment and whatsoever."

**But Track It:**
- Known issues list
- Technical debt backlog
- Prioritized improvements

**Address When:**
- Blocking new features
- Causing frequent bugs
- Slowing development
- Creating security risks

---

## Immediate Action Items

- [ ] Implement daily standup/scrum
- [ ] Create task prioritization matrix
- [ ] Define feature → story breakdown process
- [ ] Set up automated test running before commits
- [ ] Establish "risk first" planning for next project
- [ ] Create prototype → project transition process
- [ ] Define scope change negotiation process
- [ ] Document "three things" examples for team
- [ ] Set up collaborative learning sessions
- [ ] Create technical debt tracking system

## Long-Term Process Goals

1. **Risk-First Development:** Always tackle hardest parts first
2. **Automated Quality:** Testing and documentation automatic
3. **Fast Iteration:** Days from idea to prototype
4. **Continuous Learning:** Team shares knowledge actively
5. **Customer Management:** Clear boundaries and communication
6. **Sustainable Pace:** Quality improves with each iteration
