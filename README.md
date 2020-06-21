<!-- PROJECT LOGO -->
<br />
<p align="center">
  <h1 align="center">Developer's Portfolio ✨</h1>

  <p align="center">
    It is a personal static website/portfolio template hosted with GitHub Pages, built to showcase my recent projects. Site URL / Demo: 
    <a href="https://souravmondaldev.me">souravmondaldev.me</a>
    <br />
    <br />
    <a href="https://souravmondaldev.me">About Me</a>
    ·
    <a href="https://github.com/souravmondaldev/souravmondaldev.github.io/issues">Report Bug</a>
    ·
    <a href="https://github.com/souravmondaldev/souravmondaldev.github.io/issues">Request Feature</a>
  </p>
</p>

![GitHub contributors](https://img.shields.io/github/contributors/souravmondaldev/souravmondaldev.github.io?color=ffcc66&style=for-the-badge)
![GitHub stars](https://img.shields.io/github/stars/souravmondaldev/souravmondaldev.github.io?color=ffcc66&style=for-the-badge)
<img style="padding:10px;" src="https://img.shields.io/github/forks/souravmondaldev/souravmondaldev.github.io?label=Forks&style=flat-square">
<img style="padding:10px;" src="https://img.shields.io/github/languages/count/souravmondaldev/souravmondaldev.github.io?style=flat-square">
[![Twitter Follow](https://img.shields.io/twitter/follow/souravmondaldev?color=ffcc66&logo=twitter&logoColor=ffffff&style=for-the-badge)](https://twitter.com/souravmondaldev)
<img style="padding:10px;" src="https://img.shields.io/badge/Open%20Source-💕%20-9cf?style=for-the-badge"><br>
[![Site preview](/SouravMondalDEV.png)](https://souravmondaldev.me/)

## Table of Contents

- [Technology Stack 🛠️](#technology-stack-)
- [Structure ⚓](#structure-)
- [Sharing 💗](#sharing-)
- [Prerequisites 🍪](#prerequisites-)
- [Setup And Deployment 🔧](#setup-and-deployment-)
- [Contributing 🙌](#contributing-)

## Technology Stack 🛠️

Dependencies defined in package.json:

[Reactjs](https://reactjs.org/)
| [Bootstrap](https://getbootstrap.com/)
| [Typist](https://github.com/jstejada/react-typist)
| [GitHub API](https://developer.github.com/v3/repos/)
| [Instagram API](https://www.instagram.com/developer/embedding/)

## Structure ⚓

- Navigation bar (optional)
- Blog (optional)
- Body
  - Name | Profession
  - Contact / Follow / Find me / Facebook / LinkedIn / GitHub / Instagram / Email / CodePen
  - Resume | About me
- About Me
  - Display picture (using Instagram API) (optional)
  - About myself, my Interests, Goals and Hobbies
  - Things I'm good at (Skills)
- Recent Projects (using GitHub API) (optional)
- Footer
  - Acknowledgements (contributors)
  - Copyrights - open source
  - (quote: Dream big, Think big)

## Sharing 💗

Project is open source. Feel free to make your own version. All you need to do is to fork this repository, edit [src/editable-stuff/configurations.json](./src/editable-stuff/configurations.json) and add resume. Mark star ⭐ if you like the project.

## Prerequisites 🍪

You should have [Node.js](https://nodejs.org/en/) and [Git](https://git-scm.com/) installed on your PC. You should also own a GitHub account.

## Setup And Deployment 🔧

1. To Get Started, Fork this repository to your GitHub account:
2. Clone the forked repo from your account using:

   ```bash
     git clone https://github.com/<your-username>/home.git
   ```

3. Open in editor and edit [src/editable-stuff/configurations.json](./src/editable-stuff/configurations.json) file.

4. Add your resume as <resume.pdf> in place of [src/editable-stuff/resume.pdf](./src/editable-stuff/)
5. Change URL in [package.json](./package.json) file:

   ```json
   "homepage": "https://<your-username>.github.io/home"
   ```

   Or for custom deployment, refer [create-react-app.dev](https://create-react-app.dev/docs/deployment/)

6. Edit [title](./public/index.html#L34) and meta [description](./public/index.html#L13) in [public/index.html](./public/index.html).

7. After editing run the following bash commands:

   ```bash
   npm install
   npm start
   ```

8. To deploy website run:

   ```bash
    npm run build
    npm run deploy
   ```

   Or for custom deployment, refer [pages.js](./pages.js)

   ```bash
    npm run build
    npm run custom-deploy
   ```

9. Congrats your site is up and running. To see it live, visit:

   ```https
     https://<your-username>.github.io/
   ```

Facing issues? Feel free to contact at souravmondaldev.cs@gmail.com.

## Contributing 🙌

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
Thanks to [@shoaeb] (https://github.com/hashirshoaeb)
