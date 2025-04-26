# 👋<br/>Hi, developers ―<br/>Thank you for visiting to my profile

I'm Jiwoo So, a Front-end developer.

저는 프론트엔드 개발자, 소지우입니다.

### Some about me

< Work /> ―  


< Hobby /> ―    
I like to build custom keyboards and also develop various kinds of softwares.

< Status /> ―   
I'm recently studying English and Rust language. English is to contribute more in open source activities, and Rust language is just for my expansion in knowledge.

### Some technologies I work with

```json
{
  "frontend": ["html", "css", "javascript", "typescript", "react", "next.js"],
  "backend": ["javascript", "typescript", "node.js", "express"],
  "ops_alpha": ["linux", "docker", "github-actions", "jenkins", "ssh", "zsh", "git"],
  "hobby": ["rust"]
}
```

### My contact or portfolio

```typescript
import axios from "axios";

const getContactList = () => {
  return axios.get("https://api.jiwoo.so/contact");
};

(async () => {
  const { data: response } = await getContactList();
  console.log(response);
})();
```

#### Response

```console
{
  "blog": "https://jiwooproity.tistory.com/",
  "notion": "https://organized-jellyfish-19b.notion.site/1579598f11a14aa5bfc83c3606914732?pvs=4",
  "email": "jiwooproity@naver.com",
  "websites": [
    "https://www.jiwoo.so/",
    "https://bglovely.com/",
    "http://www.skinclouds.net/"
  ],
}
```

### ― See you again 🙌
