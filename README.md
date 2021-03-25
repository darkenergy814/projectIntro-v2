**Git code**
---
새로운 저장소 만들기
```
git init
```
저장소 받아오기
```
git clone 링크
```
파일 추가
```
git add <파일이름>
```
파일 확정
```
git commit -m "확정본에 대한 설명"
```
변경 내용 발행
```
git push origin 브랜치 이름
```
원격 서버 주소 알려주기
```
git remote add origin <원격 서버 주소>
```
"feature_x"라는 이름의 가지를 만들고 갈아타기
```
git checkout -b feature_x
```
main가지로 돌아오기
```
git checkout main
```
가지 삭제
```
git branch -d feature_x
```
원격저장소에 맞춰 로컬 저장소를 갱신
```
git pull
```
변경 내용 병합
```
git merge <가지 이름>
```