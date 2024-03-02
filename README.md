**Schedule-Creator Program Overview**

**Running The Program**
To initiate the program, execute the script `ui.py`.

**Program Purpose**
This scheduling software was originally designed for the administrative staff at a summer camp. It facilitated the generation of group schedules for campers, taking into account various constraints specified by the camp.

**Schedule Layout**
Each group's schedule comprises 6 periods – 2 in the morning and 4 in the afternoon. The morning sessions involve 2 sports activities, while the afternoon includes lunch, a swim, and 2 additional sports activities. Lunch and swim sessions consistently occur at the same period each day.

**Schedule Rules**
Several rules govern the schedule creation process:
- No group can have the same activity more than 3 times a week (ideally 2 times).
- The same activity cannot be scheduled for a group on the same day.
- Two groups cannot have the same activity at the same time.
- If an activity occurs twice in a week, it should be at least one day apart from the last occurrence.
- Activities occurring more than twice in a week should be in the opposite part of the day. For example, if soccer is in the morning, the second occurrence should be in the afternoon.
- Group 2 will never participate in tennis.

**Details**
The office staff manually create schedules for each group every week. The primary goal is to maintain diversity in each group's schedule, ensuring participation in as many activities as possible. Given the complexity of balancing activities both between groups and within individual schedules, the process is akin to solving an advanced version of sudoku.

**Limitations**
Certain constraints chosen in the program interface may render schedule generation impossible. For instance, if there are 10 groups and only 8 morning activities available, scheduling becomes impossible due to the restriction of activities occurring simultaneously.

Feel free to ask if you have any specific questions or if there's anything else you'd like assistance with!
