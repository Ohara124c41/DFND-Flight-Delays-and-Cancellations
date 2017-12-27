# Flight Delays and Cancellations with Data Dashboards in Tableau
___


##### Scholar: Christopher Ohara
##### Program: Udacity Data Foundations Nanodegree+



[//]: # (Image References)

[image1]: https://github.com/Ohara124c41/DFND-Flight-Delays-and-Cancellations/blob/master/images/008.png?raw=true?raw=true
[image2]: https://github.com/Ohara124c41/DFND-Flight-Delays-and-Cancellations/blob/master/images/010.png?raw=true?raw=true
[image3]: https://github.com/Ohara124c41/DFND-Flight-Delays-and-Cancellations/blob/master/images/009.png?raw=true?raw=true
[image4]: https://github.com/Ohara124c41/DFND-Flight-Delays-and-Cancellations/blob/master/images/007.png?raw=true?raw=true


## Introduction

___

This project consists of building data dashboards for visual representation using ```Tableau```. The corresponding datasets document a variety of airline information including delays, cancellations, dates, and destinations. The dataset is from **2015** for major airlines and airports.

The goal of the dashboards are to visualize which airlines have the *most delays* and potential causes. This information could potentially be useful in the improvement and optimization of airlines, which could improve their branding, customer experience/satisfaction



## Which airlines have the worst frequencies of delays?
![alt text][image1]

This visualization shows a comparison of airlines with delays, given in thousands of minutes. This shows that Southwest Airlines (WN) has the most delays of any kind, nearly double of any competitor. While arrival delays are different than departure delays, they are related, especially when considering connecting flights.  

A ```Bar Chart``` is used to show data with minimal chart junk. A general negative slope can be seen as a trend.

###### Tableau: https://public.tableau.com/views/Flights_37/Sheet1?:embed=y&:display_count=yes&publish=yes

## What is the frequency of cancellations by type?
![alt text][image2]

This visualization shows the occurrences of cancellations due to reasons (A, B, C) relative to the day given the week, time of month, and month. It can be seen that the primary cause of cancellations is "B" which accounts for more than half. While the ```Excel Sheet``` does not explicitly state what reason "B" is, looking at the month of February implies it is related to weather conditions since this is the dead of winter.

The ```Area Chart``` was utilized as it can draw the attention of the user to the magnitude of the dilemma, without being distracting or misleading.

###### Tableau:
https://public.tableau.com/views/AirlineDelaysCancellationsandTrends/Sheet2?:embed=y&:display_count=yes
___

## How does flight distance and time impact delays and cancellations?
![alt text][image3]

Now, we can see something interesting and insightful. While this graph still shows that Southwest (WN) still has the worst delays and cancellations, we can see that these issues are proportional to the total distance of the trip and the length of the flight time. This is relatively true for all airlines as well, except for American Eagle (MQ) that has a high amount of cancellations with respect to their flight times and distances. Since this dataset is from 2015, there might have been an incident that caused a massive amount of cancellations that skew the results.

###### Tableau:
https://public.tableau.com/profile/christopher.ohara#!/vizhome/AirlineDelaysCancellationsandTrends/Sheet3

A ```Scatter Chart``` was used as it clearly shows the relationship between each airline and multiple measures of data while avoiding chart junk.

## Dash Board
![alt text][image4]

Finally, a rudimentary Dash Board is added to show relationships between each research question and the similiarities between their results.

###### Tableau:
https://public.tableau.com/views/AirlineDelaysCancellationsandTrendsmkII/Dashboard1?:embed=y&:display_count=yes&publish=yes



## Discussion & Future Improvements
___

If my career was as a travel agent, I would advise my clients **not** to *"fly Southwest on a Sunday in February"* if they have an important trip to book with a tight schedule. These are cursory observations though, as the dataset is for 2015 and may not represent previous trends or future possibilities.

In all fairness, dilemmas surrounding airlines, airports and air traffic control have been studied in great detail and curiosity for economists and scholars under the field of ```Science, Technology & Society."``` It turns out that these issues are not simple to resolve and the system is difficult to optimize. This is investigated in great detail by *Allenby and Sarewitz* in the ```Techno-Human Condition``` in which they address the complexity of problem solving and predicting even the near future (focusing on social and technological aspects of air traffic control systems and human interaction).

However, this data could be analyzed against multiple years and could result in improvements. If the airline or airport knows that there will be these sorts of dilemmas, they could notify users in advance or offer some form of compensation. This is under the premise that these conditions are unavoidable (weather is relative to location and season), and the best course of action would be a social resolution.

Recently, airlines have experienced disruptions due to entrepreneurial innovation and business models. An American example is "Spirit Airlines," and while they offer very low quality flights (no carry on, no free drinks) they offer cheap alternatives to fly which targets an audience of college students, travelers, backpackers and short "get-aways." This is addressed in this report, since aspects of social media and user experience are disrupting the stocks and value chain for large companies that cannot adapt. Once a companies image is tarnished, it is very difficult to recover. Therefore, dashboards such as these can give some direction to potentially mitigating or creating business plans to improve the companies profits.
