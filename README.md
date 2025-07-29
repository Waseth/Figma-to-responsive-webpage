### Day 2 – 29th July 2025

# Figma-to-Responsive-Webpage

A fully responsive webpage built with **HTML** and **CSS**, based on a Figma design. The layout adapts seamlessly to **mobile**, **tablet**, and **desktop** screen sizes for an optimal user experience.

---

## Technologies Used

- HTML5
- CSS3
- Figma (as design reference)
- Visual Studio Code

---

## What I Learned

- I had trouble using the `calc()` function to calculate the width of the cards dynamically.
- I learned how to avoid stretching of images by using the `object-fit` property:
  ```css
  object-fit: cover;
````

* I also learned how to use **child selectors** to apply styles to only children of the parent selector:

  ```css
  .blog-card-image > img {
    object-fit: cover;
  }
  ```
* Learned how to center a `div` horizontally using:

  ```css
  margin-left: auto;
  margin-right: auto;
  ```

---

## Acknowledgments

* [freeCodeCamp](https://www.youtube.com/c/Freecodecamp) for beginner-friendly tutorials
* Figma for the design reference

