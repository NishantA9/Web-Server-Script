## Flask Contact Form Application

This is a simple Flask web application that allows users to submit a contact form. The submitted data is saved to both a text file and a CSV file.

# Install the required Python packages using pip:

        pip install Flask

# File Descriptions
        server.py: The main Flask application script. It includes routes for displaying HTML pages and handling form submissions.
        templates/: Contains HTML templates for rendering different pages.
        static/: Contains static files such as CSS and JavaScript.
        venv/: Virtual environment for the project.

# Routes

        /: Renders the index.html page.
        /<string:page_name>: Renders a page based on the provided page_name.
        /submit_form: Handles POST requests from the contact form and saves data to database.txt and database.csv.
        /thankyou.html: Displays a thank-you page after form submission.

# Running the Application
To start the Flask development server, run the following command: Visit http://127.0.0.1:5000/ in your web browser to see the application in action.

       python server.py


##  Made by Nishant Acharekar, under Course of Complete Python Developer 2024 by ZTM on Udemy
