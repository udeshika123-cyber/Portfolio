# Personal Portfolio

This is a responsive personal portfolio website built with HTML, CSS, and JavaScript.

## Features

- Animated text introduction
- Responsive navigation bar with sticky and mobile menu support
- Animated skill bars and circular skill indicators
- Portfolio section with filterable projects (using MixItUp)
- Contact form (static)
- Animated scroll effects
- Modern, neon-inspired design

## Project Structure

```
index.html
style.css
style.js
mixitup.min.js
img/
```

- **index.html**: Main HTML file containing all sections (Home, About, Services, Skills, Portfolio, Contact, Footer).
- **style.css**: All styles for layout, animations, and responsiveness.
- **style.js**: Handles text animation, skills animation, menu toggling, sticky header, scroll effects, and MixItUp initialization.
- **mixitup.min.js**: Library for filtering portfolio items.
- **img/**: Folder containing all images used in the site.

## How to Use

1. Clone or download this repository.
2. Open `index.html` in your browser to view the portfolio.
3. To customize, replace images in the `img/` folder and update content in `index.html`.

## Customization

- **Colors & Fonts**: Change CSS variables in `style.css` under `:root`.
- **Skills & Projects**: Edit the relevant sections in `index.html`.
- **Animations**: Modify or add CSS keyframes in `style.css` as needed.

## Dependencies

- [Boxicons](https://boxicons.com/) for icons (loaded via CDN in `index.html`)
- [MixItUp](https://www.kunkalabs.com/mixitup/) for portfolio filtering (`mixitup.min.js`)

## License

This project is for personal and educational use.