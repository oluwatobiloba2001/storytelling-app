# Storytelling App

This project is a simple web-based storytelling app that allows users to hear different types of short stories: Scary, Funny, or Adventure. The app provides an interactive experience with dynamic styling based on the selected story type.

---

## Features

* **Dynamic Story Display**: Users can select from three buttons (Scary, Funny, or Adventure), and a short story corresponding to their choice will appear.
* **Interactive Design**: Each story dynamically updates the border color of the story container, adding a unique visual effect.
* **Responsive Layout**: The design adapts to various screen sizes, offering a seamless experience on both desktop and mobile devices.

---

## File Structure

```
├── index.html       # Main HTML file
├── styles.css       # CSS file for styling
├── story.js         # JavaScript file for interactivity
```

---

## Code Overview

### HTML (`index.html`)

* The structure includes:

  * A heading prompting the user to interact.
  * Buttons for selecting the type of story.
  * A paragraph element (`#result`) for displaying the chosen story.
  * A `main` container with a double border design for visual appeal.

### CSS (`styles.css`)

* Uses CSS variables for consistent and reusable styling.
* Provides a dark-themed aesthetic with vibrant colors for buttons and dynamic elements.
* Ensures responsive design with a flexible button layout that adapts to screen sizes.

### JavaScript (`story.js`)

* Defines story objects containing:

  * The story text.
  * The border color corresponding to each genre.
* Implements the `displayStory` function to update the displayed story and styling dynamically.
* Attaches click event listeners to buttons for interactive functionality.

---

## Usage

1. Clone or download the repository.
2. Open `index.html` in any modern web browser.
3. Click one of the story buttons:

   * **Scary Story**: Displays a spooky story with a red border.
   * **Funny Story**: Displays a humorous story with a yellow border.
   * **Adventure Story**: Displays an adventurous story with a green border.

---

## Technologies Used

* **HTML5**: For structure and content.
* **CSS3**: For styling and responsiveness.
* **JavaScript**: For interactivity and dynamic updates.

---

## Future Improvements

* Add more story genres.
* Enhance accessibility for screen readers.
* Allow users to contribute their own stories through a form.

---

## License

This project is licensed under the MIT License. Feel free to use and modify it as needed.

---

## Author

Developed by \Alomaja Oluwatobiloba.

Enjoy the stories! 😊
