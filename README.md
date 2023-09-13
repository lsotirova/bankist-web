# Bankist Web App

**Preview of Project:** [https://lsotirova.github.io/bankist-web/](https://lsotirova.github.io/bankist-web)

The JavaScript code for the Bankist Web App enhances the user experience by adding interactive features and functionality to the app's front-end. Below is a breakdown of key features and their corresponding code sections:

## Modal Handling

The app allows users to open and close a modal dialog box. This modal is used for actions like opening an account. The relevant code includes:

- `modal`, `overlay`, `btnCloseModal`, and `btnsOpenModal` are selected using `querySelector`.
- `openModal` function removes the "hidden" class from `modal` and `overlay`.
- `closeModal` function adds the "hidden" class to `modal` and `overlay`.
- Event listeners are added to buttons to open and close the modal, as well as to the overlay for closing it.

## Smooth Scrolling

The app provides smooth scrolling when users click on navigation links or a specific button. This feature is achieved using:

- `btnScrollTo` for selecting the button.
- `section1` for selecting the target section.
- The `scrollIntoView` method with the `behavior` option set to "smooth" for smooth scrolling.

## Tabbed Content

The app includes tabbed content that allows users to switch between different sections of information. Relevant code sections include:

- Selecting tab elements and content containers using `querySelector` and `querySelectorAll`.
- Event listener for handling clicks on tabs (`tabsContainer.addEventListener`).
- Clicked tab's dataset is used to identify and display the corresponding content.

## Navigation Hover Effect

The app creates a navigation hover effect that changes link opacity when users hover over navigation items. This is implemented using:

- Event listeners for `mouseover` and `mouseout` on the navigation (`nav`) element.
- `handleHover` function updates link and logo opacity.

## Sticky Navigation

The app makes the navigation bar sticky when scrolling. This is achieved with:

- Intersection Observer (`headerObserver`) to detect when the header is no longer in the viewport.
- Adding and removing the "sticky" class on the navigation bar based on the observer's callback.

## Revealing Elements on Scroll

The app reveals elements on scroll when they enter the viewport. This effect is achieved using:

- Intersection Observer (`sectionObserver`) to detect when sections enter the viewport.
- Adding and removing the "section--hidden" class to reveal or hide sections.

## Lazy Loading Images

Images are loaded lazily to improve page loading performance. This is accomplished with:

- Selecting images with the `lazy-img` class.
- Intersection Observer (`imgObserver`) to load images when they are about to enter the viewport.

## Slider Component

The app includes a slider component that allows users to navigate between different slides, including testimonials. Key features of the slider include:

- Selecting slider elements and buttons.
- Functions for creating dots, activating dots, going to a specific slide, and initializing the slider.
- Event listeners for keyboard navigation, button clicks, and dot clicks.

## Initialization

The app initializes various components and event listeners when the page loads. This ensures that the interactive features are available to users from the start.

## HTML Structure

The code assumes a specific HTML structure with elements having specific class names and IDs. The JavaScript code interacts with these elements based on their class and ID attributes.

This JavaScript code enhances the Bankist Web App's user experience by adding interactive and visually appealing features to the front-end.


