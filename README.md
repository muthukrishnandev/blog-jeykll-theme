# blog-theme

blog-theme is a clean and minimalist theme for [Jekyll](https://jekyllrb.com/), focuses on pure and efficient writing. This is a fork from [Moving](https://github.com/huangyz0918/moving).

## Installation

If you want to create a new blog using blog-theme. You can follow these steps after setting up the [Jekyll](https://jekyllrb.com) environments:

Clone this repository: 
```bash
git clone https://github.com/muthukrishnandev/blog-theme.git
```

Move into that directory:
```bash
cd blog-theme/
```

Install required gems using `bundle`:
```bash
bundle install
```

Run the blog in localhost
```bash
jekyll serve
```

Once you successfully run the blog-theme blog, you can modify the theme and add posts by yourself, have fun!

## Usage

You can modify the `_config.yml` to custom your blog. An example is if you want to change the back button's text in each post, you can change the `back_to`.

```yaml
title: Blog Theme # The title of the blog
description: > # this means to ignore newlines until "url:"
  Simple Blog description
url: http://blog.website # this is your site's root address.
favicon: "assets/favicons/favicon.ico" # set the favicon of the site

author: Blog Author # Your name 
email: author@blog.com # your email shown in the footer
avatar_url: "https://via.placeholder.com/500x500.png?text=Author%20Photo" # avatar in about page
about_you: a short description about you. # short description about you in about page

# refer to https://shopify.github.io/liquid/filters/date/ if you want to customize this
date_format: "%b %d" # date format of posts in home page
back_to: "Home" # In the post page, you have a back button above the title, you can custom the text by yourself.
show_excerpts: true # set to true to show excerpts on the homepage
permalink: /:slug/ # change this permalink
```

## Development

To set up your environment to develop this theme, run `bundle install`.

Your theme is setup just like a normal Jekyll site! To test your theme, run `bundle exec jekyll serve` and open your browser at `http://localhost:4000`. This starts a Jekyll server using your theme. Add pages, documents, data, etc. like normal to test your theme's contents. As you make modifications to your theme and to your content, your site will regenerate and you should see the changes in the browser after a refresh, just like normal.

When your theme is released, only the files in `_layouts`, `_includes`, `_sass` and `assets` tracked with Git will be bundled.

## License

The theme is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
