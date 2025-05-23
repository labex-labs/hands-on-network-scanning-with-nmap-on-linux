# Linux 환경에서 Nmap 을 이용한 실전 네트워크 스캐닝

## 언어

🇨🇳 [简体中文](README_zh.md) 🇪🇸 [Español](README_es.md) 🇫🇷 [Français](README_fr.md) 🇩🇪 [Deutsch](README_de.md) 🇯🇵 [日本語](README_ja.md) 🇷🇺 [Русский](README_ru.md) 🇰🇷 [한국어](README_ko.md) 🇧🇷 [Português](README_pt.md) 🇺🇸 [English](README.md) 

[![Linux 환경에서 Nmap 을 이용한 실전 네트워크 스캐닝](https://cover-creator.labex.io/hands-on-network-scanning-with-nmap-on-linux.png?lang=ko)](https://labex.io/ko/courses/hands-on-network-scanning-with-nmap-on-linux)

[![Start-Learning](https://img.shields.io/badge/Start-Learning-whitesmoke?style=for-the-badge)](https://labex.io/ko/courses/hands-on-network-scanning-with-nmap-on-linux)

Linux 에서 Nmap 을 사용하여 네트워크 스캐닝을 마스터하세요! 실습을 통해 호스트 탐지, 포트 스캐닝, OS 탐지, 방화벽 우회 등 실용적인 기술을 배우세요.

![Cybersecurity](https://img.shields.io/badge/Cybersecurity-whitesmoke?style=for-the-badge&logo=cybersecurity)
![Nmap](https://img.shields.io/badge/Nmap-whitesmoke?style=for-the-badge&logo=nmap)


## 환경

LabEx 는 코딩과 기술에 전념하는 대화형 실습 학습 플랫폼입니다. 실험실, AI 지원 및 가상 머신을 결합하여 비디오 없는 실용적인 학습 경험을 제공합니다.

![](https://tutorial-screenshot.getvm.io/images/vm-1725247253.png)

- 비디오 없는 독점적인 실습 실험실로 엄격한 "실습을 통한 학습" 접근 방식.
- 브라우저 내 대화형 온라인 환경에서 자동화된 단계별 확인.
- 스킬 트리 기반 시스템으로 구조화된 콘텐츠 구성.
- 30 개의 스킬 트리와 6,000 개 이상의 실험실을 포함하는 성장하는 학습 리소스.
- ChatGPT 를 기반으로 구축된 AI 학습 도우미 Labby 가 제공하는 대화형 학습 경험.

자세히 알아보기 [LabEx VM](https://support.labex.io/using-labex/virtual-machine).

## 연습

|   인덱스 | 이름                                            | 난이도   | 연습                                                                                                                    |
|----------|-------------------------------------------------|----------|-------------------------------------------------------------------------------------------------------------------------|
|       01 | 📖 Linux 에 Nmap 설치하기                       | 초급     | <a target='_blank' href='https://labex.io/ko/tutorials/nmap-install-nmap-on-linux-530181'>실습 시작</a>                 |
|       02 | 📖 Nmap 도움말 및 옵션 탐색                     | 초급     | <a target='_blank' href='https://labex.io/ko/tutorials/nmap-explore-nmap-help-and-options-in-nmap-547101'>실습 시작</a> |
|       03 | 📖 Nmap 명령 구문 이해                          | 초급     | <a target='_blank' href='https://labex.io/ko/tutorials/nmap-understand-nmap-command-syntax-530159'>실습 시작</a>        |
|       04 | 📖 Specify Targets for Scanning in Nmap         | 초급     | 곧 출시                                                                                                                 |
|       05 | 📖 Randomize Targets in Nmap                    | 초급     | 곧 출시                                                                                                                 |
|       06 | 📖 Perform Host Discovery with Nmap             | 초급     | 곧 출시                                                                                                                 |
|       07 | 📖 Perform Advanced Host Discovery in Nmap      | 초급     | 곧 출시                                                                                                                 |
|       08 | 📖 Conduct Port Scanning with Nmap              | 초급     | 곧 출시                                                                                                                 |
|       09 | 📖 Execute UDP Scanning with Nmap               | 초급     | 곧 출시                                                                                                                 |
|       10 | 📖 Scan Specific Hosts in Nmap                  | 초급     | 곧 출시                                                                                                                 |
|       11 | 📖 Conduct TCP FIN Scanning in Nmap             | 초급     | 곧 출시                                                                                                                 |
|       12 | 📖 Execute TCP Null Scanning in Nmap            | 초급     | 곧 출시                                                                                                                 |
|       13 | 📖 Perform TCP Xmas Scanning in Nmap            | 초급     | 곧 출시                                                                                                                 |
|       14 | 📖 Conduct TCP ACK Scanning in Nmap             | 초급     | 곧 출시                                                                                                                 |
|       15 | 📖 Perform Window Scanning in Nmap              | 초급     | 곧 출시                                                                                                                 |
|       16 | 📖 Scan with Custom Ports in Nmap               | 초급     | 곧 출시                                                                                                                 |
|       17 | 📖 Scan IPv6 Targets in Nmap                    | 초급     | 곧 출시                                                                                                                 |
|       18 | 📖 Combine TCP and UDP Scanning in Nmap         | 초급     | 곧 출시                                                                                                                 |
|       19 | 📖 Perform Aggressive Scanning in Nmap          | 초급     | 곧 출시                                                                                                                 |
|       20 | 📖 Detect Services and Versions in Nmap         | 초급     | 곧 출시                                                                                                                 |
|       21 | 📖 Identify Operating Systems with Nmap         | 초급     | 곧 출시                                                                                                                 |
|       22 | 📖 Combine OS and Service Detection in Nmap     | 초급     | 곧 출시                                                                                                                 |
|       23 | 📖 Detect Service Banners in Nmap               | 초급     | 곧 출시                                                                                                                 |
|       24 | 📖 Enumerate HTTP Services in Nmap              | 초급     | 곧 출시                                                                                                                 |
|       25 | 📖 Manage Output Formats in Nmap                | 초급     | 곧 출시                                                                                                                 |
|       26 | 📖 Convert Output Formats in Nmap               | 초급     | 곧 출시                                                                                                                 |
|       27 | 📖 Analyze Scan Statistics in Nmap              | 초급     | 곧 출시                                                                                                                 |
|       28 | 📖 Optimize Scan Timing and Performance in Nmap | 초급     | 곧 출시                                                                                                                 |
|       29 | 📖 Adjust Packet Rates in Nmap                  | 초급     | 곧 출시                                                                                                                 |
|       30 | 📖 Simulate Network Conditions in Nmap          | 초급     | 곧 출시                                                                                                                 |
|       31 | 📖 Utilize Nmap Scripting Engine                | 초급     | 곧 출시                                                                                                                 |
|       32 | 📖 Scan for Vulnerabilities in Nmap             | 초급     | 곧 출시                                                                                                                 |
|       33 | 📖 Enumerate DNS Records in Nmap                | 초급     | 곧 출시                                                                                                                 |
|       34 | 📖 Detect SSL Certificates in Nmap              | 초급     | 곧 출시                                                                                                                 |
|       35 | 📖 Enumerate SMB Services in Nmap               | 초급     | 곧 출시                                                                                                                 |
|       36 | 📖 Evade Firewalls and IDS with Nmap            | 초급     | 곧 출시                                                                                                                 |
|       37 | 📖 Perform Idle Scanning in Nmap                | 초급     | 곧 출시                                                                                                                 |
|       38 | 📖 Spoof MAC Addresses in Nmap                  | 초급     | 곧 출시                                                                                                                 |
|       39 | 📖 Troubleshoot Nmap Scans                      | 초급     | 곧 출시                                                                                                                 |
|       40 | 📖 Perform Comprehensive Scanning in Nmap       | 초급     | 곧 출시                                                                                                                 |
|       41 | 📖 Automate Scans with Nmap                     | 초급     | 곧 출시                                                                                                                 |
|       42 | 📖 Compare Scan Results in Nmap                 | 초급     | 곧 출시                                                                                                                 |
|       43 | 📖 Simulate Real-World Scenarios in Nmap        | 초급     | 곧 출시                                                                                                                 |

## 더 보기

- 🔗 [Nmap 프로그래밍 코스](https://github.com/labex-labs/awesome-programming-courses)
- 🔗 [Nmap 프로그래밍 프로젝트](https://github.com/labex-labs/awesome-programming-projects)
- 🔗 [Nmap 무료 튜토리얼](https://github.com/labex-labs/nmap-free-tutorials)

