# paige

A simple Hugo theme. [Try it out.](https://willfaught.com/paige)

## Screenshots

Home page:

<img src="https://github.com/willfaught/paige/raw/master/images/home1.jpg">

<img src="https://github.com/willfaught/paige/raw/master/images/home2.jpg">

Single page:

<img src="https://github.com/willfaught/paige/raw/master/images/single.jpg">

List page:

<img src="https://github.com/willfaught/paige/raw/master/images/list1.jpg">

<img src="https://github.com/willfaught/paige/raw/master/images/list2.jpg">

Taxonomy page:

<img src="https://github.com/willfaught/paige/raw/master/images/taxonomy.jpg">

Term page:

<img src="https://github.com/willfaught/paige/raw/master/images/term.jpg">

404 page:

<img src="https://github.com/willfaught/paige/raw/master/images/404.jpg">

## Features

- Blog
- Facebook sharing support
- Google Analytics support
- Landing page
- Light color scheme
- Math typesetting support
- Menu navigation
- Minimal design
- Responsive, mobile-first layout
- Sections for other kinds of content
- Single column presentation
- Social links
- Twitter sharing support

## Design

The HTML author is the site author.

The HTML description is the page description.

The HTML keywords is a union of the page keywords, tags, and categories.

The HTML title is the page title, followed by a middle dot, followed by
the site title. If one is missing, the other is used without the middle
dot. If both are the same, only one is used without the middle dot.

The HTML body can have a header, a body, and a footer. The header has
the section menus, if any; the page title, if any; the page description,
if any; and the page date, if any. The body has the page content, if
any. The footer has the copyright notice, if any.

A section menu is highlighted if its path is a prefix of the path of the
current page. For example, the section menu path `/foo/` matches the
pages `content/foo/_index.md`, `content/foo/bar.md`, and
`content/foo/bar/_index.md`. The section menu path `/` only matches the
page `content/_index.md`.

The page date is the publish date, if any; otherwise, it's the creation
date.

The home page body has the `stretch`, `center`, `greeting`, and `blurb`
parameters from `content/_index.md`, if any; the page content, if any;
and linked icons for the social sites configured in `config.yaml`, if
any. `stretch` is an image that is stretched fully horizontally with
`background-position: center` and `background-size: cover`. `center` is
an image that is centered.

Single pages use the `link` page parameter, if any, as the reference for
an anchor around the page title, if any. If the page or site parameter
`math` is set to true, math typesetting is enabled with KaTeX.

If `partials/head.html` exists in the site, it is included at the end of
the head tag. If `partials/body.html` exists in the site, it is included
at the end of the body tag.

Bootstrap 5.2.2 CSS and JavaScript and Bootstrap Icons 1.10.2 are loaded
from the Bootstrap CDN for every page.

## Configuration

See the example site directory for an example configuration.

## Credits

- Center photo by [Yuvraj Singh](https://unsplash.com/photos/ljziSm0DXg8)
- Stretch photo by [Sergey Pesterev](https://unsplash.com/photos/JV78PVf3gGI)
