# proshop-ecommerce-production

ProShop is a comprehensive and feature-rich e-commerce web application built using Django, React, JavaScript, Bootstrap, PostgreSQL, Redux, and other technologies. It provides users with a seamless online shopping experience, incorporating essential e-commerce functionalities such as product browsing, searching, purchasing, user authentication, and secure payment processing. The application leverages various tools and platforms like Amazon Web Services (AWS), Heroku, Git, HTML/CSS, and more to deliver a robust and scalable solution.


**Technologies Used**

The ProShop e-commerce web application utilizes the following technologies:

**Django**: A powerful Python web framework that enables rapid development and clean design.

**React**: A JavaScript library for building dynamic and interactive user interfaces using reusable components.

**JavaScript**: A versatile scripting language used to enhance interactivity and functionality on web pages.

**Bootstrap**: A popular front-end framework for creating responsive and visually appealing websites.

**PostgreSQL**: A robust and open-source relational database management system used to store and retrieve data efficiently.

**Redux**: A predictable state container for JavaScript apps, providing a centralized and scalable state management solution.

**Amazon Web Services (AWS)**: A comprehensive cloud services platform utilized for hosting and managing the application.

**Railway**: A cloud-based platform that simplifies application deployment and scaling.

**Git**: A distributed version control system used for tracking changes and collaborating on the source code.

**HTML/CSS**: Fundamental web technologies used for structuring and styling web pages.


**Installation and Setup**

To run the ProShop e-commerce web application locally, follow these steps:

Clone the repository:
git clone https://github.com/Douglous-Sobei/proshop-ecommerce-production.git


Install the required dependencies. Make sure you have Python installed on your system. Use the package managers pip and npm to install the dependencies.

pip install -r requirements.txt

npm install


Configure the environment variables. Create a .env file in the project root directory and set the following variables:

SECRET_KEY=your_secret_key

DEBUG=True

DATABASE_URL=your_database_url

STRIPE_API_KEY=your_stripe_api_key


Apply the database migrations:

python manage.py migrate
Start the development server:
python manage.py runserver
Open your browser and navigate to http://localhost:8000 to access the ProShop web application.


Installed Apps

The following Django apps have been installed in ProShop:

django.contrib.admin: Enables the Django admin interface for managing the application's models and data.

django.contrib.auth: Provides user authentication functionality.

django.contrib.contenttypes: A framework for content types, allowing models to associate extra data with any object.

django.contrib.sessions: Manages sessions for authenticated users.

django.contrib.messages: Handles user-facing messages.

django.contrib.staticfiles: Manages static files (CSS, JavaScript, images) for the application.

rest_framework: A powerful and flexible toolkit for building Web APIs.

corsheaders: Adds Cross-Origin Resource Sharing (CORS) headers to Django responses, allowing the application to interact with APIs on different domains.

storages: Provides a collection of custom storage backends for Django, facilitating the handling of media and static files.

base.apps.BaseConfig: The main Django app for the ProShop web application.


Deployment

The ProShop e-commerce web application can be deployed using platforms like Railway and Amazon Web Services (AWS). Follow the respective documentation for detailed instructions on deploying Django and React applications.  

See the deployed link here: [https://proshop-project-production.up.railway.app/](https://proshop-project-production.up.railway.app/)

For more information, follow https://devcenter.heroku.com/articles/github-integration to view the deployment process


License


Contributing

Contributions to this project are welcome. To contribute, please follow the guidelines outlined in ....

Contact

If you have any questions or feedback, feel free to reach out to me at douglousmangoyi@gmail.com. I would be happy to assist you.
Thank you for using the ProShop e-commerce web application!
