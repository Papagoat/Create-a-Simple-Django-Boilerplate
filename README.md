# Create a Simple Django Boilerplate
[Follow the tutorial](http://terencelucasyap.com/create-simple-django-boilerplate-part-1/).

## Installation

1. Install [Python](https://www.python.org/downloads/).
2. Set up [venv](https://docs.python.org/3/library/venv.html)
3. Activate your virtual environment

```sh
$ python3 -m venv myvenv
$ source ./myvenv/bin/activate
```

4. Install [pip](https://pip.pypa.io/en/stable/installing/)

5. Install Django

```sh
$ pip install django
```

## Usage

Start the Django Server

```sh
$ python manage.py runserver
```
Visit http://localhost:8000/ from your browser.

To access the admin page, you would need to create an admin superuser first.

```sh
$ python manage.py createsuperuser
```

Visit http://localhost:8000/admin and log in to the the admin page using your credentials.


## License
**MIT License**

Copyright (c) [2019] [Terence Lucas Yap]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
