Aquí está la transcripción del texto de las imágenes en formato Markdown:

---

# The Engx Culture

## Engineering Best Practices
- Acting with Empowerment and Motivation.
- Building Trust and Owning Actions.
- Being Able to Self-Organize.
- Collaborating Effectively in a Team.

## Engineering Practices
- **Software Development Lifecycle (SDLC)**
  - All the phases a project undergoes end-to-end to manage resources, control costs, anticipate possible risks.
  - Most common approaches are waterfall and Scrum-based Agile SDLC.

## SDLC Process
- **Requirements**
- **Design**
- **Software Development**
- **Testing**
- **UAT/Staging**
- **Maintenance**

- "Make changes faster without increasing costs or degrading quality."
- "Produce a potentially shippable (ready for detailed customer feedback) product increment at the end of each iteration."

---

# Scrum

## Unites Business and Development
- **Business Side**: PO (Product Owner) → Product Backlog.
- The development team is all the development team.
- **Scrum Master**: Facilitating Scrum practices → Monitoring and improving their workflow.

## Sprints
- Time-boxed iterations.

## Daily Scrum
- Brief check-ins that occur each day.

## Other Events
- **Sprint Planning**
- **Sprint Review**
- **Sprint Retrospective**

## The Three Pillars of Scrum
- **Transparency**
- **Inspection**
- **Adaptation**

## Tips for Implementing Scrum
- Refine Scrum elements.
- Prioritize tasks.
- Make progress visible.

## Best Practices for Agile
- Create and maintain a product backlog that is used as a single source for your tasks.
- Update and prioritize a backlog regularly.
- Regular sprint reviews.
- PO provides feedback.
- Reprioritize a backlog based on the PO feedback.
- Involve the whole team.

---

# Agile Fundamentals

## The Agile Mindset
- Ways of thinking that support Agile practices.
  - Put customer first.
  - Trust in the team.
  - Emphasize experimentation.

## Values and Principles

### Values
1. Individuals and interactions over processes and tools.
2. Working software over comprehensive documentation.
3. Customer collaboration over contract negotiation.
4. Responding to change over following a plan.

### Principles
1. Highest priority is to satisfy the customer.
2. Welcome changing requirements.
3. Deliver working software frequently.
4. Business people and developers must work together.
5. Build projects around motivated individuals.
6. Face-to-face conversation.
7. Working software is the primary measure of progress.
8. Promote sustainable development.
9. Attention to technical excellence and good design.

---

# Shifting from Traditional Waterfall to Modern Agile Development

- With waterfall, clients see the final product at the end of the project lifecycle.
  - **Requirements** → **Design** → **Develop** → **Test** → **Deploy**

- With Agile development, a team takes an iterative approach, gets feedback, testing regularly, clients can see results at the end of each iteration.

## Focus Areas
- Adaptability
- User experience
- Testing

---

#  Culture

## 4 Pillars
- Develop Yourself
- Start-up Mindset
- Committed Partners
- Problem Solvers

##  Values
- Value the individual
- Focus on the customer
- Act as a team
- Strive for excellence
- Act with integrity

## How to Grow with 
- **Learn**
- **Level up**
- **Grow**
  - Inspire yourself; imagine the ideal you.
  - Realize where you are at the moment.
  - Set goals for development.
  - Set clear and measurable success criteria.
  - Plan steps.

---

# Key Principles of Agile-Driven Software Development

1. **Prioritize Code Quality First**
   - Ensure the team will have fewer issues to address at a later stage.
2. **Shift Feedback Left**
   - Earliest point possible in the SDLC.
3. **Automate All Repeatable Tasks**
   - Save time, increase productivity.
4. **Follow Lean and PDCA Practices**
   - Identify ways to improve SD processes.
   - Plan-Do-Check-Act (PDCA).

## Implementing the Key Principles with CI/CD
- **Continuous Integration (CI) / Continuous Delivery (CD)**
  - SD practice where members of a team integrate their work frequently.
  - Run tests as early as possible, shifting engineering focus.
  - CI/CD encourages automation.
  - Helps to implement code quality.

---

# The Development Phase

## Pre-Coding Activities

## Coding
- Follow the same coding standards and coding principles.
- Support all dev activities with automated static code analysis tools.
- Check every code change with automated testing.

## Code Review
- Other development activities.
- Knowledge sharing.
- Technical debt management.

---

# The Testing Phase

## Pre-Testing Activities
- Automated and manual test execution.
- Defect management.

---

# Best Practices for Ensuring Agility of Your Project
- Focus on the client's goals and requirements.
- Adhere to engineering excellence standards.
- Implement key principles of CI/CD.

---

# The Foundation of Engx Best Practices Survey

I'm a mid-level role.
- Update, prioritize, and reprioritize a backlog regularly.
- Conduct regular sprint reviews.
- Be involved in decision-making.
- Act with empowerment and motivation.
- Build trust and own actions.
- Collaborate effectively in a team.
- Focus on the client's goals and requirements.

---

# Code Quality Fundamentals

## What It Is and How It Looks
- **Functional Code Quality**: Functional requirements include unit testing and functional testing.
- **Structural Code Quality**: Adhering to project-specific guidelines.

---

# Characteristics of Structural Code Quality
- It should have certain characteristics:
  - **Clear**: Is my code easy to understand and edit?
  - **Easy to Maintain**: High-quality code is simple and clean, which makes it easy for others to edit and maintain it.

- "When your code works but is difficult to understand, it is not high-quality code."

- By focusing on code quality, your team can minimize the time required to read the code, giving developers more time for writing and creating.

- By incorporating coding standards, your team takes steps to:
  - Enhance code clarity.
  - Increase code readability and consistency.
  - Support better maintainability and control.
  - Reduce complexity.

## Three Major Elements
- Style Guides
- Code Principles
- Project-Specific Code Conventions

- Use SonarQube.

---

# Best Practices for Code Quality

- Clear onboarding for new team members.
- An agreed-upon guide for how code should be developed.
- Processes and tools in place for testing to ensure coding standards.
- Documentation of any project-specific information.
- Alignment on the coding principles for the project.

## Unit Testing
- "All the verifications should be done at the lowest possible level."
- Unit testing allows developers to keep the maintainability high.
- **Maintainability**: The ability to change, understand, and test an application easily.
- Unit tests should run fast, generate stable results, and can be modified quickly.
- **Integration Test**: Validate the interaction of a piece of code with external components.

---

# User Interface Tests

## Practical Implementations
- Use the lowest level possible. At the higher levels, you check only the interaction between the elements.
- Unit testing should have a short feedback cycle.
- Run a unit test suite every time you add a new piece of code.

## Principles of Good Unit Testing
- **F.I.R.S.T. acronym:**
  - **Fast:** Test should be fast-running.
  - **Independent:** Test should not be dependent on each other.
  - **Repeatable:** Test should be repeatable in any environment.
  - **Self-Validating:** Test should have a boolean output and either pass or fail.
  - **Timely:** UT should be written in a timely manner.

---

# Best Practices for Unit Testing
- Write unit tests when you work on a development task or user story development.
- Ensure that unit tests follow the F.I.R.S.T. principles.
- Include the execution of unit tests in the CI.
- Measure code coverage.

---

# Code Review

## The Key Goals of Code Review
- Identify initial development bugs and facilitate a maintainable codebase.
  - **Fewer Defects:** Other points of view.
  - **Knowledge Sharing:** Guarantees all team members are on the same page and strengthens positive communication and cooperation.
  - **Consistent Standards**
  - **Compliance**

## Code Review Types and Workflow
- **Peer Review:** Several team members review code at different times.
- **Specialist Review**
- **Instant Code Review**

---

# Key Areas of Code Review
- **Functional Correctness / Business Logic**
- **Structural Correctness / Design**
- **Readability / Complexity**
- **Test Correctness**
- **Non-Functional Hidden Implications**

## Developer's Checklist
- My code compiles (linting passed, tests passed, quality are passed).
- My code has been developer-tested.
- My code is fully documented.
- My code is tidy.
- I have eliminated unused imports and code editor warnings.
- My code follows my team’s established coding standards.
- There are no hard-coded values.
- I considered performance and security.
- No code can be replaced with calls to extend reusable components or library functions.

---

# Tips for Implementing Code Review
1. Limit changes per merge request.
2. Set a reasonable time limit.

---

# Knowledge Sharing
- Exchanging of information, expertise, and skills.
- **Knowledge Sharing Goals:**
  - Keep projects up and running.
  - Communicate project standards and best practices.
  - Optimize the team's efforts and keep everyone’s focus on the right track.
  - Make necessary information readily available.
  - Decrease the amount of time your team members spend on regular activities, like onboarding.

## Healthy Knowledge Sharing
- Ensures a project runs smoothly and minimizes risks to delivery or implementation.

## Unhealthy Knowledge Sharing
- Can put a project at risk.

---

# Types of Risks
- Unclear project priorities.
- Unclear project standards.
- Waste of project resources.
- Bus factor: The number of members on your team whose absence can block project implementation.
- Missing information.
- Ineffective onboarding.

## Benefits
- A stable team.
- Alignment through documented standards.
- Available comprehensive information.
- Smooth onboarding.

## Software Development Lifecycle Process
- Review artifacts with rotating peers.
- Diversify task assignments.
- Keep breadcrumbs of your work.
- Plan time for documentation.

## Knowledge Base
- Keep all project documents in one location that every team member can access.

---

# Onboarding Procedures
- Include comprehensive guidelines for newcomers.

## Team Communication
- Conduct knowledge sharing sessions/sync-ups.
- Keep team chat focused and diverse.
- Post important updates in new channels.
- Participate in project townhalls.
- Send meeting follow-ups.

## Best Practices for Knowledge Sharing
- Establish a knowledge-sharing process among development team members.
- Use a technical knowledge base stored in a collaboration system (Confluence, Wiki, etc.).
- Keep the technical knowledge base updated so it properly reflects the current project details.
- Ensure team members pick development tasks for all parts of the system evenly to prevent situations where some parts of the system are known by only one person (bus factor).

---

# Technical Debt

## Types of Technical Debt
- Meeting time-to-market deadlines.
- Creating POC and MVPs.
- **Unintentional Technical Debt:**
  - Lack of technological expertise.
  - Internal process issues.

## Delivery Indicators
- Related to solution quality:
  - **Quality Degradation:**
    - Production issues: Production bugs.
    - Regression issues.
    - Known issues.

---

# Indicators of Technical Debt

## High Cost of System Change
- If the amount of effort and time it takes to make a new change increases, it can indicate technical debt.

## Architecture Indicators
- Hard to integrate.
- Hard to reuse.
- Hard to grow.
- Hard to support.

## Team Indicators
- Delays.
- Low level of confidence in scope estimation.
- Demotivation.

## Tracking Technical Debt
- Keep the technical debt registry up-to-date.
- Use a technical debt backlog.
- Use technical debt management tools.

## Examples of Technical Debt Visualization
- Code coverage.
- Code smell.

---

# Risks of Unmanaged Technical Debt
- Substantial damage to quality.
- Scalability and performance issues.
- Team issues.
- Tense communication.

## Recommendations for Leaders
- Reserve time for technical debt tasks.
- Motivate your team.
- Report technical debt statistics.
- Conduct regular review meetings with client stakeholders.

## Recommendations for Devs
- Avoid code smells.
- Conduct code reviews.
- Share knowledge.
- Use code analysis tools.
- Use automated testing.

---

# Best Practices for Managing Technical Debt
- Measure technical debt.
- Regularly allocate time to address technical debt.
- Track intentional technical debt.
- Estimate your intentional technical debt.
- Regularly allocate time to reduce intentional technical debt.

## Branching Strategy
- **Version Control Systems:**
  - Gives developers on your team a way to create their own version of code they copy from the central codebase to edit. It also provides a place for other team members to access stored versions of the edited code.
  - **Repositories and Working Copies:**
    - Repositories house the edited code while developers on your team review and make further updates.
    - Working copy: Devs shouldn’t modify the files in the repository directly.

---
