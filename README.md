# Secrets Project (API Edition)

<img width="669" height="827" alt="image" src="https://github.com/user-attachments/assets/b7778a9d-6c11-4737-a551-b0c4fb84c38b" />


A simple web application that fetches and displays a random secret and its author from the [App Brewery Secrets API](https://secrets-api.appbrewery.com/). Built with Node.js, Express, and EJS.

---

## Features

- Fetches a random secret and username from a public API.
- Displays the secret and username on the home page.
- Handles API errors gracefully.
- Serves static files from the `public` directory.

---

## Technologies Used

- Node.js
- Express.js
- EJS (Embedded JavaScript templates)
- Axios

---

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/<your-github-username>/secrets-api-project.git
   cd secrets-api-project
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Start the server:**
   ```bash
   node index.js
   ```

4. **Open your browser and go to:**
   ```
   http://localhost:3000
   ```

---

## Folder Structure

```
secrets-api-project/
├── public/           # Static files (CSS, images, etc.)
├── views/            # EJS templates
│   └── index.ejs
├── index.js          # Main server file
├── package.json
└── README.md
```
