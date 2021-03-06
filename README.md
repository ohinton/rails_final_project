# Auctionary

#### By Olivia Hinton | Fall 2016

## Description

Auctionary makes it easy for volunteers to gather and track donations for charity auctions. As a former fundraising auction coordinator, I experienced the difficulty that volunteers face when reaching out to donors and keeping track of their responses.

Features include:
* a database of your donors and volunteers, with the ability to assign a volunteer to a donor
* a dashboard so volunteers can see which donors they are responsible for contacting and record updates about donors
* a Google Map that shows where all donors are located

## General Setup Instructions

* Clone this repository
* Open project and create an .env file in the top level of the project for MAP_API_KEY and set it equal to your Google Map API key
* Install gems by running command `$ bundle` in the terminal
* Open another terminal tab and type `postgres` to start PostgreSQL database
* Return to first terminal tab and run `rails db:create` to create the databases
* Run `rails db:schema:load` to create tables
* Launch the Rails server by running command `$ rails s` in the terminal
* Launch site by visiting localhost:3000 in browser

## Tech Used

* Ruby on Rails (v. 5.0.0.1)
* Active Record
* PostgreSQL
* Google Maps API
* Materialize CSS framework

### License

*This software is licensed under the MIT license.*

Copyright (c) 2016 **Olivia Hinton**
