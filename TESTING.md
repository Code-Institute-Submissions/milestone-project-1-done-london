![Done London logo](https://github.com/theopmw/milestone-project-1-done-london/blob/master/assets/images/done_boxlogo_lg.png?raw=true)

# DONE LONDON - Testing Details

[Main README.md File](README.md)

[View website in GitHub Pages](https://github.com/theopmw/milestone-project-1-done-london)

## Testing
---

**W3C  Markup Validation Service** and **W3C CSS Validation Service** were used by the developer to check the website code.

* [W3C Markup Validation](https://validator.w3.org/)
* [W3C CSS Validation](https://jigsaw.w3.org/css-validator/)

### User Stories Testing:

The most common path through the website:

* Home>Shop
    * The Home page features a **call to action button**, leading the user to the **Shop page**. This is also achievable using the **navigation bar** situated at the top of every page.
    * The About and Contact pages are not necessarily part of the flow of the site for all users but have been included to offer information about the company and how to contact them for users that are interested. All information is kept brief to avoid overloading the user.
    * The Basket page is not currently functional as it is beyond the scope of this project, this feature will be added in in the future.

Once basket/checkout functionality has been added and there are specific product pages for each item providing detailed product information and sizing options, this will change and become more complex. For example:
Home>Shop>Product Information>Basket/Checkout

### Testing User Stories From UX Section of README.md:

#### First time User Goals:

* As a First Time User, I want to easily understand the purpose of the site.
    * The imagery and navigation bar on the home page clearly indicte that this site is a clothes shopping site.
    * The call to action button on the hero carousel leads the user towards the shop page to view the products on offer.

* As a First Time User, I want to be able to easily navigate the site.
    * No matter what page of the site the user lands on, there is a clear navigation bar, highliging the current active page.
    * The logo to the top left of every page always leads back to the Home page.
    * The Home page call to action button leads the user to the Shop page in order to streamline the steps needed to make a purchase.

* As a First Time User, I want to be able to easily find out more information about the company.
    * A clearly labelled About page is easy to find in the navigation bar on every page.
    * The About page contains a short compelling text about the company, a brief video and links to press articles concerning the company should the user wish to find out more.

* As a First Time User, I want to be able to easily locate thier social media links to gather more information.
    * Links to the companies social media platforms in the form of icons are found in the footer of every page on all screen sizes.

#### Returning User Goals:

* As a Returning User, I want to be able to quickly view the products on offer.
    * A call to action button is featured on the Home page to direct the user to the Shop page.
    * A clearly labelled Shop page is easy to find in the navigation on every page.

* As a Returning User, I want to be able to make a purchase with the fewest steps possible.
    * As above, there is a call to action button on the Home page and a clearly labelled Shop page is easy to find in the navigation on every page to lead the user to the Shop page in order to make a purchase. Note that cart functionality is beyond the scope of this project but is listed as a feature to be added in later.

* As a Returning User, I want to find out about any new products on offer.
    * As above, there is a call to action button on the Home page and a clearly labelled Shop page is easy to find in the navigation on every page to lead the user to the Shop page in order view all product on offer.

* As a Returning User, I want to find the best way to contact the company with any questions or issues I may have.
    * A clearly labelled Contact page is easy to find in the navigation on every page.
    * The Contact page features several clear ways in which to contact the company, to suit the needs of the individual user.

#### Frequent User Goals:

* As a Fequent User, I want to sign up to the Newsletter so I am kept up to date with products, news and promotions/sales direct to my inbox.
    * The user can join the mailing list either via the email input in the footer on every page on desktop, or the join mailing list call to action button on the Contact page to recieve updates about new and upcoming products/promotions direct to their email.

* As a Fequent User, I want to find out if there are any new products for sale.
    * By using either the call to action button featured on the Home Page or the clearly labelled Shop page in the navigation on every page, users will be able to find the products currently on offer.
    * The user can also join the mailing list either via the emial input in the footer on desktop or the join mailing list call to action button on the contact page to recieve updates about new and upcoming products direct to their email.
    * New products and upcoming releases will also be annouced on the brands' social channels and links to them can be found in the footer of every page.

* As a Fequent User, I want to find out about any new releases coming up.
    * The user can join the mailing list either via the email input in the footer on desktop or the join mailing list call to action button on the contact page to recieve updates about new and upcoming products direct to their email.
    * New products and upcoming releases will also be annouced on the brands' social channels and links to them can be found in the footer of every page.

* As a Fequent User, I want to be able to find out the latest news on what the company is doing.
    * This information can be found on the company social media, links to all platforms can be found in the footer of every page.
    * A clearly labelled About page is easy to find on every page and provides more information about the company, including links to relevant recent press articles.

### Manual (logical) Testing of all Elements and Functionality on Every Page:

The below testing was completed to ensure that each element of the site behaves the way it is expected to and that the website design is responsive - that layout changes appropriately and maintains structural integrity across all device screen sizes:

#### Home Page:

1. Navigation Bar:
    1. Go to the Home page on a desktop.
    2. Reduce screen size to mobile to confirm that the navigation bar is responsive and switches from in-line menu to navbar toggler/burger icon dropdown at the appropriate place.
    3. When reducing screensize check that there is no overflow or overlap of menu items and that they always look appropraitely spaced.
    4. Check that the Home menu item is the active page and the navbar shows this - Home should be highlighted in black.
    5. Hover over other menu items to confirm they change colour from light grey to dark grey.
    6. Click on the logo to top left of navigation bar to confirm that it links to the home page.
    7. Click on each navigation menu item to confirm that it links to the correct page.
    8. Change screen size to mobile, click burger icon and confirm that menu drops down and menu items are positioned correctly.
    9. Repeat confirmation of responsiveness and functionality on different browsers.
    10. Repeat confirmation of responsiveness and functionality on tablet and mobile devices.

2. Hero Carousel:
    1. Go to the Home page on a desktop.
    2. Confirm carousel is visible and images scroll correctly.
    3. Check that header, carousel and footer take up the full viewport.
    3. Reduce screen size to confirm images change when reduced to tablet size.
    4. Reduce and enlarge size of window to confirm that "Shop Now" call to action button responds correctly.
    5. Click Hero Carousel controls to ensure they work on all screen sizes.
    6. Hover over "Shop Now" call to action button to confirm colour transition is correct.
    7. Click "Shop Now" call to action button to ensure it links to the shop page.

3. Footer:
    1. Confirm that Join Mailing List section works and "Submit" button colour transition on hover is correct - Note mailing list functionality is beyond the scope of this project and this feature will be added in at a later date.
    2. Click on each social media icon to confrim it links to the correct page and opens in a new tab.
    3. Reduce screen size to confrim that on tablet and mobile devices, the footer changes correctly to shop only social icons and copyright information.
    4. Confirm that social links are centre aligned on mobile and tablet and aligned right on desktop.

7. Review and confirm responsiveness and functionality on different browsers.

8. Review and confirm responsiveness and functionality on tablet and mobile devices.

#### Shop Page:

1. Navigation Bar:
    1. Repeat varification steps for Navigation Bar as completed on Home page.
    2. Confirm Navigation Bar code is identical on every page of site.

2. Hero Image:
    1. Reduce and expand window size to ensure the hero image behaves as it is expected and looks good on all screen sizes.
    2. Hover over image in Developer Tools to ensure correct alt text attribute is correct and descriptive.
    2. Check Hero Image on tablet and mobile devices.

3. Shop Items:
    1. Reduce screen size to ensure that shop items behave as expected when on moblile devices - from 4 items per row to 2 items per row.
    2. Hover over each image in Developer Tools to ensure correct alt text attribute is correct and descriptive.
    3. Check all shop items have correct title and pricing and these respond as expected on all screen sizes and devices.
    4. Click each shop item image to confirm this is a link back to the shop page - This will be changed to link to a bespoke item page in the future but is currently beyond the scope of this project.
    5. Hover over all "Add to basket" buttons to confirm colour transition is correct - Note cart funtionality is beyond the scope of this project but this feature will be added in the future.

4. Repeat steps performed to confirm footer responsiveness and funtionality on Home page.

5. Review and confirm responsiveness and functionality on different browsers.

6. Review and confirm responsiveness and functionality on tablet and mobile devices.

#### About Page:

1. Navigation Bar:
    1. Repeat varification steps for Navigation Bar as completed on Home page.
    2. Confirm Navigation Bar code is identical on every page of site.

2. Hero Image:
    1. Repeat varification steps for Hero Image as completed on Shop page.

3. Who We Are Section:
    1. Reduce and expand window to confirm about text behaves as expected on all screen sizes and devices.

4. Promo Video:
    1. Confirm video is visible on all screen sizes and devices, sizing behaves as expected and requires the user to click play in order to play the video (autoplay is disabled).
    2. Reduce and expand window to confirm promo video behaves as expected on all screen sizes and devices.

5. Press Section:
    1. Reduce and expand screen size to confrim text is center aligned on mobile and aligns left on tablet and desktop and each press article/link behaves as expected.
    2. Hover over "See more >>" buttons to confirm colour transition is correct.
    3. Click each link to confirm the correct link opens in a new tab.

6. Repeat varification steps performed on Home page to confirm footer responsiveness and funtionality.

7. Review and confirm responsiveness and functionality on different browsers.

8. Review and confirm responsiveness and functionality on tablet and mobile devices.

#### Contact Page:

1. Navigation Bar:
    1. Repeat varification steps for Navigation Bar as completed on Home page.
    2. Confirm Navigation Bar code is identical on every page of site.

2. Hero Image:
    1. Repeat varification steps for Hero Image as completed on Shop page.

3. Visit Is In Store Section:
    1. Reduce and expand window to confirm sub-heading and text behave as expected on all screen sizes and devices.

4. Shop Images and Map:
    1. Reduce and expand window to confirm images and map behave as expected.
    2. Reduce screen size to confirm only map image is shown on mobile - Google maps API to be added here in future but is currently beyond the scope of this project.

5. Send Us An Email Section:
    1. Reduce and expand window to confirm sub-heading and text behave as expected on all screen sizes and devices.
    2. Hover over email addresses to confirm colour transition is correct.
    3. Click each email address to confirm links work correctly.

6. Send Us A Message Section:
    1. Reduce and expand window to confirm sub-heading and from behave as expected.
    2. Fill in form to ensure it works correctly - Form submit funtionality is beyond the scope of this project but will be added at a later date. 
    3. Hover over "Send" button to confirm colour transition is correct.

7. Join Our Mailing List Section
    1. Reduce and expand window to confirm sub-heading and text behave as expected.
    2. Hover over "Join Mailing List" button to confirm colour transition is correct.
    3. Click "Join Mailing List" button to launch modal.
    4. Input email address into modal - Note mailing list functionality is beyond the scope of this project and this feature will be added in at a later date.
    5. Hover over "Join Mailing List" button to confirm colour transition is correct.
    6. Hover over "Close" button to confirm colour transition is correct and that it closes the modal pop-up.

8. Repeat varification steps performed on Home page to confirm footer responsiveness and funtionality.

9. Review and confirm responsiveness and functionality on different browsers.

10. Review and confirm responsiveness and functionality on tablet and mobile devices.

#### Basket Page:

1. Navigation Bar:
    1. Repeat varification steps for Navigation Bar as completed on Home page.
    2. Confirm Navigation Bar code is identical on every page of site.

2. Sub-heading and text:
    1. Reduce and expand window to confirm that text behaves as expected.

3. Repeat varification steps performed on Home page to confirm footer responsiveness and funtionality.

4. Review and confirm responsiveness and functionality on different browsers.

5. Review and confirm responsiveness and functionality on tablet and mobile devices.

### Testing using Chrome Developer Tools Lighthouse:

Lighthouse was used to flag any problems across all pages of the site for mobile and desktop devices, below are the issues that were fixed where applicable as a result of the reports generated.

#### Best Practices

* Links to cross-origin destinations flagged as unsafe for social links in footer (all pages) and press links (about.html).
    * rel="noopener" added to links improve performance and prevent security vulnerabilities.

#### SEO

* Document does not have a meta description flagged for all pages.
    * Added a <meta name="description"> element to all pages to improve search traffic and make each page appear more relevant.

### Bugs

* Navbar toggler icon/burger icon dropdown menu not working on xs/sm screen sizes using HTML code.
    * Rewrote navbar code using the [Bootstrap4 Navbar component](https://getbootstrap.com/docs/4.0/components/navbar/) to include navbar toggler functionality which simplified the code and allowed for improved UX and responsive design.

* Unable to style navbar toggler/burger icon dropdown menu featured in the navigation bar on xs/sm screen sizes
    * The default Bootstrap4 icon is an image URL so cannot be styled. To fix this, the image was replaced by a [Font Awesome bars icon](https://fontawesome.com/icons/bars?style=solid). Link to the Stack Overflow answer used [here](https://stackoverflow.com/questions/63695329/how-can-i-change-bootstrap-4-navbar-toggler-color-on-hover).

* Navabar toggler/burger icon dropdown menu items not aligning with logo.
    * Changed [Bootstrap Spacing](https://getbootstrap.com/docs/4.0/utilities/spacing/#notation) to remove spacing on small screens and increased spacing as screen sizes increased.

* Heading and Hero image elements were overflowing the page, pushing the right edge of the viewport too far out.
    * Used [Bootstrap4 Grid System](https://getbootstrap.com/docs/4.0/layout/grid/) to fix this using the container>row>col syntax.

* Images not loading in Github Pages 
    * When the site was originally deployed to Github Pages, the images failed to load despite working in the development version and previews. This was fixed by changing the file paths for images from "src="/assets/images" to "src="assets/images". This was achieved by removing the leading "/" using find & replace in GitPod.

* Hero carousel images on index.html not fitting all screen sizes with space for header and footer
    * Applied the following styling as suggested by mentor:
    ```
    .hero-carousel-image {
    height: calc(100vh - 158px);
    object-fit: cover;
    }
    ```

* Hero images too large on larger screen sizes
    * Applied the following sizing as suggested by mentor:
    ```
    .hero-image img {
    width: 100%;
    max-height: 70vh;
    object-fit: cover;
    }
    ```

* Video not loading in Github Pages
    * Similar issue to the above, the video failed to load despite working in the development version. This was fixed by changing the file path for the video from "src="/assets/video" to "src="assets/video". This was achieved by removing the leading "/" using find & replace in GitPod.

### Further testing:

* Asked friends and fellow students to use the site on a range of devices and report any potentail issues or bugs they found. No major issues were reported but there were comments made about uneven spacing on the About page so this was checked and modified.