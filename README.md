# P1-Mental-Health

<h1>ClearSpace</h1>

This is my first independent project as part of the Code Institute 16 week bookcamp. In this I aim to Design a cohesive one-page layout website with a main navigation menu and structured content using HTML with CSS and Bootstrap.

By providing accessible, beginner-friendly information on mental health and creating a welcoming webpage we can direct users toward our CTA: Sign up.



## Contents

1. [Introduction](#p1-mental-health)
2. [User Experience Design](#UX)
3. [Features](#features)
    - [Homepage Design](#homepage-design)
    - [Color Scheme](#color-scheme)
    - [Hero Image and Tagline](#hero-image-and-tagline)
    - [Articles and Resources Section](#articles-and-resources-section)
    - [Testimonials](#testimonials)
    - [Sign up Page](#sign-up-page)
    - [Thank You Page](#thank-you-page)
    - [Validated with](#validated-with)
3. [Resource Credit](#resource-credit)
4. [Known Bugs](#known-bugs)
5. [Future Features](#future-features)

<h2> User Experience Design </h2>

<h3> User Stories </h3>
1. User Story: Homepage Design

As a first-time visitor, 
I want to see a welcoming and visually calming homepage, 
so that I can feel encouraged to explore the website further.

2. User Story: Articles and Resources Section

As a user seeking mental health resources, 
I want to browse a well-organized articles section, 
so that I can easily find information relevant to my needs.

3. User Story: Responsive Design

As a mobile user, 
I want the website to be fully responsive, 
so that I can access content easily from any device.

4. User Story: Testimonials or Success Stories

As someone looking for support, 
I want to read success stories from others, 
so that I can feel inspired and hopeful about seeking help.

5. User Story: Contact and Support Options

As a visitor in need of help, 
I want a clearly visible "Contact Support" section, 
so that I can quickly find ways to reach out for assistance.

6. User Story: Color Scheme for Accessibility

As a user with visual sensitivities, 
I want the website to have a calming and accessible color scheme, 
so that I can navigate comfortably without strain.

7. User Story: Interactive FAQ Section

As a user with specific questions about mental health, 
I want an interactive FAQ section with collapsible answers, 
so that I can quickly find the information I need.


<h3> Project Board </h3>

External User’s Goal: The user seeks accessible, beginner-friendly information on mental health, including how to recognize common issues and manage stress, presented in a supportive and organised layout.

Site Owner’s Goal: The site owner wants to create a welcoming webpage that provides basic mental health information using a clean and supportive design. The focus is on using HTML and CSS with Bootstrap to create a calming and well-organised user experience.

<h2> Features </h2>

<h3> Homepage Design </h3>

 Designed a clean, visually appealing homepage with:
A calming hero section (e.g., soothing background image or gradient).
A clear navigation bar linking to key sections (e.g., resources, contact).
A brief welcome message or mission statement.
Used semantic HTML and styled the homepage using CSS for layout and aesthetic

 
<h3> Responsive Design </h3>

 Used media queries in CSS and boostrap to create a responsive layout.
Test and adapt the design for various breakpoints (e.g. mobile, tablet, desktop).

<img src="assets/images/Screenshot%20from%202024-11-12%2016-40-23.png">

<h3> Color Scheme </h3>

 For the color scheme I chose a calming color palette suitable for mental health (e.g., pastels, blues, and greens).Ensured text met WCAG contrast standards with tools like Contrast Checker.



<h3> Hero Image and Tagline </h3>

Hero Section with Positive Messaging: A Bootstrap Jumbotron with an encouraging message about mental health, using a calming colour scheme and a simple background image.
![Hero Section](assets/images/Screenshot%20from%202024-11-13%2010-24-08.png)

<h3> Articles and Resources Section</h3>

Created an Articles section with a grid or list layout of articles (e.g., title, short description, and “Read More” link). Semantic HTML elements like
and. Styled with CSS for a clean, organized look and ensured text content is easy to read with sufficient contrast.

<h3> Contact and Support </h3>
Included details and contact information for three of the leading mental health emergency services in a visually appealing but informative section which includes the their logos and a brief description.

<h3> Testimonials and FAQ </h3>
Created a Testimonials section using
and "section" and "blockquote". Added placeholder testimonials styled with CSS (e.g., card layout or sliders). 
<img src="assets/images/Screenshot from 2024-11-13 11-05-35.png">


<h3> Sign up Page </h3>
The Sign Up page includes a form where users can enter their details to create an account. The form captures essential information such as name, email, and password. Additionally, an embedded iframe is used to direct user to a wellness centre nearby they can use their memberships for discounts with.
<img src="assets/images/Screenshot%20from%202024-11-12%2014-08-14.png">

<h3> Thank You Page </h3>
The thank you page reverts the user back to the homepage and includes an inviting image.

<h2> Manual Testing </h2>
<h3> Validated with: </h3>
<li> https://validator.w3.org/nu/ </li>
<li> https://jigsaw.w3.org/css-validator/ </li>
<li> WCAG Color contrast checker </li>
<li> Lighthouse: Performance: 46-73, accessibility: 94, Best Practices: 93 <li>

<img src="assets/images/Screenshot from 2024-11-13 11-00-01.png">

<h2> Resource Credit </h2>
<li> ChatGPT for User Stories, Acceptance Criteria and Task List</li>
<li> Copilot for Image Generation</li>
<li> Imgur and Shuttershock for images </li> 
<li> Copilot for code generation</li>
<li> https://jigsaw.w3.org/css-validator/ </li>
<li> https://validator.w3.org/#validate_by_input </li>
<li> https://www.diffchecker.com/text-compare/ </li>
<li> https://www.fontawesome.com </li>
<li> Used Iconify to generate the icon </li>

<h2> Deployment </h2>
Used github for deploying the project and using lighthouse.

<h2> Known Bugs </h2>
<li> Responsive Design Issues: Initially, the layout was not responsive on smaller screens. This was fixed by adjusting the media queries and ensuring all elements scaled properly.</li>
<li> Form Validation Errors: The sign-up form was not validating user inputs correctly. This was resolved by adding proper HTML5 validation attributes and JavaScript checks.</li>
<li> Broken Links: Some internal links were broken due to incorrect file paths. This was corrected by updating the paths to match the project structure.</li>
<li> CSS Styling Conflicts: There were conflicts between custom CSS and Bootstrap classes. This was fixed by using more specific selectors and avoiding overrides of Bootstrap styles.</li>
<li> Image Loading Issues: Some images were not loading due to incorrect file paths or missing files. This was resolved by verifying the paths and ensuring all images were in the correct directory.</li>
<li> Accessibility Problems: The initial design did not meet WCAG standards. This was addressed by improving color contrast, adding alt text to images, and ensuring keyboard navigability.</li>

<h2> Future Feautures </h2>
<li> Make FAQ section interactive</li>
<li> Add some articles to a blog page </li>