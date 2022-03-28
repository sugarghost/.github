# <img src="https://user-images.githubusercontent.com/97428216/160321165-bd337416-a703-4f53-a1f7-5d8844ab66a2.png" align=left width=150> 꿈깨
> 온라인 3D 방탈출 게임 서비스 😴

<br />

## 💭 About

> ‘zzz’ 는 꿈을 꾸는 상태를 표현한 단어이자, 게임 프로젝트의 이름입니다
>
> ‘꿈’ 이라는 매체를 이용하여 상상하고 문제를 풀면서 해결하여
> 방탈출을 하는 것이 본 게임을 이어나갈 수 있는 방법입니다
>
> 당신은 꿈 속에서 얼마만큼의 역량을 발휘할 수 있는지 궁금하지 않으신가요?

<!-- <img width="1363" alt="스크린샷 2022-01-22 오전 5 27 36" src="https://user-images.githubusercontent.com/75469131/150595708-bd84f11e-ed2d-4dfe-9242-1b69e10756ac.png"> -->

<br />

## 📅 프로젝트 기간

- 2022.2.25 ~ 2022.4.9
- 1차 배포 : 2022.3.30

## ✨ 주요 기능


- **`홈`**
  방탈출 게임을 위한 방을 만들고, 랭킹조회 및 게임 설명을 확인할 수 있습니다.
- **`대기`**
  현재 대기중인 인원을 체크하고 게임을 시작할 수 있습니다.
- **`게임`**
  팀원들과 보이스채팅을 나누며 방에 배치된 3D 물체를 클릭해 주어진 문제를 풀고 탈출할 수 있습니다.

<!-- ![This is the last](https://user-images.githubusercontent.com/75469131/150535885-e6c38a60-19b0-4957-8919-2c78074cdb50.png) -->

<br />

## 🍎 Team Member

| Name     | GitHub                             | Position  |
| -------- | ---------------------------------- | --------- |
| 류강현   | https://github.com/softwat          | 프론트엔드 |
| 우혜민   | https://github.com/hyemin9403       | 프론트엔드 |
| 김가은   | https://github.com/paran22          | 백엔드     |
| 최규원   | https://github.com/cooked-developer | 백엔드     |
| 반원재   | https://github.com/wonjaeban        | 백엔드     |
| 서혜원   |                                     | 디자인     |
| 김보경   | https://github.com/bokyung29        | 디자인     |

---

<br />

## 📚 기술스택
<div align=center><h3>프론트엔드</h1></div>
<div align=center> 
</div>

<div align=center><h3>백엔드</h1></div>
<div align=center> 
  <img src="https://img.shields.io/badge/java-007396?style=for-the-badge&logo=java&logoColor=white">
  <img src="https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white">
  <img src="https://img.shields.io/badge/gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white">
  <br>
  <img src="https://img.shields.io/badge/webrtc-333333?style=for-the-badge&logo=webrtc&logoColor=white">
  <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"> 
  <img src="https://img.shields.io/badge/node.js-339933?style=for-the-badge&logo=Node.js&logoColor=white">
  <img src="https://img.shields.io/badge/express-000000?style=for-the-badge&logo=express&logoColor=white">
  <img src="https://img.shields.io/badge/socket.io-010101?style=for-the-badge&logo=socket.io&logoColor=white">
  <br>
  <img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
  <img src="https://img.shields.io/badge/spring data jpa-F28D1A?style=for-the-badge&logo=springdatajpa&logoColor=white">
  <img src="https://img.shields.io/badge/aws ec2-07C160?style=for-the-badge&logo=amazoneaws&logoColor=white">
  <img src="https://img.shields.io/badge/amazon s3-569A31?style=for-the-badge&logo=amazons3&logoColor=white">
  <br>
  <img src="https://img.shields.io/badge/aws codedeploy-9D1620?style=for-the-badge&logo=amazonaws&logoColor=white">
  <img src="https://img.shields.io/badge/aws codepipeline-072240?style=for-the-badge&logo=amazonaws&logoColor=white">
  <img src="https://img.shields.io/badge/nginx-009639?style=for-the-badge&logo=nginx&logoColor=white">
  <img src="https://img.shields.io/badge/github actions-181717?style=for-the-badge&logo=github&logoColor=white">
</div>

<div align=center><h3>Tools</h1></div>
<div align=center> 
  <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">
  <img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white">
</div>

## 📌 바로가기
- Project : https://zzz-escape.netlify.app
- 프론트엔드 GitHub Repository : https://github.com/HangHae99Zzz/dream_escape-fe
- 백엔드 GitHub Respository(Spring) : https://github.com/HangHae99Zzz/RoomEscape_BE
- 백엔드 GitHub Respository(NodeJS) : https://github.com/HangHae99Zzz/RoomEscape_BE-nodeJS

## 📺 Detail

<details markdown="1">
<summary>아키텍처</summary>
</details>

<details markdown="2">
<summary>ERD</summary>
</details>

<details markdown="3">
<summary>Flow Chart</summary>
</details>

<details markdown="4">
<summary>API 명세서</summary>
  
> 🚨 API 설계규칙

```
Rest API URI 설계규칙을 따른다.
  1. 후행 /는 URI에 포함하지 않는다.
  2. 계층관계를 나타낼 때 슬래시 구분자를 사용한다. ex) /rooms/{roomId}/quizzes/{quizType}
  3. 긴 path를 표현하는 경우에는 가독성을 높이기 위해 하이픈(-)을 사용한다.
  4. 언더바(_)는 URI에 사용하지 않는다.
  5. URI는 모두 소문자로 작성한다.
  6. 파일확장자는 URI에 포함하지 않는다.
  7. 모든 resource는 복수형을 사용한다.
```
  
</details>

## 🔨 Trouble Shooting

> WebRTC signalling 서버 구축 문제
```

```
> 게임방 Resource
```

```

