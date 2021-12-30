# Willem Platerink Photography

Willem Platerink is an internationally acclaimed photographer who specialises in African wildlife and culture. With over 20 years’ experience, he has, over that time, built a global following who are drawn to his unique style when it comes to capturing the beating heart of Africa and its people. His work has featured in print media in over 100 countries as well as exhibiting in some of the most renowned galleries in the world. This website has been designed as an extension of the photographer himself. It is an expression of the artist’s style designed to bleed seamlessly through his work and back again. It is a place where collectors, exhibitors and dealers come together to look at work that has sold for several thousand dollars apiece. This is not designed to lasso an impulse purchase, rather it is built to emulate the experience of seeing Mr. Platerink's work in person.

<a href="https://robdeseg.github.io/HTML-CSS-Portfolio-Project/" target="_blank" rel="noopener">Willem Platerink Photography</a>

![A picture showing Willem Platerink Responsivity across four screen sizes.](assets/images/responsive-screens.webp)

# Contents

* [**Tone and Inspiration**](<#tone-and-inspiration>)
* [**Features**](<#features>)
    * [**Landing Page**](<#landing-page>)
    * [**Header**](<#header>)
    * [**Home**](<#home>)
    * [**Selected Works**](<#selected-works>)
    * [**Fine Art**](<#fine-art>)
    * [**Fine Art Example**](<#fine-art-example>)
    * [**Exhibitions**](<#exhibitions>)
    * [**Contact**](<#landing-page>)
    * [**Footer**](<#footer>)
    * [**RDS Design**](<#rds-design>)
    * [**Future Amendments**](<#future-amendments>)
* [**Testing**](<#testing>)
    * [Browsers](<#browsers>)
    * [Responsivity](<#responsivity>)
    * [Functionality](<#functionality>)
    * [Bugs](<#bugs>)
    * [Validator Testing](<#validator-testing>)
        * [HTML](<#html>)
        * [CSS](<#css>)
        * [Accessibility](<#accessibility>)
* [**Deployment**](<#deployment>)
* [**Credits & Acknowledgements**](<#credits-&-acknowledgements>)

## Tone and Inspiration

    The tone and inspiration for the style and feel of the website came from two sources. The first being the photographer himself. I was lucky to be able to interview him at length and discuss both his work and his philosophies on life. These became important considerations when designing the essence of the website and how it felt. The second, of course, are the photographs themselves, and these drove the overall aesthetic. It was important that his work sat within the pages of a site that looked seamless alongside them.

[Back to top](<#contents>)

## Features

    Form follows function. Always. And although that does not mean achieving one means compromising on the other, the overall UX was the principal consideration behind the design. The traffic through this site will be high net worth individuals who live in a world where everything works and works well. This drove the overriding goal of creating a simple and clean aesthetic, that is easy to use and intuitive.

 * ### Landing Page

    The landing page is designed to create the first and lasting impression of the kind of man Willem Platerink and, by extension, the sort of work he aims to create. There is an Entry button that takes you straight through to the Home Page, but equally, the site traffic here will not be rushing towards an impulse purchase. They are here to indulge in an artist and his work.

 * ### Header

    The header is clear, clean, and simple. Each heading explains precisely what it is, while the header itself lends a special awareness to where you are in the site. It operates as the compass to help steer you both forwards and backwards through each page of the site. 

    For the mobile phone screen size, it was decided that a dropdown menu would work better than simply shrinking the header menu further. This maintains ease of access to each page even on a small screen.


 * ### Home

    The home page is the business and the brand wrapped into one and it is imperative to set the tone and style for the whole website from the moment the user sets foot on this page. It also establishes the framework of header and footer for each page that follows throughout the site for a sense of uniformity and to help the user guide themselves through it intuitively.

 * ### Selected Works

    Selected works are a carefully curated selection of the artist's work. On the bigger screens they are displayed in two rows, while on the smaller one just one so that the user can sensibly appreciate each image even on the tablet and mobile sized screens.

 * ### Fine Art

    Each photo presented by the artist is available for purchase on a limited print run. This section aims to show you what to expect the finished, framed product to look like.

 * ### Fine Art Example

    This page is only accessible on the bigger screens to give the user a nice clear image of the artist's framed work. On smaller screens that image is displayed alongside the paragraph discussing the framing process. It is not expected that a serious buyer would view the work on a mobile-sized screen before initiating a purchase.

 * ### Exhibitions

    This section has been designed to be easily be changed every month to incorporate new and forthcoming exhibitions as and when they arise. 

 * ### Contact

    The contact section is designed to illustrate the international reach of the artist's work, while remaining true to the ethos of clean and simple functionality.

 * ### Footer

    Much like the header, the footer maintains the ethos of simplicity that runs throughout. There is a very simply form for those interested in joining the mailing list that requires only an email. The rest of the items all have their purpose without overfilling or cluttering the bottom of the site. 

 * ### RDS Design

    The link to the page for RDS Design is intentionally discreet. It is there without distracting from the focus of the site. For those interested in using RDS Design services, a simple form can be filled on a separate page. The website for RDS Design is under construction and a link to it will appear in future versions of this site. For now, the contact page for RDS Design has been kept simple and in line with the aesthetic of the rest of the site.

 * ### Future Amendments

    It is intended that each photo in the Selected Works section will be clickable and once done so, each image will expand to fill the whole screen so that the user can see the level of detail that goes into each photograph.

    The Privacy Policy and Terms & Conditions links do not currently have any content. This will be added once the lawyers have drawn up the appropriate wording.

[Back to top](<#contents>)

## Testing

 * ### Browsers

    The site has been fully tested across Chrome, Safari and Firefox and works well on each with no obvious issues.

 * ### Responsivity

    The site has been tested on standard sized screens across all platforms including on mobile phones, tablets, laptops and various different sized. Each page of the site proves fully responsive.

 * ### Functionality

    The site has been fully tested on several different subjects who found the navigation through the site to be straightforward and intuitive. Three repeating notes were made suggesting the clickable links to return from RDS Design page to the main website and to move from the Fine Art page to the Fine Art Example page more obvious. The same applied to the RDS Design tab in the footer. All three suggestions were addressed.

 * ### Bugs

    Bugs were generally small and resolved as part of the development process. 
    
    The validator testing threw up an issue with having a div as a child of a label element in the dropdown menu for mobile phones. This was resolved by using spans instead.

    Conversely, in the Contact section it stated h3 elements are not allowed as child elements of a span. I changed the spans to divs and this was equally resolved.

    It also said that the value of the attribute of one of the label elements in the Contact Form page needed to match the ID of a non-hidden form control. In this instance, I checked the label for="services-required" and the corresponding textarea id="services-required". They appeared to match. I copied and pasted one to the other to be sure and under further testing, no issues arose.

    Finally, there was an erroneous closing tab for an input field which was unnecessary and removed, as well as a stray end tag for a div in the Fine Art section which was also removed.

    * ### Unresolved Bugs

    On the index page for mobile phones only, there is a black line that appears above the photograph. It is not intended to be there, though currently I cannot work out how to remove it.

 * ### Validator Testing

    * #### HTML

        Save the one issue mentioned above, all pages returned the below report.

    ![HTML validator test result](assets/images/html-validator-result.webp)

    * #### CSS

    ![CSS validator test result](assets/images/css-validator-result.webp)

    * #### Accessibility

[Back to top](<#contents>)

![Lighthouse Accessibility test result](assets/images/lighthouse-accessibility-score.webp)

The pages of the site achived 100% across the board for Accessibility, Best Practices and SEO on desktop platforms. Performance ranged between 98-100% on all pages except the Selected Works page which is very image heavy. While the images have been compressed, it did pull the Performance down to 67%.

For mobile platforms, the SEO fell to 96% with the suggestion that the "tap targets" in the footer section are not appropriately sized. Having tested this on several subjects, I received no feedback that there were any issues when selecting those targets and therefore do not see this as a concern. Performace returned a figure of 65% on the Selected Works section for the same reason stated above, while all other pages corresponded to the results on the desktop platform.

THe Accessibility score remained at 100% throughout on both platforms.

## Deployment
    
 * #### This site was deployed to Github Pages using the following steps:

    1. First go to the project repository page [here.](https://github.com/Robdeseg/HTML-CSS-Portfolio-Project)
    2. From there, click on the Settings tab on the righthand side of the menu section across the top:
    ![Settings Tab](assets/images/settings-tab.webp)
    3. Once you are in Settings, click on the Pages tab on the left, second from the bottom.
    ![Pages Tab](assets/images/pages-tab.webp)
    4. You will then be in [Github Pages](https://github.com/Robdeseg/HTML-CSS-Portfolio-Project/settings/pages) where you will need to select the *Source*. From the *Branch* dropdown menu under the *Source* heading, choose *Main*.
    ![Selecting Source](assets/images/source-main.webps)
    5. Once you click *Save* the site is deployed and ready to share.

[Back to top](<#contents>)

## Credits & Acknowledgements

W3Schools helped with the arrangement of the photos into two columns in the selected works section using flexbox.

Coder Coder helped resolve the issue of amending the opacity of the background image (the globe) and not the text on top of it using ::before.

https://coder-coder.com/background-image-opacity

The navigation dropdown bar for mobile phone sized screns was taken from the following site, though amendments were made (mentioned above) to make it pass validation checks.

https://codepen.io/ngochuynh/pen/yKrvVZ

I used pexels.com for an image of a photo gallery for the background of the Exhibition page.

I would also like to thank the tutors, mentors and allumni at Code Institute for their advice and support throughout the development of this website. It has been invaluable.

[Back to top](<#contents>)

 