# Enhancing Audio Description
## Overview
A new website to replace the old one: http://enhancingaudiodescription.com/

## TODO
### now

- add podcast 1 transcript
- ask Mariana: López, M. , BBC Sounds Amazing: Celebrating Innovation in Audio. 15th October 2020 [There is a video for this and I can ask for permission to use it, but it would have to be captioned as well]
- which one is this? https://dtg.org.uk/webcast/lets-talk-innovation-with-dr-mariana-lopez/

- check accessibility - continue with https://www.experte.com/accessibility
  - make meaningful alt texts (iframe titles as well)
  - add image-alt: '' to all posts
  - also check with https://platform.elevin.cloud/
  - check with Warren
  - consider seeking advices from 
    - https://www.york.ac.uk/about/equality/digital-accessibility/ and
    - https://groups.google.com/a/york.ac.uk/forum/#!forum/accessibledocuments-group
    - check: https://www.york.ac.uk/staff/it/staff-digital-skills-framework/
- new logo
  
### Home
- more integrated mailing list signup form (without new page opening up)

### Team 
- do we need a heading for Lewis and Morgan e.g. Honorary Mentions
- should we add other people from the last advisory panel (EAD I) as honorary mentions?

### Contact
- shall we add/mention Mariana's Twitter handle?

### Output
#### publications
- ! add publications (journal and conference as well?) as new posts (individual files) with links to the Output page

#### podcasts
- SoundCloud mini-player still not working
- add an audio symbol to the feature images in the post grid where the podcast has a media file e.g. podcast or video - but not to the image, instead, in a similar way to how the data is added to the tiles (so that it is not seen on the feature image added on the top of the post)

### general
- add tag filter to footer where tags link to the tag page (to specific headings)
- how to add more authors? (so I can display the author with an avatar for specific posts e.g. Mariana wrote some and Morgan as well. And this way we could have many authors e.g. contributions with more appropriate credits)
- ! the search results still have a hyperlink on the feature images and the title and they don't display all info under the image
- provide captions for videos and audio?
- can we embed Shelf Life or Pearl?
- how can I design a feature image that can be used as an OpenGraph for Facebook/Twitter, etc? - do I need to?
- shall I add meta to each page/post separately to aid SEO?
- how come site folder is not seen in GitHub Desktop?
- maybe remove the dates from the post tiles and add the date from the front-matter to the article.html (with new CSS)
- check Shelf Life link in Kling Gut
- random gallery after new page is loaded e.g. something dynamic

## before switch
- export analytics (Google or other)
- what I've learnt when moving the EAD website from Wordpress to GitHub Pages?

## after switch

## log
- 2022-01-08 sent summery video to M
- 2022-01-07 smaller team photos, smaller fixes for access, emma and lisa added to a.panel
- 2022-01-06 main MailChimp integration fixed, however would be good to have a better UX
- 2022-01-03 mailchimp identifier added (needs testing).  waiting for Elevin support to access dashboard (to test accessibility)
- 2021-21-28 higher score with https://www.experte.com/accessibility
- 2021-12-28 code changes
- 2021-12-10 pagignator has blog heading anchor, more outputs organised, minor feature image fixes
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
- https://www.smashingmagazine.com/2021/09/improving-accessibility-of-markdown/
