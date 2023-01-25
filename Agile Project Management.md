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
- [Release plan template](http://)