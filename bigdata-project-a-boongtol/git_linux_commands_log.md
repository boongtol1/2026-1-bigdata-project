# 🧪 Git 및 리눅스 명령어 실행 기록

## 📌 Git 명령어 실행

```bash
# Git 버전 확인
git --version

# 저장소 복제
git clone https://github.com/example/repo.git

# 프로젝트 폴더 이동
cd repo

# 변경사항 확인
git status

# 모든 변경사항 스테이징
git add .

# 특정 파일만 스테이징
git add app.py

# 커밋
git commit -m "프로젝트 초기 설정"

# GitHub에 업로드
git push

# 최신 내용 가져오기
git pull
```

---

## 📌 리눅스 명령어 실행

```bash
# 파일에서 특정 텍스트 검색
grep "검색어" 파일.txt

# 파일 목록에서 키워드 필터링
ls | grep "키워드"

# 빈 파일 생성
touch newfile.txt

# 파일에 내용 쓰기
echo "내용" > file.txt

# 파일 앞 5줄 보기
cat file.txt | head -5

# 파일 뒤 5줄 보기
cat file.txt | tail -5

# 파일 줄 수 세기
wc -l file.txt

# python 위치 확인
which python

# 환경변수 설정
export MY_VAR="값"

# 명령어 연속 실행
command1 && command2
```
