# 🎸 Band Generator Project

A lightweight **Node.js + Express** application that generates fun, random band names by combining a random **adjective** and **noun**. The app uses **EJS** for templating and serves static assets from the `public/` directory.

---

## 📌 Features

- 🎲 **Random Band Name Generation**  
  Click a button to generate a new band name (adjective + noun).

- 🧩 **EJS Templating**  
  Uses EJS views with reusable header and footer partials.

- 🎨 **Static Assets Support**  
  CSS and client-side files are served from the `public/` folder.

---

## 🛠 Tech Stack

- **Runtime:** Node.js  
- **Framework:** Express  
- **Middleware:** body-parser  
- **Templating Engine:** EJS  

---

## 📂 Project Structure

band-generator/
│
├── index.js # Express app setup and routes
├── views/ # EJS templates
│ ├── index.ejs
│ └── partials/ # Header and footer partials
│
├── public/ # CSS and static assets
│
├── package.json
└── README.md


---

## ⚙️ Installation

Install the required dependencies:

```bash
npm install
▶️ Running the Application

Start the server:

node index.js


Or run using nodemon for development:

nodemon index.js

🌐 Open in Browser

After starting the server, open:

http://localhost:3000

🧪 Usage

Open the home page.

Click Generate Name.

A random band name (adjective + noun) will be generated.

The result is rendered dynamically in index.ejs.

✏️ Customization

To customize the generated band names:

Open index.js

Edit the adjective and noun arrays

Add or remove words as needed
