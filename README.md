# Webpage of Girlfriend

A fun and interactive webpage asking "Do you love me?" with playful responses.

## Features

- Interactive buttons for Yes/No responses
- Adorable GIFs from Tenor
- Playful animations with multiple "No" page variations
- Responsive design

## Project Structure

- `index.html` - Main landing page
- `yes.html` - "Yes" response page
- `no1.html`, `no2.html`, `no3.html` - Various "No" response pages
- `style.css` - Styling
- `script.js` - JavaScript functionality
- `vercel.json` - Vercel deployment configuration

## Deployment on Vercel

### Steps to Deploy:

1. **Create a Vercel Account**
   - Go to https://vercel.com
   - Sign up or log in

2. **Push to GitHub**
   ```bash
   cd "Webpage of Girlfriend"
   git init
   git add .
   git commit -m "Initial commit"
   git remote add origin <your-github-repo-url>
   git push -u origin main
   ```

3. **Deploy on Vercel**
   - Go to https://vercel.com/new
   - Select your GitHub repository
   - Click "Deploy"
   - Your site will be live in seconds!

## Local Development

Run locally with:
```bash
python3 -m http.server 8000
```

Then open http://localhost:8000 in your browser.

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Tenor API (for GIFs)

## License

MIT
