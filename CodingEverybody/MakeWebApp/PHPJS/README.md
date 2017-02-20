php 소스 코드를 변경한 후에 반영되지 않는 문제가 있을 수 있습니다. 이런 경우  

MAC 사용자의 경우 아래의 파일을 열어주세요. 
/Applications/mampstack(버전번호)/php/etc/php.ini

윈도우 사용자의 경우 아래의 파일을 열어주세요. 
C:\Bitnami\wampstack(버전번호)\php\php.ini

이 파일에서 opcache.enable=0 라고 되어 있는 부분을 opcache.enable=1로 변경 하신 후에 Apache를 재시작하시면 됩니다.  (아파치 재시작 방법을 모르시면 서버제어 참고)

잘 안되는 분은 아래 영상을 참고해주세요. 
https://www.youtube.com/watch?v=PrxI52lc9AA
만약 위의 경우로도 해결되지 않으면 웹브라우저에 저장된 임시 파일의 문제일수도 있습니다. 이런 경우 아래의 방법으로 웹페이지를 리로드 해주세요. 

Windows: ctrl + F5
Mac/Apple: Apple + R or command + R
Linux: F5