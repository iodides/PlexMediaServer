# PlexMediaServer  

각종 어플리케이션 및 스크립트를 활용하여 '거의 자동화된' Plex 서버를 구성  
환경마다 성능 및 효율이 다를 수 있으므로 본인 환경에 맞는 최적화 구성이 필요

## 1. Hardware
서버 : Gigabyte Brix GB-BLCE-410  
CPU : Intel Celeron J4105  
MEM : DDR4 8GB  
DISK : M2 SSD 120G / SSD 512G  
O/S : Ubuntu 18.04

## 2. Architecture

## 3. Folder Structure
- 폴더는 서버내의 실제 디스크 공간을 사용하는 local 폴더와, 구글드라이브를 마운트한 google 폴더, 그리고 그 둘을 합친 union 폴더로 구성한다.
- 각각 /local, /google, /union 으로 표현한다.

