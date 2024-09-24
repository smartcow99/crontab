# crontab🎆
##### crontab 학습

## 👨‍💻Team

|<img src="https://avatars.githubusercontent.com/u/139302518?v=4" width="100" height="100"/>|<img src="https://avatars.githubusercontent.com/u/78792358?v=4" width="100" height="100"/>|
|:-:|:-:|
|곽병찬<br/>[@gato-46](https://github.com/gato-46)|박현우<br/>[@smartcow99](https://github.com/smartcow99)|


## 주제🎞

### 우리 FISA 퇴실 서비스🎨
- shell script를 통해 우리 FISA 수강생 출결관리 페이지 접속
- 접속 후 퇴실 요청 수행
- crontab을 사용하여 평일 17시 51분에 수행 반복
- 반복 이후 1분 뒤 shutdown 명령어를 통해 자동으로 노트북 종료

### Crontab 명령어
``` bash
50 17 * * 1-5 /home/ubuntu/fisa_login.sh
