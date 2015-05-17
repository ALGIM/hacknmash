# Team 3: More useful minutes and agendas

## Background
Output is to make agendas and minutes for council meetings more user-friendly/accessible. Most people are reluctant to scan through a document that sometimes exceeds 200 pages and are often laden with jargon. People come to find out about a specific issue and follow its progress.

Content around an issue doesn't necessarily have to be buried in a PDF. We're assuming that we can scrape some of this data if it's tagged in the source document, but other related content could be curated on other platforms, linking back to a single page on a council website, the single authoritative source. The level of detail offered would initially be brief (eg. what decision was made), and allowing the visitor to drill down into further detail (eg how each councillor voted) including background detail (useful for media queries) and locations. This could extend to linking to timestamps in audio or video so people can see/hear how topics were debated.

Issues could be followed by a unique hashtag across multiple platforms and/or location, with the ability to subscribe to updates.

* Users' interest is in the content of the agenda - not necessarily the agenda itself, which can be 200+ pages.
* Find info through search
* Must be responsive
* Document structure/styling not applied
* Information tagged appropriately
* Tagging timestamps on audio/video
* Council legalese not user friendly
* Hashtag subscription to issue-focused updates
* High level result, drill down to details (which way councillors voted), debate video /audio, transcript, issue timeline (eg. storify).
* Tagging segments of content inside source document (assumed to be PDF for this exercise).

## Outcomes
* More transparent around decision making processes
* Better informed and engaged community
* Useful research tool for community and media

## Brainstorm
* Users' interest is in the content of the agenda - not necessarily the agenda itself, which can be 200+ pages.
* Find info through search
* Must be responsive and lightweight, recognising some users could be on flaky 3G connections.
* Document structure/styling not applied
* Information tagged appropriately, issue/topic, location, meeting, organisation 
* Tagging timestamps on audio/video
* Council legalese isn't user-friendly. Re-purpose plain language versions from media releases.
* Hashtag subscription to issue-focused updates
* High level result, drill down to details (which way councillors voted), debate video/audio, transcript, issue timeline (eg. storify).
* Tagging segments of content inside source document (assumed to be PDF for this exercise).


## Defining the problem
![problem ideas](assets/team3-problem-id.jpg)

## Original content creation process
* Content creators (HR staff, minute takers etc) need to be trained to write the content in a way that when it is uploaded to the website it is already useable and scrapable e.g. proper heading and paragraph sections, good use of keywords and tags, bookmarking chapters within the document. This will save time later on adding extra tags and metadata to the pdf.
* Training may be needed on using built-in features in Microsoft Word for styles and metadata information.
* While creating the document, be mindful of the topics and areas of potential interest and note these down to be tagged later.
* Possibly have a small list of tags/hot topics to keep an eye out for.
* Ensure any documents being saved to PDF or other static filetypes are indexed and searchable - both for ease of searching later and to ensure accessibility for text-to-speech readers.

## PDF segmenting/scraping
* Use of existing tools to index and extract keywords from PDFs
* Tag documents with relevant keywords, apply date/location metadata
* Apply bookmarks and indexes if needed.

## Pulling in other media
* Many meetings and workshops are now recorded, either just audio or with full video
* Link to the relevant media
* Add timestamps so that users are taken directly to the relevant time in the discussion
* This is especially important for visually impaired users - listening to the meeting itself is more engaging than listening to text-to-speech of meeting minutes
* These can also be pushed out to social media platforms

## Mapping process
Extracting submitters' addresses from last month's agenda into a spreadsheet/fusion table
Convert to Fusion tables https://www.google.com/fusiontables/DataSource?docid=1nuA1thK6Di8M3uiDs5QjJ9RvyhdHVqT_6zvYC06r
embed code for heatmap of location of submissions map
<iframe width="500" height="300" scrolling="no" frameborder="no" src="https://www.google.com/fusiontables/embedviz?q=select+col2+from+1nuA1thK6Di8M3uiDs5QjJ9RvyhdHVqT_6zvYC06r&amp;viz=MAP&amp;h=false&amp;lat=-43.529555192349164&amp;lng=172.64111918891604&amp;t=1&amp;z=12&amp;l=col2&amp;y=2&amp;tmplt=2&amp;hml=GEOCODABLE"></iframe>

embed code for actual locations
<iframe width="500" height="300" scrolling="no" frameborder="no" src="https://www.google.com/fusiontables/embedviz?q=select+col2+from+1nuA1thK6Di8M3uiDs5QjJ9RvyhdHVqT_6zvYC06r&amp;viz=MAP&amp;h=false&amp;lat=-43.51310094886914&amp;lng=172.6653523842773&amp;t=1&amp;z=11&amp;l=col2&amp;y=3&amp;tmplt=4&amp;hml=GEOCODABLE"></iframe>
## UI ideas
![ui1](assets/team3-ui-idea.jpg)

![ui2](assets/team3-ui-idea2.jpg)
