# Tableau


I am creating a tableau story with the flights datasets of the year 2008. The dataset contains the information on united states flights delays and performance comes from RITA. Flights are considered as delayed when it takes off or arrives 15 minutes later than its scheduled time. Planes can be delayed due to plenty of things like weather,plane malfunction, Heavy air traffic etc. Delays can cause a lot of anxiety in travelers. Many times, there are connecting flights to consider, not to mention special scheduled events like weddings, meetings, and reunions. Sometimes even a relatively small delay can wreak havoc on your travel plans, so needless to say, passengers all over the world are desperate to avoid them. Here i investigate the different delays across the flight carriers so the user can select best carrier.

# DESIGN

I choose to show the relation between different flight carriers and how good they are in keeping up their schedule timing. Always overview is good place to start, As a first part in my story i show all the different delays and their count for each carrier. In the second part i show relation between scheduled and the actual departure time , I choose scatter plot to show the trend in keeping up their schedule.This part also show the taxi out time for each carriers. In the third part, relation between scheduled arrival time and the actual arrival time is displayed along with the total taxi in time for the carriers.

# Design of first part
It shows the count of weather delay, NAS delay, late aitcraft delay , security delay and carrier delay.
Filters for day,week of the month and month are included . This helps to know the delay for particular day or month.

# Design of the second part
Here i designed the scatterplot to show the relation between scheduled departure and the actual departure time. In the scatter plot different carrier have different color , this helps to distinguish between pattern for different carriers. each point denotes the flight of the carrier. In addition to that orgin filter is added ,this helps to know relation between scheduled and the actual arrival time for the differnt orgin places. Taxi out time taken by the different carrier is included as a bar chart at the bottom. Filter of the scatterplot is also linked to the taxi out time bar chart, so that whenever the filter set to a particular place, total taxi out time taken by the carriers in that place is shown at the bottom. Action is also included, whenever a point is selected from the scatterplot taxi out taken by the particular flight is shown in the bar below. Likewise when a bar of the carrier is highlighted then the pattern for the carrier is displayed in the scatter plot. Trend line is added to show the relation between the schedule and the actual departure time.


# Design of the Third part
All the design steps carried out for the second part are followed here as well. Here the the relation between the scheduled and the actual arrival time is shown as the scatter plot. Taxi in time taken by the carrier is shown as the bar graph at the bottom. Desitination filter is added to see the pattern for different places.

Published in https://public.tableau.com/app/profile/joshlin.ronisha/viz/carrierandtheirperformance/Story1?publish=yes
