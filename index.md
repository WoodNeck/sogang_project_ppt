---
marp: true
size: 16:9
theme: uncover
footer: '![height:15](images/naver.png)'
---

#### 내가 그린 그림을 움직이는 3D 모델로 만들어보자

---

![hi](https://stickershop.line-scdn.net/stickershop/v1/sticker/78182/iPhone/sticker_animation@2x.png;compress=true)
안녕하세요!

---

# 과제설명

---

#### 내가 그린 그림을 움직이는 3D 모델로 만들어보자

![height:100](https://www.flaticon.com/svg/static/icons/svg/191/191714.svg) ![height:100](https://www.flaticon.com/svg/static/icons/svg/545/545682.svg) ![height:100](https://static.turbosquid.com/Preview/2015/01/27__14_08_40/ggt.jpg25a6ec5c-1566-46f9-91d6-4aaac8670f0dLarge.jpg)

---

[예시](https://youtu.be/5fiqe7Rl02E)

---

### 해주셔야 하는 것들

- Object Segmentation
- 3D Model from segmented 2D image
- Rigging
- Animation

---

### 1. Object Segmentation
![height:300](https://www.pyimagesearch.com/wp-content/uploads/2016/04/extreme_points_hexample_01.jpg)
특정 오브젝트만을 이미지 내에서 분리하는 기술

---

![height:300](https://www.researchgate.net/profile/Binh_Pham2/publication/220465300/figure/fig1/AS:637404792750081@1528980553289/The-original-outline-and-triangulated-polygon-template.png)
사용자가 사진을 입력시,
사진 내의 그림을 폴리곤 형태로 분리하는 프로그램 작성

---

### 관련 키워드
- Contour Detection
- Object Segmentation
- OpenCV

---

### 2. 3D Model from segmented 2D image
![height:250](https://icdn2.digitaltrends.com/image/digitaltrends/12-19.jpg)
앞서 분리한 이미지를 실제 3D 모델로 변환

---

- **1**에서 만든 폴리곤을 "glTF(glb)" 포맷의 3D 모델로 변환
- 가급적이면 glTF Exporter를 사용해주세요

---

### 관련 키워드
- glTF
- Polygon Triangulation
- UV mapping

---

### 3. Rigging
![height:200](https://camo.githubusercontent.com/21a4a8097718610ca3b591563b61eebdcb696fb6/68747470733a2f2f63646e2e676c697463682e636f6d2f35316464613232392d643735352d343531622d613439392d37396131323835393936666125324673616d706c652e706e673f31353530343730393230383034) ![height:200](https://images.otwojob.com/product/D/C/M/DCMQ0qGmBYJvGBq.jpg/o2j/resize/900%3E)
그림의 뼈대를 찾아서, 3D 모델에 입히는 작업

---

- **2**에서 만든 3D 모델에 뼈대를 추가해서 Skinned Mesh
- 즉, 애니메이션이 가능한 상태로

---

### 관련 키워드
- Skeletonization
- Rigging

---

### 4. Animation
![height:300](https://forum.unity.com/attachments/new_walk_bones-gif.115238/)
3D 모델에 Skeletal animation을 추가하는 작업

---

![](https://4.bp.blogspot.com/-a_EixnWZB8A/WEME8PLmT9I/AAAAAAAAMBw/TJblDdWszIwn9T2Yl09g0zt_C6kWLCR8wCK4B/s1600/GIF2.gif)
- 완성된 3D 모델에 자유롭게 애니메이션을 추가해봅시다~

---

### 관련 키워드
- Skeletal animation
- Inverse Kinematics

---

### 개발환경 - **자유!**

---

### 일정
-  9/28 ~ 10/16 (3주)
    - 자유롭게 구현
- 10/19 ~ 10/30 (2주)
    - Object Segmentation
    - 2D image to 3D model
- 11/2 ~ 11/20 (2주) : Rigging
- 11/23 ~ 11/27 (1주) : Animation
- 11/30 ~ 12/4 (1주) : 마무리

---

궁금하신점 자유롭게 물어봐주세요~
