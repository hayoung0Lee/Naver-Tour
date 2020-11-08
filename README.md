# Naver-Tour
https://flight.naver.com/flights/ 네이버 여행상품 사이트 리액트로 만들어보기!!

여행가고 싶은데 못가서 여행을 갈 수 있었다면 쓸수 있었던 웹사이트를 만들어 보겠습니다!! 노드는 아직 공부가 진행중이긴한데, 하면서 간단한 서버도 만들 수 있으면 좋겠지만, 그게 어렵다면 더미 데이터를 렌더링 하려구요


## NVM
nvm 을 이용해서 node 버전을 관리하고 있다. 지금 v10.6.0을 이용하고 있는데 노드 버전을 업데이트 하려고 한다. [nvm 사용법](https://jeonghwan-kim.github.io/2016/08/10/nvm.html)


## CRA
다음 프로젝트에서는 아예 초기 설정부터 다 해보려고 하는데, 이번엔 일단 cra로 시작하려고 한다. \
[참고자료](https://the-illusionist.me/77) \ 
나중엔 [이렇게](https://jeonghwan-kim.github.io/dev/2019/06/25/react-ts.html) 초기구성부터 해봐야지. 
`npx create-react-app toy-naver-tour`


## 프로젝트 진행 일지
[diary](diary/README.md)

### how to run
inside `toy-naver-tour`

`yarn start`: Starts the development server.

`yarn build`: Bundles the app into static files for production.

`yarn test`: Starts the test runner.

`yarn eject`: Removes this tool and copies build dependencies, configuration files
    and scripts into the app directory. If you do this, you can’t go back!

### 프로젝트 구조
리액트 프로젝트의 구조는 [김민태님의 프로젝트](https://codesandbox.io/s/ordermonitor04-n51jrkq2wl?file=/src/App.tsx)를 참고했다. 

## 사용할 open api
1. KAC: https://www.airport.co.kr/www/extra/openApi/liveScheduleList/layOut.do?cid=2015110913572092756&menuId=456
2. 호텔: https://www.data.go.kr/dataset/3076386/openapi.do

