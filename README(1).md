# Tour & Travel Website

A responsive, single-page website for a tour and travel agency. It lists adventure ideas and popular holiday packages across India and gives visitors a contact form to enquire.

Built with HTML5, CSS3 and JavaScript.

<!-- Replace the file name below with an image from your screenshot/ folder -->
![Home page screenshot](screenshot/home.png)

## Features

- **Hero section** with a call to action that scrolls to the adventures section
- **Navigation bar** with links to Home, Adventures, Packages and Contact, plus a menu button for small screens
- **Search bar** that opens from the header
- **Adventure Ideas** cards for bungee jumping, zip lines and canoeing, each with a "read more" link
- **Popular Packages** cards for Manali, Goa, Delhi, Jaipur, Kerala and Darjeeling, each with a short description and a price range
- **Contact form** with name, email, phone, subject and message fields
- **Footer** with quick links, contact details and social links
- **Back to top** button
- Font Awesome and Iconscout icons

## Tech Stack

| Part | Technology |
|---|---|
| Markup | HTML5 |
| Styling | CSS3 |
| Interactivity | JavaScript |
| Icons | Font Awesome 6, Iconscout Unicons |

## Project Structure

```
Tour-project_guide/
├── css/
│   └── style.css
├── images/          # hero, adventure and package images
├── js/
│   └── script.js
├── screenshot/      # preview images
└── index.html
```

## Getting Started

1. Clone the repository

   ```bash
   git clone https://github.com/vishesh1603/Tour-project_guide.git
   ```

2. Open the folder

   ```bash
   cd Tour-project_guide
   ```

3. Open `index.html` in any browser. No build step or install is needed.

An internet connection is required the first time so the icon libraries load from their CDNs.

## Contact Form

The form sends a `POST` request to `contact_us.php`. That PHP file is not part of this repository, so the form will not store or send messages until you add a backend. To use it locally, run the project under PHP with MySQL (for example with XAMPP) and add your own `contact_us.php`.

## Customizing

- Change the package names, descriptions and prices in the `packages` section of `index.html`
- Replace the images in `images/` with your own, keeping the same file names
- Update the footer phone, email and social links in the `footer` section of `index.html`
- Adjust colors and layout in `css/style.css`

## Author

**Vishesh Chaturvedi**
[GitHub](https://github.com/vishesh1603) | [LinkedIn](https://www.linkedin.com/in/vishesh-chaturvedi1603)
