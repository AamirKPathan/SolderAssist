---
title: "Solder Assist Development Journal"
author: "Aamir Khan Pathan"
project: "Solder Assist"
created_at: "2026-07-25"
status: "Completed"
---

# July 25, 2026 — Solder Assist CAD Design

The goal of this session was to design a compact and adjustable tool for holding circuit boards, wires, and small electronic components during soldering.

I first planned the project around a weighted base, three articulated arm sections, and simple friction joints. I chose a steel base for stability, 3D-printed parts for easy manufacturing, and M3 hardware because it is inexpensive and commonly available.

I then designed the base, vertical arm, horizontal arm, and lateral arm as separate components. Creating each part separately made the project easier to modify and allowed individual parts to be replaced without redesigning the entire assembly.

![Solder Assist base](../Images/Base.png)

![Solder Assist vertical arm](../Images/Vertical%20Arm.png)

![Solder Assist horizontal arm](../Images/Horizontal%20Arm.png)

![Solder Assist lateral arm](../Images/Lateral%20Arm.png)

After completing the parts, I assembled them in CAD to check alignment, joint movement, clearances, and overall proportions. I adjusted the component positions until the arm could move through a useful range without interfering with itself.

![Complete Solder Assist CAD assembly](../Images/Solder%20Assist.png)

The main challenge was balancing adjustability with simplicity. I considered more complicated joints using FRC 1/2" ball bearings, but selected friction-based joints to reduce cost, part count, and manufacturing difficulty.

The completed files were:

```text
CAD/Base.step
CAD/Vertical Arm.step
CAD/Horizontal Arm.step
CAD/Lateral Arm.step
CAD/Solder Assist.step
```

By the end of the session, the full CAD assembly was complete, the files were organized, and the project was ready for physical manufacturing and testing.

**Total time spent: 1h**
