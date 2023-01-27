# Google PM Course Notes

## Agile Project Management

### Introduction on Agile
- Iterations - shorter blocks of time

![Agile vs. Waterfall](https://i.imgur.com/uV1ZlVZ.png)

### The Agile Manifesto and Its Principles
Read more here: https://agilemanifesto.org/

### When to Use Agile?
- Project with high levels of **VUCA** (Volatility, Uncertainty, Complexity, Ambiguity) = Agile

### Popular Agile Framework
1. **Scrum** - led by a Scrum master, 3-9 team members, for open-minded team and management
2. **Kanban** - visual board
3. **Extreme Programming (XP)** - test first development (design, code, test, listen, repeat)
4. **Lean** - Continuous improvement methodology

### Scrum
- An iterative and incremental approach
- The Official Scrum Guide: https://scrumguides.org/

**Scrum Team roles:**
1. Product Owner (responsible for what the team builds)
2. Scrum Master (responsible of when to deliver value to users)
3. Development Team (responsible to deliver the product)

**3 Pillars:** transparency, inspection (timely checks of work), adaptation

**5 Values:** commitment, courage, focus, openness, and respect

### Scrum Roles
- Establish a **mission** (tells me why we're doing the work) and **product vision** (helps imagine what the work will be like when we're done)
- If you, as a manager, compelled to start telling your team what to do and interferes with the self-organizing nature, **the benefits of Scrum will begin to collapse**.

#### Scrum Master
- helps everyone to understand and implement Scrum
- managing the Product Backlog (source of product features, requirements, activities related with deliverables)
- facilitates scrum events, remove blockers, remove interruptions
- creating agreed definition of a done task

#### Product Owner
- ensures that the team is buildng the right product or service
- voice of the customer, owner and priortizes the Product Backlog
- help inspect, adapt, and plan the next iteration on a regular basis

#### Development Team
- do the work to build the product

### Product Backlog
- guide and roadmap of your product
- a living document (always updated), owned by the Product Owner, prioritized list of features/requirements

**Best Practices:**
1. **clear item descriptions**, includes essential details, such as an action and location
2. for the value field, rate on **how much it provides business value **(scrum team decisions)
3. for estimate value, **indicate how much effort the Scrum team needs to complete **(Low, Medium, and High), owned by the Development team
4. add an order or priority list

The goal is **to include as you can while not stressing about the unknowns too much**, you can study each tasks in more detail when it is higher on the priority list.

Read more here: https://scrumguides.org/scrum-guide.html#product-backlog

#### User Stories
- create a solution that's always centered around the user and the user experience
3 elements: User, Action, Benefit

- Use this format: As a [user role] I want this [action] so that I can get this [value].

User stories must be independent (no additional needed context), negotiable, valuable, estimable, small (1 story = 1 sprint), testable (**INVEST**).

- If a user story is too big, it should be broken down into smaller stories.
- **Epic** -  a group of collection of user stories

**Develop a acceptance criteria to each user story** (what can the user to with this user story, steps or features)

**Example**:

- User Story: As a **Virtual Verde client** (user role), I would like to **acquire a bonsai tree** (action) so that I** can have a beautiful plant and I can meditate as I trim the branches** (value).

- Acceptance Criteria:
![Acceptance Criteria](https://i.imgur.com/Iq0RYR9.png)

**Best Practices**:
- include the following components: user persona (personality), definition of Done, tasks to complete the user story, and any feedback already provided.

**Product Backlog Template**: [Template](https://github.com/ralmario/googlepmguide/blob/main/Documents/Project%20Agile%20Management/Product%20Backlog%20Template.xlsx)

#### Backlog Refinement

**Best Practices for Refining the Product Backlog:**
- contains the appropriate items
- items prioritized by the Product Owner
- items at the top are ready for delivery with clear acceptance criteria
- items must inclues estimates or informed assessment

#### Relative Estimation
- comparing the effort of one task to another task and that becomes the estimate

**2 Common Relative Estimation:**
1. **T-shirt Size**: identify a task that is considered a "Medium" and compare it to other tasks and assign a T-shirt size, assign a number to each size
2. **Story points**: use of Fibonacci number to determine effort and risk

#### Sprints/Iterations (mini-project)
- amount of work based on the historical capacity of the team
- must have strict deadlines or in a timebox (1 to 4 weeks)

**5 Events of Scrum:**
1. The sprint
2. Sprint Planning
3. Daily Scrum
4. Sprint Review
5. Sprint Retrospective

**Considerations in Setting a Timebox:**
1. frequency of changes
   - if needs are ever changing = 1 week/Sprint
   - if needs are more stable = > 1 week/Sprint
2. Needed focus time by the Development Team
   - baseline effort + 1 week (common is 1 week + 1 week)
3. Overhead on the Product delivery
   - if each Sprint output/product needs extensive review or testing after development = 3-4 weeks/Sprint

**During the Sprint:**
- No changes are made that would endanger the Sprint Goal
- Quality does not decrease
- The Product Backlog is refined as needed
- Scope may be clarified and renegotiated with the Product Owner

#### Planning a Sprint
- planned by the entire Scrum team

**Sprint Backlog**
  - items from the Backlog that will be done during this sprint
  - subset of items from the Product Backlog

**Essential Points during Sprint planning:**
1. Availability of staff during this Sprint
2. Conflicts from staff such as vacation leaves
3. Average velocity of work (How many points or Backlog items have been done in one Sprint?)
4. Accomplishments that needs to be done during this Sprint
5. Ultimate Sprint goal
6. Methods to finish work
7. Staff responsible for each tasks

**Creating a Sprint Backlog Spreadsheet**
1. Assign all items for each Epic in the Product Backlog tab (columns include Epic title, User Story Title, Story, Acceptance Criteria, Value, Estimate, Sprint)
2. Add Value for each item (ranging from $ to $$$) with minimal value to greatest value
3. Add Estimate via Story Points (Fibonacci sequence)
4. Assign the Sprint Type of each item (Current Sprint, Next Sprint etc.)
5. In the Sprint Backlog tab, add the Point Capacity of the team, which is commonly at 60 points (measure this by average of points done on at least 3 Sprints)
6. Copy all items to be done in the current Sprint in the Sprint Backlog tab, total estimate points all of Sprint items must be below or above the set Point Capacity
7. Ensure that the total value points all of Sprint items in the current Sprint must be larger than the next Sprint.

You may use [this template](https://github.com/ralmario/googlepmguide/blob/main/Documents/Project%20Agile%20Management/Sprint%20Backlog%20Sample.xlsx) as a base of the Sprint Backlog and Sprint Plan.

#### Daily Scrum/Daily Standup
- daily, same time and place, for 15 minutes

**Questions to Be Asked:**
- What did you do yesterday?
- What you will do today?
- Do you have any immpediments/blockers?

#### Sprint Review
- at end of each Sprint, less than 4 hours

**Covers:**:
- checking of Product Backlog items that considered done
- demo the product, what is produced after a given Sprint (**Product Increment**)

Consider if a Product Increment is already a** Minimum Viable Product (MVP)** which a version of a product with just enough features to satisfy early customers.

#### Sprint Retrospective
- up to 3 hours

**Covers:**
- Working (or not working) regarding the people, processes and tools for the team
- Improvements for the next Sprint
- Improvements for the last Sprint that are working (or not)

**Avoid:**
1. Avoid too many gimmicks.
2. Try not to only focus on the negative.
3. Avoid changing processes after each retrospective.

**Best Practices:**
1. Ask open-ended, probing questions.
2. Consider diverse styles of communication and participation (journaling, survey)
3. Consider reflecting periodically on Scrum theory and values by asking specific questions.

#### Scrum Tools
1. Burndown chart
   - **Best Practices:**
      - if running late on burndown, don't panic, find out how you can help and unblock them
2. Computing velocity
   - The measure of how many points the team burns down in a given Sprint on average.
   - **Best Practices:**
      - don't compare velocity to other teams (comparison metric)
      - don't share velocity with stakeholders
      - don't use velocity as a performance metric
      - caution when using velocity as a metric for project delivery date (don't use estimated delivery dates as commitments)
3. Kanban/Scrum board
   - **Best Practices:**
      - assign a *WIP limit* (Work in Progress limit)
      - 3 categories: **To Do**, **Doing**, and **Done**, you may add additional category: **Blocked**

#### Scrum Software
- scheduling and resource management tools: **Jira by Atlassian, Trello, spreadsheets**
- Sprint Planning and Backlog management: **Asana**
- documentation: **Word, Google Docs**
- spreadsheets: **Excel, Google Sheets**
- presentations: **Powerpoint, Google Slides**
- collaboration and communication

#### Review Video: [Agile Product Ownership in a Nutshell](https://www.youtube.com/watch?v=502ILHjX9EE)

#### Value Roadmap
- mapping out the product development

**3 Components:**
1. Product vision
2. Product roadmap
3. Release plans (release goal, backlog item lists, est. release date, other relevant dates)

**Benefits:**
- clarifies sequence of deliverables
- showing team efforts related to the ultimate goal
- showing stakeholders incremental value
- helping stakeholders the layout of the work

**Avoid:**
- letting stakeholders that the roadmap is set and permanent
- too much fine-tuning of delivery dates
- putting too much work in roadmap creation

**Overall Best Practices:**
- make it highly noticeable
- indicate highest priority and value items
- make it visible to stakeholders
- conduct regular reviews to sponsors, users and team

**Specific Tips**
1. Product Roadmap
   - product release dates are only rough estimates

2. Release Plan
   - Product Owner and Scrum Master
   - Connect with team's capacity and velocity
   - Factor in any "hard" dates or deadlines
   - Scrum Master must review the release plan before starting a Sprint Planning session

#### Change over following a plan
**Process:**
1. Identifying a needed change
2. Deciding to make the change
   - identify the "decider" of the change
   - Develop and share what factors are important to the decision
   - Openly discuss the benefits and costs of the decision
   - Document the decision
3. Implementing the change
   - Document the change and decision-making process
   - Capture the change in any affected artifacts
   - Share the change with all affected stakeholders
   - Monitor the change for a certain amount of time

#### Template:
- [Release plan template](https://github.com/ralmario/googlepmguide/blob/main/Documents/Project%20Agile%20Management/Sample%20Release%20Plan.docx)

### Transition Your Organization to Agile
- understand the organization culture and change management process
- implement a few changes incrementally if the organization is new to Agile

#### Introducing Agile to Your Team
- start small (start with a Kanban board, setup a retrospective after a major milestone)
- listen to feedback (how it's going, get ideas)
- be strategic, addresses challenges with improvement and new ways
- find allies in your organization and networks

#### Initiating the Transition
**What to Do:**
1. Find an executive sponsor that will co-own or co-lead the change
2. Point out connections between the changes you're making and the company's mission or values
3. Get buy-in or support from someone at the top
4. Ask what is and what's not working right now, and relate your changes as solutions to problems that arose
   - *Example questions: *
   - What is preventing us from providing the best product to our users? 
   - What is allowing our competitors to outperform us in this market? 
   - How can we help you become more productive and supported in their work?

#### Influencing your Agile Team
**3 Keys to Influence:**
1. *Clarify measurable results* (what, why and when you want it)
2. *Find vital behaviors* (identify vital behaviors of your team and promote that beneficial to the changes)
3. *Use the 6 sources of influence* (Personal motivation, Personal ability, Social motivation, Social ability, Structural motivation, Structural ability)

Read more here: https://sourcesofinsight.com/influencer-the-power-to-change-anything/

#### Coaching Your Agile Team
**3 Steps:**
1. *Design the plays with the team* (involve the team in planning, decisions and processes)
2. *Provide real-time and meta feedback to the team*
3. *Celebrate and learn with the team*

#### Challenges on Your Agile Team
1. Value delivery issues
   - missing expected delivery dates
   - burned out
   - too many items "in progress"
   - **Solutions**: More demos of the whole product, retrospectives, understanding "done" means, focus on few user stories per Sprint
2. Business collaboration issues
   - overwhelmed team with critical feedback or change requests (lead to avoiding feedback of clients and complaints on the requested changes)
   - "Us vs. Them" mentality (team vs. management)
   - **Solutions**: More demos, solution design Sprint (how to solve a problem by meeting with all involved), adding changes to the Backlop only between Sprints
3. Team dynamics and culture issues
   - low team morale
   - lots of conflict
   - low conflict, not a safe environment
   - **Solutions**: team brainstorm session (best and worst team), change up workflows, training class, retrospectives

#### Challenges on Agile Coaching
1. Unstable product roadmap caused by product ambition (over-ambitious)
   - **Solutions:**
     - Agree up front how to handle new opportunities
     - Set up regular roadmap reviews with the entire team
     - Promote sharing knowledge between the Product Owner and the Development Team
2. Unstable product roadmap caused by too many product assumptions
   - **Solutions:**
     - Dccument your assumption and share it to the team
     - Conduct unbiased research (surveys, focused groups) to check assumptions
3. Incomplete implementation of Scrum
   - lack of clear roles, skip or blend Scrum events, no Scrum coaching
   - **Solutions:**
     - Implement Scrum completely
     - Roles are well defined and fulfilled
4. Lack of team stability (changes on team composition)
   - **Solutions:**
     - quick onboarding process
     - Pair Programming
     - shorter Sprints

### Emerging Agile Methodologies
- DevOps
- Business agility
- Agile in construction industry

#### Scaling Agile
**Popular Frameworks:**
1. Scaled Agile Framework (SAFe)
2. Scrum of Scrums
3. Large Scale Scrum (LeSS)
4. Disciplined Agile Delivery (DAD)
5. Spotify Model

Read more here: [Lecture on Scaling Agile](https://github.com/ralmario/googlepmguide/blob/main/Documents/Project%20Agile%20Management/Lecture%20-%20Scaling%20Agile.pdf)

## Applying for an Agile Project Manager Role
- **Common Job Positions:** Agile Project Manager, Scrum Master, IT Agile Project Manager, DevOps Project Manager

### Common Agile Project Manager Interview Questions
1. What's the difference between Agile and Waterfall project management?
   - **Ideal Responses:**
     - Agile is abput more than just Scrum, Sprints, and Standups
     - Agile is about founding values that include customer collaboration, value delivery, self-organizing teams
     - Waterfall is not the worst project management approach
     - Understanding that all projects benefit from certain types of approaches, including Waterfall
   - **Sample Answer**
     - Agile is an iterative process, and Waterfall is more linear. Both have their merits, depending on the project.
2. Tell me more about your approach to Agile.
   - **Sample Answer**
     - I plan out the project to ensure customer collaboration, defined value delivery, and space for teams to organize themselves.
3. How do you know when to use an Agile approach or framework on your project?
   - **Ideal Responses:**
     - Understands how Agile or Scrum can help a project manager with specific challenges
   - **Sample Answer**
     - When I learn that the requirements are still being defined, or that we need a phased delivery, I know to go with Agile.
4. If you are facing resistance with your team following a Scrum or Agile practice, how do you convince them to give it a try?
   - **Ideal Responses:**
     - The candidate is aware of how to use communication and influence skills
     - Evidence that the candidate truly believes that an Agile team can be self-organizing
     - The candidate is someone who will work with a team and not try to force certain processes
   - **Sample Answer**
     - I start small. Kanban boards can be a nice entry point because they give my team bite-sized tasks to accomplish.

### Questions for Your Interviewer
1. How supportive is the management here towards blending project management approaches?
2. What's the first thing I should know about the culture here?
3. How often will I get to hear about the needs of our users or customers?
4. What would a typical day look like for me if I were to take on this position?




