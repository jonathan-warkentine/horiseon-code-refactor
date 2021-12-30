# horiseon-code-refactor

##Description of Changes

1. HTML Restrucutring
    1. Relabeled title element to "Horiseon Home Page"
    2. created "header" element out of div container, preserved class "header", modified corresponding CSS to preserve styling (see 2.1)
    3. Created "figure" element out of what was previous a div container containing the board meeting image
    4. Created a "figcaption" element within our new "figure" element for accessibility standard purposes (see 3.1)
    5. Created a "main" element from what was previously a div container, preserved class "content"
    6. Created "section" elements from what was previously div containers for the respective subsections of our "main" element.
    7. Added the id "search-engine-optimization" to the respective section to allow the function of the nav link
    8. Created an "aside" element from what was previously a div container, which contains the "benefit-lead", "benefit-brand", and "benefit-cost" sections
    9. Created sections from what was previously divs within the aforementioned "aside" element (see 1.8)
    10. Created a "footer" element out of what was previously a div container with class "footer"
    11. Changed the h2 in the footer to an h4 to be consistent with the heading hierarchy in the rest of the webpage. Updated the CSS accordingly.
    12. Removed the class "content" since we can use the new "main" element to select the element semantically (ie "main{}" in the CSS)
    


2. CSS
    1. replaced "div" with "nav" to preserve styling for 1.2 modifications.
    2. Consolidated classes "search-engine-optimization," "online-reputation-management," and "social-media-marketing" into the class "main-section", and updated the HTML accordingly
    3. Consolidated selectors ".online-reputation-management img", ".social-media-marketing img", and ".search-engine-optimization img" to one selector ".main-section img"
    4. Consolidated selectors ".online-reputation-management h2", ".social-media-marketing h2", and ".search-engine-optimization h2" to one selector ".main-section h2"
    5. Removed the "footer" class and replaced the selector with a direct "footer {}" tag in place of the ".footer {}" class tag
    6. Replaced class "benefits" for our aside with the semantic element selector "aside {}"
    7. Consolidated ".lead-generation", ".benefit-brand", and ".cost-management" classes with a single, shared class, ".benefit-section"
    8. Consolidated ".lead-generation h3", ".benefit-brand h3", and ".cost-management h3" classes with a single, shared class, ".benefit-section h3"
    9. Consolidated ".lead-generation img", ".benefit-brand img", and ".cost-management img" classes with a single, shared class, ".benefit-section img"
    10. Because it was redundant, the "header" class was removed from the "header" element, and the CSS updated accordingly to preserve styling.
    11. Simplified the "header h1 .seo" selector to "#seo", updated the seo class to be an ID tag




3. Accessibility Standard Improvements
    1. Created a caption for the primary image on our site (see 1.4)
    2. Created alt attributes for all HTML img elements



Outstanding Improvements:
- CSS commenting
