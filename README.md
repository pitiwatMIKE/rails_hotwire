# README

## rails s
ActionView::Template::Error (Error: File to import not found or unreadable: bootstrap/scss/bootstrap.
        on line 2:1 of app/assets/stylesheets/application.scss
>> @import "bootstrap/scss/bootstrap";

   ^
):
     6:     <%= csrf_meta_tags %>
     7:     <%= csp_meta_tag %>
     8:
     9:     <%= stylesheet_link_tag 'application', media: 'all', 'data-turbolinks-track': 'reload' %>
    10:     <%= stylesheet_link_tag 'style', media: 'all', 'data-turbolinks-track': 'reload' %>
    11:     <%= javascript_pack_tag 'application', 'data-turbolinks-track': 'reload' %>
    12:

## use
- yarn add bootstrap@next jquery @popperjs/core
- bundle exec rails webpacker:install