# STUTZ website

The website of the STUTZ

# Features

- Responsive
- Accessible
- Contact form
- Custom Robots.txt (changes values based on environment)
- Internal templates for meta data and google analytics
- RSS Discovery
- Pagination (internal template)
- Taxonomies
- Archetypes
- Custom shortcode
- Hugo built-in menu
- `with`
- `STUTZ_ENV`
- `first`
- `after`
- `sort`
- Site LanguageCode
- `where`
- Content Views
- Partials
- Template layouts (type "post" uses a special list template, single template,  and a content view)
- Tags
- `len`
- Conditionals
- `ge` (greater than or equal to)
- `.Site.Params.mainSections` to avoid hard-coding "blog," etc. 

# Installation

## Install GIT
see https://git-scm.com/downloads

## Install Hugo
### MacOS
```
brew install hugo
```
### Windows
Install Chocolatey, see https://chocolatey.org/install

Open Command prompt as admin (right click as administrator)
```
choco install hugo -confirm
```
### Linux
```
sudo apt-get install hugo
```
or use snap in Ubuntu store.

## Install Website
```
git clone https://github.com/StutzCoin/website.git
cd website
hugo server -D
```

Browse website at http://localhost:1313


