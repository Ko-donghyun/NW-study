# shell 프로그래밍 기본
 - 자동 테스트 프로그램 만들기 
 
## [Loop](https://skylit.tistory.com/321)
 - 반복문 For 문
```
SET=$(seq 0 9)

for i in $SET
do
    echo "Running loop seq "$i
    # some instructions
done
```


## [sleep](https://brocess.tistory.com/84)
 - 프로세스 Sleep 모드
```
sleep 5  # Waits 5 seconds.
```


## [timeout](http://bahndal.egloos.com/595779)
 - 특정 시간 이내 동안만 수행
```
timeout 3.5s sleep 10
```

### [exec과 eval](https://neet.tistory.com/entry/bash%EC%97%90%EC%84%9C-exec%EC%99%80-eval%EC%9D%98-%EC%B0%A8%EC%9D%B4%EB%8A%94-%EB%AC%B4%EC%97%87%EC%9D%BC%EA%B9%8C)

### g++
C로 구현된 코드는 gcc compiler로 C++로 구현된 코드는 g++ compiler로
https://erato1004.tistory.com/entry/exturn-C


