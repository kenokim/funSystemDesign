# 처리율 제한 장치의 설계

DoS 공격에 의한 자원 고갈과 비용 절감, 서버 과부하를 막는 효과.

## 면접에서의 대응
* 처리율 제한 장치의 종류, 시스템 규모 등에 대해 질문.
* 개략적인 설계안을 제시하고 동의를 구하기
### 처리율 제허나 알고리즘
* 토큰 버킷 - 지정된 용량을 갖는 컨테이너로, 꽉 차면 해당 요청 토큰은 버려짐.
* 누출 버킷 - 토큰 버킷과 비슷하나 FIFO 큐로 구현
* 고정 윈도 카운터
* 이동 윈도 카운터

### 분산 환경에서의 처리율 제한 장치
* 경쟁 조건, 동기화 문제를 해결하여야 함.

## 클라이언트 설계의 개선
* 클라이언트 측 캐시나 메시지 전송 빈도 제한으로 요청수 자체를 줄이는 기법
