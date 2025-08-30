# Decorom - Custom Decorative Signage

A responsive website showcasing a collection of custom decorative signage products including stainless steel letters, acrylic designs, and unique shapes with backlighting options.

## Features

- Responsive product gallery
- Product filtering by material, shape, and size
- Detailed product information including:
  - Material specifications
  - Dimensions
  - Product descriptions
  - High-quality product images

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Bootstrap (for responsive design)

## Project Structure

```
decorom/
├── main.html
└── images/
    ├── Product images (1-61)
    └── Other assets
```

## How to Run Locally

1. Clone this repository
2. Open `main.html` in a web browser

## Hosting on GitHub Pages

To host this website on GitHub Pages:

1. Create a new repository on GitHub
2. Rename `main.html` to `index.html`
3. Push your code to the repository:
   ```bash
   git init
   git add README.md
   git add images
   git add index.html
   git commit -m "first commit"
   git branch -M main
   git remote add origin https://github.com/Kp2340/Decorom.git
   git push -u origin main
   ```
4. Go to repository Settings > Pages
5. Under "Source", select "main" branch
6. Click Save

Your site will be published at `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME`

## Connecting Custom Domain

To connect your custom domain:

1. Go to repository Settings > Pages
2. Under "Custom domain", enter your domain name
3. Add these DNS records at your domain registrar:
   - Type: A
   - Name: @
   - Value: 185.199.108.153
   - Value: 185.199.109.153
   - Value: 185.199.110.153
   - Value: 185.199.111.153

   If using www subdomain:
   - Type: CNAME
   - Name: www
   - Value: YOUR_USERNAME.github.io

4. Wait for DNS propagation (can take up to 24 hours)

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

Your Name - your.email@example.com
Project Link: [https://github.com/YOUR_USERNAME/YOUR_REPO_NAME](https://github.com/YOUR_USERNAME/YOUR_REPO_NAME)
