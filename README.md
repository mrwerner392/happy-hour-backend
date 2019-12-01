# Happy Hour Frontend

Our app provides a virtual bar experience for users where users can choose a seat at the bar, buy a drink, favorite a drink, and create their own drink.

## Motivation

Who doesn't appreciate a good happy hour cocktail?

## Features

- Search ingredients

- Filter by drink category

- Buy a drink

- Favorite a drink

- Create own drink

- Watch TV

- Choose a seat

- Drink your cocktail

- Make account and log in

- Validations on account information

## Instructions

- A user can log in or sign up

- Choose a seat to sit

- View menu with drink names, ingredients, and drink creator

- Can filter drinks by category on the menu

- Can click the heart to favorite drink which will show up in side bar

- Can click drink name to buy

- After buying a user can close the menu and drink will appear on bar

- User can click on the drink to chug it

- On the menu, a user can click the "Create a Drink" button

- This page allows the user to choose a category, name, ingredients and instructions for their drink

- User can choose a maximum of 5 ingredients

- Once the drink is made, the user will be redirected to the bar

- The user's newly created drink will now be shown on the menu

## Technologies
- CocktailDB API: (https://www.thecocktaildb.com/api/json/v1/1/search.php?s=margarita)
- PostgreSQL
- Ruby on Rails
- JWT Auth
- BCrypt
- ActiveRecord
- ActiveModel Serializers
- RestClient

## Installation

Check back soon for a link to the live version of this app.

To test locally, follow the instructions below:

1. Clone repository to your local machine and navigate into the directory in your terminal
2. Open the repo in a code editor and create a file called '.env' in the root directory
3. In this file create a JWT_SECRET_KEY with `JWT_SECRET_KEY: '<your key here>'`
4. Back in the terminal run `bundle install`
5. Run `rails db:create && rails db:migrate && rails db:seed`
6. Run `rails s`
  - Make sure this runs on port 3000 (should by default)
7. If you have not already, go to the [frontend repository](https://github.com/mrwerner392/happy-hour-frontend/tree/headless-horse-rider) and follow the installation instructions in the README

## Demo

Follow [this link](https://www.youtube.com/watch?v=wpUKh5bZr2U) for a video demonstration of the app.

## Authors
[Kimberly Bone](https://github.com/kimberlybone) & [Matt Werner](https://github.com/mrwerner392)
