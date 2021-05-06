현재 개발중인 버전입니다.
==========================

## Feature development info
### 완료

 - ~자가진단 자동화 플러그인과의 연동~ 자가진단 플러그인과 메인 apk와의 통합 완료
 - 자가진단 자동화 기능
 - 학습실 신청 자동화 프로그램 API 제작
 - 기초적인 display 기능

### 진행 예정

 - 학습실 다중신청 자동화
 - Server side program develop
 - UI/UX
 - 분실물 찾기 feature
 - 학습실 신청 자동화 프로그램과의 통합
 - 자가진단, 학습실 신청, 과제 관련 알림 푸시(w. GCP, FCM)
 - Crawl meal data in https://gbs.hs.kr
 - Create setting fragment(fragment exist but that has no action)
 - 과제 리스트 및 다운로드 기능

### Deprecated

 - Feature which makes able to move legacy launcher: 신런쳐의 완성도 상승시 삭제 예정. 관련 코드는 lgs_MainActivity.kt에 존재

## Server side Launcher logic
 - Parse Data from comsi.kr: node.js
 - Save homework data: not specialized
 - Open server: Apache Web Server

## Client side Launcher logic
 - Save weekly data
 - Auto self check feature
 - Auto set learning room info
 - Launcher: Kotlin

## Developer
 - Edit this part your self via PR
 - Dayo