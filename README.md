# 3D Portfolio

## 🌐 Live Demo



## 📝 Description

**3D Portfolio** is a well-designed and fully functional portfolio website built with React.js and Three.js. It is a fully responsive website that works well on all devices.

<details><summary><b>Folder Structure</b></summary>

```bash
reactjs18-3d-portfolio/
├── src/
├   ├── App.tsx
├   ├── globals.css
├   ├── main.tsx
├   ├── vite.env.d.ts
├   ├── components/
├   ├   ├── atoms/
├   ├   ├   └── Header.tsx
├   ├   ├── canvas/
├   ├   ├   ├── Ball.tsx
├   ├   ├   ├── Computers.tsx
├   ├   ├   ├── Earth.tsx
├   ├   ├   ├── Stars.tsx
├   ├   ├   └── index.ts
├   ├   ├── layout/
├   ├   ├   ├── Loader.tsx
├   ├   ├   └── Navbar.tsx
├   ├   ├── sections/
├   ├   ├   ├── About.tsx
├   ├   ├   ├── Contact.tsx
├   ├   ├   ├── Experience.tsx
├   ├   ├   ├── Feedbacks.tsx
├   ├   ├   ├── Hero.tsx
├   ├   ├   ├── Tech.tsx
├   ├   ├   ├── Works.tsx
├   ├   ├   └── page.tsx
├   ├   └── index.ts
├   ├── constants/
├   ├   ├── config.ts
├   ├   ├── styles.ts
├   ├   └── index.ts
├   ├── hoc/
├   ├   ├── SectionWrapper.tsx
├   ├   └── index.ts
├   ├── utils/
├   ├   └── motion.ts
├   ├── types/
├   ├   └── index.d.ts
├   └── assets/
├       ├── company/
├       ├── tech/
├       └── index.ts
├── public/
├   ├── desktop_pc/
├   ├   ├── textures/
├   ├   ├── license.txt
├   ├   ├── scene.bin
├   ├   └── scene.gltf
├   ├── planet/
├   ├   ├── textures/
├   ├   ├── license.txt
├   ├   ├── scene.bin
├   ├   └── scene.gltf
├   ├── logo.png
├   └── logo.svg
├── .env
├── .eslintignore
├── .eslintrc.cjs
├── .gitignore
├── .prettierignore
├── .prettierrc.cjs
├── index.html
├── LICENSE
├── README.md
├── package.json
├── postcss.config.cjs
├── tailwind.config.cjs
├── tsconfig.json
├── tsconfig.node.json
└── vite.config.js
```

</details>

## 📖 Table of Contents

<details><summary>Table of Contents</summary>

- [Live Demo](#-live-demo)
- [Description](#-description)
- [Technologies Used](#-technologies-used)
- [Get Started](#-get-started)
  - [Prerequisites](#-prerequisites)
  - [Installation and Run Locally](#-installation-and-run-locally)
  - [Scripts](#-scripts)
- [Environment Variables](#-environment-variables)
- [Deployment](#-deployment)
- [Contributing](#-contributing)
- [Acknowledgements](#-acknowledgements)
- [Contact](#-contact)
- [License](#-license)

</details>

## ✨ Technologies Used

<details><summary><b>3D Portfolio</b> is built using the following technologies:</summary>

- [TypeScript](https://www.typescriptlang.org/): A typed superset of JavaScript that compiles to plain JavaScript.
- [Vite](https://vitejs.dev/): A build tool providing a faster and leaner development experience for modern web projects.
- [React.js](https://reactjs.org/): A free and open-source front-end JavaScript library for building user interfaces.
- [Three.js](https://threejs.org/): A cross-browser JavaScript library for creating and displaying animated 3D graphics in a web browser using WebGL.
- [Framer Motion](https://www.framer.com/motion/): A production-ready motion library for React.
- [Tailwind CSS](https://tailwindcss.com/): A utility-first CSS framework for rapidly building custom user interfaces.
- [ESLint](https://eslint.org/): A static code analysis tool for identifying problematic patterns in JavaScript code.
- [Prettier](https://prettier.io/): An opinionated code formatter.
- [Vercel](https://vercel.com/): A cloud platform for frontend developers.

</details>

## 🧰 Get Started

To get this project up and running in your development environment, follow these step-by-step instructions.

### 📋 Prerequisites

You will need the following installed on your local machine:

- [Node.js](https://nodejs.org/en/)
- [NPM](https://www.npmjs.com/get-npm)
- [Git](https://git-scm.com/downloads)

### ⚙️ Installation and Run Locally

**Step 0:**

This application uses EmailJS to send emails from the client side. Create an [EmailJS account](https://emailjs.com/) and set the following environment variables in a `.env` file.

**Step 1:** Clone the repository:

```bash
git clone https://github.com/saikatkumar421/reactjs18-3d-portfolio.git
```

**Step 2:** Install dependencies:

```bash
npm install
```

**Step 3:** Start the development server:

```bash
npm run dev
```

**Step 4:** Open [http://localhost:5173](http://localhost:5173) in your browser.

### 📜 Scripts

| Script             | Action                                      |
| :----------------- | :------------------------------------------ |
| `npm install`      | Installs dependencies                       |
| `npm run dev`      | Starts local dev server at `localhost:5173` |
| `npm run build`    | Builds your production site to `./dist/`    |
| `npm run preview`  | Boots up a local static web server          |
| `npm run lint`     | Runs ESLint                                 |
| `npm run ts:check` | Performs TypeScript type-checking           |

## 🔒 Environment Variables

Create a `.env` file in the root directory and add the following:

```env
VITE_EMAILJS_SERVICE_ID=<VITE_EMAILJS_SERVICE_ID>
VITE_EMAILJS_TEMPLATE_ID=<VITE_EMAILJS_TEMPLATE_ID>
VITE_EMAIL_JS_ACCESS_TOKEN=<VITE_EMAIL_JS_ACCESS_TOKEN>
```

## 🚀 Deployment

**Build for production:**

```bash
npm run build
```


## 🔧 Contributing

Contributions are greatly appreciated! To fix a bug or enhance an existing module:

1. Fork the repo
2. Create a new branch (`git checkout -b improve-feature`)
3. Make the appropriate changes
4. Commit your changes (`git commit -am 'Improve feature'`)
5. Push to the branch (`git push origin improve-feature`)
6. Create a Pull Request 🎉

## 💎 Acknowledgements

- [Tailwind CSS](https://tailwindcss.com/)
- [Three.js](https://threejs.org/)
- [Framer Motion](https://www.framer.com/motion/)
- [React Vertical Timeline Component](https://www.npmjs.com/package/react-vertical-timeline-component)
- [React Parallax Tilt](https://www.npmjs.com/package/react-parallax-tilt)
- [Maath](https://www.npmjs.com/package/maath)
- [EmailJS](https://www.emailjs.com/)
- [JavaScript Mastery](https://www.jsmastery.pro/)

## 📞 Contact

**Saikat Mondal**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Saikat%20Mondal-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/saikatkumar421/)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-%2B8801954355330-25D366?style=flat&logo=whatsapp&logoColor=white)](https://wa.me/8801954355330)

## 📋 License

This project is open source software licensed under Saikat
