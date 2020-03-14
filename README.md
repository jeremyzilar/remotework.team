# Remote Friendly
We help small and medium-sized organizations transition to remote working.

To learn more, visit https://remote-team.work/
Book a free 15min session https://calendly.com/jeremyzilar/online?month=2020-03


---


## Developing this site

This site was made using [Jekyll](https://jekyllrb.com/) and the [U.S. Web Design System](https://designsystem.digital.gov/), and [USWDS Gulp](https://github.com/uswds/uswds-gulp).

### Installing locally :computer:

1. Clone this site https://github.com/jeremyzilar/remotework.team — this will
1. Navigate to the project directory in terminal and run the following:
  - `bundle install`
  - `npm install`
  - `npm install gulp-cli -g`
  - `npm install autoprefixer gulp@^4.0.0 gulp-notify gulp-postcss gulp-replace gulp-sass gulp-sourcemaps postcss-csso sass uswds@latest uswds-gulp@github:uswds/uswds-gulp --save-dev`
1. Move on to building the site.

### Build the site locally :computer:

To build the site on your computer, you'll need to run two separate commands in Terminal, at the same time.

**To build the pages**
1. Navigate to the project directory in terminal and run the following:
  - `bundle exec jekyll serve` — this will build all of the pages using Jekyll

Then open a new tab in Terminal

**To build the CSS styles**
1. Navigate to the project directory in terminal and run the following:
  - `gulp` — this will build all of the styles and CSS changes
