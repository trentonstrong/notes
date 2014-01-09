## Extreme Planning - Chapter 1 - Why Plan?

- Plans allow us to operate rationally and not succumb to panic under change and unpredictable events.

- Plans can also cause problems when used improperly.  Plans can be used to conceal problems, give a false sense of control, and use up disproportionate resources that could be allocated to development.

### Why We Should Plan

- In order to plan a project effectively one must understand the goals of the project clearly.  Goals need to be specific and concrete in order to be measurable.

- Plans serve the purpose of:

  * Prioritizing by importance the things we need to do so we can work on the most important thing

  * Act as the substrate for team / stakeholder communication and collaboration about what to do.

  * Give an understanding of how unexpected events change the relative importance of things to do, coordinate and distribute the new information.

- Time is the scarcest resource, and is expended on work on one item at the mutual exclusion of other items.

- Planning relies on estimates.  Estimates are often inaccurate and are *always* secondary to actuals.

- In order for a plan to be effective, one must change the plan as soon as the effect of new information is known.  It can then be coordinated with others.

### What We Need In Planning

- Planning occurs at different time scales and different organizational scales.  Plans are fractal in nature and choosing the granularity of planning is important (planning for every step of a walk around the park is not helpful).

- Planning requires measurable milestones in order to provide a reference frame for progress within the plan.  Software is inherently abstract and makes this difficult.  Without a reference frame people feel uncomfortable and unable to find their bearings (both team and stakeholders).

- Planning should *add* visibility so that *everyone* involved with the project can see the progress.  Milestones need to clearly represent progress to *everyone* so they can be understood and trusted.

- Plans need to be simple to build and easy to update.  Complex plans that require too much effort to change are not cost effective.  Simple plans are easily understood by everyone involved.

- Plans need to be honest and include all information available.  Plans should make it more difficult, not easier, to be fooled by inconsequential progress.

### The Planning Trap

- Planning can give a false sense of control over events.  Events are not under our control, only our reactions.  Events *change* plans.

- A complicated plan can hide its disagreement with reality, and often the planner wants to appear to be in control and is motivated to keep up the illusion that things are going according to plan.

- A plan that diverges from reality and is not changed accordingly will cause problems.  Developers will lose morale.  Outside parties depending on the plan will not have the latest information and will base their plans on false data.

- The worst possible thing that can happen to a plan is divergence from reality.  Honest plans continually change.

## Extreme Planning - Chapter 2 - Fear

- Process around building software helps to mitigate fear.

- Fear comes from both sides: customer and developer.

- Customer fears:
  * Deliverable will not be what was required.

  * They will improperly specify the deliverable.

  * Deliverable will cost too much.

  * Developers aren't invested in the project as much as stakeholders.

  * Development will not be transparent about plans.

  * Plans shared will be fictitious.

  * They won't understand technical details or impediments.

  * They will be held to all their decisions and unable to react to business changes.

  * Developers will not be trustworthy.

- Developer fears:

  * Will be given too much work to do in a reasonable amount of time.

  * Will be given requirements that don't make sense or are too vague.

  * Will be unable to achieve requirements because solution is too difficult.

  * Will be held responsible without authority to make project work.

  * Will have to sacrifice engineering quality in order to meet timelines.

  * Will have to solve difficult problems without enough expertise or assistance.

  * Will not have enough time to make project succeed.

### Unacknowledged Fear is the Source of All Software Project Failures

- Unacknowledged fears result in defense mechanisms.  An unacknowledged fear will not be dealt with, but will be avoided and hidden until it is too late.

- Witholding communication based on expectations of an undesired response will always cause problems.

- Customers and developers have rights within any collaborative development process.

### Customer Bill of Rights

- You have the right to an overall plan, to know what can be accomplished when and at what cost.

- You have the right to get the most possible value out of every programming week.

- You have the right to see progress in a running system, proven to work by passing
repeatable tests that you specify.

- You have the right to change your mind, to substitute functionality, and to change
priorities without paying exorbitant costs.

- You have the right to be informed of schedule changes, in time to choose how to reduce the scope to restore the original date.  You can cancel at any time and be left with a useful working system reflecting investment to date.

### Programmer Bill of Rights

- You have the right to know what is needed, with clear declarations of priority.

- You have the right to produce quality work at all times.

- You have the right to ask for and receive help from peers, managers, and
customers.

- You have the right to make and update your own estimates.

- You have the right to accept your responsibilities instead of having them assigned
to you.



- Good development requires a culture that acknowledges fears and uncertainties and communicates about them.  (Painful truths!)

- Once fear is acknowledged, responsibilities and ownership can be taken.  Only then can offensive action be taken.

- Defensive fear-based process is rooted in control, and slows down the entire development effort.

- Offensive process enables setting goals that are difficult to achieve and striving to achieve them as a team.  Offensive process does only what is required to get the work done in an order from most important to least important.

## Extreme Planning - Chapter 3 - Driving Software

- Guiding a software project is a lot like driving where one makes lots of tiny corrections to keep the car on course.

- Once motion on a software project has started, it can take into account feedback (new information) to be used in driving the project.

## Extreme Planning - Chapter 4 - Balancing Power

- Planning process should result in business people making business decisions and technical people making technical decisions.

- Estimates are a good example of a technical decision that business people may try and make.  Those tasked with building something are usually the best pick to estimate how long it will take to build.

- Feature priorities are a good example of a business decision technical people try and make.  The most important feature to work on next is best determined by the customer, not on the basis of how interesting the feature is to the developers.

- Business decisions:

  * Dates
  * Priority
  * Scope

- Technical Decisions:

  * Estimates

### The Customer

- Customers are those tasked with making business decisions, which may include product managers, users, etc...

- The customer is part of the team, not an external entity.  The customer must fulfill their responsibility by making business decisions and providing feedback.

### Finding a Customer

- A good customer:

  * Understands the domain well by working in that domain, and also by understanding how it works (not always the same thing)

  * Can understand, with development's help, how software can provide business value in the domain

  * Is determined to deliver value regularly and is not afraid to deliver too little rather than nothing

  * Can make decisions about what's needed now and what's needed later

  * Is willing to accept ultimate responsibility for the success or failure of the project

### Guiding the Customer

- The customer must always be prepared to answer the question of what is most valuable to work on next.

- The customer must trust the developers' estimates, but understand that there will be estimation errors.  Estimation error tends to decrese over the span of a project.

- *Never* let a date slip.  It's easier and smarter to provide a smaller amount of functionality and release than to skip a release date.

- Release to customers as often as possible, as this improves the feedback necessary to steer the car.  Break large features into smaller bits of functionality that can be released periodically.

## Extreme Programming - Chapter 5 - Overviews

- XP releases are on the order of months, divided into ~2 week iterations.  Tasks are on the order of a few days.  The process of planning allocates stories (chunks of funcionality) into releases and iterations in reaction to reality.

### Top Down XP Outline

- The challenge of planning is to synchronize two different cycles: the business cycle and the development cycle.

- The business cycle revolves around business activities:

  * Press releases

  * Scheduled software releases

  * Training

  * Billing

- Business cycles are termed *releases* in XP.  They are on the order of 1-6 months.

- Development cycles are always shorter than business cycles, in order to accomodate feedback.

- Development cycles are termed *iterations* in XP.  They are on the order of 1-3 weeks.

- Short, few week iterations present a problem: only a relatively small amount of development can be accomplished in that amount of time, and rarely can anything be considered 'complete'.   Another measure of progress is needed: the *story*.

- Stories represent a feature of the software, ideally something someone could tell someone else that the software does.  "Amazing ToDo App sorts my todo items by importance!"

- Stories have to be small enough to fit into an iteration, and usually there will be more than one story per iteration.  Stories should take a few days to a few weeks to implement.

- The resulting system at the end of an iteration should be fully-tested and production ready system.

- Automatic testing greatly assists in maintaining verification of a system's stories.  Adding sets of stories each iteration does not then require work to re-verify the work of previous iterations.

### Bottom Up XP Outline

- What if you shrink the entire software development lifecycle -- spec, design, implementation, testing, deployment, documentation -- into two weeks?  One can only achieve a little of each in that cycle, necessarily shrinking the problem size.  Some elements of the lifecycle may not always be necessary on a smaller cycle.

- Each element of the lifecycle will not be treated as a linear phase, but will be distributed across the cycle.  Every work day involves a little design, a little development, etc...

- At the end of an iteration, one has a deployable piece of software without a lot of features.  Each iteration will add features to that deployable piece of software.

- Planning allows us to pick the most important feature to add to the deployable piece of software next.  The business picks the most important features at the beginning of each iteration.

- Planning lays out the whole of required to develop.  What to work on is chosen each iteration (each couple weeks).

- The end result is a plan of small changes, such that when a piece of the plan does not go as expected the information is known as soon as possible and can be reflected in the overall plan.

## Extreme Programming - Chapter 6 - Too Much to Do

- Time is a scarce resource that cannot be created.  Overload is the consequence of trying to put too much work into too small an amount of time.

- The only responses one can have to overload are to:

  * Prioritize and not do some things

  * Reduce the size of some things to do

  * Delegate the things to do to someone else

- There is a way out of having too much to do, but not a way out of not enough time.

## Extreme Programming - Chapter 7 - Four Variables

- Four variables control the development of a project:

  * Cost

  * Quality

  * Time

  * Scope

- Each variables is related to the others and therefore cannot be adjusted independently.  Fixing one variable affects the other variables.  

- Adjusting a variables has effects that are delayed and usually non-linear.

### Cost

- Cost is comprised of several sub-variables, the most obvious and important of is people on the project.

- Adding people to a project has a delayed, non-linear effect in development speed.  There is a major drag force caused by adding people to a project that results from an increased overhead in the communication between people on the project.  The effect is not easy to predict and can only be measured for a specific team / project.

- People need time when joining a project to come up to speed before they are contributing at the level of experience members of a project.

- Tools are another possible cost, with a similar effect as adding people.  Tools have a warmup time and their effectiveness can only be known after a while.

- Overtime of existing people can speed up a project in the short term, but will have detrimental effects that show up quickly.  Humans are driven by motivation, and motivation is easily harmed.  On top of that, overworked humans make mistakes, and mistakes cause more work to be created in order to correct the mistake.

### Quality

- There are two types of quality in software, external (perceived) quality and internal quality.

- External quality is best controlled via scope, and includes things such as aesthetic quality and performance.  External quality also includes bugs.

- Bugs (defects) will often need to be traded for stories during development.  This is controlled via scope.

- Internal quality should be kept as high as possible at all times.  Internal quality includes the quality of system design, the quality of internal testing, and so on.  Sacrifices in internal quality will never pay off in the long run as it will result in a higher effort to add functionality in the future.  The predictability of development can only be guaranteed by keeping internal quality static.

### Time and Scope

- Time and scope are the best variables to control in the short term and in a predictable manner.  It is typical to consider cost and quality fixed during planning.

- Scope has a natural tendency to increase and is inversely related to time.  Time is difficult to reason about and not explicitly visible.

- Planning makes the time variable visible, and shows the relationship between scope and time.

- Using iterations allows us to measure progress at the end of every few weeks, making the effects of scope changes very visible.

### Shopping for Stories

- Planning can be thought of as analagous to shopping on a budget.

- The entities involved in shopping are:

  * Items

  * Prices

  * Budget

  * Constraints (We must have milk!)

- Planning equivalents:

  * Items = Stories

  * Prices = Estimates

  * Budget = Measured progress in terms of estimates (velocity)

  * Constraints are business and technology constraints!

- Other analogies:

  * Sales: some stories or types of stories may turn out to be easier to implement than expected.

  * Rain check: Some stories will have to be re-scheduled for another iteration.

  * Inflation: Some stories will may turn out to be harder to implement than expected.  Future estimates will go up.

- Choosing what to work on in an iteration is "shopping" for stories, with all the relevant analogies applied.


## Extreme Planning - Chapter 8 - Yesterday's Weather

- As the basis for your planning, assume you'll do as much this week as you did last week.  Since estimating the capacity of a project's team is so difficult, it's best to base it on empirically measured values.

- Planning capacity is determined by the moving average of the number of stories / features / points done per iteration.

- Properties of the "Yesterday's Weather" rule:

  * We won't habitually overestimate our abilities. We have to use actual accomplishment. If we overestimate once, we won't be able to the next time.

  * If we are overcommitted, we will tend to try to finish some items in any given time period instead of half finishing them all. It is so embarrassing to tell the customer they can have zero features next time.

  * On the other hand, if we have a disastrous period, we are guaranteed a little breathing space to recover.

  * Everyone learns to trust our numbers because they are so easy to explain.

  * Our estimates automatically track all kinds of changes— changes to the team, new technology, dramatic changes in product direction.

## Extreme Planning - Chapter 9 - Scoping a Project

- The best way to begin the planning process is to plan at a coarse level first, to get a feel for the size of the project.

- Step 1: Run the shopping game at a coarse level with the following analogies:

  * Items: Big stories (epics)

  * Prices: rough estimates of epics

  * Budget: estimated number of people on the project

  * Constraints: supplied by the customer with business knowledge

- Goal is to determine if project makes sense as conceptualized.

- The rough plan is a conversation starter, meant to begin honest conversation about project requirements and scope.

### Making the Big Plan

- Purpose of big plan is to figure out how much to invest

- Addresses this question by:

  * Breaking the problem into pieces.

  * Bringing the pieces into focus by estimating them.

  * Deferring less valuable pieces.

- Start with a conversation about the system.  Try to keep it abstract.

- Do not plan details at this point.  Estimates should be very coarse (months).

- This should be a fast sketch, do not invest too much time.

## Extreme Planning - Chapter 10 - Release Planning

- Release planning synchronizes the dates and scope of the project between business and development.

- Releases can be internal, but exist for business reasons or in the interest of releasing often.

- Release planning allocates stories into releases and iterations.

- Release planning strategies:

  * Break big stories (epics) into smaller stories.

  * Sharpen focus on stories by estimating how long they will take.

  * Defer least valuable stories until stories fit in capacity (time left / allocated).

  ### Who Does Release Planning?

  - Release planning involves both parts of the team, customer and developer.

  - Customers drive release planning while programmers help navigate by responding with feedback and context.

  - Customers choose which stories to place in which release and which stories to backlog.  Developers provide estimates for sensible allocation of stories.

  - The customer

	* Defines the user stories
	
	* Decides what business value the stories have
	
	* Decides what stories to build in this release

  - The developers

	* Estimate how long it will take to build each story
	
	* Warn the customer about significant technical risks
	
	* Measure their team progress to provide the customer with an overall budget

### How Stable is the Release Plan?

- Release plans are inherently unstable.

- Any time the customer changes their mind about priority or requirements, the release plan must be updated.

- When developers learn new information about the project (speed of implementation), the release plan must be changed to reflect this.

- A release plan is just a current snapshot of state and knowledge to orient the team.

- The release plan *will* change.

### How Far in Advance Do You Plan?

- Release should be planned 1-2 releases in the future (current release and next one).

- Iterations should be planned 1-2 iterations in the future (current iteration and next iteration).

- The cost of keeping the plan up-to-date is proportional to how far in advance you plan.  Plans far in the future are inherently volatile, and therefore the cost-benefit ration declines the further ahead you plan.  The break-even point is more art than science.

### How Do You Plan Infrastructure?

- How do you plan for infrastructure requirements such as messaging queues, databases, automated testing, CI, deployment?

- Infrastructure development *should not* precede functionality.  It should be built just in time corresponding to functionality that needs it.

- Infrastructure without feature development exposes the following risks:

  * You spend a lot of time not delivering things that are valuable to the customer, which strains the relationship with the customer.

  * You try to make the infrastructure cover everything you think you might need, which leads to an overly complex infrastructure. (YAGNI)

- Building the infrastructure as you need it (for the stories in the iteration) allows the customer to see how the infrastructure relates to the functionality which aligns the interests.  Just because you can guess into the future at what you will need does not mean you should build it this second.

### How Do You Store the Release Plan?

- Each story is contained in a "card".

- Group cards together by release.

- Store future story cards away.

### How Much Can You Put into a Release?

- Velocity is the rate at which a development team completes features (measured in units of choice).

- Sum of effort in a given iteration cannot exceed current velocity.

- Sum of effort in a given release cannot exceed number of iterations * current velocity.

## Extreme Planning - Chapter 11 - Writing Stories

- Story is base unit of functionality

- Progress is demonstrated by delivering tested, integrated code that implements a story.

- Stories should be understandable by customers and developers, testable, contain business value, and small enough to fit several in an iteration.

- Stories should be simple!

### Principles of Good Stories

- Stories must be understandable to the customer and written in natural language.

- Stories should be terse enough to fit on an index card in big letters.

- Stories should represent a concept.  They are not the specification.

- Stories represent an agreeement that the developers and customer will talk about a feature in the future.

- Details can be provided later during the implementation of the story, and planning to details does not reduce uncertainty.

- Stories must provide something of value to the customer.

- Stories should be of a size to fit a few in each iteration.

- Customers write the story, developers estimate the story.

- Stories are independent of each other.  It is best to ignore dependencies as important ones will shake out during implementation.

- Each story must be testable in order to determine whether or not it is done.

### Feedback from Estimation

- It is easy to write stories that cannot be estimated.

- Conversations are often needed to elicit concrete stories from vague or abstract stories.

### Prioritizing User Stories

- Prioritization needs to identify the order stories should be implemented.

- Elements of differing priority within a story should be split into separate stories.

- It is easiest to detect differing priority within a story during iteration planning and estimation or development.

### Traceability

- Acceptance tests determine whether stories are implemented properly.

### Splitting User Stories

- Splitting a story means creating two new stories and removing the old one.  The new stories are then re-estimated and re-prioritized by the customer.

- Many events trigger story splitting:

  * When you're writing the initial stories the developers may say that a story is too large.
  
  * When you're doing release planning you find you cannot fit all of a story into an iteration. Then you can split the story so that part of it can be done in the iteration.

  * As you're tracking an iteration you realize you have too much to do.

- Splitting a story may require some trial and error between customer and developer to determine the proper split.

### User Story Adornments

- Stories should only contain:

  * The name

  * The story itself

  * Estimates

### The Story Writing Process

- Stories are iterative in nature, and require lots of feedback and trial-and-error to get right.

- Questions to ask while iterating on stories:

  * Can the story be tested?

  * Can the story be estimated?

  * Can the story fit in an iteration with other stories?

- Stories should be written in chunks of 2-5, then estimated by developers.  This keeps the story creation process iterative.

- Sometimes stories will require exploratory programming in order to estimate.

### When Are You Done Writing Stories?

- The story process does not stop until the project is over.

- Development begins when the customer feels they have identified the most important stories and you have enough stories for multiple months worth of development.  There should be enough stories for the customer to make meaningful tradeoff decisions.

- Stories are often about feeling heard, especially at the beginning of the project.  It is good for morale for everyone to feel heard.

- The aim of iterative development is to deliver software that meets the requirements at the time of release, not at the beginning of development.


### Disposition of Stories

- Once stories are implemented, they are disposed.  Acceptance tests provide better documentation of an implemented system.


## Extreme Planning - Chapter 15 - The First Plan

- First plan is based on 0 history of accurate estimates.  Therefore estimates will be very inaccurate.

- First plan is required to get started and build a history for accurate estimates.

- First plan has two major uncertainties: team velocity and story size.

- Since velocity is an empirical quantity, velocity of the first plan must be a guess.  A fudge factor approach often works here based on a priori knowledge of how team members work.

- Have developers estimate the most "comfortable" stories first.  Then estimate other stories based on comparison.  Estimate in terms of ideal days, with no distractions.

- Do not let anyone other than the team estimate the stories.  This sets external expectations that can damage morale.

### Choosing Iteration Length

- Short iterations around 2-3 weeks give frequent updates as to project progress, and therefore better estimates of velocity.

- Iterations come with overhead which must be considered in iteration length.  Overhead comes from:

  * Running acceptance tests (automate as much as possible)

  * Iteration planning

  * Reporting to management

- Overhead cannot exceed or be on order of what is attempted in an iteration.

### Getting Started

- Often a good starting iteration is to achieve things like:

  * Getting the testing framework working

  * Getting the automated build structure working

  * Getting the network up and running with all the appropriate permissions

  * Getting the basic install scripts set up

