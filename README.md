# horiseon-code-refactor

List of changes made:
1. HTML Semantic Element Cleanup:
    1. created a header element from what was previously a div container
    2. created a nav element from another div container (see also 3.2)
    3. Replaced class "seo" with id "seo" (see 3.1)
    4. Created a footer out of what was previously a div element with class "footer"
    5. Changed the footer h2 to a level h4 heading, updating the corresponding CSS selector accordingly, to preserve styling
    6. Created "section" semantic elements from div containers for the "Search Engine Optimization", "Online Reputation Management," and "Social Media Marketing," and "Lead Generation," and "Brand Awareness," and "Cost Management" sections
    7. Created a "figure" element from what was previously a div container with class "hero" (see 1.8)
    8. Created a figcaption for aforementioned figure element; hid said caption (see 1.7)
    9. Created an "aside" element from what was previously a div, to house the Lead Generation, Brand Awareness, and Cost Management sections


2. CSS Selector Consolidation
    1. 


3. CSS Cleanup
    1. Replaced ".header h1 .seo" with "#seo" id selector (see 1.3)
    2. Preserved stylings after creating the nav element from what was previously a div by changing 
    3. Replaced the clas "hero" with id tag of the same name, because it is single use.

4. Accessibility standard improvements
    1.  

Outstanding fixes:
- broken nav links (change HTML classes to id tags)
- div containers for content - find more appropriate HTML element
- img alt attributes
- heading attributes in sequential order