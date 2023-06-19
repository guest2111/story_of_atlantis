[project at GitHub pages](https://guest2111.github.io/story_of_atlantis/)
 
 # Table of Content

 * [Stories of Atlantis](#stories-of-atlantis)
 * [Features](#features)
 * [Testing](#testing)
   * [Browers](#browers)
   * [on small phone](#on-random-wide-screen)
   * [ipad](#ipad)
   * [on random wide screen](#on-random-wide-screen)
   * [zoomed on desktop pc](#zoomed-on-desktop-pc)
   * [Spelling Check](#spelling-check)
   * [Lighthouse Approved](#lighthouse-approved)
 * [Issues](#issues)
   * [Bugs](#bugs)
     * [Solved](#solved)
     * [Open](#open)
   * [Future Improvements](#future-improvements)
 * [Deployment & Local Development](#deployment--local-development)
   * [Deployment](#deployment)
   * [Local Development](#local-development)
 * [Codeanywhere Reminders](#codeanywhere-reminders)
 * [Sources](#sources)
   * [Media](#media)
   * [Code](#code)

# Stories of Atlantis

The webpage is intended to collect various webpages, which try to explain the history of Atlantis. People can contribute their own webpage to be displayed on this host webpage. One can navigate through the buttons on the top navigation bar. 
The welcome and story page have a background picture to support the athmosphere of ancient Greek world.
On the right site are supportive webpages.
The last page gives a form where a user can contribute with his own fantastical story.

# Features

Welcome page with short explanation what the webpage is for and how to interact.

Top navigation bar with buttons, which exchange the content by switching referenced html page.

The last button opens a page where to give ones own story and by that contribute to the idea.

The right side holds space for partners as references, where to go for building websites or just some distraction.

# Testing

## browers:
Firefox 112.0.2 (64-bit) on 5.19.0-41-generic #42~22.04.1-Ubuntu with KDE
Ecosia on Android 11, kernel 4.19.157-perf+

## on small phone: 			
![image](/docu/localhost_8000_(Samsung%20Galaxy%20S20%20Ultra).png)

on Fairphone with Ecosia:
![image](https://user-images.githubusercontent.com/93140389/235036969-58348e39-b191-4bf0-be2c-f304c47da8a1.png)

## ipad:
![image](https://user-images.githubusercontent.com/93140389/235037015-b2320f5a-4131-4179-9a89-ca786cb2fd10.png)

## on random wide screen:
![image](https://user-images.githubusercontent.com/93140389/235037065-327941cb-d804-43dd-a22b-ccfbffda23dc.png)

## zoomed on desktop pc:
![image](/docu/fullscreen_zoomed.png)

## desktop pc switched to 'wikipedia' subpage
![image](/docu/fullscreen_external_website.png)

## Spelling Check

style.css checked by
https://jigsaw.w3.org/css-validator/#validate_by_input

html files (excluding external page) checked by 
https://validator.w3.org/#validate_by_input

# Lighthouse Approved:

![image](https://user-images.githubusercontent.com/93140389/235037108-577e97b8-d3ed-4648-b1ff-2be77fd98962.png)

![lighthouse traders](/docu/lighthouse_traders.png)

The performance decreased because of not downscaled pictures. But this does not remove the possibility to zoom into pictures.

# issues

## Bugs:

### solved
1. Links were not all working.
2. I noticed, those where working which did not start from root directory ('/'), but locally and by that on referenced pages it was necessary to navigate first upwards in directory and the to the target: '../assets/css/style.css'
3. On wide screen the icons of partners could overlap because the image size was repsonsive although the wrapping element had a fixed height. As solution I removed the fixed height and added a margin to give space to each other.

 ![bug appearance](/docu/bug_wide_screen.png) ![bug fixed](/docu/bug_wide_screen_fixed.png) 

### open
1. between screen width 630 and 960 the background image in traders is jumping away from left side bar.
2. but 1. appears on zooming as well

## Future improvements:
1. In case of many storys, the buttons must appear to be scrollable or positioned more flexible.
2. Giving visual response as indicator on which story page the visitor is - maybe giving a colored border around the button.

# Sources

## Media

### Referenced

- https://codeinstitute.net/de/wp-content/themes/codeinstitute/img/svg/Code_logo_grey_fit.svg

- https://www.webfx.com/archive/assets/global/img/header/webfx-logo.png

- http://www.w3.org/2000/svg

- https://porenhub.de/img/porenhublogo4.gif

- https://img.freepik.com/free-vector/city-landmarks-background-video-conferencing_23-2148635775.jpg?w=2000&t=st=1682418883~exp=1682419483~hmac=809b46ef3442856d753d7eb17fcda789fbd88e433bbfd59ccef29a761f7655d9

- https://img.freepik.com/premium-photo/greece-santorini-island-iconic-view-with-blue-churches-oia-village_287743-185.jpg?w=2000

### Downloaded into source files

- https://de.freepik.com/fotos-kostenlos/taj-lake-palace-in-udaipur-rajasthan-indien_3540095.htm#page=2&query=ancient%20city%20on%20water&position=4&from_view=search&track=ais

- https://de.freepik.com/fotos-kostenlos/hausboot_1278009.htm#query=wooden%20house%20on%20water&position=48&from_view=search&track=ais

- https://de.freepik.com/fotos-kostenlos/schoene-aufnahme-eines-kleinen-dorfes-umgeben-von-einem-see-und-schneebedeckten-huegeln_13005858.htm#query=wooden%20house%20on%20water&position=26&from_view=search&track=ais

- https://de.freepik.com/fotos-premium/ein-see-mit-einem-dock-und-einem-berg-im-hintergrund_44867410.htm#query=houseboot&position=45&from_view=search&track=ais?sign-up=google

- https://de.freepik.com/fotos-premium/ein-bootshaus-am-wasser-mit-bergen-im-hintergrund_44737994.htm#query=houseboot&position=42&from_view=search&track=ais

- https://de.freepik.com/fotos-premium/antike-unterwasserstadt-in-den-tiefen-des-ozeans-atlantis-verlorene-welt-ki_36269755.htm#query=atlantis&position=7&from_view=search&track=sph


## Code

On a html report file generated by TraceCheck from Tracetronic I have seen the posibility to exchange the contant of an element by clicking on link. It was done via a `frame` element. I searched a way to this with buttons and found the `onclick=function()` method on:
 - [w3docs.com/](https://www.w3docs.com/snippets/html/how-to-make-button-onclick-in-html.html)

and thanks to 
 - [stackoverflow.com/](https://stackoverflow.com/questions/4836290/how-to-change-html-object-element-data-attribute-value-in-javascript)
I could write a little function which is exchanging the html reference of the element an replace it with another webpage.

But on the publi documentation it was adviced to not use the `frame` element since it is soon not supported
 - [developer.mozilla.org/../frame?](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/frame?retiredLocale=de)

So I searched for replacement elements and found the `obj`:
 - [stackoverflow.com/](https://stackoverflow.com/questions/18259232/alternative-for-frames-in-html5-using-iframes)

which can be read in detail: [developer.mozilla.org/../object](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/object)


# Deployment & Local Development 

## Deployment 

- the project is available on GitHub [link to github projes](https://github.com/guest2111/story_of_atlantis)

- a running example is on GitHub-Pages: [link to github pages](https://guest2111.github.io/story_of_atlantis/)

## Local Development 

- download the source code 
  - via the grafical user interface on GitHub [How to download](/docu/download_sources.png)
  - via command line with git: `git clone https://github.com/guest2111/quiz_of_trees`
    - for more details read documentations, eg. [2.1 Git Basics - Getting a Git Repository](https://git-scm.com/book/en/v2/Git-Basics-Getting-a-Git-Repository)
- run `python3 -m http.server` on your local terminal in the downloaded projects main folder (where the 'index.html' is located)
- open the website on your pc on your web browser: [localhost:8000](localhost:8000)
- or use open it on your phone: `<your-local-network-ip-adress>:8000`

[<font size = 4> `toc` </font>](#table-of-content)
