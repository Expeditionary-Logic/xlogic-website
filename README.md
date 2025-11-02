# Expeditionary Logic Website

A simple, clean website for Expeditionary Logic, hosted on GitHub Pages.

## Structure

- `index.html` - Homepage with company philosophy
- `sponge.html` - Product page for Sponge Apple Watch app
- `style.css` - Styles for the entire website

## Deploying to GitHub Pages

1. Create a new repository on GitHub (e.g., `expeditionarylogic.com` or `username.github.io`)

2. Initialize git and push your code:
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Expeditionary Logic website"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
   git push -u origin main
   ```

3. Enable GitHub Pages:
   - Go to your repository Settings
   - Navigate to "Pages" in the left sidebar
   - Under "Source", select "main" branch and "/ (root)" folder
   - Click Save

4. Set up custom domain (expeditionarylogic.com):
   - In the GitHub Pages settings, enter `expeditionarylogic.com` in the "Custom domain" field
   - Add a CNAME file to your repository (GitHub may create this automatically)
   - Configure your DNS with your domain registrar:
     - Add an A record pointing to GitHub Pages IP addresses:
       - 185.199.108.153
       - 185.199.109.153
       - 185.199.110.153
       - 185.199.111.153
     - Or add a CNAME record pointing to `YOUR_USERNAME.github.io`

## Updating the Sponge Product Page

To add more details about the Sponge app later, edit `sponge.html` and update:
- Features section
- Add screenshots or demo videos
- Update the CTA section with App Store link when available

## Local Development

Simply open `index.html` in your web browser to view the site locally.
