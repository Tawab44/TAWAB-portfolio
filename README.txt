Tawab portfolio
===============
Files: index.html, style.css, script.js, images/ (planet textures and shading)

Deploy (free): drag this whole folder onto Netlify Drop (app.netlify.com/drop),
or push it to GitHub Pages / Cloudflare Pages / Vercel.

Test on your computer: open a terminal in this folder and run
    python -m http.server 8000
then visit http://localhost:8000
(Do not double-click index.html: browsers block the 3D planets on file:// pages,
so you would only see the still fallback planets.)

Your own photos: put them in images/ (WebP or JPG; profile ~600x600, screenshots ~1280x800)
and use <img src="images/your-file.webp" alt="..." loading="lazy"> in index.html.
