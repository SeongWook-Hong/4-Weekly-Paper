# <3주차 위클리 페이퍼>

### ✅ Git에서 branch merge 방법들과 각 방법의 특징을 설명해 주세요.
1. merge commit을 만들며 합치기

'Merge commit' 방식은 두 브랜치의 변경 사항을 모두 유지하면서 병합합니다. 이 방식을 사용하면, 각 브랜치의 변경 사항이 과거의 커밋으로 보존되고, 새로운 커밋이 추가되어 최종 병합이 완료 됩니다.

2. Squash and merge 하기

'Squash and Merge'는 브랜치에서의 모든 변경 사항을 하나의 커밋으로 압축하여 병합하는 방식입니다. 이 방식은 각각의 커밋에서 발생한 모든 변경 사항을 병합 후에 하나의 새로운 커밋을 생성합니다.

3. Rebase and merge 하기

'Rebase and Merge'는 현재 브랜치를 target 브랜치에 재위치(rebase)시킨 후 병합하는 방식입니다. 이는 target 브랜치의 커밋 위로 현재 브랜치의 모든 커밋을 옮겨 놓는 것과 같습니다. 이렇게 되면 커밋 히스토리는 선형적으로 유지됩니다.

### ✅ Git Flow 브랜치 전략에 대해 설명해 주세요.

Git Flow는 크게 Main 브랜치, Develop 브랜치, Supporting 브랜치로 구분하여 브랜치를 관리합니다. 이때, Supporting 브랜치는 또 다시 Feature 브랜치, Release 브랜치, Hotfix 브랜치로 나뉩니다.

Main 브랜치와, Develop 브랜치는 개발 프로세스 전반에 걸쳐 항상 유지되는 브랜치입니다. 반면, Supporting 브랜치는 필요할 때마다 생성되고, 역할을 다하면 삭제됩니다. Supporting 브랜치 덕분에 팀이 병렬적으로 업무를 할 수 있게됩니다.