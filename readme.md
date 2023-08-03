# 2023_Aws_cloud를_활용한_INHA_SW_NET_ZERO_공동해커톤_팀_연수실
### *해당 레포지토리는 해커톤 기간의 cloud9 코드를 복원해놓음.*
## 주제 : 에어 코리아의 실시간 대기정보 데이터를 활용한 서비스 개발
<h2>서비스명 : 먼지여정 슬랙봇<img src="https://github.com/meridaKim/meonji_Yeojung/assets/71478325/d518d70b-44a0-429b-ab27-ea503e0e87a2" width="5%"/>
</h2>

## 개발 기간 : `2023.07.14-2023.07.15`(약 2일간 진행)

### 서비스 설명 
: 에어 코리아의 실시간 대기정보 데이터를 활용한 미세먼지 청정지역 추천 및 외부 활동 일정에 따른 미세먼지 알림 서비스 

* aws cloud9을 이용하여 공동개발
* 공공데이터와 google calendar api,map api,chatGpt api 사용
* 구글 캘린터의 개인 일정에서 외부 일정이 있을 경우, 3일 전 미세먼지 정보와 일정 정보를 알림으로 제공
* "놀러가고 싶어"라고 먼지봇에게 채팅하면 현재 위치에 기반하여 미세먼지 정보를 제공하고, 주변 미세먼지 청정지역의 갈만한 관광명소를 추천
### 역할

1. 팀장 김도희 : pm, 발표 및 발표 자료 작성, 대기정보 데이터 담당
2. 팀원 김연수 : chatGpt api 담당, 현재 위치에 따른 추천 서비스 개발
3. 팀원 김세은 : map api 담당, 현재 위치 위도,경도, 주변 지역 위치 데이터와 대기 정보 데이터 담당
4. 팀원 김수진 : google calendar api 담당, 사용자의 구글 캘린더 일정 관련 서비스 개발, 먼지여정 캐릭터 개발
