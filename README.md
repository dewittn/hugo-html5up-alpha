# Hugo HTML5up Alpha

Hugo HTML5up Alpha is a port of the static HTML template [Alpha by HTML5 UP](https://html5up.net/alpha). It is designed to mirror the look and feel of the original template as closely as possible while taking advantage of all the best features Hugo has to offer.

![](https://github.com/dewittn/hugo-html5up-alpha/blob/master/images/screenshot.png)

## Features

- Blog
- Sections
- Taxonomies
- Page bundles
- Disqus Comments
- Fontawesome icons
- Menus and Submenus
- OpenGraph Metadata
- Customizable Homepage

## Demo

This theme comes with a more comprehensive demo, which closely mimics the original [HTML5 UP](https://html5up.net/alpha) theme and demonstrates more of its features. You can view a fully functional demo at:

https://hugo-html5up-alpha.nelsonroberto.com/

To run the demo locally use the following commands:

```
$ git clone https://github.com/dewittn/hugo-html5up-alpha/
$ cd hugo-html5up-alpha/exampleSite
$ hugo server --themesDir ../..
```


## Configuration

See the demo's configuration as an example:

https://github.com/dewittn/hugo-html5up-alpha/blob/master/exampleSite/config.toml

### Homepage
The homepage has five sections that are customizable and removable.

- Banner
- Highlight
- Features
- Blog
- Call to Action

Settings for the homepage come from `data\homepage.yml`.

```
### Banner ###
banner:
  enable: true
  title: "Alpha"
  content: "" # Change this if you want something other then the site description
  buttons:
    - title: "Sign Up"
      link: "#"
      class: "primary"
    - title: "Learn More"
      link: "#"

### Highlight ###
highlight:
  enable: true
  header: "Introducing the ultimate mobile app <br /> for doing stuff with your phone"
  content: "Blandit varius ut praesent nascetur eu penatibus nisi risus faucibus nunc ornare<br /> adipiscing nunc adipiscing. Condimentum turpis massa."
  image: "images/pic01.jpg"

### Features ###
features:
  enable: true
  rows:
    - items:
      - title: "Magna etiam"
        icon: "fa-bolt"
        accent: "accent2" #accent values are 1-8
        content: "Integer volutpat ante et accumsan commophasellus sed aliquam feugiat lorem aliquet ut enim rutrum phasellus iaculis accumsan dolore magna aliquam veroeros."
      - title: "Ipsum dolor"
        icon: "fa-chart-area"
        accent: "accent3" #accent values are 1-8
        content: "Integer volutpat ante et accumsan commophasellus sed aliquam feugiat lorem aliquet ut enim rutrum phasellus iaculis accumsan dolore magna aliquam veroeros."
    - items:
        - title: "Sed feugiat"
          icon: "fa-cloud"
          accent: "accent4" #accent values are 1-8
          content: "Integer volutpat ante et accumsan commophasellus sed aliquam feugiat lorem aliquet ut enim rutrum phasellus iaculis accumsan dolore magna aliquam veroeros."
        - title: "Enim phasellus"
          icon: "fa-lock"
          accent: "accent5" #accent values are 1-8
          content: "Integer volutpat ante et accumsan commophasellus sed aliquam feugiat lorem aliquet ut enim rutrum phasellus iaculis accumsan dolore magna aliquam veroeros."

### Blog ###
blog:
  enable: true
  # Leave header text blank to remove entire <section>
  header: "Recent Posts"
  buttonText: "Read More"
  postCount: 2

### Call to Action ###
cta:
  enable: true
  header: "Sign up for beta access"
  content: "Blandit varius ut praesent nascetur eu penatibus nisi risus faucibus nunc."
```

### Global Banner
The global header is also configurable by modifying the `globalheader.yml` file.

```
title: "[Alpha](/) by HTML5 UP"
button:
  enable: true
  title: "Sign up"
  link: "#"
```

### Cover Image

The cover image URL is hard-coded, therefore to replace this add an image to the following location in your Hugo application:

```
/static/images/banner.jpg
```

### Comments powered by Disqus

The comments section is **not** shown unless a Disqus code is set in the `config.toml` file.

```
disqusShortname = "XXX"
```

## Original Theme Credits

- [Alpha by HTML5 UP](https://html5up.net/alpha)

## License

This theme is licensed under the [Creative Commons Attribution 3.0 License](https://creativecommons.org/licenses/by/3.0/).

Read More - [LICENSE](LICENSE)
