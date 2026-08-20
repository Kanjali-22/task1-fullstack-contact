# Java Full Stack Internship - Task 1

This project demonstrates a frontend landing page connected to a Spring Boot backend through a POST contact form. It is designed as a simple but professional Java Full Stack internship task focused on the connection between HTML/CSS, form submission, and backend processing.

## Technologies

- Java 17
- Spring Boot 3.x
- Maven
- HTML5
- CSS3

## Features

- Responsive landing page
- Sticky navigation
- Hero section
- Services section
- About section
- Contact form
- Spring Boot POST endpoint
- Console form processing

## How to Run

From the project root, run:

```bash
mvn spring-boot:run
```

Then open:

```text
http://localhost:8083
```

## Backend Endpoint

```text
POST /contact
```

The form fields must use the exact names:

- `name`
- `email`
- `message`

## Expected Console Output

When the form is submitted, the Spring Boot console will print output similar to:

```text
New Contact Form Submission
Name    : Anjali
Email   : anjali@example.com
Message : Hello
```

The backend also returns:

```text
Thank you! Your message has been submitted successfully.
```
