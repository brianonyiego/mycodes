# Ticket Scraping Project

This project is a web application built with **Django**, **HTML**, and **CSS** to scrape and display ticket information from various sources. The goal is to gather ticket availability and pricing data from different platforms and present it in a user-friendly format.

# Features

- Scrapes ticket information such as availability, price, and seat details.
- Displays ticket data in a well-organized table format.
- Allows users to filter and sort tickets based on various parameters.
- Fully responsive design with custom styles using **CSS**.
- Backend powered by **Django**, ensuring secure and efficient data handling.
- Supports scraping from multiple ticketing platforms.

# Technologies Used

- **Django**: Backend framework for building the web application.
- **HTML**: For structuring the pages.
- **CSS**: For styling and layout design.
- **BeautifulSoup** (optional): Used for web scraping ticket details.
- **Requests**: For sending HTTP requests to fetch the data.
- **SQLite** (or other database): Default database for storing ticket information.

# Installation

 Clone the repository:
   ```bash
   git clone https://github.com/your-username/ticket-scraping-project.git  
```

# Navigate to the project directory:
```
cd ticket-scraping-project 
```


# Create a virtual environment and activate it:
```

python -m venv venv 
source venv/bin/activate  # On Windows: venv\Scripts\activate 
```

# Install dependencies:

```
pip install -r requirements.txt 
```


# Apply migrations:
```

python manage.py migrate 
```


# Run the development server:
```

python manage.py runserver 
```


# Open your browser and navigate to ``` http://127.0.0.1:8000/.```



# How to Use

1. On the homepage, you'll see a search bar and filters.
2. Use the filters to narrow down tickets based on price, date, or availability.
3. The scraped data is presented in a table format with relevant information.
4. Click on a ticket to view more details or to be redirected to the source for purchase.

# Customization

- To modify the scraping logic, edit the scraping script located in `scraper.py`.
- The styles are managed in `static/css/styles.css`. You can update or enhance the design as needed.
- The templates for the frontend can be found in the `templates` folder.


# License

This project is licensed under the MIT License - see the LICENSE file for details.


