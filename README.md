# Paws

Rails application that helps animals in street situations find a home or help people to find their pets.

## Getting Started

#### Requirements

You'll need the following installed to run the project successfully:

* Ruby 2.6 or higher
* Bundler - `gem install bundler`
* Rails 6.0 - `gem install rails`
* Yarn - `brew install yarn` or [Install Yarn](https://yarnpkg.com/en/docs/install)
* Foreman (optional) - `gem install foreman` - helps run all your
  processes in development

#### Installation

Go to the project folder and run `bundle install`, then you need to create the databases with `rails db:create` and execute the migrations `rails db:migrate`, Rails 6 include webpacker by default so you need to run `yarn install` to get all javascript dependencies in your project.

#### Development

This project uses `foreman` to help with the development so to run your app, use `foreman start` or `foreman start -p 3000` if you prefer that port, this will run `Procfile.dev` via `foreman start -f Procfile.dev` as configured by the `.foreman` file and will launch the development processes `rails server` and `webpack-dev-server` processes.

You can also run them in separate terminals manually if you prefer.
