# Astrolink: Template to share about yourself

```sh
git clone https://github.com/alamguardin/Astrolink.git
```


![Preview](/src/assets/screenshot-app.png)

## 🚀 How to change the content?

To change the content of the templates, simply locate the ```user.json``` file inside the data folder. You can change the name, profession, and the links you want.

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── assets/
│   │   └── screenshot-app.png
│   │   └── user-profile-image.png
│   ├── components/
│   │   └── icons/
│   │   └── Link.astro
│   │   └── List.astro
│   │   └── Profile.astro
│   │   └── Shadow.astro
│   ├── data/
│   │   └── user.json
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```

Oh, additionally, you have the entire iconography of [Remixicons](https://remixicon.com/) available. You just need to write the name of the icon within the ```"icon"``` key of each link in the ```user.json``` file.



## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |
