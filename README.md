# Products Tracker
  ![License](https://img.shields.io/badge/license-MIT-yellowgreen.svg)
  ## Table of Contents
  [Description](#description)
  [Installation](#installation)
  [Usage](#usage)
  [Questions](questions)
  [License](license)

  ## Description
  mysql ecommerce database using sequelize that can store products with categories and descriptive tags.
  https://drive.google.com/file/d/1lt7MsDZEGpzTXNyDQTnc19LF5HM5caU0/view
  
  ## Installation
  Clone github repository
  type 'npm i' into console

  ## Usage
  change .env.EXAMPLE to .env
  change contents of .env file to align with your mysql user credentials
  type 'npm run seeds' into console
  type 'npm start' into console
  open insomnia and enter your localhost url with api/categories, api/products, or api/tags route
  
  post request with a category name to create a category

  post request with a product name, product price, stock, and category id to create a product

  post request with tag id to create a tag

  put request with category name and category id parameter to change category name

  put request with product data and product id parameter to change product data

  put request with tag name and tag id parameter to change tag name

  delete request with any table and any existing id in parameters to delete item

  ## Questions
  https://github.com/ElijahAFrancis
  efrancis64@gmail.com

  ## License
    Licensed under the MIT license
    https://www.mit.edu/~amini/LICENSE.md
  