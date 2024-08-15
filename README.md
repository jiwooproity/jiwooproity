# 👋<br/>Hi, developers ―<br/>Thank you for visiting to my profile

My name is So Jiwoo as a Front-end developer.

제 이름은 소지우이며, 프론트엔드 개발자입니다.

### Some about me

< Work /> : I'm currently working as a Front-end developer at Dejay.

< Hobby /> : I like assemble custom keyboard, and develop some software.

< Status /> : Recently, I am studying English for open source contribution activities and learning rust language

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
