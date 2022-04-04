# 오늘 배운 Tip

1. mv [기존 파일 및 폴더명] [새로운 파일 및 폴더명]
2. mv [옮길 전 파일 및 폴더] [옮길 경로]

- mv를 써도 되지만 git mv 쓰는게 더 Best이다.

- mv를 쓰면 git에서 삭제된걸로 인식하기때문에
  git mv를 쓰면 자동으로 처리되어 내역이 안남는다.

# Commit Convention

1. 커밋 제목은 50자 이내로 요약하여 작성한다.

2. prefix를 사용하여 한 눈에 커밋의 용도를 알기 쉽게 한다.

- docs : Documentations (문서 수정 작업) 

- feat : Features (새로운 기능 추가)

- cont : Configuratioms (환경설정 관련)

- test : (테스트 코드, 리펙토링 테스트 코드 추가)

- fix : (오류 개선 및 버그 수정)

- refactor : (코드 리펙토링)

- ci : Continuous Integration (빌드/테스트 자동화 과정) , 
(개발자를 위한 자동화 프로세스인 지속적인 통합)

- build : (빌드 관련) (서버에 올릴 수 있는 상태로 만드는 것)
