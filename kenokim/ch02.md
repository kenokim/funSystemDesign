## ch2
- Q1). QPS 를 추정했다고 가정하고, 서버 스펙을 어떻게 산정할 것인가?
- Q2). QPS 를 추정해서 서버 스펙을 산정했는데, 최대 트래픽과 평균 트래픽이 차이가 심할 경우 서버 비용을 절약할 수 있는 방법? 
- Q3). QPS 가 스파크성으로 몰리면 어떻게 대응할 것인가?

### 참고자료
- https://learn.microsoft.com/en-us/azure/azure-monitor/autoscale/autoscale-get-started?toc=%2Fazure%2Fapp-service%2Ftoc.json
- https://keda.sh/
- https://aws.amazon.com/ko/blogs/tech/amazon-aurora-auto-scaling-strategy-for-ktown4u-global-spike-traffic-response/

### db sharding 관련
1. application level
2. middleware level
3. infra level 에서 가능
- 아래는 ProxySQL 을 통해 MySQL 를 샤딩하는 사례
- https://www.youtube.com/watch?v=8Eb_n7JA1yA
