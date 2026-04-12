# Personal Academic Website

Personal website built using jemdoc, styled after Cong Ma's website.

## Local Development

### Prerequisites
- Python 3.x

### Building the Website

1. Compile all jemdoc files to HTML:
   ```bash
   python build.py
   ```

2. Or compile individual files:
   ```bash
   python jemdoc.py index.jemdoc
   python jemdoc.py paper.jemdoc
   python jemdoc.py activity.jemdoc
   python jemdoc.py education.jemdoc
   ```

### Preview Locally

You can preview the website using Python's built-in HTTP server:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000` in your browser.

## File Structure

- `*.jemdoc` - Source files (edit these)
- `*.html` - Generated HTML files (auto-generated, can be committed for GitHub Pages)
- `jemdoc.css` - Stylesheet
- `MENU` - Navigation menu definition
- `figure/` - Images directory
- `Publication/` - PDFs and slides (optional)

## Deployment to GitHub Pages

1. Commit all files (including generated HTML) to your repository
2. Make the repository public
3. Enable GitHub Pages in repository settings (Settings > Pages > Source: main branch)
4. Your site will be available at `https://boxinz17.github.io/`

## Customization

- Edit `.jemdoc` files to update content
- Modify `MENU` to change navigation
- Customize `jemdoc.css` for styling changes
- Add images to `figure/` directory
- Add publications PDFs to `Publication/` directory (optional)

