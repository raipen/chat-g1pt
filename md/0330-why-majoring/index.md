---
theme: default
size: 4:3
class:
   - invert
paginate: true
_paginate: false
marp: true
style: |
   section.center {
      text-align: center;
      border: none;
      word-break: keep-all;
      padding: 0 200px;
   }
   section.center::before {
      content: "";
      position: absolute;
      top: 0;
      left: 50%;
      transform: translateX(-50%);
      width: 690px;
      height: 690px;
      border: 5px solid white;
      margin: 10px;
   }
   section.center h1 {
      font-size: 2em;
   }
   section {
      word-break: keep-all;
   }
   section::before {
      content: "";
      position: absolute;
      top: 0;
      left: 0;
      width: calc(100% - 30px);
      height: calc(100% - 30px);
      border: 5px solid white;
      margin: 10px;
   }
   li li{
      font-size: 0.8em;
   }
   strong {
      border-bottom: 1px solid white;
   }
---
<!-- _class: center invert-->
# 마크다운으로 인스타 게시물 만들기
---
