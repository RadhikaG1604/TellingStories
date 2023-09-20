| [Home Page](https://radhikag1604.github.io/Telling_Stories_With_Data/) | [Data_Visualization_1](https://radhikag1604.github.io/Telling_Stories_With_Data/Data_Visualization_1.html) | [Critique by Design](https://radhikag1604.github.io/Telling_Stories_With_Data/critique-by-design.html) | [Final Project Part I](https://radhikag1604.github.io/Telling_Stories_With_Data/final-project-part-one.html) | [Final Project Part II](https://radhikag1604.github.io/Telling_Stories_With_Data/final-project-part-two.html) | [Final Project Part III](https://radhikag1604.github.io/Telling_Stories_With_Data/final-project-part-three.html) |

# Assignment 4: Critique & Design

## Step one: Finding a Data Visualization

Given my profound dedication to healthcare, I was keen on selecting a data visualization that holds significant sway in comprehending and combatting healthcare challenges. In my research, I encountered the National Governor Association's Report on COVID-19 Statewise Outbreak Summary Statistics. Within this comprehensive report, the Kansas Cluster Summary Dashboard stood out to me. This particular visualization stands as a beacon of critical insights, shedding light on the COVID-19 outbreak dynamics across diverse healthcare settings. It serves as a significant story for making well-informed decisions and executing targeted interventions.

Yet, what truly spurred my interest in this visualization was its evident shortfall in effectively conveying pivotal data. This realization highlighted the untapped potential that, if harnessed, could yield a substantial impact in healthcare strategy and response efforts.

[Click here](https://www.nga.org/wp-content/uploads/2021/01/NGA_Covid-19-Outbreaks_State-Reporting.pdf) to view the source report

<img src="Kansas Cluster Summary Dashboard.png" width="1000"/>

## Step Two: Critique the Data Visualization

As the next in redesigning the visualization, I wanted to identify the strength and weaknesses in the current form of visualization. I utilized Stephen Few's [Data Visualization Effectivess Profile](http://www.perceptualedge.com/articles/visual_business_intelligence/data_visualization_effectiveness_profile.pdf) method to critique the visual on several intricate aspects.

As can be seen above, the Kansas cluster summary dashboard consists of a table presenting diverse outbreak settings, detailing the instances within each setting, alongside case counts, and counts of hospitalizations and deaths. However, it can be observed that headers for "All Clusters" and "Active Clusters" are included, but without clarification on the criteria for active clusters. The data regarding cluster occurrences per setting is depicted in one pie chart, while the corresponding COVID-19 case counts per setting are shown in another. Both charts feature separate legends, utilizing a multitude of colors.

Upon a comprehensive assessment based on seven aspects of data visualization effectiveness, several critical observations emerged. In terms of usefulness i.e., if it is useful for the intended audience and if communicates valuable information, the visualization does contain the intended data, crucial for identifying COVID-19 hotspots and guiding precautionary measures. However, the inclusion of extraneous information on active clusters, deaths, and hospitalizations proves distracting, as interpretation proves challenging.

Regarding completeness, while the visualization offers essential information, the additional attributes of deaths and hospitalizations introduce potential distortions to the overall impact. This leads to potential dilution of the core message. Perceptibility emerges as a significant concern, with the multiple pie charts failing to clearly represent the variations between outbreak options or provide clear quantitative significance. Moreover, the separation of COVID-19 case numbers into a distinct pie chart complicates direct comparison and necessitates additional cognitive effort.

Truthfulness is also an area of consideration, as the pie chart representation deviates from an accurate depiction, with the segments failing to cumulatively total to 100%. Given the rapidly evolving nature of COVID-19 in 2020, the data may not offer pinpoint precision, particularly concerning hospitalizations and fatalities. The basic representation form, a pie chart, is familiar, yet in this context, it proves challenging to discern proportions and differences between categories.

Furthermore, the cluster sizes may hold less significance compared to case numbers, as a substantial correlation between the two is absent. Specific guidance on which hotspots to avoid is not effectively communicated, necessitating deeper audience analysis. From an aesthetic perspective, the visual layout is less appealing, with data scattered across multiple components, including tables and pie charts. Additionally, the pie charts lack gradients to convey variations in outbreak spots, instead employing a dominant rainbow color scheme that demands heightened audience attention.

In summary, while the Kansas cluster summary dashboard provides critical data, its effectiveness is hindered by challenges in completeness, perceptibility, truthfulness, and aesthetics. These elements should be carefully addressed to enhance the visualization's impact and clarity.

Below is my rating for each of the seven individual aspects in the effectiveness profile:

- **Usefulness -** 4
- **Completeness -** 4
- **Perceptibility -** 1
- **Truthfulness -** 3
- **Intuitiveness -** 2
- **Aesthetics -** 1
- **Engagement -** 2

## Step Three: Sketch out a solution

When I first conceptualized a solution, my primary objective was to enhance the data representation within the visualization. To achieve this, I decided to replace the conventional pie chart with a more intuitive bar chart. The shift to a bar chart would enable the audience to interpret case counts in terms of length, simplifying the understanding of differences in outbreak intensities across various hotspots.

Moreover, my aim was to streamline the visualization by eliminating unnecessary or irrelevant data, such as hospitalization and death counts. I recognized that the original visualization contained multiple instances of data, not all of which may be of significant value to the audience, particularly in discerning the most critical hotspots and outbreak intensities. Hence, I opted not to include hospitalization or death count data to maintain focus on the core message.

Additionally, I sought to provide a clear storyline in the heading to facilitate easier and more meaningful interpretation for the audience. This narrative approach was intended to ensure that viewers could swiftly grasp the key takeaways from the visualization.

Lastly, I aimed to illustrate the absence of a correlation between cluster size and case count. To convey this, I introduced a line representing cluster size, offering insights into which hotspots contributed to substantial clusters while emphasizing the disconnect between cluster size and the number of cases. Below is my inital re-sketch of the cluster summary visualization of Kansas

<div class="flourish-embed flourish-chart" data-src="visualisation/15085351"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

## Step Four: Test out the Solution

To put my solution to the test, I decided to seek feedback from two of my friends, both of whom are students in their mid-20s.

### Interviewee 1: 
One of my friends, who happens to be a fellow student and is also enrolled in the 'Telling Stories with Data' class, provided some valuable insights:

- **Can you tell me what you think this is and describe what you interpret?** 
As I presented the interpretation to her, she quickly grasped that the visualization was depicting case counts associated with different clusters. Moreover, she correctly deduced that it was a report specific to Kansas, with a notable emphasis on long-term care facilities due to their high case counts.

- **Do you find anything confusing or suprising?**
However, there was a point of confusion for her. She expressed difficulty in understanding the concept of 'clusters,' indicating that this term wasn't immediately intuitive to her. After I clarified that it referred to the number of instances in each outbreak spot, she mentioned that it made much more sense.

- **Who do you think is the intended audience for this visualization ?**
When asked about the intended audience for this visualization, she believed it would be beneficial for the general public of Kansas, as well as public health professionals who are keen on identifying major outbreak spots and taking precautionary measures to avoid them.

- **Is there anything you would change or do differently?**
Furthermore, she provided some constructive suggestions for improvement. Firstly, she proposed using a different word or phrase instead of 'cluster' to make it more user-friendly. Secondly, she recommended a change in coloring scheme, aligning it with the graph's title and giving extra prominence to the long-term care facility while keeping the rest in a subdued gray. Finally, she advised minimizing the size of the subtitle to maintain focus on the main message.

These suggestions proved immensely helpful, as they contributed to a more refined and effective presentation of the core message in my visual representation.

### Interviewee 2:
For my second interview, I approached another graduate student who had also taken the 'Telling Stories with Data' class. I aimed to gather insights from a broader audience to understand how they would perceive and interpret the visualization. I asked her the following questions:

- **Can you tell me what you think this is and describe what you interpret?** 
She promptly identified that the visualization represented COVID-19 data specific to the state of Kansas. Impressively, she noted that there was a clear correlation between cluster sizes and case counts in most instances, although there were exceptions. She keenly observed that regardless of cluster size, the number of cases could vary. However, she concurred that using a different term instead of 'cluster' could make the information more informative and straightforward.

- **Do you find anything confusing or suprising?** 
he remarked that she found it surprising and enlightening to observe that the locations she initially thought were enclosed spaces with limited interactions from the outside actually had higher case counts. She hadn't considered that closed spaces might lead to more interactions with fewer opportunities for isolation.

- **Who do you think is the intended audience for this visualization ?** 
She emphasized that it would be relevant to the general public in Kansas or health department officials tasked with formulating policies regarding pandemic outbreaks.

- **Is there anything you would change or do differently?** 
She was overall affirmative of the visualization, except on the usage of colors - she held a similar view on colors, aiming to communicate a sense of severity or danger, which I have incorporated into my revised sketch.

### Insights from in-class group critique:
I presented my redesigned visualization, displayed below, to my fellow classmates. They examined both the original visual that I aimed to improve and my final sketch. They shared a common sentiment about the original dashboard visual, finding it challenging to interpret and causing a loss of interest in the data. However, they did note that my resketch was clear in communicating the key message. In terms of the visual aspect, their suggestion was to enhance the prominence of the line by introducing a noticeable differentiation.

## Step Five: Build your solution

Taking into account these insightful suggestions, I made several adjustments to my resketch. I replaced the term "cluster" with "outbreak spots" to enhance clarity. Furthermore, I opted to remove the legend and incorporated it as annotations within the visualization to actively engage the audience. In order to emphasize the importance of long-term care facilities, I highlighted them in red, providing a visual cue for their notable impact. Additionally, I heightened the visibility of cluster sizes by employing a dark dashed line, ensuring they were distinctly noticeable.

<div class="flourish-embed flourish-chart" data-src="visualisation/15077935"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

## Summary

In this journey, I followed a structured framework that encompassed several crucial steps. It all began with the careful selection of the most fitting visual representation. From there, I delved into a comprehensive critique, employing the data effectiveness profile as my guide. This process paved the way for a meticulous resketching endeavor, aimed at refining the visualization to its fullest potential. Seeking feedback was the next pivotal step, allowing for further refinement and improvement.

This systematic approach not only sharpened my critiquing abilities but also enabled me to present the visual and data in a more streamlined manner, minimizing unnecessary clutter. What struck me most was how this exercise transformed my perspective on visualizations. The exposure to a variety of visual representations left a lasting impact, reshaping the way I perceive and interact with them.

Engaging in this feedback loop and observing others' visuals created a dynamic learning environment. It became a space where different styles and techniques were shared, fostering a collective growth and adaptation in my own visualization practices. This collaborative exchange of insights and ideas truly enriched the entire process.
