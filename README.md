# My College Finance - Investment Growth Calculator (V2)

[![GitHub Pages Deploy](https://img.shields.io/github/deployments/My-College-Finance/investment-growth-calculator/github-pages?label=Live%20Calculator&style=flat-square&logo=github)](https://my-college-finance.github.io/investment-growth-calculator/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](https://opensource.org/licenses/MIT) 

An interactive web tool by **[My College Finance](https://mycollegefinance.com/)** designed to help users visualize and project the potential growth of their investments over both short-term (1-5 years) and long-term (5+ years) horizons.

---

## Live Demo & Access

Calculate your potential investment growth online:

🚀 **[Launch Investment Growth Calculator](https://my-college-finance.github.io/investment-growth-calculator/)** 🚀

---

## Features

*   **Separate Calculators:** Dedicated inputs for short-term (1-5 years) and long-term (5+ years) scenarios.
*   **Growth Calculation:** Computes projected total amount, total contributions, and interest earned based on initial investment, monthly contributions, estimated annual rate, and time period.
*   **Interactive Visualizations:** Dynamically generated line charts (using Chart.js) display the growth trajectory for both short-term and long-term projections.
*   **Notes Section:** A dedicated area to add, save, and delete personal investment notes, strategies, or insights. Notes are saved locally using the browser's `localStorage`.
*   **Informative Tooltips:** Help icons provide context for each input field.
*   **Theme Toggle:** Switch between Light and Dark modes for user comfort.
*   **PDF Export:** Download a print-friendly summary of the calculator inputs, results, and notes using the browser's native print-to-PDF functionality. Charts are excluded from the print view for clarity.
*   **Responsive Design:** Adapts for optimal use on desktops, tablets, and mobile devices.

## How to Use

1.  **Online:** Access the calculator via the [**Launch Link**](https://my-college-finance.github.io/investment-growth-calculator/) above. Notes will be saved in *that browser's* localStorage.
2.  **Locally:** Download `index.html` and open it in your browser. Notes will be saved locally.
3.  **Embedding:** Use the following iframe code (replace the `src` if your URL differs):

     ```html
    <iframe
        src="https://my-college-finance.github.io/investment-growth-calculator/"
        width="100%"
        height="900" /* Adjust height as needed */
        style="border: 1px solid #ccc;"
        title="Investment Growth Calculator"
        allowfullscreen>
    </iframe>
    ```

## Technology Stack

*   HTML5
*   CSS3 (Flexbox, Grid, CSS Variables)
*   Vanilla JavaScript (ES6+)
*   Chart.js
*   Browser `localStorage` API (for Notes)
*   Browser `sessionStorage` API (for temporary chart redraw parameters)

## Source File

The application is contained within the single `index.html` file.

## Contributing

Feedback and contributions are welcome!

*   Open an [**Issue**](https://github.com/My-College-Finance/investment-growth-calculator/issues) for bugs or feature ideas.
*   Submit a [**Pull Request**](https://github.com/My-College-Finance/investment-growth-calculator/pulls) with code improvements.

## License

Licensed under the MIT License. 

---

Provided by **[My College Finance](https://mycollegefinance.com/)**
