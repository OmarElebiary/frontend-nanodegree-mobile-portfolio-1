####Get started (Original README)

  1. Clone the repository
    1. To inspect the site on your phone, you can run a local server

  ```bash
  $> cd /path/to/your-project-folder
  $> python -m SimpleHTTPServer 8080
  ```

  1. Open a browser and visit localhost:8080
  1. Download and install [ngrok](https://ngrok.com/) to make your local server accessible remotely.

  ``` bash
  $> cd /path/to/your-project-folder
  $> ngrok http 8080
  ```

####Part 1: Optimize PageSpeed Insights score for index.htmlI have done
  1. inlined CSS.
  2. minified CSS and HTML.
  3. Compressed images.

PageSpeed Insights : https://developers.google.com/speed/pagespeed/insights/?url=https%3A%2F%2Fomarelebiary.github.io%2F&tab=desktop

####Part 2: Optimize Frames per Second in pizza.html

  Replaced a slow method to access the DOM, document.querySelectorAll(), with a faster method,     document.getElementsByClassName().
  
  Added translate3d property 
