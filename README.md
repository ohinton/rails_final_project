# 🎆  Reach Your Fundraising Auction Goals 🎆

#### By Olivia Hinton | Date: September 9, 2016

## Description

This app helps you reach your fundraising auction procurement goals by assisting with donor record management and communicating with your volunteer committee!

Features include:
* a database of your donors and volunteers, with the ability to assign a volunteer to a donor
* an admin dashboard to see the current progress toward your fundraising goal
* a dashboard so volunteers can see which donors they are responsible for contacting and record updates about donors
* a Google Calendar to goal deadlines, schedule volunteer committee meetings, invite volunteers to meetings and record responses to invites

## General Setup Instructions

* Clone this repository
* Install gems by running command `$ bundle` in the terminal
* Open another terminal tab and type `postgres` to start PostgreSQL database
* Return to first terminal tab and run `rails db:create` to create the databases
* Run `rails db:migrate db:test:prepare` to create tables
* Launch the Rails server by running command `$ rails s` in the terminal
* Launch site by visiting localhost:3000 in browser

## Tech Used

* Ruby on Rails (v. 5.0.0.1)
* Active Record
* PostgreSQL
* Bootstrap/SCSS

### License

*This software is licensed under the MIT license.*

Copyright (c) 2016 **Olivia Hinton**
