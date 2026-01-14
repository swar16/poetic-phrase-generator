# 🖋️ Poetic Quote Generator

A dynamic web application that generates witty, satirical, and poetic phrases inspired by the literary style of Oscar Wilde, paired with high-quality imagery based on your favorite locations.

---

## 🌟 Features

- **AI-Powered Quotes**  
  Generates unique, witty, and poetic text using OpenAI’s `text-davinci-003` model.

- **Contextual Imagery**  
  Automatically fetches high-resolution photos from the Unsplash API based on your favorite place.

- **Oscar Wilde Persona**  
  Carefully crafted AI prompts emulate Wilde’s sharp wit and elegant prose.

- **Smart Caching**  
  Uses `localStorage` to store the last generated quote and prompt, preventing unnecessary API calls on refresh.

- **Real-Time Date Stamping**  
  Each quote is tagged with the current month and year.

---

## 🚀 Getting Started

### Prerequisites

- A modern web browser  
- [Node.js](https://nodejs.org/) installed on your system  

---

## 📦 Installation

1. Clone or download this repository.
2. Open a terminal in the project directory.
3. Install dependencies:

```bash
npm install
```
---
## ▶️ Running the App

Start the development server by running:

```bash
npm start
```
- The application will open in your default browser.
---

## 🛠️ Customization

Open `index.js` and update the following variables to personalize the generator:

```js
// 1. Your Name
let name = "Guil Hernandez"

// 2. Your Favorite Activity
let favoriteActivity = "kayaking"

// 3. Your Favorite Place
let favoritePlace = "florida keys"

// 4. AI Creativity Level (0 to 1)
let temperature = 1
```
Note:
You can replace avatar.jpg in the project folder with your own photo to appear as the author of the quote.

---
## 📂 Project Structure
```
├── index.html # Main HTML structure and Google Fonts
├── index.css # Custom styling and responsive layout
├── index.js # User configuration variables
├── utils.js # API logic, caching, and DOM manipulation
└── avatar.jpg # Author image (replaceable)
```


---

## 🔌 APIs Used

### Unsplash API
Retrieves random, high-quality images based on location keywords.

### OpenAI API
Generates poetic and satirical text via the Scrimba OpenAI proxy.



