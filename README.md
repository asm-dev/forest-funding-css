# Reforestation in Galicia - Design with CSS

This repository contains a simple crowdfunding web page. The page is focused on achieving environmental actions that help restore Galician forests after they have been burned. 
> No real data is included; this is an educational proof of concept with purely demonstrative purposes.

The creation of this website is part of the activity program of the UEM Master's in Web Development. If you want to know more about the reasons behind its HTML structure or see how it looks with some JS, you should visit the following links:

1. [HTML structure](https://github.com/asm-dev/forest-funding-html)
2. [JS functionality](https://github.com/asm-dev/forest-funding-js)

The main idea behind the design proposed with this CSS is to create an intuitive and accessible interface that contributes to a good browsing experience, thereby boosting user donations.

&nbsp;

## Technical design notes

This activity reflects how modern CSS tools, combined with a user-centered approach, can transform a web page into a functional and visually appealing platform, thereby contributing to the success of _crowdfunding_ initiatives. 

As Steve Krug said in _Don't Make Me Think_, web design is not only about how something looks or works, but about how it feels to use. In terms of usability, we have integrated visual and functional elements that guide the user toward key goals, such as making a donation or exploring projects. For example, by choosing the "accent" color for the _Call To Action_ buttons. Although it may look like a simple website, every design element has been thought out to connect with potential users and thus reinforce the environmental purpose of the site.

- **Divide and conquer**. The CSS has been split into several files in order to improve scalability and code maintenance.

- **Use of variables**. They help maintain consistency throughout the page and reduce errors.

- **Implementation of nested CSS**. Nesting makes it possible to organize rules hierarchically, thereby improving readability.

- **Precise control of positions**. Using Flex and Grid makes it possible to play with alignments in a precise, adaptable and safe way.

- **Use of transitions and effects**. Several small details have been added to help keep the user's attention while browsing the site, for example an effect on the hover of the cards.

- **User first**. We must design interfaces with the user in mind. The color selection is inspired by the tones of nature and the forest, symbolizing the environmental goal of the project. As for typography, a modern and minimalist font was chosen to connect with a young audience.

- **A design adapted to all screens**. Although it is not _mobile first_, we made sure it is by no means _mobile last_ thanks to a responsive design that uses scalable units such as `rem` and _media queries_. Ensuring smooth navigation on all devices has a positive impact on the accessibility and usability of our site. Two examples of changes depending on the device dimensions are:

  - The top menu turns into a hamburger menu on mobile devices. 
  - In the "Let's Save Crecente" section, all available images are shown only when the device exceeds certain dimensions.

&nbsp;

Mobile devices             |  Larger devices
:-------------------------:|:-------------------------:
![mobile-screenshot](https://github.com/user-attachments/assets/0cd744fe-ffc6-4557-8ffe-3c91dd30fd3e)  |  ![desktop-screenshot](https://github.com/user-attachments/assets/0541c3ab-2dd7-4980-83de-cc14841bbcbd)
