## 03. 브랜치와 브랜치를 합치기 : 병합(merge)



#### 병합은 무엇인가요?

- 병합은 간단히 말해서 두 버전의 합집합을 구하는 것이다.
  1. **Merge commit (병합 커밋)** : 새로운 커밋
     - 새로운 상태니까 새롭게 저장함
  2. **Fast-forward (빨리 감기)**: 기존 커밋과 같음
     - 새로 상태를 만들어 줄 필요 없이 뒷 커밋으로 상태를 바꿔줌
  3. **Confilct (충돌)** : 뭘 커밋해야할지 모르겠음
     - 충돌이 난 부분을 확인하고 무엇을 남길지 수동으로 선택해줌







#### 두 브랜치를 합치는 과정

* **Merge** : Git에서 브랜치와 브랜치를 합치는 명령어 -> "병합"

* 브랜치를 기준으로 병합한다는 것?

  [master] 브랜치를 기준으로 병합한다는 것은 합친 결과물을 [master] 브랜치에 반영한다는 것이다.





#### 브랜치 합치기 실습: 빨리감기 병합

1. 소스트리에서 [master] 브랜치로 체크아웃 한다.

2. 병합하기를 원하는 커밋에서 마우스 우클릭 -> [병합] 메뉴를 선택한다.

3. 해당 브랜치를 병합할 것인지 묻는 팝업창이 뜬다. ok버튼 클릭

4. 두 브랜치가 합쳐진다.

   [master] 브랜치가 [feature/detail-page] 브랜치와 같은 커밋을 가리킨다. : 빨리감기 방식

5. [Push]를 눌러 방금 진행한 병합을 원격 저장소에 적용된다.

6. [master], [origin/master] 모두 같은 커밋을 가리킨다.


