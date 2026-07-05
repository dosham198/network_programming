# PCAP Packet Sniffing Program

화이트햇스쿨 네트워크 보안 - PCAP Programming 과제

## 개요
PCAP API를 활용하여 캡처한 TCP 패킷의 정보를 출력하는 프로그램입니다.
Ethernet Header(MAC), IP Header(IP), TCP Header(Port), HTTP Message를 출력합니다.

## 구성
- `sniff_improved.c` : 패킷 캡처 및 정보 출력 프로그램
- `myheader.h` : Ethernet / IP / TCP 헤더 구조체 정의

## 컴파일
gcc -o sniff_improved sniff_improved.c -lpcap

## 실행
sudo ./sniff_improved
