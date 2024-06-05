![remon](/images/remon.png)
# REMON
### REMON은 Redis Multi-instance Monitoring 의 약자로 Redis 데이터베이스의 상태를 모니터링하여 사용자에게 Redis 인스턴스들이 정상 작동되고 있는지 한눈에 볼 수 있도록 편의기능을 지원하는 소프트웨어입니다.

### 1. 주요기능 및 특장점
- Matrix view : Redis instance를 그룹별로 묶어서 모니터링할 수 있습니다.

![matrixview](/images/matrixview.png)
- CPU 부하 최소화 : agent의 CPU 사용률이 2% 이하로 매우 적은 부하를 유발합니다.

![cpu](/images/cpu.png)
- 임계치 알림 및 빠른 확인 : 관리자메뉴 임계치 설정 화면에서 지표의 임계값 설정으로 중요 지표를 모니터링하고 알림을 발송할 수 있습니다.

![stats](/images/stat.png)

### 2. 구성요소
- Agent : 설치된 인스턴스의 OS 지표, Redis 지표 수집
- DB : 각 인스턴스에서 수집된 지표 저장
- WAS : 수집된 지표 Visualization

### 3. Version
- Standard : 일반적인 모니터링 기능
- Enterprise : 일반적인 모니터링 기능에 클러스터 관련 지표 모니터링
- Community : 일반적인 모니터링 (1개 인스턴스)

### 4. Community Version
- 본 프로젝트를 통해 배포되는 버전은 Community 버전으로 1개 인스턴스에 대한 모니터링 기능을 제공합니다.
- 개인 사용자에 한하여 무료로 사용가능합니다.
- 본 소프트웨어의 저작권 및 특허는 (주)씨에스리에 있으며, 변경이나 무단전재 및 재배포는 금지됩니다.

### 5. 설치 
1) mariadb_console_install.pdf 내용 확인(Community_install_File.zip파일 사용, mariadb, WAS 설치)
2) redis_agent_install.pdf 내용 확인(remon_agent.zip파일 사용, redis, agent 설치)

### 6. 제품소개
- https://blog.cslee.co.kr/remon-redis-monitoring-solution/
- https://www.cslee.co.kr/remon.html

### 7. 도입문의 
- sypark@cslee.co.kr
- 02-307-0182
