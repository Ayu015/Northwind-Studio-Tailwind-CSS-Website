# Northwind Studio – Tailwind CSS Website

A responsive, single-page creative studio website built with **HTML** and **Tailwind CSS v4**. The page presents a fictional creative studio, its services, selected work, and a contact form.

## Preview

The website includes these sections:

- **Home:** Hero section introducing Northwind Studio with calls to action.
- **About:** Studio introduction and project/client/experience highlights.
- **Services:** Branding, web design, and photography service cards.
- **Work:** A gallery featuring Coffee Corner, GreenLeaf Market, and Skyline Events.
- **Contact:** A contact form UI with name, email, and message fields.
- **Footer:** Displays the current year automatically.

## Built With

- HTML5
- Tailwind CSS v4
- JavaScript (for the mobile navigation menu and dynamic footer year)

## Project Structure

```text
website using tailwind/
├── images/
│   ├── about-us.jpg
│   ├── coffee.jpg
│   ├── green-leaf.jpg
│   └── skyline.png
├── index.html
├── main.css
├── output.css
├── package.json
└── package-lock.json
```

## Run Locally

### 1. Clone the repository

```bash
git clone YOUR_REPOSITORY_URL
```

### 2. Open the project directory

```bash
cd "website using tailwind"
```

### 3. Install dependencies

Make sure Node.js and npm are installed, then run:

```bash
npm install
```

### 4. Start the Tailwind CSS watcher

```bash
npx @tailwindcss/cli -i ./main.css -o ./output.css --watch
```

Keep this terminal running while you work so Tailwind can rebuild the CSS when files change.

### 5. View the website

Open `index.html` in your browser, or use the VS Code Live Server extension.

## Notes

- The HTML links to the generated stylesheet `output.css`.
- `main.css` is the Tailwind CSS entry file and imports Tailwind with `@import "tailwindcss";`.
- The mobile navigation menu is toggled with JavaScript.
- The contact form is a front-end demonstration only. It does not send or store messages because no backend or form service is connected.
- Do not commit the `node_modules/` folder. It can be recreated using `npm install`.

## Author

**Ayush Singh**

GitHub: [@Ayu015](https://github.com/Ayu015)
