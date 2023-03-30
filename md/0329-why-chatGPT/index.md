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
# GitHub Copilot과 Chat GPT가 <br> 개발자의 성장을 방해한다?

[https://jojoldu.tistory.com/709](https://jojoldu.tistory.com/709) 로부터 영감을 받아 작성한 글입니다.

---

# 의도적으로 IDE의 자동완성을 사용하지 않고, 코드를 작성해보자
## IDE의 자동완성은 개발자의 성장을 방해한다

* 대부분의 개발자들은 위 생각에 동의하지 않을 것이다. 그럼에도 위와 같은 조언이 나오는 이유는 무엇일까?
    * 아는데 편리하게 쓰는 것과 모르는데 기능에만 의존해서 쓰는 것은 천지 차이이기 때문에, 초보 개발자들이 IDE의 기능에 의존하여 코딩을 하게 되면, 그들은 개발자로서의 성장을 하지 못한다는 데에서 출발한다.
    * 그럼에도 불구하고, 요즘에는 IDE의 사용을 권장하는 추세다.
    진짜 개발자라면, 코드를 작성하는 것보다 비지니스 로직과 아키텍처, 데이터 구조 등을 고민하는 것이 더 중요하기 때문에 코드의 작성은 IDE에게 맡기는 것이다.

---
## 코파일럿과 Chat GPT는 개발자의 성장을 방해할까?
* IDE의 자동완성 기능이 개발자의 성장을 방해한다고 생각했던 시기가 있었던 것처럼, 코파일럿과 Chat GPT도 현재 그런 시기가 아닐까?
* 개발은 GitHub Copilot과 Chat GPT에게 맡기고,<br>이제 우리 **개발자**들은 어떤 문제를 해결해야하는지 **문제를 정의**하고, 인공 지능이 제시하는 여러 해결 방법들을 **어떻게 활용**할 것인지를 고민하는 것이 더 중요해졌다.
* 코파일럿과 Chat GPT가 개발자의 성장을 방해할까 두려워하기보다, **얼마나 더 멋진 일을**, **얼마나 더 생산성있게** 해낼 것인가 하는 것에 집중해야한다.

---
# 전설의 팡션좌
![width:500px](./팡션좌.webp)
너무 엑셀 팡션? 사용하지 마세요
너무 IDE? 사용하지 마세요
너무 ChatGPT? 사용하지 마세요