# Veeva Vault Help

* Example article/release posts, pages and feedback form
* Responsive CSS Grid layout with fallbacks for older browsers
* Continuous Deployment workflow via Netlify and Github
* Netlify CMS for managing content
* Netlify Identity for authenticating users
* Netlify Forms for processing your static HTML forms with reCAPTCHA
* Optional Netlify `_redirects` and `_headers` files ready to use
* Jekyll SASS pipeline
* Minified HTML and CSS

Go to `/admin` on the site, choose your OAuth provider from the
login box and then login

## Local Development

Clone this repository and run:

```bash
bundle install
bundle exec jekyll server --watch
```

In case you don't want to install ruby-bundler you can use docker:

```bash
docker-compose up
```

Jekyll will watch your project folder for changes.
