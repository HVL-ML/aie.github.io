# Artificial Intelligence Engineering (AIE) website

## Overview

This repository contains the source code for the Artificial Intelligence Engineering (AIE) website. The site is built using Hugo, a fast and flexible static site generator, with the Beautiful Hugo theme.


## Getting Started

### Prerequisites

- Hugo (version 0.124.0 or higher)
- Git

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/your-username/aie.github.io.git
   cd aie.github.io
   ```

2. Install the theme as a submodule:
   ```
   git submodule add https://github.com/halogenica/beautifulhugo.git themes/beautifulhugo
   ```

3. Start the Hugo server:
   ```
   hugo server -D
   ```

4. Open your browser and navigate to `http://localhost:1313` to see the site.

## Customization

### Configuration

The main configuration file is `config.toml` in the root directory. Edit this file to change site-wide settings.

### Content

- Add new pages in the `content/` directory
- Create blog posts in the `content/post/` directory

### Layouts

Custom layouts can be added or modified in the `layouts/` directory.

### Static Files

Add images, CSS, JavaScript, and other static files to the `static/` directory.

## Deployment

The site is configured to deploy automatically to GitHub Pages when changes are pushed to the main branch. See the `.github/workflows/hugo.yml` file for the deployment configuration.

## Contributing

We welcome contributions to improve the AIE website. Please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/AmazingFeature`)
3. Make your changes
4. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
5. Push to the branch (`git push origin feature/AmazingFeature`)
6. Open a Pull Request

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

For questions or feedback, please contact Alexander S. Lundervold at allu@hvl.no.

## Acknowledgements

- [Hugo](https://gohugo.io/)
- [Beautiful Hugo Theme](https://github.com/halogenica/beautifulhugo)
- [Bootstrap](https://getbootstrap.com/)
- [Font Awesome](https://fontawesome.com/)