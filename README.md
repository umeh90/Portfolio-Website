# Portfolio Website

This project is a personal portfolio website built using HTML, CSS, and JavaScript. It was created to showcase web development skills and demonstrate how a simple and functional portfolio site can be built from scratch without using external frameworks.

The website contains multiple sections including Home, About, Skills, Projects, and Contact. A fixed navigation bar allows users to easily move between sections, and the active link highlights automatically based on the section currently in view.

One of the main features of the project is the contact section, which allows visitors to send a message directly to a WhatsApp number. When a user fills out the form and clicks the send message button, a WhatsApp link is generated with the message already filled in. This opens WhatsApp (either the app or WhatsApp Web) so the visitor can quickly send the message.

This approach provides a simple alternative to traditional contact forms because it does not require a backend server or email service.

## Features

- Built using HTML, CSS, and JavaScript
- Fixed navigation bar
- Section-based layout (Home, About, Skills, Projects, Contact)
- Active navigation highlighting while scrolling
- WhatsApp contact form integration
- Clean and simple user interface

## WhatsApp Contact Feature

The contact form collects the visitor's name, email, and message. JavaScript is used to construct a WhatsApp message and generate a link using the WhatsApp API. When the user clicks the send message button, WhatsApp opens with the message already prepared.

To use this feature in your own project, you only need to replace the placeholder phone number in the JavaScript file with your own WhatsApp number in international format.

Example:

234XXXXXXXXX

For desktop users, the phone number should already be connected to WhatsApp Web so messages can open correctly.

## Purpose of the Project

The goal of this project is to demonstrate practical front-end development skills and provide a simple example of how websites can integrate direct messaging features without requiring complex backend systems.
