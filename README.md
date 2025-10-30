# Prevent Aware
Prevent Aware is a flagstone project with Code Institute, that aims to show a solid understanding of HTML and CSS. It's a single page website focusing on the PREVENT initiative created by the UK Government.

Users should expect to be able get a quick understanding of the main principles of PREVENT through a variety of media including: text, images and video.

Design choices for this project were focused on creating a sense of calm, while also maintaining a professional and cohesive look. A responsive design was also implemented to provide ease of navigation regardless of the device accessing the site.

## Desktop


![screenshot](readme-images/prevet-desktop.png)


## Tablet

![sreenshot](readme-images/prevent-tablet.png)

## Mobile

![screenshot](readme-images/prevent-mobile.png)

## UX Design

### Typography

[**Font Awesome**](https://fontawesome.com) icons were used throughout the project. Examples being the contact and social media icons

[**Manrope**](https://fonts.google.com/specimen/Manrope) was used for headings.

[**Sora**](https://fonts.google.com/specimen/Sora?query=sora) was used for the main bodies of text.

### Colour Palette

A [**Colour Picker**](https://imagecolorpicker.com/) was used to grab various tones from one of the site's images.

![screenshot](readme-images/colour-picker.png)

This produced a colour palette like this:

![screenshot](readme-images/prevent-palette.png) 

Which was then refined into this:

![screenshot](readme-images/prevent-palette-final.png)

Selecting a colour palette this way allowed for a cohesive design between both the site's text and images. A Dark Teal was used as the primary colour, namely the navigation bar, headers and buttons, a lighter teal was used on the button to give user feedback. A white was used for text on the navigation bar and footer to provide better contrast, as well as for the background. A light grey was used on the social icons to again provide user feedback. All other text is black for contrast.

A [**Colour Contrast Checker**](https://webaim.org/resources/contrastchecker/) was used to check colour contrast.

### Wireframes

#### Desktop
![screenshot](readme-images/wireframe-desktop1.png)
![screenshot](readme-images/wireframe-desktop2.png)
![screenshot](readme-images/wireframe-desktop3.png)


#### Mobile

![screenshot](readme-images/wireframe-mobile1.png)
<br>

![screenshot](readme-images/wireframe-mobile2.png)


#### Tablet

![screenshot](readme-images/wireframe-tablet1.png)
<br>

![screenshot](readme-images/wireframe-tablet2.png)





## User Stories

<strong>As a user , I want the website to be able to access the site regardless of whether I am on desktop or mobile so I can view the page content on any device.</strong>

- The website is fully responsive across various devices and screen sizes.

- Site layout and navigation are intuitive, allowing easy access to different sections.

<strong>As a user with accessibility needs, I want the website to have proper colour contrast and alt text for images, so that I can access all the information regardless of my abilities.</strong>

- All images used should have alt text


- Colour pallete used should contrast and be easy to read

<strong>As a first-time user, I want the information to be organised in clear sections with headers, so that I can easily find the specific information I need.
</strong>

- Information is organised clearly in sections with headers

- Internal links should help users navigate to specific sections of information

<strong>As a user seeking help, I want prominent call-to-action buttons, so that I can quickly access resources or reporting mechanisms without searching.</strong>

- Clear and contrasting call-to-action buttons

- Call-to-action buttons are available to the user without the need for searching

- Links to external resources available for the user

<strong>As a first time user, I want to quickly understand what the Prevent strategy is, so that I can learn about its purpose and importance in the community.</strong>

- A clear, concise introduction to Prevent is visible within the first viewport on desktop and mobile

- The explanation uses plain language accessible to a general audience

- The purpose and importance are highlighted prominently

<strong>As a concerned individual, I want to easily recognise the signs of radicalisation, so that I can identify potential risks in my community or workplace.</strong>


- Signs of radicalisation are presented in a clear, scannable format (e.g., bullet points or list groups)

- Information is organised logically with clear headings

- Content avoids jargon and uses accessible language

- Visual hierarchy makes key points stand out

<strong>As a member of the public, I want clear information on how to report concerns, so that I can take appropriate action if I suspect someone is at risk.</strong>

- Contact details or links to reporting mechanisms are clearly visible

- Reporting information is easily findable and prominently displayed

![screenshot](readme-images/project-board.png)

## Features

### Acordion

- Accordion was used to present information to the user without overload. It has been designed to provide feedback to the user by changing the heading colour when clicked.

![screenshot](readme-images/desktop-accordion.png)

- The picture was hidden on smaller screens to prevent clutter.

![screenshot](readme-images/mobile-accordion.png)

### Cards

- Cards were used in the Radicalisation section, on smaller screens (mobile and tablet), they are displayed as a carousel:

![screenshot](readme-images/cards-mobile.png)

- however on larger screens, they are displayed in a 3 x 2 grid.

![screenshot](readme-images/cards-desktop1.png)

![screenshot](readme-images/cards-desktop2.png)

### Video
- The video is fully responsive across mobile and desktop and was embedded via YouTube.

![screenshot](readme-images/video-desktop.png)

![screenshot](readme-images/video-mobile.png)


### Navigation Bar

- The navigation bar was created via Bootstrap's navigation bar and so is responsive across devices.

![screenshot](readme-images/navbar-desktop.png)

![screenshot](readme-images/navbar-mobile2.png)

### Footer
- Footer is a simple design with contact details and social links

![screenshot](readme-images/footer.png)


## Testing

### Manual Testing

The site was manually tested using the following web browsers:

<strong>Chrome</strong>

| Test | Result |
|------|--------|
|Click logo| Success|
|Click Home|Success|
|Click Prevent Strategy|Success|
|Click Radicalisataion|Success|
|Click Report Concerns|Success|
|Click External Resources|Success|
|Click Button|Success|
|Open/Close Accordion| Success|
|Next/Prev on Carousel|Success|
|Play Video|Success|
|Open External Resources|Success|


<strong>FireFox</strong>

| Test | Result |
|------|--------|
|Click logo| Success|
|Click Home|Success|
|Click Prevent Strategy|Success|
|Click Radicalisataion|Success|
|Click Report Concerns|Success|
|Click External Resources|Success|
|Click Button|Success|
|Open/Close Accordion| Success|
|Next/Prev on Carousel|Success|
|Play Video|Success|
|Open External Resources|Success|


<strong>Edge</strong>

| Test | Result |
|------|--------|
|Click logo| Success|
|Click Home|Success|
|Click Prevent Strategy|Success|
|Click Radicalisataion|Success|
|Click Report Concerns|Success|
|Click External Resources|Success|
|Click Button|Success|
|Open/Close Accordion| Success|
|Next/Prev on Carousel|Success|
|Play Video|Success|
|Open External Resources|Success|


### Lighthouse
- Lighthouse from Chrom Developer Tools was used for performance and provided these scores:

![screenshot](readme-images/lighthouse.png)

### Validators

#### HTML

W3C's HTML Validator provided:

![screenshot](readme-images/html-valid.png)

#### CSS

W3C's CSS validator provided:

![sreenshot](readme-images/css-valid.png)

## Deployment
GitHub Pages was used to deploy the site.

## AI

AI was used throughout the project to compliment my own coding. It was used mainly for user stories, debugging and image generation but was also used for some styling. The AI used was ChatGPT and Copilot.

### Debugging

There was a couple of times in this project where AI was used to debug issues, the code was reviewed by me before being either accepted or rejected. Example below is from when my CSS styles weren't applying to the navigation bar.

![screenshot](readme-images/debug.png)

### Image Generation
Although there are ethical concerns when using AI for image generation, as this is a first solo project, code was first and foremost. In future projects AI image generation may not be used.

### Styling
AI was used to help style some of the Bootstrap elements, namely the accordion, but it was also used to help with some positioning of other elements.

![screenshot](readme-images/style.png)

## Credit
The information for this project was gathered from:
- [**Sunderland City Council**](https://www.sunderland.gov.uk/article/12176/Preventing-radicalisation-and-the-prevent-duty)

- [**Lewisham Safeguarding Adults Board**](https://www.safeguardinglewisham.org.uk/lsab/lsab/professionals/contest-and-the-prevent-strategy)

- [**Action Counter Terrorism**](https://actearly.uk/spot-the-signs-of-radicalisation/what-to-look-for/)

Video Credit:
- [**London Professional College**](https://www.lpc.ac.uk/)

Image Credit:
- Generated by Copilot



