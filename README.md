# THINGS IN HERE

## GEMS

```
gem "sassc-rails"
gem 'haml'
gem 'bootstrap-sass'
gem 'devise'
gem 'simple_form'
```
- i didnt use bootstrap sass
- image processing for storage
- devise set for turbo, rails 7
- from: https://dev.to/efocoder/how-to-use-devise-with-turbo-in-rails-7-9n9
- haml for devise links

```
- if user_signed_in?
	= link_to "New Post", new_post_path
- else
	= link_to "Sign Up", new_user_registration_path
	= link_to "Sign In", new_user_session_path

```

## MODELS
- devise user: has many posts and comments
- posts has many comments
- comments belongs to post and users

## OTHER
- he did his own styling

