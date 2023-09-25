# Phone_Hunting_API
# Hosted Link:-https://tulasidurga1.github.io/Phone_Hunting_API/
# explantion:-
### Document Structure and Metadata:

- The <!DOCTYPE html> declaration defines this document as an HTML5 document.
- The <html> element contains the entire document.
- The <head> section includes metadata and external resources.
- Metadata includes character encoding (<meta charset="UTF-8">) and viewport settings (<meta name="viewport" content="width=device-width, initial-scale=1.0">).
- The page has a title (<title>Phone Hunting API</title>).
- It has a favicon, a small icon displayed in the browser tab, specified with a <link> element.
### CSS and Styling:

- Various styles are applied to the page using CSS.
- External CSS is imported from a CDN (Content Delivery Network) for styling (DaisyUI and Tailwind CSS).
- Font styles are defined for the body text using Google Fonts (<link> and <style>).
- Custom styles are defined within a <style> block for elements with the class .body.
### Page Layout:

- The <body> element contains the main content of the page.
- There is a navigation bar at the top (<nav>), which includes a logo ("Hot Gadgets") and a "Sign Up" button.
- A header section follows the navigation bar, which displays information about the Apple iPhone 13 Pro Max and a "Buy Now" button.
- There are images of phones displayed in a grid within a <section>.
- A search input field and a "Search" button are provided for searching for phones.
### JavaScript:

- JavaScript functionality is included at the end of the document in the <script> tag, linking to an index.js file.
- It defines functions like searchHandler, loading, loadPhone, displayPhones, showBtn, and showDetailsHandler for dynamic behavior.
- These functions are used to handle user interactions, load phone data from an API, and display phone details in a modal.
### Phone Data Display:

- Phone data is fetched from an API (https://openapi.programming-hero.com/api/phones) and displayed in the section with the id="phone-container".
- Each phone is displayed as a card with an image, phone name, and a "Show Details" button.
- A loading spinner is displayed while data is being fetched.
- There's a "Show All" button (<button id="showALLBtn">Show All</button>) that presumably shows all the phones when clicked.
### Modals:

- The page uses a modal (<dialog id="my_modal">) to display detailed phone information when the "Show Details" button is clicked.
- The modal contains various elements for displaying details such as the phone's image, name, brand, specifications, and release date.
### Footer:

- The footer contains links to various sections and pages related to the website, such as "Product," "Browse jobs," "Company," etc.
- It also includes social media icons as links.
### External Resources:

- The page references external resources, including images and CSS libraries, using <link> and <script> tags.
- It fetches data from an external API for displaying phone information.
- The JavaScript code appears to be responsible for handling user interactions, fetching data from the API, and dynamically updating the page content. The page seems to be a front-end interface for browsing and searching for phone gadgets.
