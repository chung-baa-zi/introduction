# 2022년 영남대학교 소프트웨어공학

# 청-바지 모바일 미니 게임

## 소스코드 및 발표영상

[<img src="https://img.shields.io/badge/클라이언트-181717?style=for-the-badge&logo=github&logoColor=white">](https://github.com/chung-baa-zi/bluejeanfront)
[<img src="https://img.shields.io/badge/서버-181717?style=for-the-badge&logo=github&logoColor=white">](https://github.com/chung-baa-zi/backend)
[<img src="https://img.shields.io/badge/발표영상-FF0000?style=for-the-badge&logo=youtube&logoColor=white">](https://www.youtube.com/watch?v=vQYdbG4Fylc)

## 1. 소개

COVID-19로 인하여 2년 동안 거리두기 및 비대면 수업이 진행되었는데, 이로 인해 2020년 입학생 부터는 대학생활의 꽃인 mt나 축제 등의 행사를 경험하지 못하였다. 이러한 상황 속에 2022년도부터 거리두기가 완화되고 mt나 축제 등의 학교 행사가 다시 실시됨에 따라 새내기 및 20, 21학번 학생들이 행사를 즐기며 놀 기회가 생겼는데 기존 코로나 이전 대학생들은 mt 등의 행사에 가서 선배들에게 술게임을 배우고 친구들과 놀았다면, 현재는 술게임을 가르쳐줄 선배도 존재하지 않으며 기존에 진행하던 학교 행사의 분위기를 느끼기 힘들어졌다. 그렇기에 우리 조는 이러한 경험과 술게임을 배우고 싶어하는 새내기 및 대학생들을 대상으로 술게임을 가르쳐 주고 대학 학교 행사때의 분위기를 경험 시켜주는 어플리케이션을 만들어 보다 원활한 대면 전환 적응을 돕기로 한다.

## 2. 기술

**2.1. Client**

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=Flutter&logoColor=white)

**2.2. Server**

![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=Express&logoColor=white)
![Socketio](https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=Socket.io&logoColor=white)

## 3. 기능 설명

### 3.1. 로딩 화면

메인 화면으로 렌더링 전 필요한 패키지와 모듈들을 load 하는 과정이 포함된 화면이다.

<img src="https://user-images.githubusercontent.com/77189999/216884601-2839ae4d-6427-4a31-86eb-20253a72fb43.gif" width="250">

### 3.2. 메인 화면

청바지 app을 사용하기 위해 방을 생성하거나 접속하는 버튼이 존재하는 화면이다.

<img src="https://user-images.githubusercontent.com/77189999/216885318-b695b8da-3772-432e-bae2-87b087eb0122.png" width="250">

### 3.3. 방 생성 화면

메인화면에서 방 생성 버튼 클릭 시 나타나는 화면

<img src="https://user-images.githubusercontent.com/77189999/216885319-077ee3b6-cb26-4077-806d-bcb63acae194.png" width="250">

### 3.4. 방 참가 화면

메인화면에서 방 참가 버튼 클릭시 나타나는 화면

<img src="https://user-images.githubusercontent.com/77189999/216885320-47e66e6e-7e72-449e-95e4-b9541f620bdd.png" width="250">

### 3.5. 옵션화면

사용자는 배경음악, 효과음 등의 설정을 변경할 수 있다.

<img src="https://user-images.githubusercontent.com/77189999/216885311-2e9f7ed1-b4b3-4ee6-b6ea-47bfd98246cb.png" width="250">

### 3.6. 도움말

게임 시작방법, 게임별 설명, 벌칙 등에 대한 설명이 적혀있다.

<img src="https://user-images.githubusercontent.com/77189999/216885317-56a1f406-f9dc-43af-84d5-043f87eff690.png" width="250">

### 3.7. 게임대기방

게임이 진행되기 전에 대기하는 화면이며, 게임에 참가할 유저들은 모두 게임방에 들어온 상태여야 한다.

<img src="https://user-images.githubusercontent.com/77189999/216885315-ed4e3ab2-ef1e-4e49-a8da-1db04f89fb1e.gif" width="250">

### 3.8. 터치 많이 하기

제한 시간 안에 화면의 버튼을 터치하여 터치 횟수가 가장 적은 참가자가 벌칙을 받는다.

<img src="https://user-images.githubusercontent.com/77189999/216884020-84b4f792-1101-4d5c-b8bd-7256c938eb65.gif" width="250">

### 3.9. 폭탄 돌리기

참가자들은 제한 시간 동안 폭탄을 다른 참가자에게 넘겨서 폭탄으로부터 살아남아야 한다.

<img src="https://user-images.githubusercontent.com/77189999/216884081-256eb760-950c-42bd-9f6d-868d27f5a98c.gif" width="250">

### 3.10. 밸런스 게임

두가지 선택지 중 하나를 선택하고, 그 중 소수가 선택한 항목을 고른 참가자들이 패배한다.

<img src="https://user-images.githubusercontent.com/77189999/216884087-83f3fa52-d7a1-467d-8892-15eaaef807c9.gif" width="250">

### 3.11. 벌칙화면

게임이 종료되면 게임에서 패배한 유저가 벌칙을 받게 된다.

<img src="https://user-images.githubusercontent.com/77189999/216884121-cc588b56-3d8a-4bad-a64d-01464768a8fa.gif" width="250">

## 만든사람들

<table border="1">
    <th>
        <img src="https://img.shields.io/badge/Client-02569B?style=for-the-badge&logo=flutter&logoColor=white"></img>
    </th>
    <th>
        <img src="https://img.shields.io/badge/Client-02569B?style=for-the-badge&logo=flutter&logoColor=white"></img>
    </th>
    <th>
        <img src="https://img.shields.io/badge/server-010101?style=for-the-badge&logo=socket.io&logoColor=white"></img>
    </th>
    <th>
        <img src="https://img.shields.io/badge/server-010101?style=for-the-badge&logo=socket.io&logoColor=white"></img>
    </th>
    <th>
        <img src="https://img.shields.io/badge/UI-F24E1E?style=for-the-badge&logo=figma&logoColor=white"></img>
    </th>
    <tr>
        <td align="center">
            <img src="https://avatars.githubusercontent.com/u/92203597?v=4" width="100px;"> <br/>
            <a href="https://github.com/Junyoung-WON">원준영</a>
        </td>
        <td align="center">
            <img src="https://avatars.githubusercontent.com/u/84281455?v=4" width="100px;"> <br/>
            <a href="https://github.com/HeoJamong">허지명</a>
        </td>
        <td align="center">
            <img src="https://avatars.githubusercontent.com/u/102767676?v=4" width="100px;"> <br/>
            <a href="https://github.com/iamdudumon">김두현</a>
        </td>
        <td align="center">
            <img src="https://avatars.githubusercontent.com/u/77189999?v=4" width="100px;"> <br/>
            <a href="https://github.com/jjaegii">최재혁</a>
        </td>
        <td align="center">
            <img src="https://avatars.githubusercontent.com/u/84281599?v=4" width="100px;"> <br/>
            <a href="https://github.com/Gordned">김재현</a>
        </td>
    </tr>
</table>
