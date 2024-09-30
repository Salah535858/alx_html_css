# HeadPhons Website

This project is a simple landing page for a hypothetical brand called "HeadPhons," featuring information on the company's services, contact details, and a call-to-action. It is styled using a combination of custom CSS and the Font Awesome icon library.

## Project Structure

The project consists of the following files:

- `index.html`: The main HTML file containing the structure and content of the webpage.
- `0-styles.css`: The main CSS file that styles the HTML page.

### HTML Structure

The `index.html` file is divided into four main sections:

1. **Header & Navigation (Section 1)**:
    - Contains a navigation bar with links to "Contact Us", "Our Results", and "What We Do."
    - Features a large hero image background with a headline and call-to-action button.

2. **What We Do (Section 2)**:
    - Includes a heading and description of the company's services.
    - Displays icons with short descriptions representing different aspects of the company's services.

3. **Our Results (Section 3)**:
    - Shows statistical results of the company's success with visual representation using pentagon-shaped elements.
    - A background image is used in this section to enhance the visual appeal.

4. **Contact Form (Section 4)**:
    - Features a form where users can input their name, email, and message.
    - A submit button encourages users to take action.

5. **Footer**:
    - Displays the company logo and social media icons (Facebook, Instagram, Twitter) using Font Awesome.

### CSS Styling

The `0-styles.css` file provides the visual design for the project. Some key aspects of the CSS include:

- **Responsive Design**:
    - Media queries are used to adjust the layout for screens smaller than 600px, ensuring the webpage is mobile-friendly.
    
- **Button Styling**:
    - Buttons are styled with rounded corners, shadows, and a hover effect to enhance user interaction.

- **Icon Usage**:
    - Font Awesome is used to display social media icons in the footer.
    - Custom icons are also included in the "What We Do" and "Our Results" sections.

- **Flexbox Layout**:
    - Flexbox is used to arrange elements in sections like the icons under "What We Do" and the pentagon shapes under "Our Results" to ensure a responsive and dynamic layout.

### Dependencies

- **Font Awesome**:
    - The project uses the Font Awesome icon library to display social media icons in the footer.

To include Font Awesome, the following link is used:
```html
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
