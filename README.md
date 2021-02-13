# CodeRefractor
The original HTML document was a website made for Horiseon. The site was written with divs and lacked semantic HTML, which limited the site's accessibility to all audiences and viewership.

## Changes I Made to HTML:

In order to make Horiseon's website accessible to all audiences I replaced all div tags in the HTML with semantic HTML tags and elements. Firstly, I moved the title tag to be positioned above the link to the Css stylesheet to organize the format of the html. Next the Div tag on line 13 was removed and replaced with a header tag. The Div tags on line 16 and 28 were changed to nav tags.  The Div tag with the "hero" class was changed to a figure tag. The Div tag on line 33 was changed to a main tag. The Div tag with the "content" class was changed to a section tag. Changed the Div tags containing the children within the section tags to article tags. Additionally, added an id called "search-engine-optimization" to enable the relative url for "search-engine-optimization" to redirect viewers to that content. Added alt and title attributes to all img tags. Changed div tag with "benefits" class to aside. Changed Div tags within the aside> to article tags. Changed Div tag with class of "footer" to footer tag. Changed the "heart" emoji inside the footer h3 tag to pseudocode to be viewed on all browswers.

### Disclaimer about Css:
In the Css I wanted to see if I could achieve the same formatting effects that float had on the .Contents and .Benefits classes by using Flex properties. It took me a lot of time to work and manipulate the Css to do so. I feel it is unfinished in the sense there is still the class Float-Left selecting the img tags of the .Content Class. Nonetheless it was fun practicing and seeing what could be achieved.
#### Changes I made to Css:

Removed Css class attribute (.) from all selectors containing header because the class was removed from the HTML.
Added Main to Css and added flex properties.
Removed float-right selector because it was redundant.
Removed Width propety from .Content and added Flex-basis 74%.
Removed width and float properties from .Benefits and added Flex-basis 25%.
Condensed the classes of benefit-brand, benefit-cost, and benefit-lead into one selector because they all shared the same properties.
Condensed all subsequent h3 tags of the aforementioned benefit classes into one selector because they all shared the same properties.
Condensed all subsequent img tags of the aforementioned benefit class into one selector because they all shared teh same properties.
Condensed the classes Online-Reputation-Management, Social-Media-Marketing, and Search-Engine-Optimization into one selector because they all shared the same properties.
Condensed all img and h2 tags of the aforementioned Online-Reputation-Management, Social-Media-Marketing, and Search-Engine-Optimization classes because they all shared the same properties.
Removed the Css class attributes from the footer tags.

##### Collaboration

I was fortunate enough to work with and share ideas with the following:
Jason Barnabell: 
Takuya Matsumoto: 
Gabe Thomas:
Patrick Walker:

###### Links:

<img src="https://files.slack.com/files-pri/T01LGCYB88Y-F01MTN0NA78/demo-horiseon-website.jpg> />

Link to Github website:
https://bdurham227.github.io/CodeRefractor/

Link to Github Repository:
https://github.com/bdurham227/CodeRefractor