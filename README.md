# iOS15beta

- iOS 15 베타에 iCloud+ 비공개 릴레이 라는 기능이 생겼다.
- VPN 같은 거라는데,,, 일단 막연하게 알고 있는 VPN에 대해서 조사해보자.

1. VPN
- Virtual Private Network, 가강 사설 망
- VPN은 인터넷에 사용되는 모든 네트워크 패킷을 암호화 해서 믿을수 있는 VPN 서버에 보내고, 
- 그 서버가 나를 대신하여 인터넷에 접속하고 그 결과를 돌려준다. 
- 내 컴퓨터와 VPN서버 사이에는 안전하게 암호화가 되어 그 내용을 중간에서 볼 수 없기 때문에 인터넷이 안전하다고 볼 수 있다.
- 물리적 주소를 내포하는 (접속자)단말 IP를 숨길 수 있기 때문에 지역(국가) 기반 제약을 우회 할 수 있다.
- 원하는 지역(국가)의 VPN 서버에 접속하는 방식.

2. Android 단말서 VPN 사용
- 구글 공식 문서 : https://support.google.com/android/answer/9089766
- 기타 : https://www.itworld.co.kr/news/121080

3. iOS 단말서 VPN 사용
- https://www.itworld.co.kr/news/108624
- https://m.blog.naver.com/dkflehd15/221792608554

다시 원래 목적으로 돌아와서 iOS 15 베타에 추가된 icloud 비공개 릴레이를 살펴보자.

1. iCloud Private Relay
- 웹 브라우징 트래픽을 암호화해서 위치, IP, 트래픽 내의 콘텐츠를 숨기는 것
- 참고 : https://www.itworld.co.kr/insight/198019

2. VPN과 다른점
- 사파리에서만 동작

3. 사이드 이펙트
- 해외 IP 차단 기능이 있는 웹사이트 접속이 안된다는 말이 있는데 실제 베타 단말 서 서비스 점검 필요. 
- 인프라, 네트워크에 해당 차단 기능이 있는지...

