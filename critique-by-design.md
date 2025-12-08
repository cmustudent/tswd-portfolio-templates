| [home page](https://mblak3y.github.io/test-portfolio/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Money, Money, Money: Budget vs Profit for the Marvel Cinematic Universe



## Step one: the visualization

[Original Visualization](https://informationisbeautiful.net/visualizations/which-is-the-best-performing-marvel-movie/)


<img width="2922" height="1508" alt="image" src="https://github.com/user-attachments/assets/aa91e9e7-ce64-4a8f-a9a5-6d5e163fd3f7" />


The visualization I selected is an interactive graphic from a movie website that shows relationships between different movie metrics, such as budget, percentage of budget recovered, critics’ score, audience score, and the deviation between critics’ and audience scores. The dataset is based on all 35 movies within the Marvel Cinematic Universe.

However, I chose this graphic because I was impressed by the volume of information captured using its interactive features. I like that the graph allows you to change the metrics on each axis. As shown at the bottom of the graphic, you can look at the actual budget, the percentage of budget recovered, audience ratings, critics’ ratings, and the deviations between the two. 



## Step two: the critique
The original visual plots all of this information on a coordinate plane, with axes that can be changed based on the metric. Personally, I found the image overwhelming. When I first encountered it, I actually scrolled past it because I thought it was a header, not the actual visualization. The black background made it hard to distinguish the boundaries of the graphic and the extent of the information being shown. The lack of background borders added to the confusion. 

Additionally, the visualization displays a large amount of information all at once. There are 35 movies within the Marvel Universe, and on first viewing, all 35 appear on the graph simultaneously. This makes it difficult to make meaningful comparisons between different franchises. As a moviegoer—the intended audience for the graphic—I typically think of Marvel films by the phases of the cinematic universe. 

Still, in this presentation, everything appears together, and the viewer is not able to easily parse or distinguish between comparisons. Because of the overwhelming amount of information and limited ability to filter or group the data, I do not see this graph having much utility in analytical settings. Instead, it seems designed primarily to be interactive and visually engaging for website visitors, rather than to support deeper data analysis.


## Step three: Sketch a solution

<div style="min-height:980px" id="datawrapper-vis-2PzT9"><script type="text/javascript" defer src="https://datawrapper.dwcdn.net/2PzT9/embed.js" charset="utf-8" data-target="#datawrapper-vis-2PzT9"></script><noscript><img src="https://datawrapper.dwcdn.net/2PzT9/full.png" alt="Step 3: Money, Money, Money:  Budgets Vs Worldwide Gross in MCU Films (Bullet Bars)" /></noscript></div>


## Step four: Test the solution

Respondent 1

MSPPM Data Analytics (1st Year)
Not a Marvel Fan
Extensive Data Viz Experience

What do you think this is?

At first glance, I thought this was a timeline of Marvel movies arranged by their overall profits. The structure made me assume the bars were showing some kind of progression over time, but it wasn’t clear how the values were being organized.

What is this telling you?

I couldn’t parse out what the visualization was trying to communicate because the information felt cluttered. The stacking of budget and gross made it difficult to distinguish the significance of each value. The organization didn’t guide my attention in a meaningful way.

Anything surprising or confusing?

It wasn’t confusing—just unclear. I could tell what the dataset was, but the presentation didn’t support quick interpretation. Nothing in the layout was surprising given the context.

Who is the intended audience?

Likely Marvel fans who want a general sense of movie performance. It does not appear intended for someone with a data background or someone looking for analytical insights.

What would you change?

I’d reorganize the graph so the hierarchy of information is clearer—stronger labeling, consistent spacing, fewer competing visuals. Separating budget and gross into distinct visuals could reduce overload.

Respondent 2

MSPPM Flagship (1st Year)
Moderate Marvel Fan
Medium Data Experience

What do you think this is?

It looks like a bar graph comparing budgets and total earnings of Marvel movies. I assumed the bars showed financial performance, though it took a moment to orient myself.

What is this telling you?

It’s highlighting the relationship between how much each movie cost and how much revenue it generated. The variation across films is visible, but there’s a lot happening visually.

Anything surprising or confusing?

The original graph felt overwhelming because of the many dots and labels. Full movie titles next to each dot added clutter and made comparison difficult.

Who is the intended audience?

Casual Marvel fans who might enjoy financial comparisons but don’t need deep analysis. It feels more like fan-site content than a technical visualization.

What would you change?

I’d streamline the presentation and group films more intuitively—by phases, characters, or release periods.

Respondent 3

MSPPM Flagship (1st Year)
Familiar with Marvel
Extensive Data Experience

What do you think this is?

It looks like an attempt to visualize Marvel film budgets and earnings using a coordinate-plane style. The layout suggested comparisons across films but felt more complex than needed.

What is this telling you?

It shows financial performance, but the axes unintentionally created quadrant implications that made me search for meaning that wasn’t there. Once I realized the quadrants weren’t intentional, the purpose became clearer.

Anything surprising or confusing?

The stacked format caused some confusion—it took a moment to understand the heights were cumulative, not separate.

Who is the intended audience?

Marvel fans who enjoy comparing films. The bar chart’s simplicity signals it’s for casual viewing rather than analytical interpretation.




## Step five: Synthesis & build the solution


DataWrapper Version:


<div style="min-height:1331px" id="datawrapper-vis-93WLF"><script type="text/javascript" defer src="https://datawrapper.dwcdn.net/93WLF/embed.js" charset="utf-8" data-target="#datawrapper-vis-93WLF"></script><noscript><img src="https://datawrapper.dwcdn.net/93WLF/full.png" alt="Money, Money, Money:  Budgets Vs Worldwide Gross in MCU Films by Phase (Bullet Bars)" /></noscript></div>





Customizable Tableau Interactive Version:



<iframe 
  src="https://public.tableau.com/views/DataCritiqueOneFD/Sheet1?:showVizHome=no&embed=true"
  width="100%" 
  height="800"
></iframe>



[Customizable Tableau Interactive Version Link](https://public.tableau.com/app/profile/monet.blakey/viz/DataCritiqueOneFD/Sheet1)

Bearing the feedback from the interviews in mind, with my edited graph, I wanted to simplify it specifically to address how overwhelming the amount of information present on the original graph was. So, for this assignment, I decided to just focus specifically on capturing the relationship between the amount of money spent on the movie and the amount of money that it actually earned. I also additionally decided to sort by phase within the MCU universe. I did this because I wanted this graphic to be catered towards casual moviegoers. 

I also wanted to remove one of the axes on the graph because, as I’ll get into later, when I looked at the original visualization I thought of it as a coordinate plane. On my initial analysis, I thought that it would make sense for movies to want to be in the third quadrant, which would indicate that there is a positive value for both of the coordinates being used. 


I decided instead to focus on the different phases of the MCU because I felt that this structure better captured the evolution and strategic development of Marvel’s cinematic storytelling. The phases also reflect Marvel’s long-term marketing strategy and the sequencing of film releases. 


With this assignment, I wanted to use the graph to captures the narrative of the MCU's sustained drastic increases in profitability with the phase's release. I organized them this way because I wanted to capture  Marvel identified an underdeveloped niche within superhero action  films, expanded it into a massively interconnected univers, and maintained the dominance over time. I also thought it was interesting how each film builds toward the next through end-credit scenes, functioning almost like narrative “Easter eggs” that guide viewers through the larger universe. 

As I looked through the different phases and their subsequent titles, I was taken back to memories of being in the theaters and seeing how the trend of waiting until after the credit became common movie going practice. Organizing the data by phase made it easier to see how the MCU grew, how audiences responded at different points in the timeline, and how Marvel’s strategies shaped the overall success of the franchise


Ideally, an optimal version of the final solution would sort the graphs by release date and not increasing profit, which is a feature that the original version. I attempted to integrate the information which combining of the film titles and release year. In the Datawrapper version, I used the sorting by Phases to chronologically capture the data. On Tableau version, I added the Filter by Phase feature to help with chronological comparisons. 






## References

The Link to the Data and Original Visualization


https://informationisbeautiful.net/visualizations/which-is-the-best-performing-marvel-movie/



## AI acknowledgements
I did not use AI for this assignment

