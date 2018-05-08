# Using Twarc to Capture and Analyze Black Student Life at UMD

## Choosing a Data Set
The most difficult aspect of this assignment for me was choosing a data set to work with. I wanted to come up with a search syntax that would align with my research interests – namely, something preferably local to UMD, related to collective memory, and to POC’s lived experience. Laurie Allen’s talk on Monument Lab fomented my desire to investigate conversation on what is the best way to publicly commemorate a hate crime – to demonstrate that this type of hate crime exists to those who choose to ignore racism and violence in America today, to celebrate a young life ended brutally, to encapsulate the way this crime affected the campus community.

Unfortunately, the twitter data I most wanted to capture – the UMD community reactions to the murder of Richard Collins in College Park last May, as seen through the use of the #UMDreflects and #FearThe Turtle hashtags – was beyond the date range that twarc can capture. I attempted to get at this data a few other ways, but ultimately it simply wasn’t doable given the tools at hand – all of the most interesting data was beyond twarc’s collection date range.

I practiced with using twarc to collect tweets using #DigitalHumanities, which yielded [1999 tweets](https://github.com/caitcl/datastory/blob/master/data/hashdhtweets.csv). I did some analysis using google Sheets on the most popular other hashtags used alongside #digitalhumanities (see chart).
<img src="https://github.com/caitcl/datastory/blob/master/images/hashdhhashtagchart.png" width="700">

However, this felt too similar to the in-class exercise Ed and Purdom did with us, so I decided to return to attempting to figure out a twarc search that would gather tweets related to black life at UMD.

## Trying Different Searches to Capture Black Life at UMD in One Week's Worth of Tweets
I gathered a few different twarc searches, since none was capturing exactly what I thought I was looking for: [tweets from @blackterp](https://github.com/caitcl/datastory/blob/master/data/tweetsfromblackterp.csv), [tweets to @blackterp](https://github.com/caitcl/datastory/blob/master/data/tweetstoblackterp.csv), [tweets that contained “black” and “umd” in their text](https://github.com/caitcl/datastory/blob/master/data/blackumdtweets.csv).

@blackterp is the twitter account of UMD’s Black Student Union. I selected their account because they maintain an active presence, tweeted many times during the weeklong collection period twarc could accommodate, and it seemed to me that the tweets of the BSU would reflect black student life and interests at UMD. In between April 29 and May 7, @blackterp tweeted 26 times. Using google sheets I determined that the most retweeted tweet from this time period was a tie between a retweet from @ASPACUMD (the African Students Progressive Action Committee at UMD) celebrating Freedom Day in South Africa, and a retweet from @SSAUMD (the Somali Student Organization at UMD) announcing their cultural show on April 29.

<img src="https://github.com/caitcl/datastory/blob/master/images/ASPACUMDretweet.png" height="400">
<img src="https://github.com/caitcl/datastory/blob/master/images/SSAUMDretweet.png" height="400">

I also captured tweets to @blackterp, in case this data would provide additional context and angles of analysis. This data set is very small, only 4 tweets, and unfortunately did not provide many points of analysis. Because these two data sets were very small (barely little big data!), I decided to do a twarc collection of tweets that included the words “black” and “umd” – I modified the search syntax to ‘”black””umd”’. 

This search uncovered 142 tweets that contained both “black” and “umd,” posted between April 27 and May 7. Using twitter’s advanced search interface, I discovered both very interested and relevant tweets:
 
“I’m so disconnected from black umd,” posted by an user who appears to be a current UMD student on May 5, a twitter thread comparing Netflix series *Dear White People* to UMD on May 4, a conversation on black men ignoring black women’s voices at UMD on May 7, as well as several tweets about the AADHUM imitative and black digital humanities. 

<img src="https://github.com/caitcl/datastory/blob/master/images/nnennannenna_tweet.png" width="700">
<img src="https://github.com/caitcl/datastory/blob/master/images/dearwhitepeopletweet.png" height="400">
<img src="https://github.com/caitcl/datastory/blob/master/images/africana_barbieblackwomentweet.png" width="700">
<img src="https://github.com/caitcl/datastory/blob/master/images/darylewilliamsblackdhtweet.png" width="700">
<img src="https://github.com/caitcl/datastory/blob/master/images/jluwritesblackdhtweet.png" height="400">

This was by far the richest twitter search for the type of data I am interested in, although there was also a significant amount of “noise” in the data set – tweets about the color black, or a satiric website named The Black Sheep (@BlackSheep_UMD) – that was unrelated to the topics of black student life on campus. This data set is also difficult to analyze using google sheets – the type of data story from Martha Kang’s 7 types that most resonates with the data I collected is “Start Big and Drill Down” – the interesting tweets I referenced in the paragraph above I discovered simply by reading the tweets in twitter’s advanced search, not by analyzing the collected data set as a whole. I struggled to find meaningful ways to use the the pivot table and chart creating capabilities of google sheets – after a few tries, I decided that the option to sort the number of each type of tweet (original, quote, retweet, reply) might provide some insight, so I will include that table and chart here.

<img src="https://github.com/caitcl/datastory/blob/master/images/blackumdtweetspivottableandchart.png" width="700">

## Ethical Considerations
Safiya Noble defined technological redlining as “the power of algorithms in the age of neoliberalism and the ways in which those digital decisions reinforce oppressive social relationships and enact new modes of racial profiling.” (page 1) I hope that by centering tweets created by black student organizations and about black life at UMD that I could negate the implicit power structures involved in using search algorithms (like twitter’s advanced search) and tools created by companies with spotty ethical records (like google), but I’m not sure if I accomplished those ends. I also worry about the ethical implications of capturing tweets created by personal student accounts in the “black” and “umd” search – while there is a certain level of personal remove when capturing organization or “official” social media communication, as in the case of @blackterp, the keyword search surfaces material that includes conversations between students that they might never imagine would be captures and analyzed in this way, and that makes me uncomfortable. While these tweets are set to be publicly viewable, I do not think the average twitter user expects that their thoughts and conversations will be used in this way. 
