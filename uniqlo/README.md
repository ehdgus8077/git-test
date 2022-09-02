# Mono-repository for Scatterlab research

스캐터랩 리서치에서 수행된 프로젝트들의 코드들이 모여있는 모노레포입니다!

## 모노레포 규칙

### 1. 프로젝트를 시작할 때, `project-name/master` 브랜치를 만들어주세요.

앞으로 프로젝트가 종료될 때까지, 해당 프로젝트 내에서 만들어지는 모든 PR은 모두 `project-name/master`에 머지하시면 좋습니다.

### 2. 프로젝트를 새로 생성하는 PR을 만들 때, 성현님과 주홍님을 리뷰로 걸어주세요.

성현님이 프로젝트 구조가 올바르게 만들어졌는지 확인하고 주홍님이 `project-name/master`에 브랜치 보호 규칙을 설정하실 거에요.

### 3. 프로젝트에 해당하는 브랜치를 만들 때, `project-name/researcher-name/functionality` 브랜치의 형태로 만들어주세요. (권장)

브랜치가 많이 생길꺼라 나중에 필터하기 좋을 거 같아요.

### 4. 프로젝트가 끝날 때, `project-name/master`에서 `master`로 옮기는 PR을 만들어서 옮겨주세요.

이 때, master 브랜치에 커밋이 많이 쌓이는 것을 방지하기 위해 **squash merge**를 강력 추천 드려요.

## 프로젝트 생성하기

아래와 같이 스크립트를 실행해주세요.

```sh
$ ./setup_project new-project-name
[+] 프로젝트 폴더 생성 완료
[+] 프로젝트 CI 파일 생성 완료
```

그 상태에서 commit을 하고 PR을 날려주세요. (주홍님, 성현님 리뷰 추가 부탁드립니다.)
