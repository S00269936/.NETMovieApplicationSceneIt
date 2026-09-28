# Scene It

Scene It is a C# movie tracking application that allows users to keep track of movies they have watched and rate them.

The application was created as part of my Software Development studies and gave me experience working with C#, WPF, databases and user authentication.

## Features

- Create an account and log in
- Browse a list of movies
- View movie information
- Mark movies as watched
- Rate movies you have watched
- Update your movie ratings
- View all of your watched movies
- Sort movies by title or release year
- Filter movies by genre
- Get a random movie using the Surprise Me feature
- User passwords are securely hashed before being stored

## Technologies Used

- C#
- .NET
- WPF
- SQL Server
- Entity Framework
- BCrypt
- Visual Studio

## How It Works

Users can create an account and log into Scene It.

Once logged in, they can browse the available movies and mark movies as watched. Watched movies are added to the user's personal list where they can also give each movie a rating.

The application stores user accounts, movies and watched movie information in a SQL database. This means each user has their own watched movie list and ratings.

## Database

Scene It uses a SQL Server database to store the application data.

The main data includes:

- Users
- Movies
- Watched movies
- User ratings

The watched movies data links a user to a movie and stores the rating that user gave the movie.

## What I Learned

While developing Scene It I gained more experience with:

- Building desktop applications with WPF
- Connecting a C# application to a SQL database
- Working with Entity Framework
- Creating and managing database tables
- User login and registration
- Password hashing with BCrypt
- Working with classes and objects
- Filtering and sorting data
- Handling user input and errors

## About

Scene It was developed as a college project while studying Software Development. The project was created to improve my understanding of C#, WPF, SQL and application development.
