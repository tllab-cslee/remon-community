![remon](/images/remon.png)
# REMON
### Redis Multi-instance Monitoring 의 약자로 Redis 데이터베이스의 상태를 모니터링하여 사용자에게 Redis 인스턴스들이 정상 작동되고 있는지 한눈에 볼 수 있도록 편리기능을 지원하는 소프트웨어.

### 1. 주요기능 및 특장점
- Matrix view : redis instance를 그룹별로 묶어서 모니터링

![matrixview](/images/matrixview.png)
- CPU부하 최소화 : agent의 CPU사용률 2% 이하

![cpu](/images/cpu.png)
- 임계치 알림 및 빠른 확인 : 관리자메뉴 임계치 설정 화면에서 지표의 임계값 설정으로 중요 지표의

![stats](/images/stat.png)

### 2. 구성요소
- Agent : 설치된 인스턴스의 OS 지표, redis 지표 수집
- DB : 각 인스턴스에서 수집된 지표 저장
- WAS : 수집된 지표 visualization

### 3. version
- standard : 일반적인 모니터링 기능
- enterprise : 일반적인 모니터링 기능에 클러스터관련 지표 모니터링
- shareware : 일반적인 모니터링 (1개 인스턴스)

### 4. community version
- 현재 배포되는 버전은 community로 1개 인스턴스에 대한 모니터링 기능 제공
- 개인사용자에 한해 누구나 설치해서 사용가능
- 본 소프트웨어의 저작권 및 특허는 (주)씨에스리에 있으며, 변경이나 무단전재 및 재배포는 금지됩니다.

### 5. 제품소개
- https://blog.cslee.co.kr/remon-redis-monitoring-solution/
- https://www.cslee.co.kr/remon.html

### 6. 도입문의 
- 박성용 영업이사 : sypark@cslee.co.kr 02-307-0182
