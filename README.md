# Restaurant Reviews App

## Description

For the Restaurant Reviews projects, you will incrementally convert a static webpage to a mobile-ready web application. In Stage One, you will take a static design that lacks accessibility and convert the design to be responsive on different sized displays and accessible for screen reader use. You will also begin converting this to a Progressive Web Application by caching some assets for offline use.

## Instructions
1. Clone or download [this repository](https://github.com/onlurking/fend-restaurant-review).
2. Run a webserver using python 3 with the following command:
    ```
    python -m http.server 8000
    python2 -m SimpleHTTPServer 8000 // for python2
    ```
3. [Access localhost:8000](http://localhost:8000) in your browser.

## Roadmap

- [x] Make the site accessible. 
- [x] Cache the static site for offline use. Using Cache API and a ServiceWorker, cache the data for the website so that any page (including images) that has been visited is accessible offline.
