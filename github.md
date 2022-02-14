# 1. **Git 설치하기** (최초 1회)
    홈페이지에서 파일 다운로드 후, 설치 진행
    <Terminal에서 확인>
    $ git --version //버전 확인
    
<br>

# 2. **Github에 repository 만들기**

  ## 저장소를 생성합니다
    Repository name: 저장소의 이름

    Description: 저장소에 대한 간단한 설명

    Public: 저장소를 모두에게 공개

    Private: 지정된 사람에게만 공개

    initialize this repository with a README를 체크해주면
    저장소가 생성될 때 README.md 파일이 자동으로 함께 생성된다.

    모두 작성했다면 Create repository 버튼을 눌러 생성한다
<br>

# 3. **Git 초기설정**
    $ git config --global user.name 'github 가입이름'
    $ git config --global user.email 'github 가입 이메일'
    $ git config --global core.autocrlf true (OS별 달라지는 문제 해결)
<br>

# 4. **Git(local branch)에 커밋**
    $ git init (git - local branch에 repository 생성)
      $ git config --global --list (git에 등록된 정보 확인)
      $ git status (git에 파일들이 버전관리가 되어 있는지 확인)
    $ git add . (모든 파일을 버전관리한다)
    $ git commit -m  '프로젝트 이름' (새로운 버전 생성)
      $ git log (버전 확인)
<br>

# 5. **GitHub Repository에 push**
    github 원격주소를 복사
      $ git log (버전 확인)
    $ git remote add origin 링크(오리진이라고 불리는 링크 저장소)
    $ git push origin 브랜치이름 (해당 브랜치에 push)
<br>

```python
'브랜치는 master브랜치와 기타 브랜치가 있다'

master = 사이트에 반영
branch = 사이트에 반영 X
```
<br>

# 6. **Github 로그인으로 권한 허용** (최초 1회)
    알림 -> continue -> authorize -> login -> visual studio code.app 열기 -> password 입력