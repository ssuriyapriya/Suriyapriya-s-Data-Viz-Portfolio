| [home page](https://ssuriyapriya.github.io/Suriyapriya-s-Data-Viz-Portfolio/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

- Web page URL: https://ssuriyapriya.github.io/Suriyapriya-s-Data-Viz-Portfolio/
- This repository: https://github.com/ssuriyapriya/Suriyapriya-s-Data-Viz-Portfolio/

# Portfolio
This portfolio showcases projects from my "Telling Stories with Data" course at Carnegie Mellon University. Here, you'll find a collection of data-driven narratives and visualizations that highlight my ability to transform complex information into clear and compelling stories.

# About me
Hello! My name is Suriyapriya (she/her). I’m a second-year Master’s student in Health Care Analytics and Information Technology at Carnegie Mellon University. My interests include data visualization, applied machine learning, and decision analytics in healthcare operations.  
Outside academics, I enjoy singing and playing Guitar.

# What I hope to learn
I’m taking this course to refine my ability to communicate complex information through data. I plan to deepen my technical skills in creating narrative visualizations and interactive dashboards while also developing a strong framework for thoughtful design critique. Ultimately, I want to master an accessibility-first approach, which I believe is essential for communicating health data ethically and effectively.

# Portfolio

## Assignment: [Visualizing Government Debt]
<div class='tableauPlaceholder' id='viz1757429101060' style='position: relative'><noscript><a href='#'><img alt='Debt-to-GDP Trends by Region (1995–2019) ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;De&#47;Debt-to-GDPTrendsbyRegion1995-2019&#47;Linechart&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Debt-to-GDPTrendsbyRegion1995-2019&#47;Linechart' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;De&#47;Debt-to-GDPTrendsbyRegion1995-2019&#47;Linechart&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-GB' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1757429101060');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>)

This is my first data visualization assignment, where I analyze and visually represent a dataset on government debt. For my visualization, I decided to group the countries into broader regions and show their Debt-to-GDP ratio trends over time. Instead of focusing on individual countries, I wanted to emphasize regional patterns and how debt burdens evolved differently across the world between 1995 and 2019. I used distinct colors for each region to make the lines easy to follow, while also keeping the color palette balanced so that no single region overwhelms the others. The title and source are clear so that viewers immediately know what the chart is showing and where the data came from.

A key part of my design choice was in the color scheme: regions with Debt-to-GDP ratios consistently above 100% were assigned colors in the brown/orange family, while those staying below 100% were shown in shades of blue. Within each group, I used light-to-dark shading to represent lower to higher values. Thus, the chart not only separates high-debt versus lower-debt regions at a glance, but it also shows relative differences within each category. For example, Southern Europe and Asia Pacific are darker browns, signaling very high levels, while lighter blues like Latin America reflect much lower ratios.

My design goal was to highlight long-term shifts rather than short-term fluctuations. For example, Southern Europe consistently shows some of the highest ratios, while Latin America and Eastern Europe remain much lower. Grouping by region makes these differences more visible than if I had kept each country separate. Compared to the heatmap I created earlier, I think this redesign is more effective because it allows me to tell a clearer story about how regions diverge over time. The heatmap was useful for spotting country-level variation, but this line visualization makes broader patterns and comparisons across regions stand out more clearly.

## Assignment 3&4: [Critique by Design]
Source: OECD Health Spending (https://www.oecd.org/en/data/indicators/health-spending.html)

I selected this particular data visualization because it presents a rich, important dataset in a way that is functional but has clear and significant room for improvement. At first glance, the chart successfully shows the total health spending for various countries and gives a basic sense of how that spending is broken down. It is a very common and familiar chart type, which makes it a perfect candidate for a redesign that can demonstrate the principles of effective data visualization.

However, I chose this chart primarily for its weaknesses, as they provide a great opportunity to tell a more compelling story. The original chart fails to guide the viewer's attention. The sorting order is unclear, hiding any meaningful ranking, and all countries are treated with the same visual priority, so nothing stands out. The most significant issue is that by presenting a static view of a single year, the chart completely misses the crucial story of how spending has changed over time. I was inspired by these limitations to explore how a different approach could better highlight the key insights, specifically the dramatic story of the United States as a global outlier in healthcare spending.

**Redesigning Health Spending: From a Static List to a Compelling Story**

This project documents the process of redesigning a data visualization about health spending as a percentage of GDP. The goal was to move beyond a simple comparison and create a visualization that provided deeper context and a clear narrative, following a five-step design process.

**Step 1 & 2: The Original Visualization and Critique**

The process began with a standard vertical bar chart, showing health spending for various countries from 1970-2019.

**[The original bar chart]**(images/Screenshot 2025-09-17 213212.png)

My initial critique, using Stephen Few's effectiveness profile, revealed several key insights. On the positive side, the chart was clean, used a proper zero-baseline, and was sorted, which made it easy to see the ranking of countries. However, the critique method made its weaknesses glaringly apparent:

1. **Poor Perceptibility:** The vertical orientation forced the country labels to be rotated, making them difficult to read.
1. **Lack of Narrative:** This was the biggest issue. The chart was a static list of facts for a single year. It showed *what* the spending levels were, but offered no context on *how* they got there. It presented data without telling a story.

The main takeaway from the critique was that the most interesting story—the United States as a massive outlier—was presented without any historical context. This insight became the driving force behind my redesign.

**Step 3: Sketching a Solution**

To address the lack of narrative, I decided the redesign must show change over time. This immediately led me to the idea of a **line chart**. My goal was to create a visualization that answered the question: "Has the U.S. always been such an outlier?"

My initial wireframe was a quick pen-and-paper sketch. It focused on plotting the spending for the top three countries from the original chart over the last 30 years. The sketch included:
* A strong, declarative title.
* A thicker, uniquely colored line for the United States to make it the focal point.
* A placeholder for an annotation to mark the approximate point where the U.S. trend began to diverge significantly.

This initial plan was simple and focused on transforming the static comparison into a dynamic story.

**(A picture of your hand-drawn sketch or digital wireframe would go here)**

**Step 4: Testing and User Feedback**

I presented my sketches to a small group of peers to gather feedback before building the final version. I spoke with a student from the MSPPM program and another from a design background. The feedback was invaluable and directly shaped the final product.

**Key Insights from Feedback:**

1.  **The "Comparison Group" was Weak:** The MSPPM student immediately questioned my choice of comparing the U.S. to only Switzerland and Sweden. Their feedback was that showing the U.S. diverging from two other high-spending countries didn't feel as powerful. They suggested, "Why not compare it to the average of all developed countries? That would be a much stronger benchmark."
2.  **The Story Needed a Clearer Frame:** The design student felt the story was powerful but needed to be "set up" better. They suggested making the title more assertive and adding a subtitle to immediately tell the audience what they were about to see.

#### **Step 5: The Final Redesigned Visualization**

Based on this feedback, I made two critical changes to my initial plan. First, I sourced the data for the **OECD** and added it as a key reference line. Second, I rewrote the title and subtitle to be more declarative.

My final redesigned visualization, created in Tableau, shows this new, focused story.

<div class='tableauPlaceholder' id='viz1758158997524' style='position: relative'><noscript><a href='#'><img alt='Dashboard 1 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;GM&#47;GMQ5S4MRN&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='path' value='shared&#47;GMQ5S4MRN' /> <param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;GM&#47;GMQ5S4MRN&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-GB' /><param name='filter' value='publish=yes' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1758158997524');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1600px';vizElement.style.height='1027px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1600px';vizElement.style.height='1027px';} else { vizElement.style.width='100%';vizElement.style.height='1727px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>

This line chart shows health spending as a % of GDP from 1970 to 2019 for the United States compared to three other major developed nations.

The visualization makes it clear that for decades, U.S. spending was in line with other countries. However, beginning in the early 1980s, its trajectory dramatically changed, creating the vast gap that exists today. By using pre-attentive attributes like a brighter color and thicker line weight for the U.S. and adding a direct annotation, the chart guides the viewer to the single most important insight in the data.

Ultimately, this redesign successfully transforms a simple, static list into a compelling and informative narrative that provides crucial historical context. It doesn't just show that U.S. health spending is high; it shows *how and when* it became a global outlier.

## Final project
My final project for this course, developed over several weeks. This comprehensive project involves selecting a unique dataset, crafting a compelling narrative, and designing and building a polished data visualization to tell that story. The project is broken down into three main parts, culminating in a final presentation.

Part I: Project Proposal and Initial Sketches
This phase covers the initial research, dataset selection, and a formal proposal outlining the project's goals, intended audience, and scope.
[Part I](final-project-part-one)

Part II: Draft and Peer Critique
This stage focuses on developing a complete draft of the visualization based on the proposal. This version was presented during an in-class critique to gather feedback for refinement.
[Part II](final-project-part-two)

Part III: Final Visualization and Presentation
The final submission includes the completed, polished data visualization and materials from the final in-class presentation.
[Part III](final-project-part-three)


