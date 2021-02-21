# Step 1: Find a Data Visualization
I selected the three visualizations shown below, reposted from the blog post, "City population dynamics since 1850."

![Data Visualization 1](https://neighborhoodeffects.mercatus.org/wp-content/uploads/2016/01/top-cities-1850-1900.jpg)

![Data Visualization 2](https://neighborhoodeffects.mercatus.org/wp-content/uploads/2016/01/top-cities-1900-1950.jpg)

![Data Visualization 3](https://neighborhoodeffects.mercatus.org/wp-content/uploads/2016/01/top-cities-1950-2010.jpg)

Images sourced from: Millsap, Adam. “City Population Dynamics since 1850.” Neighborhood Effects, January 26, 2016. https://neighborhoodeffects.mercatus.org/2016/01/26/city-population-dynamics-since-1850/.

# Step 2: Critique the Data Visualization
These visualizations show the top ranking U.S. cities over time based on their population. They present the information in line charts, which on the one hand is good since they show change over time. Having years across the x-axis in uniform increments made sense and worked for this visual. However, having rank on the y-axis is confusing. Since a rank of 1 indicated the most populous city, and lower rankings meant lower populations, it is counterintuitive to have the y-axis go from 0-20 because then cities appear to be increasing on the chart when their populations are actually decreasing.
Another critique I have of this chart is that it may be useful to have all of the information in one chart instead of across three charts so viewers can see a more continuous change over time. 
Additionally, the charts each have different colors and symbols representing the cities. For example, Philadelphia is represented in the first chart as a straight yellow line, but in the second chart it is shown as a gray line with a diamond-X shape in it, and in the third chart as a gray line with a square in it. 
In terms of the design choices for the visualizations, the symbols on the lines for each city are unnecessary since the lines are already different colors. 
The symbols on the lines only add clutter to the chart and make it more difficult to read.
Finally, the headlines for the charts could be more descriptive.

# Step 3: Wireframe a Solution
I used Basalmiq to wireframe two possible ways to improve these visualizations. My wireframes are included below.
![image](https://user-images.githubusercontent.com/78364263/108615125-d6d9fe80-73ce-11eb-8c7c-ae42c1aab970.png)

![image](https://user-images.githubusercontent.com/78364263/108615140-fa04ae00-73ce-11eb-846b-e3f3b11df9dc.png)

# Step 4: Test the Solution
I presented my wireframes to two friends and asked them the following questions:
- Can you tell me what you think this is?

- Can you describe to me what this is telling you?

- Is there anything you find surprising or confusing?

- Who do you think is the intended audience for this?

- Is there anything you would change or do differently?

Their responses were as follows:

- Can you tell me what you think this is?
Friend 1 Response: Ranking of what cities have had more population growth comparatively to other large cities.
Friend 2 Response: Picture one looks like a ladder of sorts of the cities. I’m guessing once dynamic the cities will move up and down past one another based on the year. Picture two being a map of the US with the largest cities ranked.

- Can you describe to me what this is telling you?
Friend 1 Response: New York has had more population growth in the past 170 years than the other cities.
Friend 2 Response: Size variations of cities based on the year.

- Is there anything you find surprising or confusing?
Friend 1 Response: No numbers context, did NYC grow by 100 million while #2 Baltimore grew by 2 million? I find the map easier to understand more immediately than the line one. The line one looked more like a subway stop map than data ranking. Is the west coast not included or did they just not make the top 10 in growth?
Friend 2 Response: Currently, not really. 

- Who do you think is the intended audience for this?
Friend 1 Response: Politicians (census, etc), urban planners, tourism/travel/airlines.
Friend 2 Response: I would guess students? To help visualize population growth over time?

- Is there anything you would change or do differently?
Friend 1 Response: I mean the first one was almost too plain to immediately understand what I was looking at, maybe numbering would have helped rather than just circles/bullets which did not immediately jump out at me.
Friend 2 Response: I might adjust the size of the circles based on larger vs. smaller populations.


In reflecting on their responses I realized there were changes I needed to make to my final visualization. First, I realized one of my friends thought the visualizations were showing population growth, which is incorrect. The visualizations are showing city ranked by their total population, not how much their population grew. As a result of this confusion I knew I needed to be clear on my y-axis label that this was showing city rank by total population. This friend was also surprised that there were no numbers for context. The original data set did not have the actual populations of the cities, only the rank of the cities each year. Nevertheless, I did decide to include the number ranking along the y-axis to provide more context. I also adjusted the circle's size based on the city ranking as per my other friend's suggestion. Since one friend thought the visualization was too plain, I also added colors and the moving timeline to make it more interesting.

# Step 5: Build Your Solution
I redesigned the visualizations as shown below.
<div class="flourish-embed flourish-scatter" data-src="visualisation/5348832"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

