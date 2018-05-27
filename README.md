﻿# 2018학년도 나르샤 프로젝트 "자치차량"
대구소프트웨어 고등학교 2018년 나르샤 실무프로젝트 "자치차량"에 하드웨어에 사용이 되는 코드를 업로드하는 github입니다. 이 레퍼런스는 자치차량에 개발에 사용이 된 모든 코드를 포함하고 있습니다.

## 다른 레퍼런스 주소
* https://github.com/fbqweasd/DGSW-Autonomous-vehicle-HW __자치차량 하드웨어__
* https://github.com/fbqweasd/DGSW-Autonomous-vehicle-OpenCV __자치차량 OpenCV__
* https://github.com/DGSW-Autonomous-vehicle/DGSW-Autonomous-vehicle-OpenCV __Server git hub__

# 자치차량이란?
자치차량은 __"자율주행 자동차"__ 를 구글 번역기에 돌리고 다시 역번역을 하면 __"차치차량"__ 이라고 번역이 됩니다. 이걸 보고 저희 팀원들은 "자치차량"이라는 이름은 "구글이 준 프로젝트명이다!"라는 생각으로 자치차량을 프로젝트명으로 결정을 했습니다.
![자치차량 번역](/img/Autonomous_vehicle.png)

__자치차량__ 은 '라즈베리 파이와 카메라를 사용을 해서 장해물을 피하고 도로를 주행할 수 있는 자동차를 만들어보자!' 라는 생각에서 출발을 했습니다. 그래서!
+ OpenCV를 사용해서 실시간으로 영상처리를 해 장해물, 도로, 신호등, 표지판을 판단 
+ 판단한 데이터를 라즈베리에 넘기면 적절한 작업 수행
+ 차치차량에 있는 여러가지의 센서를 사용을 해서 정확도 향상

이러한 기능을 구현을 하고 추가적으로 기회가 되면 도로에 라인이 깔려 있으면 라인트레이싱을 해서 안정적인 주행을 하고, 주차장과 같은 곳에서 서버와 통신을 해서 주차관리, 요금납부등 를 할 수 있도록 생각을 하고 있습니다.

## 차치차량 모습
![자치차량 이미지1](/img/Auto_veh_img_1.jpg)
![자치차량 이미지2](/img/Auto_veh_img_2.jpg)

처음 나르샤를 시작한고 처음 만들어진 "자치차량"의 모습

## 차치차량 구현 과정

* 나르샤 시적전

![마일스톤](/img/Milestone.png)
  
 나르샤를 시작을 하기전에 미리 팀원들끼리 의논을 해서 어떻게 자치차량을 만들건가? 에 대해서 의논을 하면서 마일스톤을 만들었습니다. 물론 100%이 계획처럼 가지는 않았지만 미리 만들어보면서 어떤 것이 필요한지를 미리 알 수 있었습니다. 
 

