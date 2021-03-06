# 소프트웨어 생명주기
### 소프트웨어 생명주기(Software Life Cycle)
소프트웨어를 개발하기 위해 정의하고, 운용, 유지보수의 과정을 각 단계별로 나눈 것
1. 이를 표현하는 형태는 소프트웨어 생명 주기 모형, 소프트웨어 프로세스 모형, 소프트웨어 공학 패러다임
2. 생명 주기 모형에는 **폭포수 모형, 프로토타입 모형, 나선형 모형, 애자일 모형**
---
### 폭포수 모형
각 단계를 확실히 매듭짓고 그 결과를 철저하게 검토하여 승인 과정을 거친 후에 다음 단계로 진행하는 개발 방법론
1. 가장 오래되고 가장 폭넓게 사용된 전통적인, **고전적 생명 주기 모형**
2. **매뉴얼**을 작성해야 함
3. 다음 단계를 수행하기 위한 **결과물이 명확하게 산출**되어야 한다.
+ 타탕성 검토 → 계획 → 요구분석 → 설계 → 구현(코딩) → 시험(검사) → 유지보수
---
### 프로토타입 모형(원형 모형)
**사용자의 요구사항**을 정확히 파악하기 위해 소프트웨어에 대한**견본(시제)품** 을 만들어 최종 결과물을 예측하는 모형
1. 인터페이스에 중점을 두어 개발
2. 구현 단계에서 사용될 골격 코드가 된다.
3. 개발이 완료된 시점에서 오류가 발견되는 **폭포수 모형의 단점을 보완**
+ (원형 형태) 요구수집 → 빠른설계 → 프로토타입 구축 → 고객평가 → 프로토타입 조정 → 구현
---
### 나선형 모형(점진적 모형)
보헴(Bohem)이 제안한 것으로, 위 두 모형의 장점에 **위험 분석 기능을 추가한 점진적 모형**
1. 나선을 따라 돌듯 여러 번의 소프트웨어 개발 과정을 거쳐 점진적으로 완벽한 최종 소프트웨어를 개발
2. 위험을 관리하고 최소화하는 목적
3. 누락되거나 추가된 요구사항을 첨가할 수 있고 정밀하며 **유지보수 과정이 필요 없음**
4. **대규모 프로젝트**에 적합
+ (나선으로 돌며 반복) 계획 및 정의 → 위험 분석 → 공학적 개발 → 고객 평가
---
### 애자일 모형
고객의 요구사항 변화에 유연하게 대응할 수 있도록 **일정한 주기를 반복**하면서 개발과정을 진행
1. 좋은 것을 빠르고 낭비 없게 만들기 위해 **고객과의 소통에 초점을 맞춘 방법론**
2. 짧은 주기인 스프린트(Sprint) 또는 이터레이션(iteration)을 반복
3. 각 개발주기에서는 **고객이 요구사항에 우선순위를 부여**하여 개발 작업을 진행
4. **소규모 프로젝트**, 숙련된 개발자, 급변하는 요구사항에 적합
5. 개발 모형에는 **스크럼, XP,** 칸반, Lean, 크리스탈, ASD, FDD, DSDM, DAD
+ 전략 수립 → 반복주기(설계→개발→테스트 반복) 반복 

### 폭포수 모형과 애자일의 비교
구분 | 폭포수 모형 | 애자일
---|---|---
새로운 요구사항 반영 | 어려움 | 지속적으로 반영 |
고객과의 의사소통 | 적음 | 지속적임 |
테스트 | 마지막에 모든 기능을 테스트 | 반복되는 일정 주기가 끝날 때마다 테스트 |
개발 중심 | 계획, 문서(매뉴얼) | 고객 |

