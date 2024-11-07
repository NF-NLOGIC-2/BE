test
### Branch Strategy - Git Flow

> BranchType : Description

- main : 배포 브랜치
- release/tag : 배포 준비
- hotfix/tag : 배포 버그 수정
- feat/issue : 기능 개발
- cicd/issue
- dev : 다음 버전 개발

⚠️ 작업이 끝난 feat 및 cicd 브랜치는 제거한다.

---

### Commit Convention

> CommitType: description  
> - 기본적으로 type(#issueNumber): 제목의 형식을 갖는다.
> - 아래 형식을 꼭 준수하며, 주요 변경 사항을 본문에 담는다.
> - 제목은 AngularJs Commit Convention을 따른다.
>   - 제목은 50자를 초과하지 않는다.
>   - 제목이 50자가 초과한다면, 주요 변경사항이 있으므로 본문에 작성한다.
> - 본문의 내용은 한 라인당 100자를 초과하지 않는다.
>   - 본문의 내용은 주요 변경사항을 위주로 작성한다.

- feat(): 기능 개발 내용
- refactor(): 개선 사항 내용
- fix(): 수정 사항 내용
- cicd(): cicd 관련 내용
- docs: 문서 관련 작업
- chore: 그 외 작업
