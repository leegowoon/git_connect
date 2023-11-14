# git_connect

# git 설치 >> 기본값으로 그대로 설치했음

# 시작버튼에서 Git Bash 열기(실행)

```
git config --global user.name "gowoon"
```

# github 가입시 입력한 이메일과 동일해야한다.
```
git config --global user.name "cui480751@gmail.com"
```

# 정보 확인하기
```
git config --list
```
![image](https://github.com/leegowoon/git_connect/assets/145514701/b1ffe2e5-966d-4808-b4df-45a564507d87)

⬆️ 의 내용은 컴퓨터에 한번만 설치하면 된다.

-----
-----

# GitHub에 코드 업로드하기 💛

1. 초기화
  
  ```
  git init
  ```

# .git이라는 폴더가 생성된다

2. 파일 올리기 (모든것을올리겠다)

   ```
   git add .
   ```

3. history 만들기
   ```
   git commit -m "내가 적고싶은 메세지"
   ```
   ☑️ 메세지에는 한글이 가능함
   -m은 메세지의 준말

4. GitHub repository랑 내 로컬 프로젝트랑 연결 (GitHub에 프로젝트를 올릴 repository를 먼저 만들어야한다)
    # 아래 주소는 GitHub에서 만든 repository에서 복사해서 가져와야한다(repository를 만들 때 readme 선택하지 말기!)

  ```
  git remote add origin https://github.com/leegowoon/webstandard.git
  ```

5. 잘 연결되었는지 확인(필수 아님)
  ```
  git remote -v
  ```

6. GitHub에 자료 올리기
   ```
   git push origin master
   ```

   # 여기까지 하면 GitHub의 repository에 자료가 올라가 있다.

---
# 💕 요약
# 1) GitHub에 new repository 만들기 (remade체크X) 
# 2) git init >> git add . >> git commit -m "내가 적고싶은 메세지" >> git remote add origin https://github.com/leegowoon/webstandard.git >> git push origin master
--- 
# 💚 netlify
1) new > import > deploying github >> deploying > 2로 바뀔 때까지 기다린다.

2) Site configuration > change site name

3) index.html의 주소 ex) "https://figmasite22.netlify.app/___" 바꿔서 연결하기
   
