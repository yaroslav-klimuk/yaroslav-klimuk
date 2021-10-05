### Hey there <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="25px">

Hi, I'm Yaroslav, a Frontend developer. <br>
You can see my resume [here](https://clck.ru/XJESW). <br>
Ready to cooperate.

```javascript
class Developer {
  constructor(info) {
    this.name = info.name;
    this.type = info.type;
    this.email = info.email;
    this.telegram = info.telegram;
    this.skills = Object.assign(info.skills);
  }
}

const info = {
  name: 'Yaroslav',
  type: 'Frontend developer',
  email: 'yaroslavklimuk21@gmail.com',
  telegram: '@yaroslavklimuk',
  skills: {
    code: ['JavaScript', 'HTML', 'CSS', 'Sass/Scss', 'Bootstrap'],
    tools: ['Git', 'Github', 'Webpack'],
  },
};

const yk = new Developer(info);
```
