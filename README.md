# PokerGame
### 포커 게임 프로젝트

텍사스 홀덤 룰을 적용하여 컴퓨터와 포커 게임을 겨루는 프로그램입니다.

<img width="326" alt="how" src="https://user-images.githubusercontent.com/96714275/180609241-bfb47c71-1d6c-4d4b-bff6-35309dd14a35.PNG">



텍사스 홀덤 룰과 동일하게 자신의 패와 커뮤니티 카드 패를 보고 자신의 판돈을 결정하여 게임을 진행하는 방식입니다. \
아직까지는 상대 CPU 플레이어의 인공지능이 구현되어있지 않은 상태로, 무조건 플레이어의 배팅을 따르게 되어있습니다.


*****

### 참여자
hcm1206(현창민)

mnyu(조영재)

*****
### 개발 정보
프로젝트 개시일 : 2022년 5월 18일\
사용 언어 : Python\
사용 라이브러리 : tkinter(UI), PIL(이미지)\
사용 툴 : VSCode

*****

### 진행도(최근 1주)

#### Changelogs 22-07-25
- 파일 일부(gameProcess)를 분할하였습니다.
- 새로운 프로그램 구조를 위한 테스트용 더미 파일을 추가하였습니다.
- *기초적인 AI 알고리즘을 도입하기 위하여 게임 진행 매커니즘 개편이 진행될 예정입니다.*
- 기타 코드 수정이 이루어졌습니다.

#### Changelogs 22-07-23
- **카드 인덱스 롤백**
- 카드 인덱스 개편 작업 실시 후 테스트를 계속 진행하였으나 불안정하다고 판단되어 구버전 카드 인덱스 체계로 롤백하였습니다.
- 카드 인덱스 롤백과 함께 스트레이트 플러시 판정 오류, 5스트레이트를 A스트레이트로 판정하는 방식을 수정하였습니다.
- 롤백된 카드 인덱스 체계와 호환되도록 키커 등의 게임 시스템을 일부 수정하였습니다.
- 기타 더미 데이터 제거 및 사소한 코드 수정을 진행하였습니다.

#### Changelogs 22-07-21
- 이제 올인 시 참여자의 모든 잔돈이 배팅되지 않고 잔돈이 더 적은 참여자의 잔돈만큼 배팅하도록 수정되었습니다.
- 모든 UI 요소에 config() 함수를 적용하여 프로그램 최적화를 진행하였습니다.
- 이제 폴드 시에도 결과창에 키커가 표시됩니다.
- 기타 코드 정리를 진행하였습니다.


