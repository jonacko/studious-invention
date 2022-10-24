# pedantic-atlantic-semantic
Challenge 1 assignment for UoB Bootcamp due 07-07-22 (updated 24/10/22)

Deployed link: https://jonacko.github.io/pedantic-atlantic-semantic/

Contents:

1. Summary
2. Key amendments
3. Issues encountered
4. Further Questions/contributions
5. Credits

# 1. Summary

This project was undertaken as a submission for a UoB Bootcamp assignment, with a brief to refactor the existing starter code with a view to improve accessibility and SEO rankings by introducing semantic HTML and consolodating CSS code where necessary.  The code style uses basic HTML and CSS.  The user story and acceptance criteria are as follows:

<img src ="Develop/assets/images/module-1-user-story.png">

The image below shows the appearance of the deployed application

<img src ="Develop/assets/images/module-1-deployed.png">

# 2. Key amendments

- Meaningful title
- 'Div soup'
- Image accessibility
- Consolidating CSS code
- Fixing links

### Meaningful title

I created a suitable title for the webpage (Horiseon: SEO & Online Reputation Management Services, to replace 'website' as in the source code) to make for more effective metadata.

### 'Div Soup'

On researching for the project I came across the term 'div soup' (which I love, and will now always rememeber!).  As I understand it, the 'div' elements should be used only as a last resort, and there are now (since HTML 5 was introduced) a number of more meaningful element terms to replace div that will enhance the semantic meaning of the code.  I therefore replaced the divs with the following elements (in chronological order):
- Nav
- Main
- Aside
- Footer (already assigned as a 'class' in the source code, but not an element)
- Sections within these elements

### Image Accessibility

One of the key points of the brief was to include accessible alt attributes.  I therefore included alt tags after each image source.

### Consolodating CSS code

An unnecessary number of classes were created in the source code.   I therefore grouped these classes for what became the 'main' and 'aside' elements to make the code more efficient and easier to read.

### Fixing links

Two of the three links from the nav bar to other areas on the webpage worked using id's; I simply substituted the div elements with the anchor element to enhance the semantic meaning of the markup, and also added the link to the 'search engine optimization' text in the nav bar which was absent from the source code.

## 3. Issues encountered

 After removing all the div elements and replacing with semantic HMTL elements, the 'aside' section moved down the page.  I tried a number of things to fix this, such as wrapping the aside into the main and reintroducing divs.  

Eventually, I changed the 'position' of the aside section, by moving it up from the bottom by 960 px, and this moved the 'aside' section upwards to the correct position.  However this inevitably resulted in a large gap between the main/aside section of the webpage and the footer.  I understand this is not an ideal solution, but it was the best fix I could manage at the time!


## 4. Further questions/contributions

1. Images in CSS/HTML - as I understand it, 'decorative' images should be included in CSS and images that relate directly to the content in HTML; I struggle to see where the line is drawn here in terms of allowing the webpage to be as accessible as possible (eg. for users with sight impairments), and feel that this particular project was ambiguous in this sense; when should images be written in HTML/CSS?

2. I am wondering whether the nav bar could be consolidated further - it would be interesting to know a) if this is possible and b) how to do this?
 
## 5. Credits

Source code: Xandromus: https://github.com/coding-boot-camp/urban-octo-telegram
