# Enhancing Audio Description
## Overview
A new website to replace the old one: http://enhancingaudiodescription.com/

## TODO
### now
home page
- pagignation starts at the top of the page - does the original one too?
- why can't I start a page at home#blog i.e. header? (was trying to add this to the pagignation code - but it didn't work)

- new Output page with filters
publications
- add hyperlinks where needed - why hyperlinks don't look the same when using Markdown?
- keep publications as list - or shall they be added as posts with feature images? perhaps both, if there is a nice way of doing this - maybe user can choose? 

press
- perhaps merge these three and add three links saying 'this article' was publishes here and here and here

podcasts/videos
- add podcast and video outputs to current posts if possible (if not, add new posts) and than add 'podcast' or 'video' tag to post?
-  recode {% if post.tags[0] == "publication" %} so that it checks whether the tag list consists of a specific tag e.g. "publication" tag instead (what it does now), of checking a specific tag[index] e.g. [0] - the first argument in the tag list
- add hyperlink conference where possible/needed
- add alt text to all images - how to add them to feature images?
- (maybe) add some sound image to the feature images where the podcast has a media file e.g. podcast or video 
  
panel list
- add new Panel List - M's email
- new logo (perhaps add logo and title next to each other in top menu?)
- readdress SoundCloud players - find minimal code and loose embedded image? 
- add Morgan and Lewis with one short paragraph at the end of Team's page
- why is image loading slow on team page?
- integrate MailChimp
- why do I sometimes need to click on the share button to see an image for Twitter/Facebook?
- how to add more authors?
- embed a SoundCloud playlist?

### Medium article
title: what I've learnt when moving the EAD website from Wordpress to GitHub Pages?

### later
- make Mailinglist subscription narrower, more centered.
- López or Lopez?
- how can I design a feature image that can be used as an OpenGraph for Facebook/Twitter, etc? - do I need to?
- shall I add meta to each page/post separately to aid SEO?
- interviews with conference presenters could maybe have a conference photo with their presentation and a link to the conference page?
- how could I remove the Gallery in the footer for some pages/posts?
- how come site folder is not seen in GitHub Desktop?
- instead of tag filter with images, have a similar tag filter as on the top of the tag page (on index page under blog grid)
- maybe remove the dates from the post tiles and add the date from the front-matter to the article.html (with new CSS)
- check Shelf Life link in Kling Gut
- update publication, presentation list
- update bios/photos, press e.g. 
  - https://www.thetechstreetnow.com/tech/researchers-develop-new-methods-to-enhance-film-experience-for-visually-impaired-audiences/1365352254061436296/1365352254061436296/
  - https://techxplore.com/news/2021-11-methods-visually-impaired-audiences.html? 
  - https://newsupdate.uk/researchers-develop-new-methods-to-enhance-film-experience-for-visually-impaired-audiences/ 
  - https://thehackposts.com/researchers-develop-new-methods-to-enhance-film-experience-for-visually-impaired-audiences/ 
  - M will send link to recent interview

## before switch
- export analytics (Google or other)

## log

- 2021-12-08 organising data in a new way using the 'Output' page
- 2021-12-05 ported all posts, changed some of the default code e.g. to have one column head in posts, experimented with sharing on social media, etc. 
- 2021-11-30 events and diary entries are posts - sometimes merged e.g. 
- 2021-11-26 got access to york assets folder (can use on external website).  added all events and sought better images. 
- 2021-11-25 teams page, redirect url, new subdomain for testing
- 2021-11-24 using hero.html for team page with additional support from details/summary html element.  having difficulties with external_url (redirect) without using a custom domain (it works on localhost and custom domain, now subdomain ead.khofstadter.com), but when publishing the site with the github url, the domain name (base url?) is added in front of the redirect url.  perhaps the idea is to always test in a subdomain (custom domain's subdomain).  menu rearranged with simply renaming them e.g. 1-home.md, 2-press.md, .. 
- 2021-11-23 exporting content from WordPress to Jekyll, most done for press and media page
- 2021-11-22 theme installed, minor changes made

## resources
- https://www.webaccessibility.com/ (one free monitoring per email account)
- https://webaccess.berkeley.edu/resources/tips/web-accessibility
- https://www.washington.edu/accessibility/web/
