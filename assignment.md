PART A: Diagnosis
Situation A - The Alert Nobody Responds To
1.Stated Problem: 
The daily alert email goes out every morning. The CEO sees red items. The same items stay red for days. Nobody escalates, nobody responds. Anil and Karthik say: "We send the report every day, we don't know why they don't act on it."
The CEO says: "I don't have visibility."
2. What is actually going on: 
The real problem is that the alert email only shows that there is an issue, but it does not clearly tell who is responsible for fixing it or what action need to be taken. Anil and Karthik send the report everyday and assume their job is done. while the department heads are not directly alerted and may not feel responsible for responding. The CEO keeps seeing the same red items, but he cannot easily understand who owns them, what has been done so far, or why they are still unresolved. As a result, everyone can see the problem, but no one takes ownership of it, so the same issues remain red for days without any action. There is also no defined process for what should happen when something turns red. who escalates, to whom, and by when. Without this, the alert is just information, not a trigger for action.
3. Evidence from the scenario:
 The scenario provides several clues that support this conclusion. The same items remain red for days, showing that issues are being identified but not resolved. Anil and Karthik say, "We send the report every day, we don't know why they don't act on it," which suggests they see their responsibility as only sending the report, not ensuring action is taken. The CEO says, "I don't have visibility," even though he receives the alerts, indicating that the report does not provide enough information about ownership, actions taken, or progress. The fact that nobody escalates or responds to the red items further shows that there is no clear accountability or defined process for handling issues once they are reported.


Situation B - The Blank Field
1.Stated Problem: 
The deviation tracker has a root cause field. 70% of entries are blank or generic. Anil and Karthik say: "People are not disciplined enough to fill it." The supervisors say something else entirely.
2. What is actually going on: 
The real problem is not that people lack discipline. The supervisors often know exactly what went wrong, but they avoid writing honest root causes because they fear being blamed for the issue. The last time someone documented a genuine root cause, that person was publicly criticized in a review meeting. As a result, employees have learned that being honest can lead to negative consequences, while leaving the field blank or writing a generic response is safer. This means the deviation tracker is not failing because people do not understand its importance; it is failing because the system unintentionally punishes honesty. Over time, this has created a culture where people protect themselves rather than openly reporting problems, making the root cause field unreliable and reducing the organization's ability to learn from mistakes and prevent them from happening again.
3. Evidence from the scenario: 
The scenario states that 70% of the root cause fields are either blank or contain generic responses, which indicates a widespread pattern rather than a few isolated cases. It also shows a clear difference in perspectives: Anil and Karthik believe that people are "not disciplined enough to fill it," while the supervisors "say something else entirely." This suggests that the issue may not be simple negligence or lack of discipline. The material further states that when someone previously wrote an honest root cause, that person was publicly blamed during a review meeting. As a result, supervisors intentionally leave the field blank or provide generic answers to protect themselves. This directly supports the conclusion that employees are avoiding honest reporting because the system associates transparency with personal blame, effectively discouraging accurate root cause documentation.






Situation C - The Meeting That Eats the Day
1.Stated Problem: 
The daily status meeting is scheduled for 30 minutes. It runs 60-90 minutes. After the meeting, everyone's day is derailed by new unplanned work that surfaced during the meeting. Anil and Karthik say: "Technical issues come up that we have to discuss."
2. What is actually going on:
 The real issue is poor planning and process management rather than the meeting itself. Since departments do not have daily micro-plans, routine work, planned tasks, and unexpected issues all get mixed together and discussed during the meeting. As a result, the meeting becomes a problem-solving session, runs much longer than intended, and creates additional unplanned work. The advisor pointed out that if there is no daily plan, then everything becomes unplanned meaning the company has no way to distinguish a genuine emergency from a routine task that was simply not planned properly
3. Evidence from the scenario: 
The meeting is scheduled for 30 minutes but regularly lasts 60–90 minutes. New unplanned work emerges from the meeting and disrupts the rest of the day. Anil and Karthik explain that technical issues need to be discussed, showing that the meeting is being used to handle operational problems rather than provide quick status updates. The senior advisor calculated that 12 people times 10 minutes equals 120 minutes, yet the meeting is scheduled for only 30  showing the format was never realistic. He also found that no department has a daily micro-plan, confirming that the planning gap is the root cause.






PART B: Intervention Design
Situation A - The Alert Nobody Responds To
1. First conversation
I would first speak with the department heads whose items remain red for several days. I would ask, "When an item turns red, what do you believe you are expected to do? Who owns the next action, and how do you know when an issue should be escalated?" This helps identify where accountability is breaking down.
2. Changes in the first 2 weeks
Assign an owner for every red item and define a simple escalation rule. During the daily review, each red item must have a named owner, an action plan, and an expected resolution date. Follow up on unresolved items daily.
3. System / Tool Design
What does the user see?
A dashboard showing Red Item, Owner, Status, Action Taken, Escalation Level, and Due Date.
Workflow
Issue turns red → Owner is assigned → Owner updates status → If unresolved after a defined period, it automatically escalates to the next level → CEO sees ownership and progress.
Technology
Google Sheets + Power Automate email notifications. Easy to implement and accessible to everyone.
4. Getting buy-in from a 15 year veteran:
I would tell the supervisor: "This is not about extra reporting. Right now, people spend time explaining why issues are still open. If ownership is clear from the beginning, fewer follow-up calls and meetings are needed."



Situation B - The Blank Field
1. First conversation
I would speak with supervisors who regularly leave the field blank and ask, "What happens when someone writes the real root cause? Why do people avoid filling this section? The goal of this conversation is only to listen — not to fix anything yet."
2. Changes in the first 2 weeks
Stop publicly blaming individuals during review meetings. Focus discussions on process failures rather than personal mistakes. Recognize teams that provide honest and useful root-cause analysis.
3. System / Tool Design
What does the user see?
A simple form with Deviation, Root Cause, Corrective Action, and Preventive Action fields, along with examples of good root-cause statements.
Workflow
Supervisor enters deviation → Root cause is recorded → Manager reviews the quality of analysis → Action items are assigned and tracked.
Technology
Google Forms linked to Google Sheets. Simple, low-cost, and easy for supervisors to use.
4. Getting buy-in from a 15 year veteran:
I would say: "I'm not asking you to write more. I'm asking you to help prevent the same issue from happening again. If we hide the cause, the same problem keeps coming back and creates more work for your team."






Situation C - The Meeting That Eats the Day
1. First conversation
I would talk to team leads and supervisors and ask, "What percentage of today's meeting time is spent on status updates versus problem-solving? Why are these issues only being discovered during the meeting?"
2. Changes in the first 2 weeks
Introduce a daily micro-plan for each department. Limit the status meeting to updates only. Any issue requiring detailed discussion is moved to a separate problem-solving session with only the relevant people.
3. System / Tool Design
What does the user see?
A daily planning board showing Planned Work, Routine Work, Unplanned Issues, Owner, and Status.
Workflow
Departments create a daily plan in the morning → Status meeting reviews progress against the plan → New issues are logged separately and assigned for follow-up discussion.
Technology
Google Sheets or Microsoft Excel shared online. Easy to update and visible to all departments.
4. Getting buy-in from a 15 year veteran:
I would tell the supervisor: "The goal isn't to add paperwork. The goal is to reduce the time you're spending in meetings. If we separate planning from problem-solving, you can get back to the shop floor faster and spend less time sitting in long discussions. The first time I introduce the daily plan, I will sit with the supervisor and fill it together I will not just send a form and expect them to figure it out alone."


PART C: Scale Thinking
1. What breaks first as the company scales?
The most dangerous failure point is the lack of clear ownership and accountability. With only two projects, people can still rely on informal communication and personal follow-ups to keep work moving. However, when the company grows to eight projects and hires more analysts, issues will start falling through the cracks because nobody will know who owns what, who should escalate problems, or who is responsible for taking action. This problem is already visible in the alert system, where issues remain unresolved even though they are visible to everyone. As the number of projects increases, this confusion will multiply and create delays, missed commitments, and poor visibility for management. At 2 projects the CEO can still follow up manually. At 8 projects that becomes impossible the system must do it automatically.
2. What system or process would you design now?
In the first three months, I would build a Project Ownership and Escalation Tracker using Google Sheets. Every deviation, alert, action item, and project task would have a clearly assigned owner, due date, current status, and escalation path. The sheet would also define what happens when an item becomes overdue and who must be notified. The goal is to make ownership visible and consistent across all projects before the company scales. This creates a common way of working that new employees can easily follow.
3. What do you automate, what do you keep human, and why?
I would automate repetitive and rule-based activities such as status reminders, overdue alerts, escalation emails, and daily summary reports using Power Automate. Google Sheets would serve as the central source of information, while WhatsApp notifications could be used for urgent reminders. Claude can help summarize trends, identify recurring issues, and prepare management reports.
However, I would keep root cause analysis, problem-solving discussions, prioritization decisions, and supervisor conversations human. These activities require judgment, context, and trust, especially because Part A showed that cultural issues such as fear of blame and lack of accountability are major challenges. Automating these decisions could reduce engagement and create inaccurate conclusions. Technology should support people in taking action, not replace the conversations and accountability needed to solve problems.

 

