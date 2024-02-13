<h1 align="center">Hi 👋, I'm woojin</h1>
<h3 align="center">A passionate backend developer from south-korea</h3>

- 📫 How to reach me **ujins8201@gmail.com**

<h3 align="left">Connect with me:</h3>
<p align="left">
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://aws.amazon.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="aws" width="40" height="40"/> </a> <a href="https://expressjs.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original-wordmark.svg" alt="express" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a> <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a> <a href="https://nodejs.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40"/> </a> <a href="https://www.typescriptlang.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="typescript" width="40" height="40"/> </a> </p>

```javascript

POST,

JSON
{
  "name": "woojin",
  "age": "25"
}

router.post('/', async (req, res, next) => {
  try {
    const { name, age } = req.body;

    console.log(`Name: ${name}, Age: ${age}`);

    return res.status(200).json({ message: " Done. " });
  } catch (err) {
    next(err);
  }
});

```

```typescript

POST,

JSON
{
  "name": "woojin",
  "age": "25"
}

interface UserData {
  name: string;
  age: string;
}

router.post("/", async (req, res, next) => {
  try {
    const { name, age }: UserData = req.body;

    console.log(`Name: ${name}, Age: ${age}`);

    return res.status(200).json({ message: " Done. " });
  } catch (err) {
    next(err);
  }
});

```

<p><img align="left" src="https://github-readme-stats.vercel.app/api/top-langs?username=woojinnnnnnn&show_icons=true&locale=en&layout=compact" alt="woojinnnnnnn" /></p>

