# [Start Bootstrap - Clean Blog Jekyll](https://startbootstrap.com/themes/clean-blog-jekyll/) - Unofficial Jekyll Version

[Clean Blog Jekyll](https://startbootstrap.com/themes/clean-blog-jekyll/) is a stylish, responsive blog theme for [Bootstrap](https://getbootstrap.com/) created by [Start Bootstrap](https://startbootstrap.com/). This repository is an improved version of this theme. This theme features a blog homepage, about page, contact page, and an example post page along with a working contact form powered by [Formspree](https://formspree.io/).

This repository holds the unofficial Jekyll version of the Clean Blog theme on Start Bootstrap!

## Preview

**[View Live Preview](https://vishalscodes.github.io/startbootstrap-clean-blog-jekyll/)**

## Installation & Setup

### Using RubyGems

When installing the theme using RubyGems, demo images, posts, and pages are not included. Follow the instructions below for complete setup.

1. (Optional) Create a new Jekyll site: `jekyll new my-site`
2. Replace the current theme in your `Gemfile` with `gem "jekyll-theme-clean-blog"`.
3. Install the theme (run the command inside your site directory): `bundle install`
4. Replace the current theme in your `_config.yml` file with `theme: jekyll-theme-clean-blog`.
5. Build your site: `bundle exec jekyll serve`

Assuming there are no errors and the site is building properly, follow these steps next:

1. Create the following pages if they do not exist already (or change the extension of existing markdown files from `.md` to `.html`):

   - `index.html` - set to `layout: home`
   - `about.html` - set to `layout: page`
   - `contact.html` - set to `layout: page`
   - `posts/index.html` - set to `layout: page` (you will also need to create a `posts` directory)

2. Configure the `index.html` front matter. Example:

   ```markdown
   ---
   layout: home
   background: "/PATH_TO_IMAGE"
   ---
   ```

3. Configure the `about.html`, `contact.html`, and `posts/index.html` front matter. Example:

   ```markdown
   ---
   layout: page
   title: Page Title
   description: This is the page description.
   background: "/PATH_TO_IMAGE"
   ---
   ```

4. For each post in the `_posts` directory, update the front matter. Example:

   ```markdown
   ---
   layout: post
   title: "Post Title"
   subtitle: "This is the post subtitle."
   date: YYYY-MM-DD HH:MM:SS
   background: "/PATH_TO_IMAGE"
   ---
   ```

   For reference, look at the [demo repository](https://github.com/StartBootstrap/startbootstrap-clean-blog-jekyll) to see how the files are set up.

5. To be able to use the form to the `contact.html` page, make sure you have the `email` setting in your `_config.yml` file set to a working email address and the `form_id` setting to your actual Formspree form's ID. Once this is set, fill out the form and then check your email, verify the email address using the link sent to you by Formspree, and then the form will be working!

6. Build your site: `bundle exec jekyll serve`

### Using Core Files

When using the core files, the demo images, posts, and pages are all included with the download. After following the instructions below, you can then go and change the content of the pages and posts.

1. [Download](https://github.com/vishalscodes/startbootstrap-clean-blog-jekyll/archive/refs/heads/master.zip) or Clone the repository.
2. Update the following configuration settings in your `_config.yml` file:

   - `baseurl`
   - `url`
   - `title`
   - `email` (after setting this setting to a working email address, fill out the form on the contact page and send it - then check your email and verify the address and the form will send you messages when used)
   - `description`
   - `author`
   - `form_id` (if you want the form to work)
   - `twitter_username` (Optional)
   - `facebook_username` (Optional)
   - `github_username` (Optional)
   - `linkedin_username` (Optional)
   - `instagram_username` (Optional)

3. Build your site: `bundle exec jekyll serve`

## Bugs and Issues

Have a bug or an issue with this template? [Open a new issue](https://github.com/vishalscodes/startbootstrap-clean-blog-jekyll/issues) here on GitHub!

## Copyright and License

Copyright 2013-2021 Start Bootstrap LLC. Code released under the [MIT](https://github.com/StartBootstrap/startbootstrap-clean-blog-jekyll/blob/master/LICENSE) license.
