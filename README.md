# CS50W Project 0 – Google Search Front-End Clone

This project is a custom front-end for Google Search, created as part of the CS50 Web Programming course. It demonstrates HTML form handling, GET parameters, and basic CSS styling to mimic Google’s interface.

## Features

1. **Google Search Page**
   - Centered search bar with rounded corners.
   - “Google Search” button performs a standard search.
   - “I’m Feeling Lucky” button opens the first search result directly.

2. **Image Search Page**
   - Search for images using Google Images.
   - Hidden GET parameter `tbm=isch` ensures image search results.

3. **Advanced Search Page**
   - Four input fields:
     - All these words (`as_q`)
     - This exact word or phrase (`as_epq`)
     - Any of these words (`as_oq`)
     - None of these words (`as_eq`)
   - Blue “Advanced Search” button with white text.
   - Properly aligned and stacked input fields.

4. **Navigation Links**
   - Top-right links to switch between Google Search, Image Search, and Advanced Search pages.

5. **Styling**
   - Search bar and buttons styled to resemble Google’s UI.
   - Centered layout, rounded input fields, button hover effects.

## Technologies Used

- **HTML5**
- **CSS3**
- Forms using **GET method** to interact with Google’s search engine.

## Usage

1. Clone this repository:
   ```bash
   git clone https://github.com/Shikha18Shukla/CS50W_Project0_Search.git
