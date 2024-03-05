# Article Management Web Application
This is a web application developed using Django framework for managing articles, serving both creators and readers. The application allows users to create, read, update, and delete articles. It implements multi-user authentication and logout for personalized experiences. Additionally, users can engage with articles through comments, fostering community interaction.

## Technologies Used
Django

django-allauth

Bootstrap

## Installation
Clone the repository:

git clone <repository_url>

Navigate into the project directory:

cd article-management-web-app

Create a virtual environment:

python -m venv env

Activate the virtual environment:

On Windows:

.\env\Scripts\activate

On macOS and Linux:

source env/bin/activate

Install the dependencies:

pip install -r requirements.txt

Apply database migrations:

python manage.py migrate

Create a superuser (admin):

python manage.py createsuperuser

Start the development server:

python manage.py runserver

Access the application at http://localhost:8000 in your web browser.

Usage
User Authentication: Users can sign up, log in, and log out using the provided authentication system.
Article Management: Authenticated users can create, read, update, and delete articles.
Comments: Users can engage with articles by leaving comments.
Admin Interface: Superusers can access the admin interface at http://localhost:8000/admin to manage articles and users.
Contributing
Contributions are welcome! Please feel free to open a pull request for any feature enhancements or bug fixes.

License
This project is licensed under the MIT License.

Acknowledgements
Django
django-allauth
Bootstrap
Contact
For any inquiries or support, please contact [your_email@example.com].
