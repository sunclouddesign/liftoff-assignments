# Project Outline

## Overview

My project will be an event log that will allow staff members at an organization to track public events that they offer. It will allow staff members to log in, and to create and edit event details such as date/time, location, title, description, number of attendees, and volunteers.

This project was motivated by the need of a nonprofit organization that wants a way to keep track of and view historical information about their events.

## Features

- User login: Users will be able to log in, either by creating accounts in the system, or by using a third-party authentication provider (e.g. Google Authentication). All access to the site will be restricted to logged-in users.
- Create and edit events: Users will be able to create new events in the system by entering in a mixture of required (title, date, time, etc) and optional fields (description, number of attendees, etc)
- View recent events: Users will be able to view a listing of recent events, and by clicking on a recent event view details about that event.
- Volunteer tracking: Users will be able to add volunteers to the system, and to assign volunteers to events.
- Delete events: Users will be able to delete events.

## Technologies

- Java
- Spring Boot
- MySQL
- Thymeleaf templates
- Bootstrap

## What I'll Have to Learn

For the login functionality, I'll have to learn something new in either scenario. If I choose to use native login functionality for the site, I'll need to learn how to use the login approach outlined in the [`spring-filter-based-auth` repository](https://github.com/LaunchCodeEducation/spring-filter-based-auth). If I choose to use third-party authentcation, I'll need to learn how to use an OAuth2 provider such as Google Authentication.

I'll also be using test-driven development, writing tests for my code before writing the code itself. I don't have much experience doing this in Spring, so I'll have to learn how to use its testing capabilities.