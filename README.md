# BookMyShow Clone

This project is a basic implementation of a movie booking website similar to BookMyShow. It allows users to view movies, add theaters, and book movie tickets. The project includes HTML, CSS, and JavaScript for frontend functionality. The following sections explain how the different parts of the website work.

## Table of Contents
1. [Project Structure](#project-structure)
2. [Features](#features)
3. [Setup](#setup)
4. [How to Use](#how-to-use)
5. [Technologies Used](#technologies-used)
6. [Contributing](#contributing)
7. [License](#license)

---

## Project Structure

```plaintext
BookMyShow-Clone/
│
├── images/
│   ├── goat.jpeg
│   ├── devara.jpeg
│   ├── puspa.jpeg
│   ├── deadpool.jpeg
│   ├── amaran.jpeg
│   ├── demonte.jpeg
│   └── logo.png
│
├── index.html            # Movie list page
├── theatre.html          # Add theatre page
├── book.html             # Movie ticket booking page
├── style.css             # CSS Styles for the website
└── back.jpeg             # Background image for the website
```

---

## Features

- **Movie List Page**: Displays a list of movies currently showing, with images, movie titles, descriptions, and a "Book Now" button for each movie.
- **Add Theatre Page**: Allows adding theaters with details such as theatre name, location, capacity, and number of screens.
- **Movie Booking Page**: Allows users to book tickets for movies by providing details such as name, email, movie selection, theatre selection, and number of tickets.
- **CSS Styling**: The website is styled with a clean, modern design using CSS. Background images and responsive design are applied to enhance the user experience.

---

## Setup

To get started with this project, follow these steps:

1. Clone the repository to your local machine.
    ```bash
    git clone https://github.com/yourusername/BookMyShow-Clone.git
    ```

2. Navigate to the project directory:
    ```bash
    cd BookMyShow-Clone
    ```

3. Open the HTML files in a browser to see the project in action.
    - `index.html` for the movie listing page.
    - `theatre.html` for the add theatre page.
    - `book.html` for the movie ticket booking page.

4. The images used in the project are stored in the `images/` folder. You may need to adjust the paths to the images if they are stored elsewhere.

---

## How to Use

1. **Viewing Movies**:
   - Visit the `index.html` page to see a list of movies that are currently showing.
   - Each movie has a brief description and a "Book Now" button that will take you to the booking page.

2. **Adding Theatres**:
   - Go to `theatre.html` to add new theaters. Fill in the details about the theatre (name, location, capacity, number of screens) and click the "Add Theatre" button. The theatres will be listed below the form.

3. **Booking Tickets**:
   - Visit `book.html` to book movie tickets.
   - Fill in the form with your name, email, movie selection, theatre, and number of tickets.
   - After submitting the form, a confirmation will be shown with your booking details.

---

## Technologies Used

- **HTML**: Used for the basic structure and content of the website.
- **CSS**: For styling and layout of the website, including background images and responsive design.
- **JavaScript**: For handling dynamic functionality, such as adding theatres to the list and booking movie tickets.
- **Bootstrap** (for the `theatre.html` page): Used for building responsive forms and UI elements.

---

## Contributing

1. Fork this repository.
2. Create a new branch for your feature (`git checkout -b feature-name`).
3. Make the necessary changes.
4. Commit your changes (`git commit -am 'Add feature'`).
5. Push to your fork (`git push origin feature-name`).
6. Create a new Pull Request.

---

## License

This project is licensed under the MIT License.

---

Feel free to modify, use, and share this project according to the license and your needs!
