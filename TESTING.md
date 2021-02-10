![Done London logo](https://github.com/theopmw/milestone-project-1-done-london/blob/master/assets/images/done_boxlogo_lg.png?raw=true)

# DONE LONDON - Testing Details

[Main README.md File](README.md)

[View website in GitHub Pages](https://github.com/theopmw/milestone-project-1-done-london)

## Testing
---

The developer used **W3C  Markup Validation Service** and **W3C CSS Validation Service** to check the website code.

* [W3C Markup Validation](https://validator.w3.org/)
* [W3C CSS Validation](https://jigsaw.w3.org/css-validator/)

### User Stories Testing:

The most common path through the website:

* Home>Shop
    * The Home page features a **call to action button**, leading the user to the **Shop page**. This is also achievable using the **navigation bar** situated at the top of every page.
    * The About and Contact pages are not necessarily part of the flow of the site for all users but have been included to offer information about the company and how to contact them for users that are interested. All information is kept brief to avoid overloading the user.

### Testing User Stories From UX ection of README.md:

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
    * Links to the companies social media platforms in the form of icons are found in the footer of every page.

#### Returning User Goals:

* As a Returning User, I want to be able to quickly view the products on offer.
    * A call to action button is featured on the Home page to direct the user to the Shop page.
    * A clearly labelled Shop page is easy to find in the navigation on every page.

* As a Returning User, I want to be able to make a purchase with the fewest steps possible.
    * As above, there is a call to action button on the Home page and a clearly labelled Shop page is easy to find in the navigation on every page to lead the user to the Shop page in order to make a purchase.

* As a Returning User, I want to find out about any new products on offer.
    * As above, there is a call to action button on the Home page and a clearly labelled Shop page is easy to find in the navigation on every page to lead the user to the Shop page in order view all product on offer.

* As a Returning User, I want to find the best way to contact the company with any questions or issues I may have.
    * A clearly labelled Contact page is easy to find in the navigation on every page.
    * The Contact page features several clear ways in which to contact the company, to suit the needs of the individual user.

#### Frequent User Goals:

* As a Fequent User, I want to sign up to the Newsletter so I am kept up to date with products, news and promotions/sales direct to my inbox.
    * The user can join the mailing list either via the email input in the footer on every page on desktop, or the join mailing list call to action button on the Contact page to recieve updates about new and upcoming products direct to their email.

* As a Fequent User, I want to find out if there are any new products for sale.
    * By using either the call to action button featured on the Home Page or the clearly labelled Shop page in the navigation on every page, user s will be able to find the products currently on offer.
    * The user can also join the mailing list either via the emial input in the footer on desktop or the join mailing list call to action button on the contact page to recieve updates about new and upcoming products direct to their email.
    * New products and upcoming releases will also be annouced on the brands' social channels and links to them can be found in the footer of every page.

* As a Fequent User, I want to find out about any new releases coming up.
    * The user can join the mailing list either via the emial input in the footer on desktop or the join mailing list call to action button on the contact page to recieve updates about new and upcoming products direct to their email.
    * New products and upcoming releases will also be annouced on the brands' social channels and links to them can be found in the footer of every page.

* As a Fequent User, I want to be able to find out the latest news on what the company is doing.
    * This information can be found on the company socail media, links to all platforms can be found in the footer of every page.
    * A clearly labelled About page is easy to find on every page and provides more information about the company, including links to relevant recent press articles.

### Manual (logical) Testing of all Elements and Functionality on Every Page:

#### Home Page:

#### Shop Page:

#### About Page:

#### Contact Page:



### Bugs

* Navbar toggler icon/burger icon dropdown menu not working on xs/sm screen sizes using HTML code.
    * Rewrote navbar code using the [Bootstrap4 Navbar component](https://getbootstrap.com/docs/4.0/components/navbar/) to include navbar toggler functionality which simplified the code and allowed for improved UX and responsive design.

* Unable to style navbar toggler/burder icon dropdown menu featured in the navigation bar on xs/sm screen sizes
    * The default Bootstrap4 icon is an image URL so cannot be styled. To fix this, the image was replaced by a [Font Awesome bars icon](https://fontawesome.com/icons/bars?style=solid). Link to the Stack Overflow answer [here](https://stackoverflow.com/questions/63695329/how-can-i-change-bootstrap-4-navbar-toggler-color-on-hover).

* Heading and Hero image elements were overflowing the page, pushing the right edge of the viewport too far out.
    * Used [Bootstrap4 Grid System](https://getbootstrap.com/docs/4.0/layout/grid/) to fix this using the container>row>col syntax.

* Images not loading in Github Pages 
    * When the site was originally deployed to Github Pages, the images failed to load despite working in the development version. This was fixed by changing the file paths for images from "src="/assets/images" to "src="assets/images". This was achieved by removing the leading "/" using find & replace in GitPod.

