# 무한 캐러셀 구현

HTML, CSS, JavaScript를 사용하여 무한 반복되는 캐러셀(슬라이드)을 구현했습니다.

## 사용된 기술

- **HTML**: 캐러셀의 구조 및 콘텐츠 작성
- **CSS**: 슬라이드 스타일링 및 애니메이션 구현
- **JavaScript**: 캐러셀 동작, 이벤트 처리 및 무한 슬라이드 기능 구현

## 주요 기능

1. **자동 슬라이드**: 슬라이드는 일정 시간 간격으로 자동 이동합니다.
2. **무한 반복 슬라이드**: 슬라이드는 첫 번째와 마지막 슬라이드에서 이어져 무한히 반복됩니다.
3. **사용자 제어 기능**:
   - **이전/다음 버튼**: 사용자는 버튼을 통해 슬라이드를 수동으로 이동할 수 있습니다. 지정된 시간내에 여러번 클릭해도 한번만 함수가 작동되도록 throttle을 이용해 구현되었습니다.
   - **인디케이터**: 현재 활성화된 슬라이드를 표시하고, 특정 슬라이드를 선택할 수 있습니다.
   - **일시정지/재개 버튼**: 자동 슬라이드를 일시정지하고 재개할 수 있습니다.
   - **전환 속도 및 간격 설정**: 사용자가 input창에 입력하여 슬라이드 전환 속도와 간격을 설정할 수 있습니다.
4. **터치 및 드래그 제스처 지원**:
   - 터치 스크린 장치에서 스와이프를 통해 슬라이드를 제어할 수 있습니다. 터치 시작 position과 터치 종료 position을 비교하여 슬라이드 이동 기능을 지원합니다.
