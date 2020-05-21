# INTRODUCE-MY-TEAM-DOCKER
해당 프로젝트는 현재 근무하고 있는 팀의 프로젝트를 관리하고 소개하기 위한 docker와 nginx기반의 페이지입니다.

실제 실무에서는 kubernetes 진입 루트 장비에 들어가는 소스이며,
월별로 프로젝트 진행내역이 업데이트 됩니다.

실제 프로젝트에는 
- 사용자들의 kubernetes 장비 접근 권한을 관리하는 yaml 파일
- 장비의 재시작을 위한 yaml 파일
- 외부노출을 위한 ingress yaml 파일
- kubernetes 서비스들의 reverse proxy 설정을 하는 yaml 파일
이 있어 전체 서비스를 총괄하는 역할을 합니다.

데모버전에서는 호스트의 팀이 어떤 프로젝트를 진행하는 지 간단한 아이콘과 설명만 노출합니다.

# Setting
docker와 docker-compose가 설치되어 있어야합니다.

# Preview
$ docker-compose up --build