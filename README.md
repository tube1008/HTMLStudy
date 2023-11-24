
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

-----------------------------------------------

# p tag (block)
* 단락(내용)태그로 제목 아래 내용을 구성할 때 사용한다.

-----------------------------------------------

# em, strong tag(inline)
* 강조의미를 가진 em, strong은 블록 내에서 강조처리를 할때 사용한다.
* 제목 태그(h)안에는 em , strong 을 사용하지 않는다. (이미 강조하고 있어서 사용x)

-----------------------------------------------

# sub, sup 아래첨자, 위첨자(inline)
# del 교체, 삭제 텍스트(inline)
# blockquote 긴 인용문(block)
# q 짧은 인용문(inline)
# address 연락처 및 주소정보(block)
    * address 자식, 자손으로는 inline 요소만 배치할수 있다.
# hr  수평선 (block)

# div태그 그룹 (block)
    * 2개 이상의 인라인 or 블록 요소를 묶어주는 그룹 태그입니다.

# span태그 인라인 그룹 (inline)
    * 2개 이상의 인라인 요소를 묶을 때 사용합니다.


.class : 반복 유형 분류시 사용, 반복지정 가능
#id : 전체 페이지 중 단 하나의 요소에만 지정 시 사용
class, id는 태그 관계없이 모든 태그에 적용할 수 있다.

span 을 인라인 그룹으로 사용할때 class 또는 id 명을 함께 사용한다