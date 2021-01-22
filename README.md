# socialmedia-earthgang

## Description
This is a social media application where users can sign up. After signing up, they can sign in and post images with a text description or simply text posts with no images. After posting, the posts will appear in a feed that that users can scroll through containing their posts and other user's posts. They can also modify their profile information and upload profile pictures. They can also like posts and the posts will display the number of likes.

## Technologies Used
* Postgresql - version 42.2.18
* Java - version 1.8.0_271
* Junit - version 4.13
* Log4j - version 1.2.17
* H2 - version 1.4.197
* SpringCore - version 5.2.12.RELEASE
* SpringBeans - version 5.2.12.RELEASE
* SpringContext - version 5.2.12.RELEASE
* SpringORM - version 5.2.12.RELEASE
* SpringWEBMVC - version 5.2.11.RELEASE
* react-aws-s3 - version 1.3.0

## Features

* Register new accounts
* Creating posts with or without images
* Live updates
* Interact with other users by liking their posts

## Getting Started

* clone the repository using 'git clone https://github.com/jamesbeighley/socialmedia-earthgang/edit/master/README.md'
* either set up your environment variables for the database url, username and password or paste them from your database inside the datasource in the application configuration file
* Start the backend tomcat server in Spring Tool Suite
* Start the frontend in visual studio code using 'npm install' to install the node_modules and 'npm start'

## Usage

First sign up on the landing page, that will take you to your feed page where you can view other people's posts. On the right side of that page you can type your text in your post and paste an image file if you want. Then hit submit and it should show up in the feed.
