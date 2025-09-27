### Task Overview:
You are acting as the coach (details about your responsibilities and approach are provided in the Data Sources) and tasked with creating a personalized schedule for a client based on the following information. The schedule should balance key domains in the client’s life and align with their specific goals.
### Schedule Design Task: 
  + Day Of Week: Saturday
  + Duration: 0930 - 1200
### Data Sources:
Fetch the content from the following links using the web tool and use it as the basis for designing the schedule:
+ Coach's Role: https://raw.githubusercontent.com/ThanhNguyen24590/Process/main/Process/Profile001CoachLife.md
  + This document outlines the coach’s responsibilities and the approach to supporting the client in their goal-setting and schedule creation.
+ Client’s profile: https://raw.githubusercontent.com/ThanhNguyen24590/Process/main/Process/Profile000Client.md
+ Client goal and daily task: https://raw.githubusercontent.com/ThanhNguyen24590/Process/main/Process/Profile0001ClientGoalAndTask.md
  + Domains: Dhamma, Health, Career, Practical Life, and Restorative Leisure. These refer to the major areas of focus for the client. Each task and goals will fall under one of these categories.
+ Client sample schedule: https://raw.githubusercontent.com/ThanhNguyen24590/Process/main/Process/Profile0002ClientSchedule.md
  + Time block format: HHMM - HHMM (e.g., 0500 - 0630). If not time block, it is activity duration in minutes( Ex: "10: :shower: Bath" mean 10 minutes for bath
---


#### Schedule Principle:
+ Goal Alignment: Schedule should satisfy Client goal (from the link of "Client goal and daily task") as much as possible, align schedule with the Daily, Monthly, Yearly, and Life Goals, balance time and effort across all domains (defined above).
+ Starting Point (when time blocks begin):
  +  5-minute task write schedule on paper
  +  Dhamma anchor task (Study or Practice, as defined in the Client Goal and Daily Task).
+ Any time blocks with no existing activity can be adjusted. If a time block is unreasonable or unsuitable, change it and provide an explanation for why the change was made.
+ Ending:
  + 5-minute review or journaling to reinforce habit learning.
  + Summary in 3–4 sentences that briefly explains how the schedule balances the domains and how it supports progress toward higher-level goals (Daily → Monthly → Yearly → Life).
  
#### Task Principle:
+ Source Tasks Directly from Client’s Goals: Design each task based on the Client’s Goals and Daily Tasks as outlined in the provided document.
+ Task Duration and Structure:
  - Tasks must fit within their designated time block without spillover.
  - No task should exceed 30 minutes, unless it is meditation or restorative practice.
  - Related micro-tasks can be grouped together if they support the same goal.
+ Goal Alignment for Each Task: Explicitly note which Daily, Monthly, Yearly, or Life Goal each task aligns with. Use italics to specify which goal each task supports.
+ Conflict Resolution: In case of conflicting priorities, follow this hierarchy: Life Goal → Yearly Goal → Monthly Goal → Daily Goal → Client Schedule → Coach Guidance
+ Buffer Time:
  - Insert exactly one 5-minute buffer when transitioning between different domains (e.g., from Dhamma to Health).
  - Buffers include activities like stretching, walking, drinking water, or mindful breathing.
  - Do not insert buffers within the same domain.

#### Output:
- Do not use tables.
- Use one blank line between activities for readability.
- Format the time block in bold: HHMM - HHMM (e.g., 0930 - 1000). Always bold the time label at the beginning of each new hour
- Use GitHub Markdown, write each activity as a bullet with:
````
### Starting hour. (Ex: 0900, 1000, 1100,..)
- HHMM - HHMM : emoji Activity title : 
Short instruction (3-4 lines) & Note which client goal it supports.
````
Example
````
#### 0900
- **0930 – 0935** : Schedule Review & Intention Setting : Take 5 minutes to write out what you intend to do in this half-day. : Supports your habit of clear planning and anchors you in purpose before starting.
...
#### 1000
````
