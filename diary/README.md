## Assets
여기는 내가 이 프로젝트를 하면서 공부한 내용을 정리하는 곳

## 프로젝트 기본 구조 세팅
1. Typescript? Javascript?
타입스크립트로 하려고 하다가, 이번에는 자바스크립트로 한다음, 리액트 프로젝트가 좀더 익숙해지면 타입스크립트로도 프로젝트를 해보려고 한다!!
이번에 리액트가 17버전으로 업데이트 되면서 각 컴포넌트에서
`import React, { Component } from 'react'; ` 안해도 된다. 
이걸 했던 이유는 바벨에서 트랜스 파일링할때, React.createElement 를 이용하기 때문인데, 이제 필요없다고 한다. 

2. Eslint 와 Prettier
Eslint는 코드 품질, Prettier는 코드 스타일을 정돈 해주는 것으로 둘다 서로를 보완하며 사용한다. [블로그 글](https://velog.io/@hwang-eunji/CRA-%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8%EC%97%90-ESLint-Prettier-%EC%B6%94%EA%B0%80%ED%95%98%EA%B8%B0)

가장 했갈렸던 부분은 eslint도 뭔가 포매팅을 해서 도대체 Prettier는 왜쓰는가 했는데, Prettier가 포매팅에 더 특화 되있어서 eslint와 prettier를 같이 쓸때는 
Eslint에서 포매터 기능을 꺼야한다고 한다. 


[제일 설명 자세히 되어있는 글](https://velog.io/@gwangsuda/2019-09-25-1009-%EC%9E%91%EC%84%B1%EB%90%A8-bwk0ylejxj)
cra를 통해서 프로젝트를 생성하면 eslint가 이미 함께 오는데, 이것만 사용하면 cli를 통해서만 eslint가 발견하는 오류를 찾을 수 가 있다. 
그런데 vs code에디터에서 이에 대해서 바로바로 보고 싶으면 eslint extention을 설치해야한다. 

[통합 방법](https://jeonghwan-kim.github.io/series/2019/12/30/frontend-dev-env-lint.html#:~:text=eslint%2Dconfig%2Dprettier%20%EB%8A%94%20%ED%94%84%EB%A6%AC,%EC%9D%B4%20%EC%B6%A9%EB%8F%8C%ED%95%98%EA%B8%B0%20%EB%95%8C%EB%AC%B8%EC%9D%B4%EB%8B%A4.&text=%EC%84%A4%EC%A0%95%ED%8C%8C%EC%9D%BC%EC%9D%98%20extends%20%EB%B0%B0%EC%97%B4%EC%97%90%20%EC%B6%94%EA%B0%80%ED%95%9C%EB%8B%A4.)

[eslit + prettier](https://eomtttttt-develop.tistory.com/223)

[영상](https://www.youtube.com/watch?v=bfyI9yl3qfE&ab_channel=Manorisms)

eslint, prettier 설정은 아직도 좀 익숙하진 않다. 다음 기회에 제대로 다시 해봐야겠다. 
요약하자면, eslint는 코드 품질, 프리티어는 코드 스타일 포매팅인데, 익스텐션을 통해서 이를 더 관리하기 좋게 하고있고, 플러그인을 통해서 두개를 연동해서 사용가능하다. 


3. 폴더 구조 생성하기

4. 기본적인 마크업 생성

5. redux, redux-saga 개념 정리

6. 마무리