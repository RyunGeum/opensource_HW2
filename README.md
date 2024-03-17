# opensource_HW2 오픈소스 개발프로젝트 과제#2

● 구현하고자 하는 기능 설명
1. 이미지를 S3에 업로드하는 기능을 구현합니다. (프로그램에서 파일을 입력 받아, 해당 파일을 S3에 업로드합니다)

2. 프로그램은 AWS Rekognition의 object detection(detect label) 서비스를 활용하여 이미지상의 객체를 인식합니다.

3. 인식된 결과(JSON)를 파싱하여 이미지에 네모 박스로 표시하되, 전방에 위치한 object에 대해서만표시하는 기능을 구현합니다.

# AWS (Amazon Web Services)

● S3 버킷 설정
버킷 이름: 2022039078

버킷 리전: 아시아 태평양(서울) ap-northeast-2

버킷 객체: 8256_36469_651.jpg

버킷 서비스키: rootkey.csv 파일을 통해 발급

- 차와 사람이 있는 사진, 우측 측면에 있는 물체(차)는 제외하고 정면의 차와 사람만 인식

![8256_36469_651 jpg](https://github.com/2022039078/2022039078_HW2/assets/131639123/a9776e86-a467-4a26-b4f1-13ca084ee80b)

![tmpxkxlneg7](https://github.com/2022039078/2022039078_HW2/assets/131639123/f39c0e7d-74b8-4c68-8b29-fdaaf594c6be)

