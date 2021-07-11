마인크래프트 간단하게 하기
간단한 간단한 개요. 당신의 사용자는 WSL을 사용하세요.

환경
자바
리눅스(쉘)
사용방법 (아래 방법중 하나를 선택하세요)
- server.sh(기본)
.server/server.sh 파일 다운로드 wget https://raw.githubusercontent.com/monun/server-script/master/.server/server.sh
실행권한 부여 chmod +x ./server.sh
실행 ./server.sh(현재 폴더에서 실행)
[선택] 서버가 설치되어 있는 ./server.sh.conf 파일에 대한 요구 사항
- <server>.sh (사전 설정 가능)
희망하는 방법 선택
예) 종이 펼치기 다운로드 wget https://raw.githubusercontent.com/monun/server-script/master/paper.sh
예) 프로젝트를 완료 git clone https://github.com/monun/server-script.git
[선택] 깔깔깔 (정등)
실행권한 부여 chmod +x ./<script>.sh
실행 ./<script>.sh(.<script> 폴더에서 server.sh 펼쳐서 실행)
[선택] 사전설정된 펼쳐보기
server.sh.conf의 서버 설정 (서버로 호출 jar파일)
URL(웹에서 파일을 다운로드하여 ~/.minecraft/server/폴더에 저장 후 서버 시작)
server=https://papermc.io/api/v1/paper/1.7/latest/download
갑포
server=/user/monun/my.jar
server=$HOME/.jar
server=C:\\Users\monun\my.jar
지금부터 해결
server=
