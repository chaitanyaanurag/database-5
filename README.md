# database-5
# Hello World Django App

This is a simple Django app that provides a Hello World message in JSON format.

## Getting Started

### Prerequisites

Make sure you have Python and pip installed on your machine.

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/helloworld-django-app.git
	```
2. Navigate to the project directory:
	```bash
	cd helloworld-django-app
```
3. Install the required dependencies:
	```bash
	pip install -r requirements.txt
	```
### Running the App
1. Apply migrations:
	```bash
	python manage.py migrate
	```
2. Start the development server:

```bash
python manage.py runserver
```
3. Visit http://127.0.0.1:8000/ in your web browser to see the welcome message.

4. To access the Hello World JSON response, visit http://127.0.0.1:8000/hello/.

##License
This project is licensed under the MIT License - see the LICENSE file for details.


