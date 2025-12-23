https://kluckysingh.github.io/Image-Search-App/


# 🖼️ Image Search App

This project is a simple **Image Search Application** built using **HTML, CSS, and JavaScript**.
It allows users to search for images and view results using the **Unsplash API**.

---

## 📄 How the App Works (Complete Flow)

The app has an input box where the user types a keyword (for example: *nature*).
When the **Search** button is clicked, JavaScript sends a request to the **Unsplash API** using an API key.

The API returns image data, and JavaScript dynamically creates HTML elements (`div`, `img`, and `a`) to display those images inside the page.
The images appear inside a container called **search-results**.

When the user clicks **Show More**, the app loads the next page of images and adds them below the existing ones instead of replacing them.

---

## 🧩 Main Components Explained Together

* **HTML**

  * Creates the structure (heading, input box, buttons, and image container)
  * `<div class="search-results"></div>` acts as an empty container where images are added dynamically

* **CSS**

  * Styles the page layout, images, and buttons
  * Makes the image gallery look clean and organized

* **JavaScript**

  * Reads the user’s input
  * Sends a request to the Unsplash API
  * Receives image data
  * Displays images on the page
  * Handles pagination using the “Show More” button

---

## 🔑 Unsplash API Usage

An **API key** is required to access images from Unsplash.

```js
const accessKey = "YOUR_API_KEY";
```

This key identifies your application and allows you to fetch image data.

---

## ⚙️ Core Logic Summary

* User submits the form → page does NOT reload
* Search text is captured from the input field
* API request is sent using `fetch()`
* Images are displayed dynamically using DOM manipulation
* Page number increases to load more images
* “Show More” button fetches additional results

---

## ✅ Features

* Search images by keyword
* Dynamic image loading
* Pagination support
* Opens image source in a new tab
* Beginner-friendly code structure

---

## 🛠️ Technologies Used

* HTML
* CSS
* JavaScript
* Unsplash API

---

## 📌 Conclusion

This project demonstrates:

* API integration
* Asynchronous JavaScript (`async/await`)
* DOM manipulation
* Building a dynamic and interactive web application

-
