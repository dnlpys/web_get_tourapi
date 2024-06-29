# web_get_tourapi

## 프로젝트 개요
- 한국관광공사 관광정보 API를 호출하여 관광정보 및 GPS 정보를 파싱합니다.
- GPS (위도/경도) 정보를 기반으로 KakaoMap API를 활용하여 지도에 관광정보를 표시하고, 고객이 원하는 범주의 관광정보를 추천해 줍니다.

### 사용된 기술 스택
- **Python:**   3.8
- **asgiref**   3.3.4
- **Django**    3.2
- **pytz**      2021.1
- **sqlparse**  0.4.1
- **pandas**
- **requests**

## 사용 API
- **kakaomap**: 지도 API
- **tourapi**: 한국관광공사 관광정보 API

## 테스트 방법
```bash
# 프로젝트 클론
git clone https://github.com/dnlpys/web_get_api.git

# 현재 API 업데이트로 인해 동작하지 않습니다.
