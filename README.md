## Template Credit  : https://github.com/yaoyao-liu/minimal-light

## Using Locally

Install [Ruby](https://www.ruby-lang.org/en/) and [Jekyll](https://jekyllrb.com/) first.

Install and run:
bundle install
bundle exec jekyll server

View the live page using `localhost`:
<http://localhost:4000>. 

You can get the html files in `_site` folder.

## Customizing

### Edit '_config.yml'
### Edit 'index.md'
### Edit 'Stylesheet'

If you'd like to add your own custom styles:

1. Create a file called `/assets/css/style.scss` in your site
2. Add the following content to the top of the file, exactly as shown:

    ```scss
    ---
    ---

    @import "{{ site.theme }}";
    ```
3. Add any custom CSS (or Sass, including imports) you'd like immediately after the `@import` line

### Edit '/_layouts/homepage.html'
