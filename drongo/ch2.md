# 개략적인 규모 추정

통상적인 응답 지연 값으로 대략적인 응답 속도를 추정 가능.

* 메모리는 빠르지만 디스크는 아직도 느리다.
* 디스크 탐색은 가능하면 피해라.
* 단순한 압축 알고리즘은 빠르므로 인터넷으로 데이터를 전송하기 전에 가능하면 압축하라.
* 데이터 센터 간의 정보 교환에는 시간이 걸린다.

지연시간 계산, 가용성 계산, QPS(Query Per Second), 저장소 요구량 계산을 통하여 대략적으로 필요한 시스템 규모를 짐작할 수 있다.

(참고표는 책 본문에) 