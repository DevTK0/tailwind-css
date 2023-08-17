# Tailwind CSS

`start": "npx tailwindcss build styles.css -o _tailwind.css`  
`minify": "postcss _tailwind.css > _tailwind.min.css`  

This repo disables the tree shaking in Tailwind in order to generate a full stylesheet.
Alternatively, you can just download the generated stylesheet in this repo. (_tailwind.css or _tailwind.min.css)

Includes
- "@tailwindcss/typography"

If you need any additional tailwind plugins, modify tailwind.config.js