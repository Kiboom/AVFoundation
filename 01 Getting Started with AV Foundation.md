# 01. Getting Started with AV Foundation

- 차세대 미디어 앱을 개발하기 위해서는 `AV Foundation`을 배우는 것이 매우 중요함.

## AV Foundation이란?
- `AV Foundation`은 **시간 기반의 미디어(time-based media)** 를 개발하기 위한 프레임워크
- **멀티코어와 GCD**를 최대한으로 활용함. 계산 비용이 많이 드는 작업들을 백그라운드 쓰레드에서 돌림.
- **하드웨어 가속**을 자동으로 제공함으로써 광범위한 기기에서 최상의 성능을 보장함.
- iPhone과 iPad 같은 모바일 기기를 위해 **높은 전력 효율**을 갖도록 설계됨.
- **64비트 하드웨어**를 최대한 활용하기 위해 처음부터 64비트 네이티브로 작성됨.

## AV Foundation은 어디에 적합한가?
<img width="350" alt="스크린샷 2019-03-18 오후 1 48 53" src="https://user-images.githubusercontent.com/12539719/54507458-c3bd8900-4984-11e9-8fbe-ee2062f2aafc.png">

- MacOS와 iOS에서는 미디어 작업을 위해 여러 **저수준과 고수준의 프레임워크**를 제공함.
- MacOS와 iOS 모두 웹뷰를 사용하여 오디오 및 비디오 콘텐츠를 재생할 수 있음.
- MacOS와 iOS 모두 `AVKit` 프레임워크를 제공함. 비디오 재생 앱을 쉽게 만들 수 있도록 편리한 기능들을 제공함.
- `AVKit`은 편리하지만 복잡한 앱을 만들기에는 유연성과 제어력이 부족함. 

