# Currency Converter

A simple and responsive currency converter application built with React. This project allows users to convert amounts between various currencies using real-time exchange rates fetched from a public API.

## Features

-   **Real-time Exchange Rates**: Fetches the latest currency exchange rates from the [Currency API](https://github.com/fawazahmed0/currency-api).
-   **Currency Swapping**: Easily swap the 'from' and 'to' currencies with a single click.
-   **Responsive Design**: A clean user interface that works on different screen sizes, styled with Tailwind CSS.
-   **Custom Hooks**: Utilizes a custom React hook (`useCurrencyInfo`) to encapsulate the logic for fetching and managing currency data.

## Technologies Used

-   **React**: For building the user interface.
-   **Vite**: As the build tool and development server.
-   **Tailwind CSS**: For utility-first styling.
-   **Currency API**: For providing the exchange rate data.

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

-   Node.js (v18 or later)
-   npm or your favorite package manager

### Installation

1.  Clone the repository:
    ```sh
    git clone <repository-url>
    ```
2.  Navigate to the project directory:
    ```sh
    cd CurrencyConverter
    ```
3.  Install the dependencies:
    ```sh
    npm install
    ```

### Running the Application

To start the development server, run the following command:

```sh
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) (or the port shown in your terminal) to view it in the browser.

## Project Structure

-   `src/components/InputBox.jsx`: A reusable input component for amount and currency selection.
-   `src/hooks/useCurrencyInfo.js`: A custom hook that fetches currency conversion data from the API based on the selected currency.
-   `src/App.jsx`: The main application component that holds the state and logic for the converter.