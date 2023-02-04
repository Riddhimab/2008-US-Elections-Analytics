# 2008-US-Elections-Analytics

Background  
It was February 19, 2008. One week earlier, Barack Obama had taken the lead in the delegate count 
during the Democratic Party’s presidential primaries, the winner of which would face the Republican 
Party’s nominee in the general election to become the next president of the United States (POTUS). 
 
On that day in February, Hillary Clinton, Obama’s primary opponent, began running ads in Ohio aimed 
at middle‐class, blue‐collar voters. One ad, “Night Shift,” closed showing Clinton at her desk: “She 
understands. She’s worked the night shift, too.” But had Clinton ever worked the night shift? Her 
spokesperson said it was a “rhetorical reference” to working late nights as a lawyer, First Lady, and 
senator [1]. 
 
Clinton was not alone in her awkward appeals to voters in key demographics. Months earlier at a 
campaign stop in Iowa, Obama noted that while produce prices had risen in grocery stores, farmers had 
not benefited from increases in crop prices: “Anybody gone into Whole Foods lately and see what they 
charge for arugula? I mean, they’re charging a lot of money for this stuff.” At the time, there wasn’t a 
single Whole Foods in the state of Iowa [2]. 
 
What did these missteps say about the candidates’ campaign strategies? Were they targeting the right 
voters? Had they crafted the right messages for these segments? One key in answering these questions 
was to analyze votes that had already been cast. 
 
 
Demographic Data  
In November 2007, the U.S. Census Bureau issued its County and City Data Book [3] which contained 
extensive demographic information by state, county, and city. The Census Bureau grouped the 50 U.S. 
states into four regions (see Exhibit 1). Within the United States, there were a total of 3,141 counties. 
 
On its website, the Census Bureau released the 2007 data tables from the County and City Data Book. 
These tables contained information commonly used by marketers to segment a population—gender, 
age, race, ethnicity, education, income, employment status, knowledge of languages, government 
dependency, disabilities, home ownership, mobility, population, population density, and region [4]. Key 
demographic data by county were extracted from these tables and placed in a spreadsheet file.  
 
 
 
 
 
Vote Data 
 
Candidates  for  the  Democratic  nomination  won  delegates—both  pledged  delegates  and 
superdelegates—through a complicated process followed closely by many news organizations and 
depicted in many different ways.1 On its website, CNN displayed an interactive graphic where candidates 
were depicted as donkeys in a foot race; visitors could roll a cursor over a candidate’s donkeys and the 
current delegate total would appear [5]. 
 
Politicians cared about votes the way marketers cared about sales. Because voting results dictated 
delegate commitment, major news outlets carefully tracked totals by county. A visitor had access to 
county vote data (also included in the spreadsheet) by rolling a cursor over a state’s map.2 
 
As of February 19, 2008, of the 2,868 total counties for which county‐level vote data would eventually 
become available, there were 1,131 counties left to report. An estimated 2,490 delegates were already 
committed, and 2,118 were needed to secure the party’s nomination; there were still 1,744 delegates 
to be awarded in upcoming states’ primaries and caucuses. (See Exhibit 2 for a list of past and upcoming 
primaries and caucuses.) Later that evening, the results of Hawaii’s caucus and Wisconsin’s primary 
would be announced. In these two states, and in over 1,000 counties in other states, it remained to be 
seen who would vote for Clinton and who would vote for Obama. Whoever won the most votes in these 
remaining primaries was likely to become the next POTUS. 
 
 
What Followed and the Role of Analytics in Politics  
Indeed, Obama won the Democrat nomination and won two Presidential elections. In the 2008 
presidential election, Obama’s targeters had assigned every voter in the country a pair of scores based 
on the probability that the individual would perform two distinct actions that mattered to the campaign: 
casting a ballot and supporting Obama. 
 
For each battleground state every week, the campaign’s call centers conducted 5,000 to 10,000 so‐called 
short‐form interviews that quickly gauged a voter’s preferences, and 1,000 interviews in a long‐form 
version that was more like a traditional poll. To derive individual‐level predictions, algorithms trawled 
for patterns between these opinions and the data points the campaign had assembled for every voter—
as many as one thousand variables each, drawn from voter registration records, consumer data 
warehouses, and past campaign contacts. 
 
Furthermore, the Obama 2008 campaign also used analytics to increase donations using A/B testing.
The campaign tried four buttons and six different media (three images and three videos). A full‐factorial 
multivariate test was used to statistically test all the combinations of buttons and media against each 
other at the same time. Since there were four buttons and six different media that meant a total of 24 
(4 x 6) total combinations to test. Every visitor to the splash page was randomly shown one of these 
combinations and we tracked whether they signed up or not. 

The campaign tried four buttons and six different media (three images and three videos). A full‐factorial 
multivariate test was used to statistically test all the combinations of buttons and media against each 
other at the same time. Since there were four buttons and six different media that meant a total of 24 
(4 x 6) total combinations to test. Every visitor to the splash page was randomly shown one of these 
combinations and we tracked whether they signed up or not. 
 
