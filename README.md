# **The Coffee Palate**

Here comes the mockup image.

---

## **Project Goal** 

Welcome to the Coffee Palate!

Aren't you tired of always having to choose between hunderds of differents coffees when you go to the supermarket? Do you always end up choosing that kind of coffee that barely meet your preferences just because there is not enough information about it? Have you ever realized how big roasters are always deciding which coffee you must drink?
The Coffee Palate is finally here to give you exactly what you are looking for in a cup of coffee! 

You can finally stop complying with what big roasting companies think you need and adjust the coffee profile to your own specific palate.
If every person is different, why do we have to drink the same kind of coffee, right? Coffee by convenience is no longer what you need. You deserve you own unique blend!
Throughout this website you can learn about different coffee origins, learn about the roasting profiles and, finally, based on your brand-new acquired knowledge, develop your own exclusive blend. 
All of this, through an appealing, intuitive website with straight-forward and clear information.

Thank you for visiting my project and do not hesitate to contact me via GitHub if you have any doubts or concerns related to The Coffee Palate project.

---

## **Table of contents** 

---

## **UX**
---
### **User Goals & Stories**

#### **Goals**
As a user I aim for:
* a simple and intuitive website,
* with value-added content,
* displayed over visual attractive pages,
* containing clear information on coffee and blending process,
* with several call-to-actions.


#### **Stories**
As a user, I want to:
* buy good quality and year-round consistent coffee.
* be able to select several origins to use in my blend.
* be able to learn more about coffee produced worldwide.
* get to know where my coffee comes from.
* understand about the different roasting profiles.
* access an intuitive website, easy to navigate.
* easily find the company contacts.
* easily find the company's social networks.

#### **User Requirements & Expectations**

#### **Requirements**
* Easy navigation.
* Interesting and pertinent content about coffee and blends.
* Clear pricing information.
* Good access points to contact the company.

#### **Expectations**

* Clear information about the steps to make my own blend.
* When clicking on links to external pages, I expect the new page to be opened in a separate browser tab.
* During the blending process, user wants to receive tips through "Tooltips".
* Reach out to the user's specific blend throughout no more than 4 steps.
* Strong connection with website visual effects.
* Links must be working properly to reach the target with any setbacks.
* Receive feedback after submitting my order through the form.

### **Company Goals**

As the company owner, I want to:

* Establish the company online.
* Advertise the "make your own blend" as an innovative and unique service. 
* Attract customers to the ***art*** of blending.
* Promote different coffee origins.
* Educate the readers in regard to the different roasting profiles available.
* Convert webpage readers into potential customers.

### **Design Choices**
As a coffee roaster specialized in blends, I tried to choose colors, both cold and warm, that work harmoniously, standing out the same effect expected on a blend from different origins and coffee with different profiles.</p>
While trying to generate the business logo through [Tailor Brand](https://studio.tailorbrands.com/) I came across several appealing color schemes. Afterwards, I have transfered the most appealing one to [Coolors](https://coolors.co/) where, through slight adjustments, came up with a final, strong and harmounious scheme.

#### Fonts
Through [Tailor Brand](https://studio.tailorbrands.com/), I also got to know interesting font types. 

Afterwards, I have used [Google Fonts](https://fonts.google.com/ "Google Fonts") to try to replicate the ones found.

For the overall content I am using [Kumbh Sans](https://fonts.google.com/specimen/Kumbh+Sans?preview.text=unique&preview.text_type=custom&sidebar.open=true&selection.family=Kumbh+Sans) font. A font that is easily readable and visually attractive.

For the headings I have decided to go with [Allerta Stencil](https://fonts.google.com/specimen/Allerta+Stencil?preview.text=unique&preview.text_type=custom&sidebar.open=true&query=stencil) font, making the heading stand out from the general content and reflecting a characteristic from the roasting process: the cracks!

I trust that both typographies used blend very well with each other, creating a calm and inviting look to the website.

#### Icons
The icons that I will be using throughout my page are from [FontAwesome](https://fontawesome.com/ "FontAwesome").

The icons choosen are easy to understand and in line with the company branding , providing interest and supporting the navigation.

For instance, the navigation bar will collapse into a hambuger icon in mobile devices.

#### Colors

![Color Scheme](wireframes/tcp_color_scheme.png)


* congo-pink: #ed8074
The congo pink will be the color standing out the most as it will be used for the call-to-action buttons.

* metallic-seaweed: #1d7a8c;
The metallic-seaweed color will be and "aid" color. It will be used, if necesssary, to separate sections or highlight borders.

* outer-space-crayola: #0b3037;
This color will be the used throughout the website as the main text color. It has a great [contrast](https://coolors.co/contrast-checker/0b3037-f8f8ff) with the background.

* ghost-white: #f8f8ff;

The overall website will have a clean and fresh background, reason why I have opted by the Ghost White.
This particular color has a blue-purple accent that eases the transition to the three colors already mentioned.

In the creation of this palette, the [Contrast-Checker](https://coolors.co/contrast-checker/0b3037-f8f8ff) tool from [Coolors](https://coolors.co/ "Coolors") has been used in order to guarantee as good user readability. 

#### Structure

My website will be divided into 3 different pages.

##### Landing Page
The landing page is aimed to be visually attractive, with appealing images/icons that says "Welcome" by itself, unconsciously engaging the reader and creating curiosity to keep navigating throughout the page.

##### The Lab
The Lab is the educational part of the website where readers can come to learn more about the different coffee origins available and the several roasting profiles provided by the company.

##### Blending Store
The Blending store is the place where the magic happens. Here, the consumer can put into practice his/her new-found knowledge and create their own unique blend.

---

## **Wireframes**
### **Mobile** ###
#### **V1** ####
#### **V2** ####
### **Tablet** ###
#### **V1** ####
#### **V2** ####
### **Desktop** ###
#### **V1** ####
#### **V2** ####

---

## **Features**
### **Existing Features**
#### ***Navigation bar***
For the navigation bar, I have used Bootstrap to implement a responsive navbar across devices. In this case, the navbar is 100% visable in large screens, while on small/medium devices it will collapse into a hamburger menu, resulting in space saving of the real-estate.

Moreover, the navbar will highlight the page where you are.


#### ***Landing page***
The landing page is displayed through 3 hero-images, each representing a separate section.

On the first two sections, custom buttons were implemented to give the user another ossibility than the navbar tonavigate to the correspondingpages.

The last section is the subscriptioin section, which is implemented the same way across the pages.

#### ***The Lab***
The Lab page has been built following closely the design structure of the landing page. 

The introductory section uses a hero-image, whereas the following two section have implemented a carousel each. The page body ends at the subscription section.

Implementing the carousels with other content than pictures and make it responsive through devices has been quite a challenge, resulting in some trade-offs.

My first idea was to have fixed height carousels, but this resulted in a very complicated way to approach variable content. See [Debugging] section.

Therefore, I saw the need to restructure the carousels so they would work properly. For that I used Bootstrap grid to make the carousel adjust to the content and turn it into a fully responsive feature across devices.

#### ***The Store***
The store has a similar structure to the [The-Lab] page, whereas only one carousel is used instead of two.
On the same line as [The-Lab], this page also run into the same issues with the carousel. Insted of having variable content across slides (i.e text and graphs/diagrams) a form has been implemented.

Embeeding a form that has several steps, and consequently varies in height throughout the form itself, into a carousel was quite tricky.
To solve the responsiveness across devices, the solution passed by restructuring the carousel as explained in [Debugging] section.

[FontAwesome](https://fontawesome.com/ "FontAwesome") icons where used in the carousel title to visually also inform the user on which step he/she is in placing the order. 

#### ***Subscription***
The subscription section was an idea that came across through the actual coding and not idealized in the design process, result of missing some more intereactivity with the user.

Firstly, this section was implemented in the footer, but after discussing with my mentor and checking several other webpages, the decision was to implement it as an individual section to be used throughout the 3 htmls.

For this section I have used the Bootstrap flex grid.

#### ***Footer/Contacts***
The contact options are placed in the footer of the page, displaying social links and e-mail options, viat [FontAwesome](https://fontawesome.com/ "FontAwesome") for the user to get in contact with the company.

This is a simple and intutitive way of approaching it.

#### ***Modals***
Feeback to the user throughout the website and actions is fundamental. To address this user need, I have decided to implement modals linked to the "Susbscribe" and "Place Order" buttons. 

### **Future Features**
* Track&Trace for each order
* Personal profiles with history of user's purchases and blends
* Validation system to guarantee that user can only proceed from first slide on TheStore form after the blend totals 100%.
* Packaging customization form, where user uploads his/her own brand/logo to be applied on their coffee bags
* Imediate payment of the order through credit card, [Stripe](https://stripe.com/en-nl "Stripe") and [Paypal](https://www.paypal.com/nl/home "Paypal")
* Carousel on [TheLab] page with information on different brewing methods
* Updates Terms&Conditions under the [GDPR](https://gdpr-info.eu/ "GDPR") on how user data is used
* Implement an interactive shopping cart so the user can visualize in real-time his/her order and correspondant pricing

---

## **Languages, Libraries, Frameworks & Tools**
### **Languages**
* [HTML](https://www.w3.org/MarkUp/1995-archive/html-spec.html "HTML")
* [CSS](https://www.w3.org/Style/CSS/Overview.en.html "CSS")
* [Javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript "Javascript")

### **Libraries**
* [FontAwesome](https://fontawesome.com/ "FontAwesome")
* [Google Fonts](https://fonts.google.com/ "Google Fonts")
* [Unsplash](https://unsplash.com/ "Unsplash)

### **Frameworks**
* [Bootstrap](https://getbootstrap.com/ "Bootstrap")

### **Tools**
* [Git](https://git-scm.com/ "Git")
* [Gitpod](https://gitpod.io/ "Gitpod")
* [Balsamiq](https://balsamiq.com/ "Balsamiq")
* [W3C-Markup-validation](https://validator.w3.org/ "Markup Validator")
* [W3C-Jigsaw](https://jigsaw.w3.org/css-validator/ "Jigsaw Validator")
* [Google-Lightouse](https://developers.google.com/web/tools/lighthouse "Google Lighthouse") 
* [TinyPNG](https://tinypng.com/ "Tiny PNG")
* [Microsoft Excel](https://www.microsoft.com/en/microsoft-365/excel "Excel")
* [Contrast-Checker](https://coolors.co/contrast-checker "Contrast Checker")
* [Techsini](http://techsini.com/multi-mockup/ "Techsini")

---

## **Testing & Debugging**
<!-- ### **Testing**
#### **Requirements**
* Easy navigation.
* Interesting and pertinent content about coffee and blends.
* Clear pricing information.
* Good access points to contact the company.

#### **Expectations** -->

### **Order**

#### **User Stories & Requirements** ####
* buy good quality and year-round consistent coffee.**
* be able to select several origins to use in my blend.**
* Clear information about the steps to make my own blend**
* Receive feedback after submitting my order through the form.
* During the blending process, user wants to receive tips through "Tooltips".
* Reach out to the user's specific blend throughout no more than 4 steps.

##### **Plan of action** #####
##### **Execution** #####
##### **Testing** #####
##### **Test result** #####
##### **Conclusion** #####


### **Knowledge acquired**
#### **User Stories & Requirements** ####
* User Story: be able to learn more about coffee produced worldwide.
* User Story: get to know where my coffee comes from.
* User Story: understand about the different roasting profiles.

##### **Plan of action** #####
##### **Execution** #####
##### **Testing** #####
##### **Test result** #####
##### **Conclusion** #####


### **Navigation**
#### **User Stories & Requirements** ####
* User Story: access an intuitive website, easy to navigate.
* Strong connection with website visual effects.
* Links must be working properly to reach the target with any setbacks.

##### **Plan of action** #####
##### **Execution** #####
##### **Testing** #####
##### **Test result** #####
##### **Conclusion** #####


### **Contacts**
#### **User Stories & Requirements** ####
* User Story: easily find the company contacts.
* User Story: easily find the company's social networks.
* When clicking on links to external pages, I expect the new page to be opened in a separate browser tab.

##### **Plan of action** #####
##### **Execution** #####
##### **Testing** #####
##### **Test result** #####
##### **Conclusion** #####


### **Debugging**

---

## **Deployment**

---

## **Credits & Acknowledgments**
### **Credits**
### **Acknowledgments**
