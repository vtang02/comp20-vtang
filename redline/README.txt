Victoria Tang
Lab: Where's the Train?

1. I was able to render googlemaps on my webpage. However, I could not get
response data from MBTA Red Line real-time API so I was not able to parse the 
JSON data and display the locations of the Red Line trains. However, I still 
wrote javascript code to parse the response text and create markers (even 
though I did not get response text from mbta).

2. I discussed the assignment with George Brown.

3. I spent about 4 hours on this assignment.

Question: Is is possible to request the real-time data from MBTA using 
XMLHttpRequest?
Answer: It is not possible. Since I am hosting on the tufts homework server 
and I am making a XMLHttpRequest to the mbta server, they have different 
origins.  The same-origin policy says I can't get information from the mbta
server. 
