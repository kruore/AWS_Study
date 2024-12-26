**목적**: **보안 취약점 탐지 및 평가**

- **주요 기능**:
    1. **취약점 스캔**:
        - Amazon EC2 인스턴스, 컨테이너 이미지(ECR), 및 Lambda 애플리케이션의 보안 취약점을 스캔.
        - 운영 체제, 네트워크 접근성, 잘못된 구성 등을 점검.
    2. **자동 평가**:
        - 자산이 변경되거나 새로 생성될 때 자동으로 보안 평가를 수행.
    3. **취약점 관리**:
        - 보안 취약점(CVE)와 AWS 보안 모범 사례에 기반한 평가 결과 제공.
    4. **통합**:
        - AWS Security Hub 및 Amazon EventBridge와 통합되어 결과를 중앙에서 관리.
- **사용 사례**:
    - EC2, 컨테이너 이미지, Lambda 등에서 보안 취약점을 사전에 식별.
    - PCI DSS 같은 규정 준수 요건을 충족하기 위해 보안 상태 평가.