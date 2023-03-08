# authentication-lab

University of Alberta, CMPUT 404 Lab 9 starter repository. Use the different
HTTP authentication schemes provided in Django Rest Framework.

## Getting Started

1. Clone this repository.
    * `git clone https://github.com/uofa-cmput404/authentication-lab.git`
2. Change directory into this repository.
    * `cd authentication-lab`
3. Initialize a Python3 virtual environment
    * `virtualenv venv --python=python3`
4. Activate the virtual environment and install the application dependencies
    ```bash
    source venv/bin/activate
    pip install -r requirements.txt
    ```
5. Run the migrations and create a superuser.
    ```bash
    ./manage.py migrate
    ./manage.py createsuperuser
    ```
6. Start the Django application.
    `./manage.py runserver`

# References
* Lab 9: https://uofa-cmput404.github.io/lab-9-authentication.html
* Lab 9 video: https://drive.google.com/drive/folders/1IIHNpGMBtx-xQ1-sAhVDDrlsWUBXyrAE
* https://www.django-rest-framework.org/
* https://developer.mozilla.org/en-US/docs/Web/HTTP/Authentication#basic_authentication_scheme
* https://www.django-rest-framework.org/api-guide/authentication/#tokenauthentication
