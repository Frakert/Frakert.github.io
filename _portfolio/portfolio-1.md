---
title: "Constraint Optimisation - Team assignment"
excerpt: "Optimizing team assignment <br/><img src='/images/500x300.png'>"
collection: portfolio
---

For the AI&ES Master, the team internship had some difficult team formation requirements. Teams needed to be 3 or 4 students, a team could have no more than 2 of the same nationality, a team could have no more than 2 of the same bachelor background, all students needed to have a common timeslot and student preference needed to be taken into account.

Given all of these constraints, it was very diffucult to find an optimal solution for 55 students and 17 projects.

Using Google's Operation Research Tools (ORTools), I used constraint programming techniques to find an optimum solution given these constraints. The tool could give a cost to breaking any constraint, such that even in situations where optimal solution didnt excist the best closest solution could be found.

This tool was then used and ran in real time, ensuring student walked out of the room with their assigned team and a fair assignment.