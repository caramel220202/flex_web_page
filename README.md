### 기술 스택 및 라이브러리

---

- React,Javascript

### 사용 기술 및 기능 구현

---
### Flex

- Container
    - **display: flex**
        - Flex 아이템들은 기본적으로 가로 방향으로 배치되고, 자신이 가진 내용물의 width 만큼만 차지
    - **flex-direction**
        - row(기본) : 아이템 가로 방향 배치
        - row-reverse : 아이템 역순으로 가로 방향 배치
        - column : 아이템 세로 방향 배치
        - column-reverse : 아이템 역순으로 세로 방향 배치
    - **flex-wrap**
        - nowrap (기본값) : 줄바꿈을 하지 않습니다.
        - wrap : 줄바꿈합니다.
        - wrap-reverse : 줄바꿈하고 아이템을 역순으로 배치
    - **flex-flow**
        - flex-flow: row wrap; : direction 과 wrap을 한번에 사용함
    - **justify-content (메인축 방향정렬)**
        - flex-start (기본값) : 아이템을 시작점으로 정렬
        - flex-end : 아이템을 끝점으로 정렬
        - center : 아이템을 중앙에 정렬
        - space-between : 아이템 사이에 균일한 간격
        - space-around : 아이템 둘레에 균일한 간격
        - space-evenly : 아이템 사이와 양끝에 균일한 간격
    - **align-items (수직축 방향정렬)**
        - stretch (기본값) : 아이템들이 수직축 방향으로 끝까지 쭈욱 늘어납니다.
        - flex-start : 아이템들을 끝으로 정렬
        - center : 아이템들을 가운데로 정렬
        - baseline : 아이템들을 텍스트 베이스라인 기준으로 정렬
- Child
    - **flex-basis**
        - flex-basis: 50%; : Flex 아이템의 기본 크기를 설정
    - **flex-grow**
        - flex-grow: 1; :grow 값만큼 비율로 차지함
    - **flex-shrink**
        - flex-shrink: 1; : 아이템들의 너비 합이 레이아웃 너비보다 넓으면 아이템 영역을 조절해서 배치함
        - "flex-wrap: wrap;" 속성을 부여한 경우 적용되지않음
