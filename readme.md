# 🎸**Guitar World** 🤘

## 📱 **Frontend** 💻

### **Description:**

Frontend of a guitars e-commerce project.
Users are required to register and log in to use the application.
Once logged in, they can view all the guitars, filter them by categories, add or remove them from their shopping cart and view the guitar details on a specific page.
There is an Admin role which can create, edit and delete the guitars.

The project was developed using [React Redux](https://react-redux.js.org/) with [Typescript](https://www.typescriptlang.org/).
Component testing was performed with [Jest](https://jestjs.io/).
First of all, the project design was created using [Figma](https://www.figma.com/) and then [Sass](https://sass-lang.com/) was used for the web style with CSS module methodology.
The media were stored in [Firebase](https://firebase.google.com/?hl=es) and finally, the app was deployed with [Netlify](https://www.netlify.com/).
<br>
<br>

<p align="left">
  <a href="https://developer.mozilla.org/en-US/">
    <img src="https://skillicons.dev/icons?i=ts,react,redux,figma,html,css,sass,jest,firebase,netlify"/>
  </a>
</p>

<br>
<br>

### **Data model:**

- **User:**

  - id: `string`
  - username: `string`
  - email: `string`
  - password: `string`
  - role: `string`
  - myGuitars: `Guitar[ ]`
    <br>
    <br>

- **Guitar:**
  - id: `string`
  - brand: `string`
  - modelGuitar: `string`
  - picture: `string`
  - style: `string`
  - material: `string`
  - price: `number`
  - description: `string`
    <br>
    <br>

### **How to use it:**

- Fork the project.
- Clone it to work in local.
- Install dependencies: `npm i`.
- Be sure the compilation is ok: `npm run build`.
- Start the project: `npm run start`.
- To run the tests: `npm test`.
- Enjoy it.
  <br>
  🥳

<br>
<br>

![guitar-world](https://t3.ftcdn.net/jpg/01/70/12/02/360_F_170120287_OqdsKQSUsa5ro0uCOMVEteoZkaMJQvue.webp)
