<div align="center">
  <br />
    <h1>📖ReBook📖</h1>
    ⭐Kakao Tech BootCamp 5조⭐<br/>
    한채형, 최윤서, 송이영, 김예지, 김남기, 장민석
</div>


## 프로젝트 개요
> C2C 방식의 중고 전공책 거래 플랫폼

<br/>

## 프로그램 차별점
> 편의성 특화(추천, 쿨거래, 편한 등록)
> <br/>
> => 책 등록과 거래의 편리성 & 인공지능을 통한 책 상태의 신뢰성 확보

|문제점|차별점|키워드|
|---|---|---|
|전공책같은 경우, 한학기 끝날 때 한꺼번에 정리해야하는데, 이 과정에서 책을 한꺼번에 다 등록하는 것이 귀찮음|바코드로 ISBN을 인식해 쉽게 중고거래 플랫폼에 등록할 수 있음|**책 등록의 편의성**|
|위치과 시간이 딱 맞는데도 불구하고 책을 발견하지 못함 & 구매하는 과정이 번거로움|위치와 시간을 바탕으로 자동 추천, 알림해주고 채팅이 필요없는 쿨거래 기능으로 책을 팔고 구매하는 수고를 덜어줌|**책 거래의 편리성**|
|책 상태에 대한 신뢰성 확보의 어려움|인공지능 오염도 검사를 통해 판매글의 책 상태 설명에 대한 신뢰성 강화|**인공지능을 통한 신뢰성 확보**|
|다양한 물건과 함께 파는 중고 거래 플랫폼에서 거래를 해야하기 때문에 필터 기능으로 내가 찾는 전공책을 찾기 어려움|전공책만 다루기 때문에 내가 원하는 상태과 가격의 전공책을 검색하기 편함|**필터 기능을 통한 책 검색의 편리성**|

<br/>

## 주 타겟층
> 20, 30대 대학 재학/졸업생

<br/>

## 주요 기능
### 게시판
- 검색 기능
- 기본 필터: 대학교 전공 별 책 추천 ➡ 회원가입할 때 입력된 정보를 가지고 세팅
- 학년, 학기에 맞는 책 목록 제공
- 커스텀 필터: 가격, 상태 등등

### 채팅 기능
- 카카오 API 지도 기능으로 위치 공유
### 결제 시스템
- 계좌번호 인증 시스템
- 안심결제 당근페이처럼 - 먹튀 방지 서로 인증
- 구매자 책 수령 확인 , 판매자 돈 받은거 확인 → 시스템 상 판단 → 사용자 차단, 사기꾼으로 등록
- 배너로 위험성 인지 시키기
### 거래에 대한 리뷰
- 매너티어(백준처럼~) or 매너지수 - 거래 기록 등 (라디오버튼)
- 모아보기 기능
- 통계 기능
### 쿨거래 버튼
- 채팅 없이 그냥 버튼으로 바로 거래 요청 - 수락하면
- 조건 : (거래 위치 등록 & 시간대를 설정) or 택배 → 나의 현재 위치정보와 시간에 따라 쿨거래 조건이 맞으면 쿨거래 버튼 활성화
### 책 등록 방식
- QR로 ISBN 자동으로 인식해서 폼 채우기
### 인공지능 기능
- 사람들이 써놓은 책의 상태와 인공지능이 측정한 오염도 비교해서 책 등록 시 경고 등
- 가격과 책의 상태가 맞는지 체크
### 신고 기능
- 신고 횟수 누적
- 채팅 & 게시물에 버튼 구현


## 기술스택 및 개발환경
- 프론트: `React`
- 백엔드: `SpringBoot`
- 인공지능: 