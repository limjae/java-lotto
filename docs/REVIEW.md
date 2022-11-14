# 우테코 회고록

### 3주차

이번 3주차 과제는 로또 게임을 구현하는 과제이고 2주차에 비해 Enum 사용과 클래스 분리가 추가되었다.</br>
다만 2주차떄에도 클래스마다 역할을 생각하여 설계를 했었는데 덕분에 이번주에도 비슷한 흐름으로 설계를 진행하였다.</br>


비슷한 역할을 하는(6자리, 6자리+1자리) Lotto, WinningNumber에 대하여 어떻게 처리 할지 고민도 했었다.</br>
고민을 해본 결과 WinningNumber 속에 Lotto를 필드로 넣으면</br>
Lotto와 WinningNumber를 비교하는 로직이 역할과 잘 안맞을 수도 있을것 같아 별개의 클래스로 각각 구현했다.</br>


그리고 2주차에서 고민했던 사항들 중에 리플랙션을 써서 전부 코드를 다소 번거롭게 테스트하지 않기 위하여</br>
public 메소드를 테스트하여 private까지 검증이 되는 메소드를 구현하려고 설계를 마지막까지 변경 했었다.</br>

구현사항 중에서 Enum에 관한 부분도 추가 되었다. Enum을 사용했던 방법은 2가지였다.</br>
우선 첫번째로는 로또 결과와 그 상금을 Enum화 했었고, 두번째로는 매개변수가 필요없는 텍스트들에 대하여 Enum화 시켰다.</br>
다만 후자의 경우는 꼭 필요한 부분이였을까에 대한 의문이 남았다.</br>

마지막으로 git 커밋 메세지에도 변화를 주었다. </br>
지난주까지는 전부 영어로 작성하려고 노력했었는데 검토할 사람(한국인)이 분명하다 싶다면</br>
모호하게 영어를 작성할바에는 확실하게 한글로 작성하는게 나을지도 모르겠다는 생각을 하여 깃메세지를 한글로 작성하였다.</br>


이번주에는 다소 시간이 부족하여 결과물의 퀄리티가 부족하다고 생각하여 아쉬웠으나</br>
다음주에 더 신경써서 마지막만큼은 최선을 다하겠다.