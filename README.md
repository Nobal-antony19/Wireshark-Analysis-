# Wireshark-Analysis
incident report and analysis of testing legal vulnerable websites  

🔍 Filters I Used in This Lab
For anyone who wants to try this themselves, these are the filters that helped me cut through the noise:
✨ HTTP Filters
 http.request.method == "POST"
 http.request.method == "GET"
✨ DNS & Discovery
 dns
 dns.qry.name contains "vulnweb"
✨ Keyword Searches
 frame contains "username"
 frame contains "password"
 
These helped me isolate exactly where the sensitive data was traveling.
the icident report is also tagged in this repo :) 


