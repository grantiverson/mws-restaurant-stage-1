# Restaurant Reviews

I modified this website as a project for my Front-End Web Development Nanodegree from Udacity. It is a simulation of a website where users can read reviews of several restaurants in New York.

## Run live

Run it live at [restaurant-reviews.iverson.io](http://restaurant-reviews.iverson.io)

## Download

These instructions will allow you to get a copy of the project that runs on your local machine.

### Prerequisites

* [Git](https://git-scm.com/downloads)
* Browser
* Python

### Installing

Instructions to clone and run the project:
1. Clone the git project using `$ git clone https://github.com/grantiverson/restaurant-reviews.git`.
2. Navigate to the root directory for the project.
3. In this folder, start up a simple HTTP server to serve up the site files on your local computer. Python has some simple tools to do this, and you don't even need to know Python. For most people, it's already installed on your computer.

In a terminal, check the version of Python you have: `python -V`. If you have Python 2.x, spin up the server with `python -m SimpleHTTPServer 8000` (or some other port, if port 8000 is already in use.) For Python 3.x, you can use `python3 -m http.server 8000`. If you don't have Python installed, navigate to Python's [website](https://www.python.org/) to download and install the software.

4. With your server running, visit the site: `http://localhost:8000`.

## Built with

* [Atom](https://atom.io) - Text Editor
* [JavaScript ES6](https://developer.mozilla.org/en-US/docs/Web/JavaScript) - Programming Language
* [Google Chrome](https://www.google.com/chrome/) - Browser and Debugging Tool

### How I made this app

I forked the project from [Udacity's Mobile Web Specialist Certification Course](https://github.com/udacity/mws-restaurant-stage-1). Once I had my own copy, I modified the CSS so that the app would be responsive to any screen size. I updated the JavaScript that populates the website to ensure that the site will be accessible to all users. Finally I added a service worker and configured it to cache a copy of the site on the client device for offline use.

## Author

* **Grant Iverson** - [GitHub](https://github.com/grantiverson)

### Acknowledgements

Legacy code was provided as part of [Udacity's Front-End Web Development Nanodegree](https://www.udacity.com/course/front-end-web-developer-nanodegree--nd001?gclid=CjwKCAjwq_vWBRACEiwAEReprL6RuGAkBbe7XRljOzu9GYr_zQ70LKtonUz_Qev-z0rf07jmNrZNMRoCF9sQAvD_BwE).
