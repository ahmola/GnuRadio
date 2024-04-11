# Receiver, Transmitter

PlutoSDR에서는 무선 신호를 송수신할 수 있다.

GnuRadio에서 PlutoSDR Source와 PlutoSDR Sink 블록을 사용하면 가능하다.

PlutoSDR Source는 수신을, PlutoSDR Sink는 송신을 담당한다.

## PlutoSDR Source

IIO Context URI : PlutoSDR의 IP주소를 설정한다.

LO Frequency : RF신호를 낮출지 높일지 정하는 주파수. 송신 모드에서는 RF 신호를 낮춰 디지털 처리에 적합한 IF로 변조한다.
수신 모드에서는 받은 Baseband Signal을 높여 RF 신호로 변조 처리한다.

Quadrature : 수신된 신호를 디지털화 할지 정함. (자세한 내용은 I/Q Signal 참조, https://blog.naver.com/rlaghlfh/221112341508)
