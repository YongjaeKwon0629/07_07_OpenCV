# OpenCV 입문

OpenCV(Open Source Computer Vision Library)는 실시간 컴퓨터 비전 및 이미지 처리 기능을 제공하는 **강력한 오픈소스 라이브러리**입니다. Python, C++, Java 등 다양한 언어에서 사용 가능하며, 이미지 필터링, 객체 인식, 얼굴 검출, 영상 분석 등의 분야에서 널리 활용됩니다.

이 문서는 OpenCV를 처음 접하는 사용자를 위해 **기본 개념, 설치 방법, 주요 기능과 용어**를 체계적으로 안내합니다.

---

## 📚 목차

### [1. OpenCV란?](./1_OpenCV란.md)
- OpenCV 정의
- 주요 활용 분야
- 지원 언어 및 플랫폼

### [2. OpenCV 설치 및 필요한 라이브러리](./2_설치및라이브러리.md)
- pip를 이용한 설치 방법
- 필수 라이브러리 목록 (numpy 등)
- 설치 시 자주 발생하는 오류 및 해결법

### [3. OpenCV 주요 기능 요약](./3. OpenCV 주요 기능 요약.md)
- 이미지 처리 (읽기, 저장, 출력)
- 비디오 스트리밍 처리
- 필터링 및 마스크
- 객체 탐지 (윤곽선, 얼굴 등)

### [4. OpenCV 자주 나오는 용어 정리](./4. OpenCV 자주 나오는 용어 정리.md)
- 이미지와 배열, 채널의 관계
- BGR vs RGB
- 커널(kernel), 컨볼루션(convolution)
- ROI, threshold, histogram 등

### [5. 이미지 및 비디오 기본 처리](./)
- `cv2.imread()` / `cv2.imshow()` / `cv2.imwrite()`
- 웹캠 스트리밍: `cv2.VideoCapture()`
- 키보드 이벤트 처리

### [6. 색상 공간 및 채널 이해](./)
- BGR → RGB 변환
- Grayscale 처리
- HSV, LAB 등의 색 공간 활용

### [. 이미지 필터링 및 변환 기초](./)
- 블러 처리 (Gaussian, Median)
- 경계 검출 (Sobel, Canny)
- 도형 검출 (Hough Transform 등)

### [8. 객체 탐지와 윤곽선 처리](./)
- `cv2.findContours()`와 `drawContours()`
- 모멘트(moment), 면적, 중심점 구하기
- 얼굴 검출: Haar Cascade / DNN

---

> 📌 각 항목은 이후 세부 `.md` 문서로 분리되어 자세히 설명될 예정입니다.

---

🔗 참고 예시: [GitHub 오픈CV 예제](./https://github.com/Donggeon2960/623_chungnam/blob/main/opencv.md)
