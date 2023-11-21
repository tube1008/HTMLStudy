1. 안일혁은 잘생겼다
2. 피부미남
3. 똑똑이다
4. 사랑스럽다
5. 최고다

git and github 순서
* 초기 디렉터리 생성시 순서
1. git init - 저장소 등록
2. git branch -m main
        master - main 으로 이름 변경
3. git remote add origin HTTPS주소 붙여넣기
    origin == github HTTPS 주소별칭
----------------------------------------------
* 초기 디렉터리 생성후 작업 진행시 순서

1. git add .
    *. 이란? == 현재 디렉터리 안 모든 파일과 폴더를 뜻함.
2. git commit -m 'message'
    *현재 스테이징된 파일의 기록명을 작성(영어, 한글 모두가능, 짧게 키워드 위주로 작성하기)
    *ex) 쇼핑몰 상품 페이지를 만들었다면?
    *    git commit -m 'shp man-product end'
    *    git commit -m '쇼핑몰 남자복 완성'
3. git push origin main
    *origin == github wnth
    *main -- local 내컴퓨터 위치
    *해석 == github에 local 작업물을 push 하겠다.
-----------------------------------------------
*위 add -> commit -> push 순서 중간 중간 작업 확인 리눅스 명령어

1. git status 
    local 과 Staging 상태에서 작업물의 등록 상태 체크

2. git log
    commit과 push 상태에서 작업물의 commit 기록과 업로드 정보체크

-----------------------------------------------

# h1~h6 tag(block)
* 제목 태그는 검색 키워드 역할을 하며 페이지 내에서 대.중.소 제목역할을 한다.
* h1이 가장 중요한 제목이며 h1, h2, h3 위주로 많이 사용한다.