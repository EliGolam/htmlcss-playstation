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

### STEP 2: Choice of Guidelines
For this project, the framework chosen is **Bootstrap** for its ready-to-use capabilities and flexibility, perfectly valid for this project requiring proper responsiveness for both Mobile and Desktop user with a few complex interactions (such as the carousel) that the Framework has already implemented.

For proper accessibility, this project uses the guidelines provided by [**Carnegie Museums**](http://web-accessibility.carnegiemuseums.org/) and [**Accessible Rich Internet Applications (WAI-ARIA) 1.3**](https://w3c.github.io/aria/).

### Step 3: Layout Mockups

Layout mockups were provided by **Boolean**.
[ADD IMAGES]

## DEVELOPMENT

### sony-header

This is a simple element which was implemented exclusively in Bootstrap. Only the width of the **img** displaying the sony logo itself required the use of the **my-style.css** stylesheet for sizing. Since it appears to be mostly a decorative section, no ARIA was implemented other than the **alt** within the img tag. 

### top-nav

For appropriate UX it seems reasonable for the top-nav element to be always available at the top of the page. Its small size, non-intrusive and non-distracting simple looks makes it perfect for this purpose. For this reason it has been implemented as a **position: sticky** element. Sticky has been chosen over position: absolute because of the [**sony-header**](#sony-header) element present above it.  
The navigation bar is a **collapsable** element created through appropriate **Bootstrap classes**: [Toggled Navbar in Bootstrap](https://getbootstrap.com/docs/5.0/components/navbar/#responsive-behaviors)
An **aria-label** and **role** are added for Accessibility.

The nav-bar contains a **clickable svg** element contained within an anchor tag **navbar-brand** displaying the PlayStation Logo that is always visible whether the nav-bar is collapsed or not.
The 
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

### V 0.9

- Updated **README** Documentation
- Started implementing ARIA accessibility
