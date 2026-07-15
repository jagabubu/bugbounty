General approach i use for bug bounty
## 1.Scope 
- Read the programs scope, what you are allow and not allowed to touch. 
#2. Subdomain
- Tools i used on allowed subdomains are "subfinder" (its on Github) and assetfinder (its also on GitHub).
#3. Identify alive hosts
- To find alive hosts linked to your findings, use httpx (GitHub)
#4.Content and endpoints findings
- I used ffuf to find some extra info about the given scope. (i havent used it as much so i can't provide useful info on this command)
5# Manual Traffic Interfarance
- Learn BurpSuite. Very powerful tool with free and paid versions. It allows users to sort of freeze time and bend reality. Intefere with travelling packets by stopping the process, change packet info and can easily exploit in website, database, etc. 
#6.Document
-DOCUMENT YOUR FINDGINGS WITH TIMES AND DATES. It's very easi to lose track of progress, especially when it feels close.  Log everything.
