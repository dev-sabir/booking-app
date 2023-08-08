# Go Conference Ticket Booking Application

This project is a simple console-based ticket booking application for a conference. It was built to get familiar with Go and its basic syntax.

## Project Structure

The project consists of two Go files:

- `main.go`: This file contains the main logic of the application. It includes the user input collection, ticket booking, and ticket sending functions.
- `helper.go`: This file contains a helper function to validate user input.

## How to Run

To run this application, you need to have Go installed on your machine. Once you have Go installed, you can run the application using the following command:

- Clone the repository to your local machine: `git clone https://github.com/your-username/go-conference-ticket-booking.git`
- `cd go-conference-ticket-booking`
- `go run main.go helper.go`

## Features

- User input collection: The application collects the first name, last name, email, and the number of tickets they want to book from the user.
- Input validation: The application validates the user input. It checks if names are not too short, the email contains an '@' sign, and the number of tickets is valid.
- Ticket booking: If the user input is valid, the application books the tickets and updates the remaining tickets.
- Ticket sending: The application simulates sending tickets to the user's email address.
