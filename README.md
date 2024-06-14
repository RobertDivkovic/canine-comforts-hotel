# Canine Comforts Hotel

Welcome to the Canine Comforts Hotel! Our hotel provides a luxurious and safe environment for your dogs while you are away on business trips or vacations. We are located in the serene surroundings of Vienna's 21st District, Floridsdorf, offering a perfect getaway for your furry friends. Our hotel is designed to cater to the needs of dogs of all breeds and sizes, ensuring they enjoy their stay just as much as you enjoy your time away. Below is an overview of our project's UX design, including the strategy, scope, structure, skeleton, and surface planes.

## Table of Contents

- [The Strategy Plane](#the-strategy-plane)
- [The Scope Plane](#the-scope-plane)
- [The Structure Plane](#the-structure-plane)
- [The Skeleton Plane](#the-skeleton-plane)
- [The Surface Plane](#the-surface-plane)
- [Project Files](#project-files)
- [How to Run the Project](#how-to-run-the-project)

## The Strategy Plane

### Creator Goals
- **Seamless Navigation:** As a creator, I aim for the website to offer intuitive navigation.
- **User-Friendly and Responsive Design:** As a creator, I want the website to be accessible and responsive on all devices.
- **Immediate Service Awareness:** As a creator, I want visitors to quickly understand the services provided by the hotel right from the homepage.
- **Encourage Bookings:** As a creator, I aim to motivate users to book accommodations for their pets through clear and compelling calls to action.
- **Establish Trust:** As a creator, I want to build trust with users by providing detailed descriptions of our services and showcasing positive testimonials.
- **Professional Presentation:** As a creator, I want the website to present a professional image that reflects the high-quality care and luxury provided to the dogs.

### User Stories
- **Effortless Site Navigation:** As a user, I want to effortlessly browse different sections of the site.
- **Clear Purpose:** As a user, I need to understand the purpose of the site quickly to determine if it meets my needs.
- **Detailed Service Information:** As a user, I want comprehensive information on the accommodation options available.
- **Accessible Contact Information:** As a user, I want to easily find contact details to reach out to the business.
- **Simple Booking Process:** As a user, I desire a straightforward process for booking accommodations for my dog.
- **Aesthetically Pleasing Design:** As a user, I prefer a visually appealing site that reflects the comfort and luxury of the hotel.
- **Reassurance on Safety and Care:** As a user, I need to know how my pet will be cared for to ensure their safety and well-being.
- **Read Positive Feedback:** As a user, I want to read testimonials from other customers to feel assured about the quality of the service.

### Research Basis
These user stories are derived from thorough online research, personal experiences, and feedback from fellow pet owners. By understanding the goals and needs of both the creators and users, the website is designed to deliver a seamless experience that meets expectations and facilitates easy booking and information access about Canine Comforts Hotel.

## The Scope Plane

### Feature Selection Process
During the planning phase of the Canine Comforts Hotel website, I prioritized the essential features that align with our user stories. Some advanced features were postponed due to time constraints but are planned for future updates.

### Features Implemented at Launch
- **Home Page:** Introduces the hotel with a welcoming message and displays operating hours.
- **Navigation Bar:** Fully functional and intuitive navigation bar allowing users to easily access different pages.
- **Accommodation Page:** Provides detailed information about the various accommodation options available for dogs.
- **Sign-Up Page:** Enables users to register their dogs and book accommodations through a comprehensive form.
- **Thank-You Page:** Confirms the user's submission and provides a summary of the information submitted.
- **Footer:** Contains the hotel’s address, contact details, and links to social media platforms.

### Planned Future Features
- **Booking Confirmation Email:** A feature to send users an email confirmation after booking accommodations or submitting a form.
- **Customer Reviews Section:** An additional section on the home page showcasing reviews from satisfied customers.
- **Photo Gallery:** A new page featuring a gallery of photos showcasing the hotel’s facilities and activities.
- **Live Chat Support:** A feature to provide real-time assistance to users navigating the site or making bookings.

### Feature Prioritization
The following table outlines the feasibility and importance of each feature, which guided the development timeline:

| Feature                  | Feasibility | Importance |
|--------------------------|-------------|------------|
| Navigation               | 5           | 5          |
| Home Page Introduction   | 5           | 5          |
| Operating Hours Display  | 5           | 5          |
| Accommodation Details    | 5           | 5          |
| Sign-Up Page             | 5           | 5          |
| Social Media Links       | 5           | 5          |
| Booking Confirmation Email | 4         | 4          |
| Customer Reviews Section | 4           | 4          |
| Photo Gallery            | 5           | 4          |
| Live Chat Support        | 3           | 3          |

These decisions were based on balancing the feasibility of implementation within the given timeframe and the importance of each feature in enhancing user experience and meeting business objectives.

## The Scope Plane

### Colors
- **#292828:**
  - Main text color
  - Icons
  - Headers and subheaders

- **#FFFFFF:**
  - Header background
  - Navigation bar
  - Background color for various sections
  - Footer background
  - Text on darker backgrounds

- **#7D481A:**
  - Table background
  - Borders for table cells
  - Background color for some sections

- **#544F4F:**
  - Table header background

- **#87603C:**
  - Background gradient start
  - Footer background

- **#C59C3D:**
  - Background gradient end

- **#EBF0F0:**
  - Input fields background
  - Form backgrounds

### Fonts
Both fonts used in this project are Google Fonts.

- **Roboto:**
  - I used Roboto as the main font, as it's one of the most popular and user-friendly fonts. The Roboto font is easy to read even on the smallest devices and provides a positive user experience.

### Images
All images used in this project have been downloaded from:

- Pexels
- External sources credited in the appropriate sections

More information in the credits section.

## The Skeleton Plane

### Layout Design

#### Header
- **Elements:**
  - Logo linking to the home page (`index.html`)
  - Navigation bar with links to Home, Accommodation, and Sign-Up pages
- **Styles:**
  - Fixed at the top of the page
  - Background color: `#FFFFFF`
  - Box shadow for slight elevation
  - Responsive design with a collapsible menu on smaller screens

#### Main Content
- **Home Page (`index.html`):**
  - **Top Section:**
    - Hero image with the hotel's name and location
    - Call-to-action button linking to the sign-up page
  - **Reason Section:**
    - Three columns highlighting key benefits (Expert Care, Socialization, Comfortable Accommodations)
    - Icons and text descriptions
    - Circular images for visual appeal
  - **Testimonials Section:**
    - Client testimonials with quotes and client names

- **Accommodation Page (`accommodation.html`):**
  - **Introduction Section:**
    - Heading and introductory text about the accommodations
    - Gradient background for visual interest
  - **Accommodation Types:**
    - Descriptions and images of different suite options (Exclusive Suites, Anti-Stress Suites, Royal Suites)
    - Separator lines between sections

- **Sign-Up Page (`signup.html`):**
  - **Form Section:**
    - Registration form for owners to book accommodations
    - Input fields for owner and dog information, suite preferences, and additional options
    - Background image with an overlay for better readability

- **Thank-You Page (`thank-you.html`):**
  - **Confirmation Section:**
    - Thank you message and summary of submitted information
    - Data table for displaying user-submitted information
    - Gradient background matching the accommodation page

#### Footer
- **Elements:**
  - Social media links (Facebook, Instagram, Twitter, YouTube)
  - Address and contact information
- **Styles:**
  - Background color: `#FFFFFF`
  - Centered icons with consistent padding

### Navigation Design
- **Desktop:**
  - Horizontal navigation bar
  - Links to Home, Accommodation, Sign-Up pages
  - Active page highlighted with a bottom border
- **Mobile:**
  - Collapsible menu with a toggle button
  - Vertical menu dropdown

### Forms and Interactions
- **Sign-Up Form:**
  - Fields for owner name, email, phone number, dog breed, dog age, pedigree certificate, suite preference, additional packages, and additional information
  - Submission button that saves data to session storage and redirects to the thank-you page
- **Thank-You Page:**
  - JavaScript to retrieve and display submitted data from session storage in a table format

### Media and Responsive Design
- **Responsive Layout:**
  - Use of media queries to adjust layout for tablets, laptops, and desktops
  - Flexible grid system for images and text sections
- **Images:**
  - High-quality images for hero sections, accommodation descriptions, and circular decorative images

### Typography
- **Fonts:**
  - Primary font: `Roboto` for all text
  - Font weights and sizes adjusted for headings, subheadings, and body text
- **Styles:**
  - Consistent use of colors and font sizes for readability and visual hierarchy
  - Text alignment centered for headings and main sections

This layout ensures a cohesive and visually appealing structure across all pages of the Canine Comforts Hotel website, providing a seamless user experience.

## The Surface Plane

### Features Present Across the Project

#### Navigation Bar
- **Description:**
  - The navigation bar is present on every page, fully responsive across all resolutions.
  - It toggles to a hamburger menu on mobile devices for better accessibility.
  - Allows users to navigate across the site freely.
- **Desktop View:**
  - ![Desktop Navbar](/docs/testing/navbar2.png)
- **Mobile View:**
  - ![Mobile Navbar](/docs/testing/navbar1.png)

#### Footer
- **Description:**
  - The footer is present on every page, providing an additional navigation option from the bottom.
  - Contains social media links that open in a new tab.
- **Footer View:**
  - ![Footer](/docs/testing/footer.png)

#### Hero Images
- **Description:**
  - Included to draw the user's attention and immediately convey the website's purpose.
- **Desktop View:**
  - ![Hero Image Desktop](/docs/testing/hero.png)
- **Mobile View:**
  - ![Hero Image Mobile](/docs/testing/heromobile.png)

##### Introduction Section
- **Description:**
  - Shows the purpose of the business right away, allowing users to determine if the website is useful within the first few minutes.
- **Introduction Section View:**
  - ![Home Page - Introduction](/docs/testing/introduction.png)

##### Reason Section
- **Description:**
  - Highlights key benefits such as Expert Care, Socialization, and Comfortable Accommodations.
  - Includes icons and text descriptions to engage the user.
- **Reason Section View:**
  - ![Home Page - Reason Section](/docs/testing/reasons.png)

##### Testimonials Section
- **Description:**
  - Displays testimonials from satisfied clients, providing social proof of the quality of services.
- **Testimonials Section View:**
  - ![Home Page - Testimonials](/docs/testing/testimonials.png)

#### Accommodation Page

##### Accommodation Types
- **Description:**
  - Provides detailed information and images of different accommodation options (Exclusive Suites, Anti-Stress Suites, Royal Suites).
- **Accommodation Types View:**
  - ![Accommodation Page - Types](/docs/testing/accommodation.png)

##### Sign-Up Form
- **Description:**
  - Allows users to register their dogs and book accommodations.
  - Includes input fields for owner and dog information, suite preferences, and additional options.
- **Sign-Up Form View:**
  - ![Sign-Up Page - Form](/docs/testing/signup.png)

##### Confirmation Section
- **Description:**
  - Displays a thank you message and a summary of the submitted information.
  - Uses JavaScript to retrieve and display the submitted data in a table format.
- **Confirmation Section View:**
  - ![Thank-You Page - Confirmation](/docs/testing/thankyou.png)

### Visual and Interaction Design
- **Color Scheme:**
  - Main text color: `#292828`
  - Background colors: `#FFFFFF` for the header and footer, `#87603C` to `#C59C3D` gradient for sections
  - Accent colors: `#7D481A` and `#544F4F` for tables and highlights
- **Typography:**
  - Primary font: `Roboto`, used consistently across the site for a clean and modern look.
  - Font weights and sizes are adjusted for headings, subheadings, and body text to create a clear visual hierarchy.
- **Imagery:**
  - High-quality images are used in hero sections, accommodation descriptions, and decorative elements to enhance visual appeal.
- **Responsiveness:**
  - The design is fully responsive, with media queries to adjust layout and styles for tablets, laptops, and desktops.
  - Flexible grid system ensures content is well-organized and accessible on all devices.

This Surface Plane section ensures that the visual and interactive elements of the Canine Comforts Hotel website are cohesive, engaging, and accessible across various devices and screen sizes.
