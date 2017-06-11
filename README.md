# sabalas-com
A customizable online shop management system. Made from ruby on rails and the UI is heavily based on [materialize-sass](https://github.com/mkhairi/materialize-sass).

> This repository is still a work-in-progress and most functionality and customization is not documented yet.

## Setting Up
Clone the code and run `bundle install`. You need at least ruby `v2.3.3` or higher to run the code.

## Customizing
### Colors
To change the primary and secondary colors, change the these lines from `app/assets/stylesheets/application.scss`

    $primary-color: #000000 !default;
    $secondary-color: color("grey", "darken-3") !default;
    $slider-indicator-color: #000000 !default;
    
For further variables, checkout [materialize-sass `_variables.scss`](https://github.com/Dogfalo/materialize/blob/master/sass/components/_variables.scss).

### Logos
Change the following files with your desired logos:

    app/assets/images/logo-dark.png
    app/assets/images/logo-light-large.png
    app/assets/images/logo-light-small.png
    app/assets/images/logo-light.png
    
All logos should be replaced because it is used in both mobile and desktop view.

## Required Gems
- [rails](https://rubygems.org/gems/rails) `v5.1.1`
- [sass-rails](https://rubygems.org/gems/sass-rails) `v5.0`
- [haml](https://rubygems.org/gems/haml) `v5.0.1`
- [jquery-rails](https://rubygems.org/gems/jquery-rails) `v4.2.1`
- [materialize-sass](https://rubygems.org/gems/materialize-sass) ([GitHub](https://github.com/mkhairi/materialize-sass)) `v0.98.2`

