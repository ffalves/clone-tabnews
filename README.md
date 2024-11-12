# clone-tabnews


## About
This project is a study initiative aimed at developing a full clone of the TabNews website from scratch. The project is part of practical exercises from the curso.dev by [Felipe Deschamps](https://github.com/filipedeschamps), the original creator of TabNews.

*Inspiring in the README format from [LuizBarel](https://github.com/LuizBarel/clone-tabnews), I'll include notes about the course classes.*

**Technologies:**
- Next.js
- React
- Git and Github

**Key project files**
- files ending with "rc": contains "run commands" that are used to automate execution of specific commands within the project's scripts.
- `.nvmrc`: this file specifies the Node.js version to be used in the project, set here to `lts/hydrogen`.
- `lts`: stands for "long-term support"and indicates that this version will receive extended support and maintenance from the community.
- `package.json`: a key file containing metadata about the project, including the author's details, licence information, project description, and a list of dependencies (such as libraries and modules required for the project).
- in the `pages` folder, each `.js` or `.ts` file is interpreted as a page because it represents a public route. For example: `index.js` ---> `site.com`;  `about.js` ---> `site.com/about`.
- `export default Home` designates `Home` as the default function, allowing React to interpret `Home` as the `index` page.
- running `npm run dev` in the terminal executes the `dev` script (`"dev": "next dev"`) defined in `package.json`.
- to toggle port visibility (privacy to `public` or `private`) on `Ports`: right-click and select the desired option in Codespaces; or locally, it will be accessible via `localhost:3000`.
- to manually set the port: select the port icon at the bottom of the VSCode, and enter `3000` in the Port input field.
`



