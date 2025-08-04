# Task-01-landing-page


# Genius Landing Page

Welcome to the Genius Landing Page  a clean, responsive, and modern landing page built with HTML5 and CSS3. This project demonstrates strong foundational skills in frontend development using Flexbox and responsive design principles.


##  Key Features

-  Responsive Navigation Header
-  Hero Section with Background Image and Overlay
-  Mobile-Optimized Layout using Media Queries
-  Call-to-Action Button
-  Sticky Footer with Social Media Links
-  Clean and accessible code structure



## Built With
 Technology                     

 HTML5 CSS3 Flexbox Media Queries       

 ##  Layout Overview

 Header
- Flexbox used to align logo and navigation links.
- Color scheme uses contrasting tones (`white`, `yellow`) for branding.

### Hero Section
- Full-screen height with background image.
- Overlay darkens image for improved text readability.
- Centered welcome message and CTA using Flexbox.

### Footer
- Fixed at bottom of viewport.
- Contains social media links with hover effects.

### Responsive Design

@media (max-width: 768px) {
  .nav-links { display: none; }
  .header {
    flex-direction: column;
    align-items: flex-start;
  }
}