# Product Landing Page: DJI Mavic 4 Pro

## 📝 Overview

This project is a static landing page for the DJI Mavic 4 Pro drone product. The page was built using only HTML and CSS, focusing on applying fundamental web design concepts such as element structuring and styling, building layout using `float`, using `position` for overlapping and fixed elements, and applying simple effects using pseudo-classes and pseudo-elements.

**Goal:** To practice building a complete web page from scratch using traditional layout techniques (Floats) and practically understanding the Box Model and Positioning.

## ✨ Page Features

* **Hero Section:** Main product showcase with a prominent image, essential information, price, and interactive buttons (Add to Cart / Wishlist).
* **Fixed Navbar:** Remains visible at the top of the page when scrolling.
* **Specifications Comparison Table:** A table designed to display product specifications and compare them with other products.
* **Customer Reviews Section:**
    * Ratings summary with a star rating breakdown chart.
    * The summary column remains fixed (`position: sticky`) while scrolling.
    * Displays individual customer reviews using a card design for each review.
* **Related Products Section:** Displays additional products as cards using `float` with simple `hover` effects (scaling).
* **Multi-Column Footer:** A footer containing links and information distributed across columns using `float`.
* **Layout using Float:** The primary column structure (Layout) in most sections of the page was built using the `float` property, utilizing `clear-fix` to ensure proper layout.
* **Positioning Usage:** `position: relative`, `position: absolute`, `position: fixed`, and `position: sticky` were used to place elements like Badges, fix the Navbar, and make the reviews summary box sticky.

## 🛠️ Tech Stack

* **HTML5:** Language for building the page structure.
* **CSS3 (Vanilla):** For styling the page and implementing layout and styling, focusing on:
    * `float` & `clear` (for building the Layout).
    * `position` (relative, absolute, fixed, sticky).
    * Box Model (`margin`, `padding`, `border`).
    * Pseudo-classes (`:hover`).
    * Pseudo-elements (`::before`, `::after`).
    * `transition` & `transform` (for simple effects).

## 📸 App Visualization

![Hero Section Screenshot](Images/hero-section.png)
![Specifications Table Screenshot](Images/why-section.png)
![Customer Reviews Screenshot](Images/reviews-section.png)
![Related Produts Screenshot](Images/related-products-dection.png)
![Footer Screenshot](Images/footer-section.png)

**Watch the Demo:** [Link to Demo Video](https://drive.google.com/file/d/1Q-u3K2vxjfErHsx7P8s8t2aog_iw_j8G/view?usp=sharing)

## 🚀 Getting Started

To run the project on your local machine for development or testing purposes, follow these steps:

### Prerequisites

* A modern web browser (like Google Chrome, Firefox, Safari, Edge).
* A code editor (like VS Code) if you wish to modify the code.

### Running

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/Rawwann/fit-core-gym.git](https://github.com/Rawwann/fit-core-gym.git)
    ```

2.  **Navigate to the project directory:**
    ```bash
    cd fit-core-gym
    ```
    *(Note: If your local project folder has a different name, use that name in the `cd` command)*

3.  **Open the `index.html` file:**
    * Open the `index.html` file (or the correct path to it, e.g., `HTML/index.html` if it's inside an HTML folder) directly in your web browser. (There are no installation or build steps, as it's a static page).

## 🤝 Contributing

This project was created as part of a learning exercise. If you have suggestions for improving the code or fixing bugs, feel free to fork the repository and submit a Pull Request.

## 📄 License

This project is licensed under the MIT License.