# Animal-Go-Draw

**React로 제작된 랜덤 우승자 추첨형 인터랙티브 동물 레이싱 게임**

---

## 개요

**Animal-Go-Draw**는 하나의 HTML 파일 안에서 **React (CDN)** 과 **Babel Standalone**을 사용해 제작된 브라우저 기반 미니게임입니다.
사용자가 여러 동물 캐릭터를 선택한 뒤 **“우승자 뽑기 시작”** 버튼을 누르면, 각 캐릭터가 무작위 속도로 결승선을 향해 달리며 **랜덤 우승자**가 자동으로 결정됩니다.
레이스가 끝나면 우승자와 순위표가 화면에 표시됩니다.

---

## 기술 스택

* **HTML5 / CSS3** - UI 구조 및 반응형 스타일 구현
* **JavaScript (ES6+)** - 레이스 로직, 상태 업데이트, 무작위 속도 계산
* **React (CDN)** - 컴포넌트 기반 구조 (`useState`, `useEffect`, `useCallback`, `useRef` 활용)
  * 주요 컴포넌트:
    * `AnimalKartRacerApp` – 전체 앱 로직 및 상태 관리
    * `CharacterCard` – 참가자 선택 UI 카드
    * `RacerVisual` – 트랙에서 캐릭터 이동 시각화
    * `Leaderboard` – 레이스 종료 후 순위표 표시
    * `AnimalKartIcon` – 동물과 탈것 이모지 겹쳐 표시
* **Babel Standalone** - 브라우저 내 JSX 실시간 변환
* **Font Awesome 6** - 인터페이스 내 아이콘 표시
* **Google Fonts (Orbitron, Noto Sans KR, Press Start 2P)** - 게임 스타일 폰트 적용
* **HTML Audio Element** - `<audio>` 태그를 이용한 간단한 효과음 재생

---

## 주요 기능

* **참가자 선택**: 최소 2명, 최대 10명의 동물 캐릭터 선택 가능
* **랜덤 레이스 진행**: 각 캐릭터의 속도가 무작위로 설정되어 매번 다른 결과 생성
* **우승자 및 순위 자동 표시**: 결승선 통과 후 우승자와 순위표 자동 표시
* **사운드 효과**: 레이스 종료 시 축하 효과음 재생
* **반응형 디자인**: 데스크톱과 모바일 화면 모두에서 자연스럽게 표시
* **단일 파일 구조**: 별도 빌드 과정 없이 `index.html` 하나로 실행 가능

---

## 설치 및 실행

### GitHub Pages

[https://xcixcode.github.io/Animal-Go-Draw/](https://xcixcode.github.io/Animal-Go-Draw/)

### 로컬에서 실행

1. `index.html` 파일을 다운로드합니다.
2. 브라우저(Chrome, Edge, Safari 등)에서 직접 엽니다.
3. 별도의 서버 설정이나 패키지 설치 없이 바로 실행됩니다.

---

## 라이선스

본 프로젝트는 개인 학습 및 포트폴리오 용도로 제작되었습니다.  
코드는 **[MIT License](https://opensource.org/licenses/MIT)** 하에 배포되며, 사용 시 해당 라이선스 조건을 준수해야 합니다.

> ⚠️ 참고
>
> * 일부 모바일 환경에서는 화면 비율이나 UI가 완벽하게 표시되지 않을 수 있습니다.
> * 외부 라이브러리 및 자료 출처:
>   * [React](https://reactjs.org/)
>   * [Babel Standalone](https://babeljs.io/docs/en/babel-standalone)
>   * [Font Awesome](https://fontawesome.com/)
>   * [Google Fonts](https://fonts.google.com/)
> * 위 라이브러리들은 CDN을 통해 로드되므로, 인터넷 연결이 없으면 기능/UI가 정상적으로 표시되지 않을 수 있음
