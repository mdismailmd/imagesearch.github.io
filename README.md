# imagesearch.github.io
🖼️ LensFinder: Image Search Engine
A sleek, responsive web application that allows users to search through millions of high-quality photos using the Fetch API. This project focuses on handling asynchronous requests, dynamic DOM manipulation, and modern CSS layouts.




🚀 Key Features
Real-time Search: Instantly fetch images based on user keywords.

Asynchronous Fetching: Utilizes the async/await syntax for seamless data retrieval without page reloads.

Infinite Scrolling / "Show More": Dynamic pagination to load more results on demand.

Lightbox Effect: Click on any image to view it in a higher resolution (if implemented).

Responsive Grid: Powered by CSS Grid and Flexbox for a flawless look on mobile and desktop.

🛠️ Technical Breakdown
The Stack
HTML5: Semantic structure for the search interface.

CSS3: Custom styling featuring a "Glassmorphism" search bar and responsive image cards.

JavaScript (ES6+): The engine of the app, handling the API logic.

The API Logic
The app communicates with the Unsplash API (or your chosen provider) using the following flow:

User Input: Captures the string from the search bar.

Request: Sends a GET request to the API endpoint with the query and API Key.

JSON Conversion: Parses the response into a readable JavaScript object.

DOM Injection: Maps through the results to create and append image elements to the gallery.

⚙️ Setup & Installation
To run this project on your local machine:






Open index.html in your browser.

📂 Project Structure
Plaintext
image-search-app/
├── index.html         # Document structure & Search bar
├── style.css          # Grid layouts and hover effects
├── script.js          # Fetch API logic & Event listeners
└── assets/images            # Project icons and screenshots
📝 Lessons Learned

