# Methodology Specification

## Rules

1. The team owns the project. There are many kinds of work to be done, and any
   work can be done by any team member. You are authorized to contribute in any
   way to the project. Some people will tend to work on particular aspects of
   the project, but that is by choice, not as a rule.
    - We foster [T-shaped
      skills](https://en.wikipedia.org/wiki/T-shaped_skills), such that all team
      members share core competencies, and individual team members provide depth
      in particular areas.


1. The team formulates a _mission statement_. This is one or two sentences that
   describe the goal of the project.
   - The primary purpose of the mission statement is to allow the team to say
     &ldquo;no&rdquo; to good ideas.


1. Use Slack for team communication.
    - The `#general` and `#random` channels are available for studio-wide communication.
    - The team may set up its own channels as needed, giving each a recognizable
      prefix corresponding to the project. 


1. We start each production day with a &ldquo;daily standup&rdquo; meeting,
   during which each member reports on the following to their team:
    - What did you contribute since last time?
    - What do you plan to accomplish before next time?
    - Are there any impediments?

    Note that _impediments_ are obstacles that stand in the way of your goals
    but that can be removed or worked around. They are never excuses for failing
    to meet commitments.

    If a team member is unable to attend a meeting, they must post to the
    #general channel on Slack.


1. The team will track its plan on [HacknPlan](HacknPlan.com).

    - Each board will have the following top-level lists:
        - _Not Yet Started_ for work items that are part of the sprint but have not yet been started;
        - _In Progress_ for work items that are currently being completed;
        - _Needs Validation_ for work that is complete to the best ability of those working on it, but which has not yet been reviewed by the team or corresponding lead;
        - _Done_ for work that is done.
        - Optionally, a _Backlog_, which contains work items that are not part
          of the current sprint but may be picked up in the future.

    - Each card in a list represents a "work item", most of which are features expressed
     from the users's perspective. 
       - Include, clearly and consistenly on each card, the total number of
         hours estimated remaining to complete it.
       - Non-atomic work items use named checklists to track the tasks necessary
         to complete a feature.
         - Each checklist item should be expressed as a _condition of satisfaction_ or
         an _acceptance test_. Each should be [specific, measurable, assignable,
         relevant, and timely](https://en.wikipedia.org/wiki/SMART_criteria).
       - Team members are assigned to features when they commit to working on them.
         - These team members are responsible for ensuring that the feature is
           completed. This does not mean that they have to be the ones to do all
           the work, but it does mean that they should always know the state of
           the feature.

    - After every work session, each team member updates the number of hours
      estimated remaining on the features they have touched. Note that estimates
      may increase, decrease, or remain the same. 
       - A feature that is complete to the working group's satisfaction is moved
         to _Needs Validation_, with its estimate updated to be the time for
         validation. The nature of validation is task-dependent, but
         frequently-used methods include some form of code/peer review.
       - A feature that has been validated and has no hours remaining on it
         should be moved to _Done_.

1. The project mentor maintains a _burndown chart_, which plots time against the
   estimated hours of work remaining. The chart is updated after each planning
   and standup meeting. 
   - The burndown chart may be kept on paper or digitally.
   - It should be referenced during or before stand-up meetings in order to
     provide feedback to the team about what they have learned and accomplished
     during the iteration.
   - The burndown chart, if maintained on Google Sheets, can be 
     [integrated into HacknPlan](https://www.youtube.com/watch?v=hfbcO7fxa2g).


1. All team members maintain effort only on tasks that are part of the current
   iteration.
    - Corollary: Solve the problems you have, not the problems you might have later.


1. Every team member has _Stop Work Authority_. This means that if you witness
   something that impacts the safety of the team, you may signal for the team to
   stop work. The team then redirects their attention to the safety issue.


1. If a team member has a conflict with another team member, he or she should
   talk to that individual about it privately first, face-to-face. If a
   resolution is not met, the issue should be brought to the project mentor.


1. When faced with a design conflict (on any piece of work) where two or
   more team members disagree, monitor the amount of time spent on the
   discussion. If a resolution is not found within five minutes, take one of the
   following options:
    - Invite the project mentor for a consultation.
    - Get a volunteer for each side. Schedule a follow-up meeting, with all
      relevant stakeholders, at which time each volunteer will be expected to
      demonstrate prototypes to defend their positions. After this, the
      stakeholders vote on which direction to pursue.


1. Prefer working in pairs whenever possible, particularly on technical and
   integration tasks. Rotate pairs at least once a week to ensure that knowledge
   is distributed across the team.


1. The team chooses a version control system and follows the conventions for that
   system.
    - This could be google docs, github, or any other suitable version control.


1. When interacting with any outside of the team, including but not limited to, any communication (via email, slack, or other) or class presentations will be reported to the project mentor.