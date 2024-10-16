# Currency Converter Web App

This is a simple currency converter web application built using HTML, CSS, and JavaScript. It allows users to convert currencies from one to another by fetching real-time exchange rates using an API.

## Features

- **Responsive Design:** The layout adapts well to different screen sizes.
- **Currency Dropdown:** Users can select the source and target currencies from the dropdowns.
- **Real-time Exchange Rates:** The app fetches the latest exchange rates and displays the result instantly.
- **Flag Display:** Displays the corresponding flags for the selected currencies.
  
## Demo

Upon opening the web app, users can enter the amount they wish to convert, choose the source and target currencies, and click the "Get Exchange Rate" button to view the converted amount.

## Files and Structure

- **index.html:** Contains the structure and layout of the web app.
- **style.css:** Styles the web app and provides a clean and simple user interface.
- **codes.js:** Contains the list of country codes and flags used to dynamically update the flag display based on the selected currency.
- **app.js:** Handles the main logic, including fetching exchange rates from the API and updating the DOM accordingly.

## How to Run the App

1. Clone the repository or download the files.
2. Open the `index.html` file in a browser.
3. The app will load, and you can start converting currencies.

## External Libraries and APIs

- **Font Awesome:** Used for the exchange arrow icon.
  - CDN: `https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css`
- **Currency API:** Real-time exchange rates are fetched from the following URL:
  - `https://cdn.jsdelivr.net/npm/@fawazahmed0/currency-api@latest/v1/currencies`
  
## How It Works

1. When the page loads, the app initializes with a default currency pair (USD to INR).
2. The user can enter the amount they want to convert and select the currencies.
3. Clicking the "Get Exchange Rate" button triggers an API call to fetch the latest exchange rate.
4. The app calculates and displays the converted amount along with the exchange rate.

## Screenshots

![Currency Converter Screenshot](screenshot.png)

## Technologies Used

- **HTML5**
- **CSS3**
- **JavaScript (ES6)**

## Future Improvements

- Add error handling for invalid input or network failures.
- Display exchange rate trends or historical data.
- Allow users to switch themes (dark mode/light mode).
