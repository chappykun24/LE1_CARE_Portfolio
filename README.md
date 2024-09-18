Design Choices
Color Scheme: A cool color palette was chosen to provide a calming and professional feel. The primary 
colors are shades of blue and gray, balancing contrast and readability.

Typography: The website uses a simple sans-serif font to maintain a clean and modern appearance,
 ensuring that the text is easy to read across all devices.

Responsive Layout: Flexbox and media queries were implemented to ensure the website is fully responsive.
 This allows content to adjust and display appropriately on different screen sizes, including mobile devices.

Navigation: A fixed header with navigation links was added for easy access to different sections. The use 
of icons from FontAwesome enhances the visual aspect of the navigation without cluttering the design.

Challenges Faced

Responsive Design: One challenge was ensuring the website looked good on both large and small screens. 
For example, positioning the name on the left side for full-width screens and centering it on smaller
 screens required precise use of CSS media queries and Flexbox. This was resolved by testing across various
  devices and screen sizes, then fine-tuning the CSS.

Image Sizing and Placement: Maintaining the aspect ratio of images while making sure they fit within their
containers was another issue. CSS properties like max-width and height: auto were used to ensure images 
scaled correctly across different devices.

Overlay on Hero Section: Adding a semi-transparent overlay on the hero image while keeping the text legible
was tricky. This was addressed using an absolute position for the overlay, ensuring it covered the entire 
section and applying a darker background color with 50% opacity for the desired effect.
