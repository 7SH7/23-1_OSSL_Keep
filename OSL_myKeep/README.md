# OSS 수업에서 진행한 프로젝트 입니다.

기능설명

init : git init의 기능
(./keep init 입력시, 현재 작업 위치에 .keep이라는 이름의 폴더를 생성.)

track : git add의 기능
(./keep track [파일명]으로 작동)

untrack : 트래킹 하고 있던 파일 중 원하는 파일을 트래킹 해제하는 기능
(./keep untrack [파일명]으로 작동합니다.)

store : 트래킹 하고 있던 파일들을 커밋 메시지와 함께 저장하는 기능
(기능 사용 시, version이 1 추가됨. ./keep store "메세지"로 저장)

restore : 저장되어 있는 버전들 중, 원하는 버전으로 파일을 복구하는 기능
(./keep restore version으로 작동)

version : 현재 저장되어 있는 버전들의 정보와 메시지를 보여주는 기능
(./keep version으로 작동합니다.)
