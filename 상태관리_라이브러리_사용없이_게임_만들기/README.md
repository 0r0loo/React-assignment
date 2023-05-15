
예시 링크 : https://numble-react.vercel.app/

상세 스펙
- Math.pow(Math.floor((stage/2) + 1), 2)개의 사각형이 표시되며, 그 중 하나만 색깔이 다릅니다.
- 한 stage 의 제한 시간은 15초입니다.
- 색이 다른 사각형(정답)을 클릭한 경우 아래 변경사항이 적용됩니다.
- 다음 스테이지로 넘어갑니다.
- stage * stage * 남은시간 만큼의 score 가 누적됩니다.
- 오답을 클릭한 경우 아래 변경사항이 적용됩니다.
- 현재 stage 의 남은 시간이 3초 줄어듭니다.
- 남은 시간이 0초 이하가 되면 게임이 종료됩니다. 최종 stage 와 누적 score 를 출력하고, 새로운 게임을 시작할 수 있습니다.
- stage 가 올라갈수록 정답과 오답의 색상 차이가 줄어듭니다.

요구 조건
- React 를 사용 할 것
- Typescript 를 사용 할 것
- Context, Redux, Mobx, Recoil 등 상태관리 도구를 사용하지 않을 것
