# ejs
## 1. ejs파일 형식은 html과 거의 똑같다.
## 2. html을 조각 내서 필요한 파일(head, header, footer, foot 등 공통사항) 을 불러다 쓴다.
## 3. css는 public(사용자가 접근할 수 있도록 지정해둔 파일: Static Router) 폴더에 넣는다.
## 4. 따라서 구성은
```
***** 모든 페이지의 공통구성 *****
head.ejs
header.ejs
footer.ejs
foot.ejs

***** http://127.0.0.1:3000/gallery의 화면구성 *****
head.ejs
header.ejs
gallery.ejs
list.ejs (gallery의 사진 리스트를 구성)
footer.ejs
foot.ejs


***** http://127.0.0.1:3000/gbook의 화면구성 *****
head.ejs
header.ejs
gbook.ejs
list.ejs (gbook의 방명록 리스트를 구성)
footer.ejs
foot.ejs
```
