# 온라인 시험 시스템

이 프로젝트는 간단한 온라인 시험 시스템입니다. 

![매인화면](/images/Main.png)


## 목차
- [시작하기](#시작하기)
- [시스템 구성](#시스템-구성)
- [기능 포인트](#기능-포인트)
- [기술 스택](#기술-스택)

## 사용법
1. Mysql에 데이터베이스를 생성하고, setting.py의 DB 설정을 추가합니다.
2. migrate를 이용하여 테이블을 생성합니다.
3. createsuperuser를 이용해 admin 계정을 만듭니다.
4. /admin 경로를 통해 접속합니다.

## 시스템 구성
시스템은 다음 세 가지 주요 역할로 구성됩니다:
1. 시스템 관리자
2. 학생 사용자
3. 교사 사용자

시스템은 다음 네 가지 주요 모듈로 구성됩니다:
1. 사용자 관리 모듈
2. 시험 문제 관리 모듈
3. 시험지 관리 모듈
4. 시험 관리 모듈

## 기능 포인트
### 사용자 관리 모듈
- 사용자 로그인 및 로그아웃
- 사용자 활성화
- 사용자 정보 편집
- 비밀번호 찾기
- 사용자 메시지
- 로그 관리

### 시험 문제 관리 모듈
- 시험 문제 추가
- 시험 문제 수정
- 시험 문제 삭제
- 시험 문제 필터 및 정렬
- 시험 문제 즐겨찾기
- 공용 문제 은행과 개인 문제 은행 분류
- 오답 조회 및 필터 (학생 사용자를 대상으로)

### 시험지 관리 모듈
- 시험지 추가
- 시험지 수정
- 시험지 삭제
- 시험지 복사
- 시험지 조회

### 시험 관리 모듈
- 시험 추가
- 시험지 응답 (학생 사용자를 대상으로)
- 시험 성적 조회
- 시험 성적 다운로드

## 기술 스택
- 서버: Python 3.7 + Django 2.1.4    
- 클라이언트: HTML+CSS+JavaScript+JQuery+Bootstrap  
- 데이터베이스: MySQL 5.7  
- 백엔드 관리 시스템: Django Admin

