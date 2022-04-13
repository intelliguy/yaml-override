# yaml-override
주어진 두개의 yaml을 하나로 합칩니다.
base로 주어진 yaml에 override에 주어진 값들을 대치하여 결과 yaml을 반환합니다.
override yaml은 Global을 정의할 수 있으며 Global 영역에 정의된 값은 override yaml 내부에서 ${정의된 값}의 형태로 정의된 곳에 모두 치환됩니다.

## Quick Start

## yamls
위 예시에서 이미 인지하였겠으나 각 단계에서 사용하는 yaml에 대해 설명하면 다음과 같다.
### base yamls
기반이 되는 yaml로 여기에 override가 합쳐져 결과가 만들어진다. 리스트 형태로 넣어줄 수 있으며 describe을 통해 그 구조를 설명해줘야 한다.

### override yaml


### describe yaml