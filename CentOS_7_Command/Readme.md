- 시스템 종료 [링크](https://hihighlinux.tistory.com/18)
  - ``$ shutdown -P now``

- 디스크 용량 확인 [링크](https://gun0912.tistory.com/22)
  - ``$ df -h``

- 마운트 된 장치 확인 [링크](https://m.blog.naver.com/diceworld/220212713378)
  - ``$ fdisk -l``
  - fdisk 는 파티션 테이블 관리 명령어입니다. fdisk -l 을 하게되면 설정가능한 파티션 목록을 보여주기 때문에 해당 명령어를 통해 새로운 하드웨어 장치를 확인하실 수 있습니다.

- yum 설치 에러 시 [링크](https://nirsa.tistory.com/17)

- ~/.bashrc 파일 Reload
  - ``$ source ~/.bashrc``

- 파일 찾기 [링크](https://recipes4dev.tistory.com/156)
  - ``$ find /Directory -name "파일명"``

- 압축풀기
  - ``tar -xzf 파일명``
  - ``tar -xvf 파일명``
  
- [심볼릭 링크 만들기](https://gold9ine.tistory.com/entry/%EB%A6%AC%EB%88%85%EC%8A%A4-%ED%84%B0%EB%AF%B8%EB%84%90%EC%97%90%EC%84%9C-symbolic-link-%EB%A7%8C%EB%93%A4%EA%B8%B0)
  - 프로그램 명만 입력해도 실행될 수 있도록
  - ``$ sudo ln -s 프로그램위치 /usr/bin/내가 명령어로 쓸 이름``
  - /usr/bin에 명령어를 그대로 링크 걸면 바로 쓸 수 있음
  
- 백그라운드로 실행
  - ``./program &``
  
# vi  
- 문자열 찾기
  - /검색 문자열 후 Enter
  - 다음 문자열 n, 이전 문자열 N

- 문자열 복사 & 붙여넣기
  - 복사 : yy
  - 붙여넣기 : p

- 라인 번호 넣기
  - :set number

- 라인 찾아 가기
  - :라인번호
