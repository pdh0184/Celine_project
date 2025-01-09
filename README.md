# Celine_project
셀린느 사이트 크롤링 및 유사 이미지 분류

# 1. 셀린느 사이트 크롤링
# 2. 이미지 인코딩 후 CSV파일에 저장
# 3. 디코딩 및 유사한 이미지 반환
- SIFT 기반 유사 이미지 반환
    - descriptor 추출 후 FAISS 를 통하여 상위 N 개 유사 이미지 반환
    - 왼쪽 가방과 유사한 4개 상품 추출
    -  ![image](https://github.com/user-attachments/assets/82501c70-6ad8-4393-83c4-b2bbb03afef8)

위 이미지와 유사한
- Rasnet50 기반 유사 이미지 반환
    - classifier 층을 제외 후 추출한 특징 벡터를 FAISS를 통하여 N개 유사 이미지 반환
    - 왼쪽 가방과 유사한 4개 상품 추출
    - ![image](https://github.com/user-attachments/assets/810d5017-0045-47a5-8f7b-598f07033cb4)



    
