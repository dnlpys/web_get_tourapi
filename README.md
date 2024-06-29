# web_get_tourapi

## 프로젝트 개요
- 한국관광공사 관광정보를 api 호출 - 관광정보 및 gps정보를 파싱
- gsp(위/경도)정보로 kakaomap를 활용해 지도에 관광정보를 보여주고 고객이 원하는 범주의 관관정보를 추천해주기

### 사용된 기술 스택
- **Python:** 3.8
- asgiref==3.3.4
- Django==3.2
- pytz==2021.1
- sqlparse==0.4.1
- **pandas**
- **requests**

## 사용 api
- **kakaomap**:  지도 api
- tourapi: 한국관광공사 관광정보 api

## 테스트 방법
```python
# 프로젝트 클론
git clone https://github.com/dnlpys/web_get_api.git

# 현재 api 업데이트로 동작X