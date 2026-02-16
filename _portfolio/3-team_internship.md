---
title: "Constraint Optimisation - Team assignment"
excerpt: "Optimizing team assignment <br/><img src='/images/Team_Allocation.png'>"
collection: portfolio
---

![Image generated using NanoBanana.](/images/Team_Allocation.png)

For the AI&ES Master, the team internship had some difficult team formation requirements. Teams needed to consist of 3 or 4 students. A team could have no more than 2 students of the same nationality and no more than 2 students with the same bachelor’s background. All students needed to have a common timeslot, and student preferences needed to be taken into account.

Given all of these constraints, it was very difficult to find an optimal solution for 55 students and 17 projects.

Using Google's Operations Research Tools (OR-Tools), I applied constraint programming techniques to find an optimal solution given these constraints. The tool could assign a cost to breaking any constraint, such that even in situations where an optimal solution didn’t exist, the closest best solution could be found.

This tool was then used and run in real time, ensuring students walked out of the room with their assigned team and a fair assignment.