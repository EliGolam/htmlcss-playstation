# Exercise Boolean : Playstation HomePage

## STEPS

### Step 1 : Analysis of the layout

For any modern it's good practice to start with a **mobile-first** approach for the layout considering the current market.  
In the **mobile layout** most elements are stacked vertically, therefore it's quite easy to divide it into separate logical sections.

#### Division of webpage document

1. DIV - Sony Logo :  
    this is a very simple section with a dark background and white **SONY logo**. It's almost an **aesthetic element** so I think it would be better to **not use any headings** for this.  
2. NAV - nav-bar :
    This is the **main navigation** bar of the entire document. So, particular attention should be put to its **functionality and accessibility(ARIA)**.
    It contains the website's **H1** Heading that should be visually hidden, but present near the Playstation Logo.
3. [main] HEADER - carousel :
    This section in the main is separate in its function from the other ones present below. It's the main focus when the page is loaded, therefore I decided to categorize it as a header for the main.
    To implement its function we can make use of the **carousel** utilities and functionalities present in Bootstrap.
4. [main] SECTION - playstation-products :
    A **call-to-action** section that showcases to the user a selection of Playstation products, starting from the Playstation 5.
5. [main] SECTION - popular-games :
    A full size banner showcasing the popular games right now on Playstation 5.
6. [main] SECTION - new-releases :
    Square rounded cards that showcase newly released games and the amount of cards per row changes responsively with the size of the viewport.
7. [main] SECTION - other-products :
    A **call-to-action** section that showcases a selection of Playstation products with a button for each session. Each element of this section can be divided into articles with their own heading.
8. [main] SECTION - playstation-plus
    A **call-to-action** breifly presenting the PlayStation Plus subscription with a button redirecting to the PlayStation Plus page.
9. [main] SECTION - sales :
    This section presents on-going sales with each image containing hyperlinks that bring to the respective sale pages.
10. [main] SECTION - playstation-now
    **Call-to-action** briefly showcasing PlayStation Now with button taking the user to the appropriate page.
11. [main] SECTION - social-links :
    A responsive grid with image-links to the various socials of PlayStation
12. FOOTER - page-footer :
    Various lists of useful links for navigating the playstation website.

## VERSIONS

### v 0.1

- Added basic METADATA
- Divided HTML macrosections

### v 0.2

- Completed sony-header section

### v 0.2.1

- Completed top-nav section

### v 0.3

- Completed hero-carousel section

### v 0.4

- Completed playstation-products section

### v 0.5

- Completed popular-games section

### v 0.6

- Completed new-releases section

### v0.7

- Completed playstation-plus section  
- Completed sales section  

### V 0.8

- Completed HTML content
