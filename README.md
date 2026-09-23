# Movie Ticket Booking System (C)

A console-based movie ticket booking system written in C. It supports up to 100 tickets held in memory and is driven by a simple menu.

## Features

| Option | Action |
|---|---|
| 1. Book Ticket | Reserve a ticket with a movie name, seat number and price |
| 2. Cancel Ticket | Cancel a booking by ticket ID |
| 3. Display All Tickets | List all current bookings |
| 4. Exit | Close the program |

## Data Model

```c
struct Ticket {
    int   ticketID;
    char  movieName[50];
    int   seatNumber;
    float price;
};
```

## Build and Run

```bash
gcc Ticket.c -o ticket
./ticket
```

On Windows, run `ticket.exe` instead.

## Concepts Practised

Structs · arrays · menu-driven programs · input handling with `scanf`
