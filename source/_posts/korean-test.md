---
title: 한글 테스트용 포스트
date: 2016-12-06 17:26:39
tags:
---
## 안녕, Hexo
이 페이지는 Hexo 한글을 테스트해보기 위한 테스트페이지입니다.

## Source Highlighting
소스 코드는 다음과 같이 보입니다.

```javascript
import express from 'express';

const app = express();

const HOST = process.evn.HOST || 'localhost';
const PORT = process.env.PORT || 3000;

app.use('*', (req, res, next) => {
  //...
  next();
})

app.listen(HOST, PORT, () => `App running : ${HOST}:${POST}`);
```
