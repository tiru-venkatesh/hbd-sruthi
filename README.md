# Happy Birthday, Sruthi

Static site (no build step): `index.html` + `assets/music.mp3`.

## Deploy on Vercel
1. Push this folder to a new GitHub repo (index.html at the repo root).
2. vercel.com > Add New > Project > import the repo.
3. Framework Preset: **Other**. Leave build command and output directory empty. Click Deploy.

Or with the CLI: `npx vercel --prod` inside this folder.

## Add photos
Put images in `assets/` (1.jpg ... 6.jpg), then in index.html change
`var PHOTOS=[]` to `var PHOTOS=['assets/1.jpg','assets/2.jpg','assets/3.jpg','assets/4.jpg','assets/5.jpg','assets/6.jpg']`
