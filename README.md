# ipfs-test

## 인스톨

실행 확인
ipfs

KeyPair 생성 (지갑 생성과 비슷)
ipfs init

to get started
ipfs cat /ipfs/<HASH>/readme

Quick Start (Usage examples)
ipfs cat /ipfs/<HASH>/quick-start

## 기본 파일 설치

ipfs에 파일 추가
ipfs add -r .

현재 폴더 Hash 조회
ipfs ls <현재폴더의 HASH>

IPFS 파일을 Local 파일로 복사
ipfs cat <CAT파일의 HASH> > cat2.jpg
dir
open cat2.jpg
HASH 값 같은 것 확인

IPFS Daemon 기동
ipfs daemon

IPFS 내 정보 조회
ipfs id
 
연결된 노드들을 볼 수 있다
ipfs swarm peers
ipfs if <PEERS의 ID>


브라우저에서 조회
http://localhost:8080/ipfs/QmYwdsJsZZ4ZLTZT653etfgAr8BV97iv82GEKkmMpfDpUf
HASH 모르면 : ipfs add -r .

외부 브라우저에서 조회
gateway.ipfs.io/ipfs/<HASH>
파일명이 바뀌어도 조회 된다

IPFS 로고는 누군가 갖고 있다

WebUI
http://localhost:5001/webui
