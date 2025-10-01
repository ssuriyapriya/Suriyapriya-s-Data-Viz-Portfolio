| [home page](https://ssuriyapriya.github.io/Suriyapriya-s-Data-Viz-Portfolio/) | [critique by design](critique-by-design) | [final project I](final-project-part-one.md) | [final project II](final-project-part-two.md) | [final project III](final-project-part-three) |

# User research 

## Target audience

Primary Audience: Hospital Administrator, Outpatient Clinic Manager, Inpatient Department Head.

Since it's hard to find those exact people, I will be interviewing three individuals who can serve as proxies for a professional audience: a graduate student in MBA program, a friend who works in a healthcare analyst role, and a student from MSPPM. These individuals are accustomed to analyzing systems and interpreting data visualizations. I have selected individuals who are not deeply familiar with my project to ensure fresh, unbiased feedback. I explained that I am seeking about 15-20 minutes of their time for a university project to get their thoughts on a data story draft.

## Interview script

(1) Introduction (2 minutes)
"Hi, thank you so much for taking the time to help with my data visualization project. My goal is to tell a story about hospital efficiency using data."
"I've created a draft of a scrolling, interactive story, and I'd love to get your feedback on it. There are no right or wrong answers, your honest thoughts are exactly what I need to make it better."
"I'll share a link with you in a moment. As you look through it, it would be incredibly helpful if you could think out loud. Just tell me what you're looking at, what you're thinking, and if anything is clear, confusing, or interesting."
"Do you have any questions before we start?"

(2) The Task (5-7 minutes)
"Great. I'm sending you the link to my draft Shorthand story now. Please open it and feel free to scroll through it at your own pace. I'll be quiet for a few minutes and just listen to your thoughts as you explore."

(3) Specific Questions (5-7 minutes)
"Thanks, that was really helpful! Now I have a few specific questions."
"What would you say is the main story or key message here?" 
"Was there any point in the story where you felt lost, confused, or that the flow was illogical?"
"Let's look at the first bar chart, 'Which Appointments Are Missed the Most?'. What does this chart tell you? Why do you think one bar is highlighted?"
"Now looking at the line chart, 'Most Patients Leave Quickly...'. What's your takeaway from the annotation about the '2-5 day' peak?"
"Based on everything you saw, if you were a hospital manager, what's one question you would ask next or one action you might consider taking?" 

(4) Wrap-up (1 minute)
"That's all my questions. This feedback is incredibly valuable. Is there anything else you'd like to share?"
"Thank you again for your time!"


| Goal | Questions to Ask |
|------|------------------|
|  Assess Narrative Clarity    |    "What would you say is the main story or key message here?"              |
|  Evaluate Visualization Effectiveness    |     "Let's look at the bar chart, 'Which Appointments Are Missed the Most?'. What does this chart tell you? Why do you think one bar is highlighted?"              |
|  Check for Story Cohesion & Flow    |    "Was there any point in the story where you felt lost, confused, or that the flow was illogical?"              |
|  Determine if the Story is Actionable    |  "Based on everything you saw, if you were a hospital manager, what's one question you would ask next or one action you might consider taking?"                |


## Interview findings

| Questions               | Interview 1 (MBA student) | Interview 2 (Healthcare Analyst)| Interview 3 (MSPPM student) |
|-------------------------|--------------------------------|-------------|-------------|
| What is the main story? |"I think it's about how no-shows cause delays inside the hospital."       |    "It seems to be two separate stories, one about missed appointments and one about how long people stay."         |       "The main message is that the hospital has efficiency problems."      |
|       Was anything confusing?                  |        "The jump from the outpatient to inpatient part was a bit sudden. I was missing the bridge."                        |        "No, the flow made sense to me. The text connected the ideas well."     |       "I wasn't sure what a KPI card was at first, but I figured it out."      |
|           Takeaway from 'No-Show' chart?              |   "That therapy is the biggest problem area. The color highlight made that obvious."                             |      "That a lot of therapy appointments are being missed, which seems important."       |  "It clearly shows where to focus efforts to reduce no-shows."|
|         Takeaway from 'Length of Stay' chart?                |           "That the real issue isn't the average patient, it's the small number who stay for a very long time."                     |      "The peak makes sense, but the annotation helped me understand why that 2-5 day range matters."       |    "Most people get out pretty fast."         |

# Summary of Findings:
- Consistent Feedback: All three participants understood the two separate problems (no-shows and long stays) but felt the connection between them needed to be made more explicit earlier in the story. Two of the three participants mentioned that the KPI cards were very helpful for getting the main numbers upfront.
- Conflicting Feedback: Participant 1 thought the story was a good length, while Participant 3 felt it could be shorter.

# Storyboard


## Changes Planned for Part III:
Problem: The connection between the outpatient and inpatient stories is not clear enough.

Planned Change: I will add a dedicated transition paragraph after the no-show analysis that explicitly states: "This backlog at the front door has a direct impact on the hospital's internal operations..." I may also create a simple flowchart graphic to visually link the two concepts.

Feedback: Users understood the highlighted charts well.

Planned Change: I will apply the same highlighting technique to the "Patient Load by Specialization" chart to draw attention to the busiest departments, reinforcing that design's effectiveness.

## References
1. [Healthcare dashboards example](https://www.gooddata.com/blog/healthcare-dashboards-examples-use-cases-and-benefits/)

## AI acknowledgements
ChatGPT was used as a learning and development tool during this project. Specifically, it was to understand and troubleshoot the technical workflows for creating specific visualizations in Tableau, such as calculated fields and annotations. It was also used to learn the step-by-step process of embedding Tableau Public visualizations into the Shorthand platform.
