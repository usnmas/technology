# Glossary for wireless network


## 6LoWPAN (IPv6 over Low-power Wireless Personal Area Networks)

IPv6의 한 패킷 크기는 1,280바이트이며 헤더의 크기가 최소한 40바이트이다. 기존의 인터넷의 주요 링크 프로토콜인 이더넷과 달리 사물인터넷의 주요 링크 프로토콜인 802.15.4 프레임의 크기는 127바이트이기 때문에 기존의 IPv6 프로토콜을 수용하기 위해서는 주소 압축 등을 포함하는 헤더 압축 등의 여러 가지 처리가 필요하다. 이를 수용하는 것이 **6LoWPAN** 이다. 현재 지그비, 스레드, 콘티키, mbed OS 등의 대부분 사물인터넷 관련 아키텍처나 오픈소스 플랫폼에서 수용하고 있다. [[source: [네이버 지식백과] IPv6와 6LowPAN (국립중앙과학관-사물인터넷)]](https://terms.naver.com/entry.nhn?docId=3386831&cid=58369&categoryId=58369)  

## Radar (RAdio Detection And Ranging) vs Antenna  

**Antenna is a part of the radar**. Antenna is the physical interface of any electronic device to the electromagnetic waves. These waves carry information such as: FM radio content, satellite TV content etc. A radar has such an antenna which first emits electromagnetic waves to the environment and senses reflections. The reflections tell the radar about the reflecting objects such as: enemy aircrafts, ships or cars on road. Along with the antenna, a radar also has circuitry for processing and display which helps a computer or human operator interpret and react to the reflecting object. [[source: Quora Q&A]](https://www.quora.com/What-is-the-difference-between-radar-and-antenna)  

## MIMO (Multi-Input and Multi-Output)

In radio, MIMO, is a method for multiplying the capacity of a radio link using multiple transmission and receiving antennas to exploit multipath propagation. MIMO has become an essential element of wireless communication standards including IEEE 802.11n (Wi-Fi), IEEE 802.11ac (Wi-Fi), HSPA+ (3G), WiMAX, and Long Term Evolution (4G LTE). MIMO / MISO / SIMO / SISO. [[source: Wikipedia]](https://en.wikipedia.org/wiki/MIMO)  

## Beamforming  

Beamforming or spatial filtering is a signal processing technique used in sensor arrays for directional signal transmission or reception. This is achieved by combining elements in an antenna array in such a way that signals at particular angles experience constructive interference while others experience destructive interference. Beamforming can be used at both the transmitting and receiving ends in order to achieve spatial selectivity. The improvement compared with omnidirectional reception/transmission is known as the directivity of the array. To change the directionality of the array when transmitting, a beamformer controls the phase and relative amplitude of the signal at each transmitter, in order to create a pattern of constructive and destructive interference in the wavefront. [[source: Wikipedia]](https://en.wikipedia.org/wiki/Beamforming) / [additional ref. 반드시 필요한 5G 핵심 기술, 빔포밍](https://blog.naver.com/sundooedu/221692044480)    


