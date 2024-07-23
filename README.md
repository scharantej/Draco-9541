## Flask Application Design for Performance Dashboard

### HTML Files

- **dashboard.html**: This file will serve as the primary template for the performance dashboard. It will contain the necessary HTML structure and elements to display the data visualizations and allow user interaction.
- **header.html**: This file will be included in all the web pages and will contain the shared HTML code for the header section, including navigation and any necessary page-independent elements.
- **footer.html**: Similar to `header.html`, this file will be included in all the web pages and will contain the shared HTML code for the footer section.

### Routes

- **`/dashboard`**: This route will serve the `dashboard.html` template and is the entry point for the performance dashboard.
- **`/sales_plays`**: This route will handle displaying data related to sales plays within the dashboard. It will generate necessary visualizations and present them in the dashboard view.
- **`/book_of_business`**: Similar to `/sales_plays`, this route will handle displaying data related to the Book of Business and provide relevant visualizations within the dashboard.
- **`/data`**: This route will be responsible for fetching the data needed to populate the dashboard. It can be an API endpoint that provides the data in JSON or any other suitable format.