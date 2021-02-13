# CodeRefractor
The original HTML document was a website made for Horiseon. The site was written with divs and lacked semantic HTML, which limited the site's accessibility to all audiences and viewership.

## Changes I Made to HTML:
The Horiseon website was written with solely using Div tags.

In order to make Horiseon's website accessible to all audiences I replaced all div tags in the HTML with semantic HTML tags and elements. 

To view and see the specific semantic HTML tags that were used please refer to the Index.html document. I have commented on all sections where div tags were either removed or replaced with semantic mark up.

### Disclaimer about Css:
In the Css I wanted to see if I could achieve the same formatting effects that float had on the .Contents and .Benefits classes by using Flex properties. It took me a lot of time to work and manipulate the Css to do so. I feel it is unfinished in the sense there is still the class Float-Left selecting the img tags of the .Content Class. Nonetheless it was fun practicing and seeing what could be achieved.
#### Changes I made to Css:

Removed Css class attribute (.) from all selectors containing header because the class was removed from the HTML.

Added Main to Css and added flex properties.

Removed float-right selector because it was redundant.

Removed Width propety from .Content and added Flex-basis 74%.

Removed width and float properties from .Benefits and added Flex-basis 25%.

Condensed multiple classes in the Css stylesheet. To view the specific classes that were condensed please refer to the comments within the Css stylesheet.

##### Collaboration

I was fortunate enough to work with and share ideas with the following:
Jason Barnabell: 
Takuya Matsumoto: 
Gabe Thomas:
Patrick Walker:

###### Links:


![refactored website demo](assets/images/demo-horiseon-website.jpg)



[github pages site] https://bdurham227.github.io/CodeRefractor/


[github repository site] https://github.com/bdurham227/CodeRefractor