# 리뷰 기반 메뉴 추천 시스템

## 프로젝트 개요
사용자 리뷰 데이터를 활용하여 메뉴를 자동 추천하고, 음식점 개선 인사이트를 제공하는 시스템입니다.  
(네이버 플레이스 리뷰 사용)

## 팀 구성
- 데이터 수집 : 김도윤 / 이서현<br/>
- 데이터 전처리,적재 : 임령아 / 장한나<br/>
- 데이터 분석 : 한가은 / 이세연 / 김효민

## 디렉토리 구조
- `/data`: 원시 데이터
- `/preprocessing`: 전처리 스크립트
- `/analysis`: TF-IDF, 워드클라우드, 감성 분석 
- `/web`: 결과 페이지 (Flask/Streamlit 등)
- 

## 실행 방법
```bash
pip install -r requirements.txt
python preprocessing/clean_review.py
python analysis/menu_recommend.py
