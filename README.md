# goDaddyEmailSignature034 - Modern html email signature

This is an HTML email signature for my personal use [HTML Email Signature for Schalk van Dyk](https://svdwebtech.github.io/goDaddyEmailSignature034/). 

## Table of contents

- [goDaddyEmailSignature034 - Modern html email signature](#godaddyemailsignature034---modern-html-email-signature)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [Purpose](#purpose)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [Best Practices](#best-practices)
      - [Design rules](#design-rules)
      - [Development rules](#development-rules)
      - [Summary](#summary)
      - [How to create your html email signature](#how-to-create-your-html-email-signature)
    - [Continued development](#continued-development)
    - [Useful resources](#useful-resources)
  - [Author](#author)
  - [Acknowledgments](#acknowledgments)

## Overview

### Purpose

I aimed to build an html email signature for my branding purposes as a web developer and designer.

### Screenshot

![](./images/HtmlEmailSignatureScreenShot.png)

### Links

- Github URL: [Link](https://github.com/SVDwebtech/goDaddyEmailSignature034)
- Live Site URL: [Link](https://svdwebtech.github.io/goDaddyEmailSignature034/)

## My process

### Built with

- html doctype (htmlPUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd")
  
- css inline styling

### Best Practices

#### Design rules

There are a few things to keep in mind when designing HTML email signatures:

* Emails should be 600-800 pixels maximum width. This will make them behave better within the preview-pane size provided by many clients.
* Design for simplicity. Use grid-based layers and avoid complicated elements that require HTML floats or positioning.
* Assume images will be initially blocked by email clients, or that certain images—background images, for example—will completely fail to load.
* Don’t design an email that’s essentially one large, sliced-up image. While these kinds of emails look pretty, they perform poorly.
* Use basic, cross-platform fonts such as Arial, Verdana, Georgia, and Times New Roman.
* Avoid elements that require Flash or JavaScript. If you need motion in an email, a .gif is your best bet.
* Don’t forget about the mobile experience! Is your email readable at arm’s length on a small screen? Will the images slow its load time on a mobile device? Are your links easy to press with a thumb?

#### Development rules

There are best practices to follow when coding HTML email.

* Code all structure using the table element. For more complicated layouts, you should nest tables to build complex structures.
* Use element attributes (such as cellpadding, valign, and width) to set table dimensions. This forces a box-model structure.
* Keep your CSS simple. Avoid compound style declarations (IE: “font:#000 12px Arial, Helvetica, sans-serif;”), shorthand code (IE: #000 instead of #000000), CSS layout properties (IE: slot, position, clear, visibility, etc.), complex selectors (IE: descendant, child or sibling selectors, and pseudo-elements)
* Inline all CSS before sending.
* Use only absolute links for images, and host those images on a reliable server. 
* Don’t bother with JavaScript or Flash—those technologies are largely unsupported by email clients.
* Account for mobile-friendliness, if possible. Use media queries to increase text sizes on small screens, provide thumb-sized (~46x46px) hit areas for links. Make an email responsive if the design allows for it.
* Test, test, test. Create email accounts across various services, and send emails to yourself. Do this in conjunction with services such as Litmus.

#### Summary

* Create a full width containing table. This ensures your signature won’t wrap next to replies and forwards
* Consider the width of your signature – you want to keep it as narrow as possible. Think of your standard html email; best practice suggests they are between 550px and 650px wide. Also, many people will see your signature in their Outlook reading pane, so you want as much as possible to be visible
* Keep the number of empty rows and columns to a minimum because those text-only clients will add a line break for every empty row or column.  Use padding instead
*Use alt tags to replace images. You can use URLs for your social media alt tags. We’ve had mixed results on plain text emails – sometimes the alt text shows in place of social media icons; sometimes it’s left out
*Use inline css (in the td tag)
*Scale images in the html (export images at twice the size for retina screens)
*Export images as transparent PNGs – these will display nicely on emails with background colours and dark mode emails (if your logo isn’t too dark, of course!)


#### How to create your html email signature
 Follow these steps to create your own html email signature for your personal or business use.

Step 1 – design
Start by designing your signature in Photoshop. Double the size so that it renders well on retina screens. So, for example, if your total email signature width is 350px, resize your Photoshop canvas to 700px. You will scale the images in the html code.

Once your signature design is finalised, create slices and export your images to the same folder you’ll be saving your html to.

For our example, our email signature will have a table with 2 columns.

Step 2 – code
Using your html editor, create a new blank html file (the doc type doesn’t matter as this part won’t be copied into Outlook)
Create a full width containing table. This is so that the signature won’t wrap next to replies and forwards
Create a nested table (with the number of columns you require) into the containing table and set the fixed width
Insert your logo and scale down to the desired size
Use inline styling for font formatting (in the td tag works well)

### Continued development

This is a difficult process as there are no standards like in web development. It is basically trial and error. Lots of testing.  It is best to read up on best practices iro design and development.

### Useful resources

- [Figma](https://figma.com/) - Use this for logo and icon design. Also great to design you email signature layout.
  
- [imgbb](https://imgbb.com/) - Use it for free hosting of your images.
  
- [tinypng](https://tinypng.com/) - Use it to compress your images.

- [Article](https://www.cantaloupedigital.com/resources/how-to-create-an-html-outlook-email-signature/) - Great article with easy html design example
  
- [Best Practices](https://templates.mailchimp.com/getting-started/html-email-basics/) - Summary of best practices for design and development
  
- [Responsive HTML Emails](https://responsivehtmlemail.com/) - Great information and tutorials

## Author

- [schalkvandyk.com](https://www.schalkvandyk.com)
- LinkedIn - [LinkedIn Profile](https://www.schalkvandyk.com)
- Github - [Github Profile](https://www.schalkvandyk.com)
- Twitter - [Twitter Profile](https://www.twitter.com/@SVDwebtech)
- Facebook - [Facebook Profile](https://www.twitter.com/@SVDwebtech)

## Acknowledgments

A huge thank you to my wife and daughther for their love and patience, and a continious flow of ice cold water, coffee and tea. 
To the coding community at large and specifically some great articles by

- Tessa MacTaggart: How to create an html Outlook email signature - [Article](https://www.cantaloupedigital.com/resources/how-to-create-an-html-outlook-email-signature/)
- Mailchimp - [Best Practices](https://templates.mailchimp.com/getting-started/html-email-basics/)

Thank you. 