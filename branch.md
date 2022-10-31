# branch_ref.md
### branch 생성 규칙에 대해 정의한 파일 
----
### 개요 
- Branch 생성 및 Branch 구분을 위한 설명 파일 

### New Branch
```
git branch [브랜치명]
```
- jira를 사용하거나 특정 브랜치를 구분 짓기 위해서는 브랜치명 규칙을 만드는 것이 필요하다 
- 단 현재 프로젝트의 규모가 낮은 편으로 "main - dev - 개인 브런치 명" 구조로 생성한다. 

### Change Branch
```
git checkout [브랜치명]
```
- 생성한 브랜치는 dev 아래에 위치하도록 한다. 
- 따라서 개인 브랜치 생성 시 브랜치를 전환하여 생성해야 한다. 

### Merge Branch 
```
git merge [브랜치명]
```
- PR이 완료된 경우 브랜치를 merge 진행한다. 
- 단 merge의 충돌의 경우 개인이 해결한다. 
  - 이러한 오류를 방지하기 위해서는 브랜치 생성이 되었을 때 pull - merge 를 생활화 하자
