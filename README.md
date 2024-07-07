# 2023 고려대-연세대 정기전 NFT 민팅 서비스, 버미와수리 

![image](https://github.com/FutureandKim/2023_BummySuri_FrontEnd/assets/95979743/a91f3aae-b72c-4883-9f48-1d1a493140eb)

2023 고려대-연세대 정기전을 기념하여 NFT를 민팅할 수 있는 웹서비스입니다.

## 배포 주소
https://www.bummysuri.com/

(현재는 운영 중단)

## 기술 스택
React, JavaScript, HTML5, CSS3, Docker

## 기능
### 1. Klip 로그인
   - Klip api로 카카오톡의 Klip 지갑을 연동하여 사용자를 인증하고, NFT 민팅을 간편하게 할 수 있도록 개발하였습니다.
   - 사용자 정보는 사이드바에서 Klip 지갑주소와 함께 확인할 수 있도록 구현되었습니다.
     - 로그인 화면
       
       <img src="https://github.com/FutureandKim/2023_BummySuri_FrontEnd/assets/95979743/1dd3723a-ae7b-4b4f-a1b5-5dc66374bc60" width="200" height="400"/>
       <img src="https://github.com/FutureandKim/2023_BummySuri_FrontEnd/assets/95979743/0606c650-6a8f-4d7f-b4b1-79f92f95bab5" width="200" height="400"/>

     - Klip 인증
       
       <img src="https://github.com/FutureandKim/2023_BummySuri_FrontEnd/assets/95979743/7d3d5e45-58f0-481d-b9d2-db7e46446aba" width="200" height="400"/>
       <img src="https://github.com/FutureandKim/2023_BummySuri_FrontEnd/assets/95979743/e2667ac1-4bc8-4650-9572-05148436a3a3" width="200" height="400"/>

     - 사용자 정보
       
        <img src="https://github.com/FutureandKim/2023_BummySuri_FrontEnd/assets/95979743/c5b3d5ec-fb8d-4468-96ca-bf6f034221af" width="200" height="400"/>


### 2. NFT 민팅
- 고려대와 연세대 버튼을 클릭하여 간편하게 NFT를 민팅받을 수 있으며, 민팅된 NFT는 사이드바에서 확인이 가능합니다.
- 실시간으로 각 대학의 NFT 민팅 현황을 그래프로 보여줄 수 있도록 구현되었습니다.
- 민팅된 NFT는 클립 앱에서도 확인이 가능합니다.
  - NFT 민팅

    <img src="https://github.com/FutureandKim/2023_BummySuri_FrontEnd/assets/95979743/ec431a5d-1d20-40b6-9325-237f06e40dd7" width="200" height="400"/>
    <img src="https://github.com/FutureandKim/2023_BummySuri_FrontEnd/assets/95979743/0d3c6958-bd8f-4090-a621-b8d343779415" width="200" height="400"/>

  - 민팅 현황 그래프

    <img src="https://github.com/FutureandKim/2023_BummySuri_FrontEnd/assets/95979743/1e6df5b8-ded2-4c3b-9141-d1386d1634f8" width="200" height="400"/>

  - Klip 앱에서 확인할 수 있는 버미수리 NFT
    
    <img src="https://github.com/FutureandKim/2023_BummySuri_FrontEnd/assets/95979743/1435e904-a7a9-4e9a-b5cc-d64f0ba71368" height="400"/>

        

### 3. 정기전 경기 예측 및 배팅
- 사용자가 정기전 경기의 승패와 점수차이를 예측하고 포인트를 배팅할 수 있도록 하여 웹사이트 이용을 더욱 활성화시켰습니다.
- 경기 예측에 성공하면 배팅한 포인트의 3배를 얻을 수 있도록 구현하였습니다.
  - 정기전 예측 화면
    
    <img src="https://github.com/FutureandKim/2023_BummySuri_FrontEnd/assets/95979743/410213d2-e3bb-45d0-a431-675d9ee2da10" width="200" height="400"/>
    <img src="https://github.com/FutureandKim/2023_BummySuri_FrontEnd/assets/95979743/b21aa24c-61c3-4687-89e6-0e76896b7ba3" width="200" height="400"/>

  - 정기전 종료 시

    <img src="https://github.com/FutureandKim/2023_BummySuri_FrontEnd/assets/95979743/db5a4dce-4984-4e51-bf9f-f2d81ca29df5" width="200"/>

### 4. 미니게임
- '넌센스 그림퀴즈'와 '가위바위보' 게임을 통해 사용자들의 참여와 재미를 유도했습니다.
- 넌센스 그림퀴즈는 10개의 그림 중 하나를 랜덤으로 보여주며 하루에 한번 참여가 가능하도록 구현했습니다.
- 가위바위보 게임은 하루에 횟수 제한이 3번이며 비기는 경우 횟수가 차감되지 않도록 구현하였습니다.
  - 넌센스 그림 퀴즈
    
    <img src="https://github.com/FutureandKim/2023_BummySuri_FrontEnd/assets/95979743/a3af7000-3202-4c03-a6af-001480ab5513" height="400"/>
    <img src="https://github.com/FutureandKim/2023_BummySuri_FrontEnd/assets/95979743/03991b1b-4914-469a-8be0-d11df4d2bcde" height="400"/>

  - 가위바위보
  
    <img src="https://github.com/FutureandKim/2023_BummySuri_FrontEnd/assets/95979743/554d5921-11e0-485b-936f-1fb1c9207c8a" height="400"/>
    <img src="https://github.com/FutureandKim/2023_BummySuri_FrontEnd/assets/95979743/ef79293e-89d7-4c72-8747-6018b7e11fb0" height="400"/>

      
### 5. 사용자 랭킹 정보
- 배팅과 미니게임을 통해서 얻은 포인트는 랭킹 페이지에서 확인할 수 있도록 구현하였습니다.
- 포인트를 가장 많이 모은 10명에게는 추후 경품을 지급하였습니다.
  - 랭킹 화면
 
    <img src="https://github.com/FutureandKim/2023_BummySuri_FrontEnd/assets/95979743/a63ba72c-2a14-4485-a088-e0da3e2b6057" height="400"/>

