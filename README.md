# Remote Friendly
We help small and medium-sized organizations transition to remote working.

To learn more, visit https://remote-team.work/
Book a free 15min session https://calendly.com/jeremyzilar/online?month=2020-03


---


## :computer: Developing this site on your computer

This site was made using [Jekyll](https://jekyllrb.com/) and the [U.S. Web Design System](https://designsystem.digital.gov/), and [USWDS Gulp](https://github.com/uswds/uswds-gulp).

### Installing

1. Clone this site https://github.com/jeremyzilar/remotework.team — this will
1. Navigate to the project directory in terminal and run the following:
  - `bundle install`
  - `npm install`
  - `npm install gulp-cli -g`
  - `npm install autoprefixer gulp@^4.0.0 gulp-notify gulp-postcss gulp-replace gulp-sass gulp-sourcemaps postcss-csso sass uswds@latest uswds-gulp@github:uswds/uswds-gulp --save-dev`
1. Move on to building the site.

## Building the pages

1. Navigate to the project directory in terminal and run the following:
  - `bundle exec jekyll serve` — this will build all of the pages using Jekyll


## Building the CSS

To build the CSS styles, you'll need to open a separate tab in terminal. Both processes can run at the same time.

1. Navigate to the project directory in terminal and run the following:
  - `gulp` — this will build all of the styles and CSS changes
