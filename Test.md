# GIT push 방법

1. '최신' main을 땡겨온다. git pull origin main

2. '내 연습장(브랜치)'을 판다. git checkout -b docs/add-spring-note (생성과 동시에 그 브랜치로 '이동')

3. '코딩'을 한다. (파일 만들고, 오늘공부.md 존나 채워)

4. '포장'하고 '송장'을 쓴다. (add, commit) git add . ->  git commit -m "docs: 스프링 어노테이션 정리"

5. '내 브랜치'로 push 한다. (main 아님!) git push origin docs/add-spring-note

6. '깃헙'으로 꺼져. (홈페이지 열어)

7. 그럼 노란색으로 "너 docs/add-spring-note 푸시했네? 'Pull Request' 만들래?" 하고 '초록색 버튼'이 떠.

8. 그거 '클릭'해.

9. '합쳐주세요(Pull Request)' 요청서 작성

10. "형, 저 스프링 노트 정리 다 했어요. 'main'에 합쳐주세요." 라고 '글' 쓰고 '요청' 버튼 누르기.

11. (리뷰 및 Merge)

- 원래는 '팀장'이 니 코드(PR) 보고 "야, 코드 X같네. 수정해" (리뷰) 하고...

12. OK 되면 '팀장'이 Merge 버튼을 눌러.

- 마무리 : 그때! 비로소! 니 코드가 'main'에 합쳐지는 거야.

(난 혼자니까 니가 'Merge' 버튼 누르면 됨 ㅋㅋㅋ)