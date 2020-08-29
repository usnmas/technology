# Glossary for wireless network


## 6LoWPAN (IPv6 over Low-power Wireless Personal Area Networks)

IPv6의 한 패킷 크기는 1,280바이트이며 헤더의 크기가 최소한 40바이트이다. 기존의 인터넷의 주요 링크 프로토콜인 이더넷과 달리 사물인터넷의 주요 링크 프로토콜인 802.15.4 프레임의 크기는 127바이트이기 때문에 기존의 IPv6 프로토콜을 수용하기 위해서는 주소 압축 등을 포함하는 헤더 압축 등의 여러 가지 처리가 필요하다. 이를 수용하는 것이 **6LoWPAN** 이다. 현재 지그비, 스레드, 콘티키, mbed OS 등의 대부분 사물인터넷 관련 아키텍처나 오픈소스 플랫폼에서 수용하고 있다. [[source: [네이버 지식백과] IPv6와 6LowPAN (국립중앙과학관-사물인터넷)]](https://terms.naver.com/entry.nhn?docId=3386831&cid=58369&categoryId=58369)  

## NB-IoT (Narrowband IoT) 

NB-IoT is a Low Power Wide Area Network (LPWAN) radio technology standard developed by 3GPP. 180kHz의 좁은 대역으로 최대 250kbps의 데이터 전송 속도와 10km 이상의 광역 서비스를 지원하고, 이동성은 지원하지 않는다. 수도,가스,온도,전기 등 검침 센서, 스마트 조명, 위치 추적 기기 등과 같이 원거리에 있고 데이터 사용 빈도와 전력 소비가 적으며 이동성이 없거나 낮은 사물 인터넷(IoT) 기기에 적합. [[source: [네이버 지식백과] 협대역 사물 인터넷]](https://terms.naver.com/entry.nhn?docId=3377375&cid=42346&categoryId=42346)  

## Radar (RAdio Detection And Ranging) vs Antenna  

**Antenna is a part of the radar**. Antenna is the physical interface of any electronic device to the electromagnetic waves. These waves carry information such as: FM radio content, satellite TV content etc. A radar has such an antenna which first emits electromagnetic waves to the environment and senses reflections. The reflections tell the radar about the reflecting objects such as: enemy aircrafts, ships or cars on road. Along with the antenna, a radar also has circuitry for processing and display which helps a computer or human operator interpret and react to the reflecting object. [[source: Quora Q&A]](https://www.quora.com/What-is-the-difference-between-radar-and-antenna)  

## MIMO (Multi-Input and Multi-Output)

In radio, MIMO, is a method for multiplying the capacity of a radio link using multiple transmission and receiving antennas to exploit multipath propagation. MIMO has become an essential element of wireless communication standards including IEEE 802.11n (Wi-Fi), IEEE 802.11ac (Wi-Fi), HSPA+ (3G), WiMAX, and Long Term Evolution (4G LTE). MIMO / MISO / SIMO / SISO. [[source: Wikipedia]](https://en.wikipedia.org/wiki/MIMO)  

## Beamforming  

Beamforming or spatial filtering is a signal processing technique used in sensor arrays for directional signal transmission or reception. This is achieved by combining elements in an antenna array in such a way that signals at particular angles experience constructive interference while others experience destructive interference. Beamforming can be used at both the transmitting and receiving ends in order to achieve spatial selectivity. The improvement compared with omnidirectional reception/transmission is known as the directivity of the array. To change the directionality of the array when transmitting, a beamformer controls the phase and relative amplitude of the signal at each transmitter, in order to create a pattern of constructive and destructive interference in the wavefront. [[source: Wikipedia]](https://en.wikipedia.org/wiki/Beamforming) / [[additional ref. 반드시 필요한 5G 핵심 기술, 빔포밍]](https://blog.naver.com/sundooedu/221692044480)    

## signal-to-noise ratio (SNR)  

Signal-to-noise ratio is a measure used in science and engineering that compares the level of a desired signal to the level of background noise. SNR is defined as the ratio of signal power to the noise power, often expressed in decibels. A ratio higher than 1:1 (greater than 0 dB) indicates more signal than noise. [[source: Wikipedia]](https://en.wikipedia.org/wiki/Signal-to-noise_ratio)   

## carrier wave 

In telecommunications, a carrier wave, carrier signal, or just carrier, is a waveform that is modulated with an information bearing signal for the purpose of conveying information. This carrier wave usually has a much higher frequency than the input signal does. [[source: Wikipedia]](https://en.wikipedia.org/wiki/Carrier_wave) / [[additional ref. 반송파 AM FM PM PCM]](https://terms.naver.com/entry.nhn?docId=4390144&cid=60217&categoryId=60217)  

## speed of light 

*c = 3 X 10<sup>8</sup> m/s*  

## Kalman Filter  

In statistics and control theory, Kalman filtering, also known as linear quadratic estimation (LQE), is an algorithm that uses a series of measurements observed over time, containing statistical noise and other inaccuracies, and produces estimates of unknown variables that tend to be more accurate than those based on a single measurement alone, by estimating a joint probability distribution over the variables for each timeframe. The filter is named after Rudolf E. Kálmán, one of the primary developers of its theory. [[source: Wikipedia]](https://en.wikipedia.org/wiki/Kalman_filter) / [[additional ref. 상세블로그]](https://blog.naver.com/chrhdhkd/221985045311)  

## Gaussian Distribution 

In probability theory, a **normal (or Gaussian or Gauss or Laplace–Gauss) distribution** is a type of continuous probability distribution for a real-valued random variable. [[source: Wikipedia]](https://en.wikipedia.org/wiki/Normal_distribution) / [[additional ref. 지식백과]](https://terms.naver.com/entry.nhn?docId=3405308&cid=47324&categoryId=47324) 

## Wireless Device Fingerprint 

**Wireless device fingerprinting** is identification of radio transmitters using device-specific artifacts of their output signals, which are caused by natural variations of hardware properties. A device fingerprint, or signature, is a compact representation of such artifacts. Wireless device fingerprinting is distinct from **wireless channel fingerprinting**, which relates to motion detection and position tracking of radio transmitters. [[source: Springer Link - Encyclopedia of Cryptography and Security]](https://link.springer.com/referenceworkentry/10.1007%2F978-1-4419-5906-5_52#howtocite)  

## frequency / bandwidth / wavelength 

*f (frequency)  =  v (speed)  /  &lambda; (wavelength)*  
*B (bandwidth)  =  f<sub>U</sub>  -  f<sub>L</sub>*  
[[Source : Difference Between Frequency and Bandwidth]](https://circuitglobe.com/difference-between-frequency-and-bandwidth.html)  

