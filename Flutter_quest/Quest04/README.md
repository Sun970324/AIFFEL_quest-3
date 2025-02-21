# 카카오톡 앱 분석 및 역설계하기

## 앱 정보 
- 앱 이름 : 카카오톡<br><br>
 <br> <br>
## 앱 구조도    <br>
![Untitled (1)](https://github.com/user-attachments/assets/92038be4-3d64-42e7-9c0a-3cb6ff8e71e2) 
![Untitled](https://github.com/user-attachments/assets/f1866ad7-52e6-4fa3-b515-744c396a89b6)
 <br> <br>
## 앱 와이어프레임(사용툴 : 파워포인트) <br>
![page1](https://github.com/eueu29/AIFFEL_quest/assets/161274014/3a20cbb9-267b-48b0-977c-75f38b0af43c)
![page2](https://github.com/eueu29/AIFFEL_quest/assets/161274014/e1098439-4b52-435f-95f2-aa927207db9c)  
<br><br>
## 프로토타이핑 구현 <br>
![kakao_prototyping_gif](https://github.com/eueu29/AIFFEL_quest/assets/161274014/1337de6b-1809-4fc5-a905-28c36c9fa38e)  
 <br> <br>
## 페이지 구현  
![result_1](https://github.com/eueu29/AIFFEL_quest/assets/161274014/9049f56b-f368-42b6-9573-8aa2f1e18c9f)
![result_2](https://github.com/eueu29/AIFFEL_quest/assets/161274014/f2aa30d0-44e0-4d76-89dd-d8f89f67cc22)
![result_3](https://github.com/eueu29/AIFFEL_quest/assets/161274014/b57fc17a-a788-4f85-9523-b6f70bccf71f)

 <br> <br>  
## 구현영상
 ![result_gif](https://github.com/eueu29/AIFFEL_quest/assets/161274014/4216c0ce-85c2-4053-96cc-2e5bebf80b21)

 <br> <br>  
## 참고 학습자료  
github에 동영상 삽입방법 참고함 : https://ndb796.tistory.com/557 <br>
getX 사용법:   
- https://pub.dev/packages/get#installing
- https://velog.io/@mi-fasol/Flutter-getX-%ED%99%9C%EC%9A%A9-%EB%9D%BC%EC%9A%B0%ED%8C%85-%EA%B4%80%EB%A6%AC
- https://salmonpack.tistory.com/27
 <br> <br>  
## 회고  
애니메이션을 넣고싶어서 getX에 대해서도 알아보고 했는데 역시 급조로 적용하기엔 애로사항이 많았다.<br>
그래서 결국 다시 익숙한 navigator로 돌아왔지만 참고학습자료에는 참고했던 자료들을 남겨뒀다.<br>
처음 페이지는 5초간만 보여주고, 자동으로 넘어가게 구현하고 싶었는데, 첫번째 퀘스트 때 'dart:async'패키지를 사용해서 타이머를 구현했던 기록을 다시 보면서 작성했더니 생각보다 잘 구현 된것 같다.<br>
역시.. 버릴게 없는 아이펠 코어과정..!<br>
친구목록과 채팅목록을 구현했는데, 실제 카카오톡 처럼 각각 보여주는 항목을 다르게 설정하였다. <br>
친구목록 : 사진, 이름, 상태메세지<br>
채팅목록 : 사진, 이름, 메세지내용, 보낸시간<br>
여기서 목록의 내용들을 입력받고, 수정하는 부분까지 나아가서 진행해보고 싶다. 구조도 아직 아쉬운 부분이 많아서 한개의 column에 여러개의 row를 넣어서 구성하는것도!!<br>
실제 잘 작동하는 앱을 만드는것은 역시 힘들구나..를 깨달았고. statefulwidget, statelesswidget 사용법과 이런저런 기능들을 사용하는 방법을 조금은 더 익힌 것 같다. <br>
시간이 부족해서 주석을 제대로 달지 못한점이 조금 아쉽고, 이정도 기능만 구현하는데도 쉽지 않았는데, 실제 카카오톡은 대체.....  모든 개발자분들이 존경스러워지는 순간이었다. <br>
이 학습을 계기로 앞으로는 어플을 접할 때 이건 어떻게 구성돼있고, 어떻게 구현하는걸까? 를 항상 생각하면서보게될 것 같다.<br>
그래도 나만의 어플만들기! 에 한발짝 다가간 느낌이라 뿌듯하다. 이제 아이디어만 구하면 되겠다 ㅎㅎ
