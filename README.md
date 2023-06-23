# HA_Related
1. Advanced SSH & Web Terminal 애드온에서 보호모드를 해제한후 애드온 재시작후 도커진입
2. ## 도커진입 명령어
   $ docker exec -it homeassistant bash
3. sh 파일 실행
   bash -c "$(wget -O - 'https://raw.githubusercontent.com/RunacKim/HA_Related/main/changing_map.sh')"
4. 명령 실행후 경로 선택   
  Connecting to raw.githubusercontent.com (185.199.110.133:443)
  writing to stdout
  -                    100% |***********************************************************************************************************************************************************************************************|  2895  0:00:00 ETA
  written to stdout
  INFO: '/usr/local/lib/' 에서 hass_frontend 디렉토리 찾는중...
  * 작업 대상 경로 목록
      0) 경로가 없음.
      1) /usr/local/lib/python3.10/site-packages/hass_frontend
  작업할 경로 번호를 입력하세요: 1
  INFO: '/usr/local/lib/python3.10/site-packages/hass_frontend 에서 패치 진행...
  INFO: frontend_es5/ 디렉토리 패치중..
    patch file : ./frontend_es5/447798b4.js
  INFO: frontend_latest/ 디렉토리 패치중..
    patch file : ./frontend_latest/23a91513.js
    patch file : ./frontend_latest/efb26c6b.js
  INFO: 작업 완료!!
