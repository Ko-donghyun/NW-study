# NW-study

## Network 기본
 - [데이터 전송과정](https://slenderankle.tistory.com/228)
 - [대역폭(BW; BandWidth)](https://blog.naver.com/on21life/221340548735)
   - 특정 기능을 수행할 수 있는 주파수의 범위(Hz 단위)
   - 신뢰성 있는 통신의 자료 전송률(data rate)은 통신을 위해 쓰이는 신호의 주파수 범위에 밀접하게 비례
     - 네트워크 대역폭(Network BandWidth)
     - 데이터 대역폭(Data BandWidth)
     - 디지털 대역폭(Digital BandWidth)
 
## [Waveform](https://guslabview.tistory.com/159)
 - [FDMA(Frequency Division Multiplex Access)](http://www.ktword.co.kr/abbr_view.php?m_temp1=806)
 - [TDMA(Time Division Multiplex Access)](http://www.ktword.co.kr/abbr_view.php?m_temp1=348&id=911)
 - [CDMA(Code Division Multiplex Access)](http://www.ktword.co.kr/abbr_view.php?nav=&m_temp1=253&id=386)

 - [OFDM(Orthogonal Frequency Division Multiplexing)](http://www.ktword.co.kr/abbr_view.php?m_temp1=2163)
   - 고속의 송신 신호를 수백개 이상의 직교(Orthogonal)하는 협대역 부 반송파(Subcarrier)로 변조시켜 다중화하는 방식
   - [참고](m.blog.naver.com › anniy7)

## 데이터 전송
 - [CP(Cyclic Prefix)](http://www.ktword.co.kr/abbr_view.php?m_temp1=3164)
   - 유효 심볼구간의 마지막 구간의 신호를 복사하여 앞에 삽입
   
## 연결
 - [MIMO(Multiple Input Multiple Output)](https://www.ni.com/ko-kr/innovations/white-papers/14/5g-massive-mimo-testbed--from-theory-to-reality--.html)
   - 송수신 기지국(BTS; Base Transceiver Station)에서 다량의 안테나(64개 이상)를 사용하여 무선 데이터 속도와 링크 안정성 향상
   - 페이딩 영향 감소, 대용량, 고속, 커버리지 증대 등의 효과를 얻는 다중 안테나 기술

## 검증
 - [LDPC(Low Density Parity Check Code)](https://medium.com/quantum-ant/ldpc-9de5241ee51e)
   - 네트워크에서 오류를 검출 또는 수정
   - <b>패리티 방식에 필요한 요소</b> : Overlapping 방식, 빠른 패리티 연산, 긴 메세지에도 적용 가능 + 모든 오류 검출 가능한 효율적인 패리티 방식이 필요
   - 저밀도 패리티 체크 등장
     - Parity Check Set가 담당하는 면적, 즉 밀도를 낮추자 => 세트에 해당하는 비트를 무작위로 선택
    
## 용어
 - [RRC(Radio Resource Control)](http://www.ktword.co.kr/abbr_view.php?m_temp1=5175&m_search=RRC)
   - 무선 자원 제어
 - [PDCP(Packet Data Convegence Protocol)](http://www.ktword.co.kr/abbr_view.php?m_temp1=5178&m_search=PDCP)
   - IP 헤더 압축 및 압축 해지, 사용자 데이터의 전송, Radio Bearer에 대한 시퀀스 번호 유지
   
## 기타
 - [참고](www.wlanpedia.org › Home › Technology)
