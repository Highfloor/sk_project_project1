# sk_project_project1
# 개요
  - 프로젝트 주제
    - 리뷰를 기반으로 한 도쿄 맛집 추천
  - 프로젝트 목표
    - 맛집 리뷰 사이트에서 리뷰 텍스트 데이터 수집
    - 키워드 별로 리뷰데이터 재가공
# 데이터 수집
- 사이트에서 리뷰부분의 데이터를 크롤링
<img src =https://user-images.githubusercontent.com/123059090/229727216-18f45dc2-a663-4818-9a7c-1e558e2e17f7.png>
- 위의 사진 부분에서 텍스트를 뽑아낸 결과
<img src= https://user-images.githubusercontent.com/123059090/229727807-8074cbad-88b8-4135-8a05-e26e42fcf539.png>

# 데이터 정제
- 크롤링된 텍스트 전세계의 언어로 된 텍스트를 한국어로 번역
<img src = "https://user-images.githubusercontent.com/123059090/229728796-1fd6648e-74b2-410f-b338-084c9c4d2832.png">

- 수집된 리뷰를 키워드별로 나누기 위해 해시태그 및 키워드 설정
<img src = https://user-images.githubusercontent.com/123059090/229729177-66fb4d10-9375-46be-bb8a-2b45330b65f3.png>
<img src = https://user-images.githubusercontent.com/123059090/229729344-ca16514c-85a6-4e49-afde-e88ea41a3861.png>
# 키워드 수집
- 키워드 검색함수로 키워드별로 데이터 축소
<img src= https://user-images.githubusercontent.com/123059090/229729759-d5501c04-07e9-411d-8702-d75205f30b96.png>
<img src = https://user-images.githubusercontent.com/123059090/229729857-2af15e17-9519-4331-bd74-f5141842c04f.png>
- 축소 결과
<img src = https://user-images.githubusercontent.com/123059090/229730227-c74e8bc6-d41d-4e9b-ad4c-1a1f382e6c09.png>

# 결론-시각화
## Quality 태그수를 리뷰 전체 개수로 나눈 비율 그래프
<img src = https://user-images.githubusercontent.com/123059090/229730554-43cd8c01-bbbd-4198-86b4-76264bdaf182.png>
## 음식점 별 원형 그래프
<img src = https://user-images.githubusercontent.com/123059090/229730770-359432bb-a723-4fc7-9419-65d2b7e074ef.png >
