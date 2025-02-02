### VPC Endpoint란?

**Amazon VPC Endpoint**는 Amazon Virtual Private Cloud(VPC) 내에서 **퍼블릭 인터넷을 거치지 않고 AWS 서비스와 안전하게 통신**할 수 있도록 하는 네트워크 구성 요소입니다.  
이를 통해 데이터 전송을 **AWS 네트워크 내에서만 이루어지도록** 하여 보안과 성능을 강화합니다.

### VPC Endpoint와 다른 네트워크 서비스 비교

| **특징**        | **VPC Endpoint**   | **NAT Gateway**   | **Direct Connect** |
| ------------- | ------------------ | ----------------- | ------------------ |
| **사용 목적**     | AWS 서비스와 안전한 통신    | 퍼블릭 인터넷을 통한 외부 연결 | 온프레미스 네트워크와 전용 연결  |
| **인터넷 필요 여부** | 불필요                | 필요                | 불필요                |
| **보안**        | 프라이빗 네트워크 내부 통신    | 퍼블릭 인터넷 연결로 보안 위험 | 전용 연결로 높은 보안       |
| **비용 효율성**    | NAT 게이트웨이보다 비용 효율적 | 데이터 전송 비용 추가      | 고정 비용 발생           |


