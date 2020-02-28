# NBA_All_Stars

Currently working on this project.

![top all stars](https://github.com/aclao89/NBA_All_Stars/raw/master/Images/allstarsrdme.jpg)

TThe National Basketball Association All-Star Game is a basketball exhibition game hosted every February by the National Basketball Association (NBA) and showcases 24 of the league's star players. It is the featured event of NBA All-Star Weekend, a three-day event which goes from Friday to Sunday. The All-Star Game was first played at the Boston Garden on March 2, 1951.

The starting lineup for each squad is selected by a combination of fan, player, and media voting, [1] while head coaches choose the reserves. The starting five from each conference consists of three frontcourt players and two guards.

In this project, I performed an exploratory analysis of the NBA All-Stars roster from 2000 to 2016 to examine the commonalities and differences of an All-Star.

                                                        Data Cleaning

Load the libraries and read file to browse columns.                                                        

![notebook screen grab](https://github.com/aclao89/NBA_All_Stars/raw/master/Images/Capture.PNG)



I noticed the original height column, E , was in the month-day format. I wrote a formula =MONTH(E3) & "'" & DAY(E3) to convert into height format in column D.

![excel height conversion](https://github.com/aclao89/NBA_All_Stars/blob/master/Images/Capture1.PNG)



I separated the NBA Draft Status column into three different columns: Draft Year, Round, and Pick for better analysis.

![split NBA draft column](https://github.com/aclao89/NBA_All_Stars/blob/master/Images/Capture3.PNG)



The Position (Pos) column had too many iterations for the same position. For example forward (F), small forward (SF), power forward (PF), can be confusing and hard to analyze. I categorized into three positions: guard (G), forward (F), and center (C).

![real positions](https://github.com/aclao89/NBA_All_Stars/blob/master/Images/Capture4.PNG)






                                                        Exploration Questions

1. Which teams have the most All-Star players between 2000 and 2016?

![all stars by team](https://github.com/aclao89/NBA_All_Stars/blob/master/Images/Capture5.PNG)




2. Which teams have the most All-Stars by each year? Are there teams whom have a drought of All-Stars? Are there teams whom have been dominant in drafting potential All-Stars or attracting All-Star talents?

![all star by year and team](https://github.com/aclao89/NBA_All_Stars/blob/master/Images/Capture6.PNG)










References:
[1] "How NBA's new voting format determined All-Star starters, snubs". ESPN. Retrieved 2017-07-03.
