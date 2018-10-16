# XJTU Journal Search

A tool for search journals in XJTU's list.
Have a try: [here](https://hehuan2112.github.io/XJTU-Journal-Search/)

## How to use

It's a simple html file contains almost everything, except 3 libs.
Just place all file under a folder which is served by HTTP server (e.g Apache, Nginx, etc).
Or use the following Python command in the folder of `index.html` to start a server:

    $ python -m SimpleHTTPServer

or Python3:

    $ python3 -m http.server

then you can access this little web site on `localhost:8000`

## How it works

1. parse xlsx files into json data by `openpyxl` (https://openpyxl.readthedocs.io/)
2. load data and other things into page by `jquery` (https://jquery.com/)
3. indexes the data in page by `lunr.js` (https://lunrjs.com/)
4. render page by `vue.js` (https://vuejs.org/)
5. use

![image of search ui](https://github.com/hehuan2112/XJTU-Journal-Search/blob/master/static/img/cover.png?raw=true)
