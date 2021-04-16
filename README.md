# README

## Blog App

This assigment was part of the The Odin Prject course and it was to create a blogging application follwing [this guide](https://guides.rubyonrails.org/getting_started.html). 

It was a fun project as it let me play around with the structure of a Rails app and I began to understand the realtionship between Routes, Models and Controllers much better than a textbook was able to do. I also familiarised myself with the common Rails commands and naming conventions. 

Whilst the main purpose of this project was to understand the inner workings of a rails app. I thought it would be fun to use [Tailwindcss](https://tailwindcss.com/) to style my app a little better. I followed a guide online and integrated Tailwindcss using Webpack and also purged the bloat that it comes with so the page speed is accetpable. 

To showcase my blog I had to then delpoy this to Heroku. I followed the Heoroku Documentation and was able to successfully do this. However, I came across an issue which caused my blog run into some errors when trying to run the local host. I searched the error online and it was because my Development & Production database settings had not been seperated. I edited the Gemfile and Database.yml file to ensure my local host would use SQLITE3 wilst Heroku needed to use POSTGRESQL. 

You can find a live version of this blog here => [Live Blog](https://safe-stream-67683.herokuapp.com/)

