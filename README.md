<h1 align="center">
    <img  src="https://github.com/GabriellMatias/upfi-upload-images/assets/80908772/f7ec2989-ea05-4720-88b4-2cb472107404">
</h1>


<h4 align="center">
  Upload your images and gifs for the world to see!
</h4>
<p align="center">
  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/joao96/upfi-upload-images?style=flat-square">

  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/joao96/upfi-upload-images?style=flat-square">
<!--   <img alt="License" src="https://img.shields.io/github/license/joao96/upfi-upload-images?style=flat-square"> -->
</p>

<p align="center">
  <a href="#checkered_flag-technologies">Technologies</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#information_source-setup">Setup</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#sparkles-how-it-works">How It Works</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
<!--   <a href="#page_facing_up-license">License</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp; -->
  <a href="#get-in-touch-monocle_face">Get in touch</a>
</p>

## :checkered_flag: Technologies

- [Next JS](https://nextjs.org/)
- [ChakraUI](https://chakra-ui.com/)
- [Framer-Motion](https://www.framer.com/motion/)
- [FaunaDB](https://fauna.com/)
- [ImgBB](https://imgbb.com/)
- [React Query](https://react-query.tanstack.com/)
- [Yup](https://github.com/jquense/yup)
- [Jest](https://jestjs.io/)
- [testing-library](https://testing-library.com/)
- [VS Code][vc] with [EditorConfig][vceditconfig] and [ESLint][vceslint]

## :information_source: Setup

In order to run this application, it's required that you have [Git](https://git-scm.com), [Node.js v10.16][nodejs] or higher + [Yarn v1.13][yarn] or higher installed on your computer. From your command line:

**Step 1:** Clone this repo & run a `cd` into project's folder.

**Step 2:** install node modules as below:

```
npm install
```

if you prefer:

```
yarn
```

**Step 3:**

```
yarn dev
```

Once the server is up, go to http://localhost:3000/ and you should see something like this:

<p align="center">
  <img src="public/cover.png" alt="Initial page">
</p>

<!-- ## :page_facing_up: License

<a href="https://github.com/joao96/the-simplest-todo/blob/main/LICENSE">
    <img alt="License" src="https://img.shields.io/github/license/joao96/the-simplest-todo?style=flat-square">
</a>

<br />

This project is licensed under the MIT. -->

## :sparkles: How It Works

[FaunaDB](https://fauna.com/) and [ImgBB](https://imgbb.com/) are used to save the files (.jpeg, .png, .gif). [ChakraUI](https://chakra-ui.com/) made building the interface so much easier.

[Yup](https://github.com/jquense/yup) validates the form used to upload the files.

[nodejs]: https://nodejs.org/
[yarn]: https://yarnpkg.com/
[vc]: https://code.visualstudio.com/
[vceditconfig]: https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig
[vceslint]: https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint
