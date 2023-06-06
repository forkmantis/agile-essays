# Theory of Constraints #

Have you ever kinked or bent a waterhose to stop the flow of water?  The choke point, or constraint you make restricts the flow of water.  It doesn't matter what the diameter of the hose is before or after the constraint.  The entire flow of the hose is reduced to only what can pass through that constraint.

Work flowing through a development team operates much in the same way.  If you think of your sprint as a flow of work through a hose, the total output of the system is limited to what can flow through the most constrained part of the system.  Doing more work before the constraint won't increase total output, because that work will just pile up at the constraint.  You cannot do more work after the constraint, because the constraint limits how much work is available to do downstream.

Often times developers want to stay busy writing code, but the velocity of their team doesn't increase because of some constraint after that portion of the system.  The only way to increase velocity is to alleviate the biggest constraint.  Maybe it's code reviews.  Maybe it's testing.  Maybe it's releasing.  Whatever it is, you have to find a way to address the constraint or the team's velocity will not increase.  

Ideally a team finds a way to alleviate the constrained portion of their system.  Success, right?  Kinda.  Relieving one constraint will reveal whatever is the next most constrained portion of a system, which will reveal the new maximul flow of work.  It's not as bad as it sounds, however.  A system will never be perfect and will always have a constraint somewhere.  You just have to be sure that you address all of the constraints that can be addressed responsibly.  From there, your system will have slack time.  Slack time is the unused bandwidth in your system before and after the limiting constraint.  Don't feel guilt about this slack time.  Use it productively.  Initially slack time can be invested towards attacking constraints.  Over time, it can be invested in other ways.

In closing, have your team take a look at your process regularly and see if you can identify your limiting constraint.  This will usually be obvious by which Jira column cards seem to get stuck in during your sprint.  Invest your slack time trying to address that constraint, knowing that success will probably lead you to discovering a new limiting constraint.  Continue to address your constraints until your system is fine tuned, and then make good use of the slack time you have in your new system.
