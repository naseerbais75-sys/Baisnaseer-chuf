# Bais Naseer — Website

## Files (sab ek hi folder me — koi subfolder nahi)
- `index.html` — main site
- `manager.html` — no-code tool: videos/products/links add-remove karne ke liye
- `data.json` — saara content (videos, products, links) yahan se load hota hai
- `logo.png`, `easypaisa.png`, `rc-worldcup2026.jpg` — images

## GitHub Pages pe daalna
1. GitHub repo banao, upar diye **saare files isi flat structure me** (koi folder banaye bina) upload/drag-drop karo
2. Repo → Settings → Pages → Branch select karke Save karo
3. Site live: `https://username.github.io/repo-name/`
4. Custom domain (baisnaseer.com) ke liye Settings → Pages → Custom domain me likho + registrar ki DNS me GitHub ke records daalo

## Naya video/product/link add karna
1. `manager.html` browser me kholo (double-click ya GitHub Pages pe host karke wahan se bhi khol sakte ho)
2. Form fill karo — image ka sirf **filename** likhna hai (jaise `product2.jpg`), koi folder path nahi
3. Wo image file bhi repo ke **root me** (isi folder me jahan `index.html` hai) upload kar do, exact wahi filename se
4. "Download data.json" dabao, GitHub pe purani `data.json` replace kar do (edit → paste → commit)
5. 30-60 second me site auto-update ho jaayegi

## Zaroori baat
- Har image **root folder me hi** honi chahiye — subfolder banane ki zaroorat nahi
- Filename me spaces ya special characters avoid karo (jaise `my photo.jpg` ki jagah `my-photo.jpg`)
