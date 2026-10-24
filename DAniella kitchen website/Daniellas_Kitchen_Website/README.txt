DANIELLA'S KITCHEN WEBSITE — CODE GUIDE

PROJECT OVERVIEW
This is a simple six-page restaurant website made with HTML and CSS only. JavaScript has been removed. The pages share one stylesheet so the design stays consistent throughout the website.

FILES AND WHAT THEY DO
- index.html — Home page. Introduces the restaurant, highlights food and links visitors to other pages.
- about.html — About page. Explains the restaurant’s story, values and approach to food.
- menu.html — Menu page. Displays sample dishes, descriptions, pictures and sample prices.
- services.html — Services page. Describes dine-in, takeaway and catering options.
- order.html — Order page. Shows a sample order request form and guidance for placing an order.
- contact.html — Contact page. Displays sample contact details and a message form.
- style.css — Controls the website’s appearance: colours, fonts, spacing, page layout, food cards, navigation, buttons, forms, footer and responsive layout for smaller screens.
- README.txt — This guide to the project.

HOW THE CODE WORKS
HTML (the .html files) provides the structure and content of each page. Links such as href="menu.html" connect the pages together. The shared stylesheet is loaded with <link rel="stylesheet" href="style.css"> in each page’s head section. CSS classes such as .site-header, .hero, .section, .food-card and .footer apply the same visual styles wherever they are used. Image elements display food and restaurant photos from external image URLs.

JAVASCRIPT REMOVAL
The script.js file and all script references have been removed. The mobile menu button was also removed because it required JavaScript to open and close the navigation. On small screens, the navigation links now remain visible and can wrap onto multiple lines. The copyright year is written as 2026 rather than being filled in automatically.

IMPORTANT LIMITATIONS
- Navigation links between the six pages work using ordinary HTML links.
- The order and contact forms are visual front-end examples only. Without JavaScript or a server-side service, they do not send an order, save information, or email the restaurant.
- The telephone number, email address, menu items and prices are sample details. Replace them with accurate information before publishing.
- Food photos are loaded from Unsplash using internet image URLs, so an internet connection is needed to load them.

HOW TO OPEN THE WEBSITE
1. Extract the ZIP file to a folder on your computer.
2. Open Visual Studio Code.
3. Select File > Open Folder and choose the extracted Daniellas_Kitchen_Website folder.
4. Open index.html.
5. To preview it, open index.html in a browser, or use the Live Server extension in VS Code if installed.
6. Click the navigation links to visit Home, About, Menu, Services, Order and Contact Us.

EDITING THE WEBSITE
- To change words, headings, contact details or prices, open the relevant HTML page and edit its text.
- To change colours, font sizes, spacing or layouts, edit style.css.
- To change a food picture, replace the URL in the relevant <img src="..."> element and update its alt text to describe the picture.
- Keep the HTML files and style.css together in the same folder so the styling continues to load.
