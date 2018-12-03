# We Are Unique


An [Eleventy](https://www.11ty.io/) implementation of Jen Simmons's generic
website.

- [Jen Simmons's Site](https://labs.jensimmons.com/)
- [CodePen](https://codepen.io/jensimmons/pen/zKgevR)
- [Dave Ellis's original article](http://www.novolume.co.uk/blog/all-websites-look-the-same/)

## Using this

1. Clone this repo
2. Install Eleventy 

    ```
    $ npm install eleventy
    ```
3. Run Eleventy

    ```
    $ npx eleventy --serve
    Writing _site/index.html from ./index.html.
    Copied 1 item and Processed 1 file in 0.13 seconds
    Watching…
    [Browsersync] Access URLs:
     ----------------------------------
           Local: http://localhost:8080
        External: http://10.0.1.6:8080
     ----------------------------------
              UI: http://localhost:3001
     UI External: http://localhost:3001
     ----------------------------------
    [Browsersync] Serving files from: _site
    ```

## Notes

This implementation:

- doesn't do the SCSS-to-CSS translation
- relies on the `.eleventy.js` file
  to copy the `css` directory to `_site`
