# Todo

This sample application was built to provide a playground for trying out the
different capabilities of the Rails Hotwire framework to support single page
application behavior. The `main` branch of this repository will include the
finished application and updates. Other branches will contain partially
completed updates. These partially completed branches will enable following
a tutorial and provide check points.

The tutorial is based on a blog post entitled [Hotwire: Supercharged Rails forms with Turbo by Alex Chevez.](https://medium.com/@alexischvez/hotwire-supercharged-rails-forms-with-turbo-6de79bb9e374)

# New Rails App
This application was started with Rails 7.1.3.2 and Ruby 3.3.1. We opted _not_
to use the testing framework, but use Rspec instead. This intial setup is found
in the `rails-devcontainer` branch. As you might guess from the branch name,
we also setup a **devcontainer** and VSCode extensions. The application was
created with:
```
rails new todo -T
```
The `-T` removes the testing boilerplate. We added the `rspec` gem to the
`Gemfile` and ran:
```
 rails generate rspec:install
 ```


