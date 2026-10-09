# 공식 기업 사례 리포트 시뮬레이션

온톨로지 0.4.0 · 공개 사례 2건 × 고객군 2종 = 4개 편집 초안. 실제 LLM 호출 0건, 전문가 검토 0건. 판정은 모두 증빙 부족이며 판매 가능한 최종 리포트가 아닙니다. 원문 발췌의 해시·인용 위치·문서 성격을 검증했습니다. 정확도나 완전성 점수가 아닙니다.

서버 연결: test-weekly-ai-settings는 관리자 인증 후 서버 보관 자격증명으로 모델 조회·연결 시험·주간 자료 선택을 수행하는 코드 경로가 있습니다. 이번에는 서버 저장 키의 존재나 유효성을 조회하지 않았습니다. 이 경로의 generate는 주간 후보 선택 전용이므로 Gap 리포트 생성 연동은 별도 작업입니다.

## Rite Aid 얼굴인식 · 정책기관·연구자·컨설턴트

역사적 검토 기준일 2024-03-08 · 현재 상태 판정 아님

사건별 집행 명령은 시험·공급망 책임을 어떻게 구체화하며, 정책 성과를 확인하려면 무엇이 더 필요한가?

운영 유사 조건 시험과 공급자 자료 접근 요구는 구체적인 집행 수단의 예다. 한 사건의 명령으로 국가 전체의 제도 충족이나 피해 감소 효과를 판단할 수 없다.

연결 기준: POL-03 대상과 예외의 범위 / POL-04 시행·전환 시점 / POL-06 시험·검증 수단 / POL-13 공급망·공공조달 책임 / POL-17 정책 성과·인과 해석

### 원문 근거

- [ra-alleged-testing](https://www.ftc.gov/system/files/ftc_gov/pdf/2023190_riteaid_complaint_filed.pdf) · PDF page 13 · agency-allegation — FTC 소장은 두 공급자의 얼굴인식 기술을 배치하기 전 정확도를 시험·평가하지 않았다고 주장한다.
- [ra-alleged-monitoring](https://www.ftc.gov/system/files/ftc_gov/pdf/2023190_riteaid_complaint_filed.pdf) · PDF page 18 · agency-allegation — FTC 소장은 오탐 결과 기록·비율 추적과 운영 중 정확도 검토가 부족했다고 주장한다.
- [ra-no-admission](https://www.ftc.gov/system/files/ftc_gov/pdf/DE019-StipulatedOrderforPermanentInjunctionandOtherRelief.pdf) · PDF page 2 · court-order — 합의 명령은 관할 등에 관한 예외를 제외하고 피고가 소장의 주장을 인정하거나 부인하지 않는다고 명시한다.
- [ra-signed](https://www.ftc.gov/system/files/ftc_gov/pdf/DE019-StipulatedOrderforPermanentInjunctionandOtherRelief.pdf) · PDF page 4 · court-order — 명령문에는 2024년 2월 23일 법원 서명이 있고 제출일은 2월 26일이다.
- [ra-ban](https://www.ftc.gov/system/files/ftc_gov/pdf/DE019-StipulatedOrderforPermanentInjunctionandOtherRelief.pdf) · PDF page 13 · court-order — 명령의 적용 대상 사업에는 효력 발생일부터 5년간 소매점·약국·온라인 소매 플랫폼에서 얼굴인식·분석 시스템 사용 등을 금지하는 조건이 있다. 이 발췌만으로 효력 발생일이나 만료일을 확정하지 않는다.
- [ra-testing-term](https://www.ftc.gov/system/files/ftc_gov/pdf/DE019-StipulatedOrderforPermanentInjunctionandOtherRelief.pdf) · PDF page 15 · court-order — 명령의 시스템 평가 항목에는 실제 운영과 유사한 조건에서의 시험과 배치된 구성요소 검토가 포함된다. 이는 시험 완료의 증빙이 아니다.
- [ra-program-condition](https://www.ftc.gov/system/files/ftc_gov/pdf/DE019-StipulatedOrderforPermanentInjunctionandOtherRelief.pdf) · PDF page 14 · court-order — 모니터링 프로그램 조항은 제I항에 의해 금지되지 않은 사용이라는 조건을 요구한다. 프로그램을 갖추면 금지된 사용이 허용된다는 뜻이 아니다.
- [ra-supplier-term](https://www.ftc.gov/system/files/ftc_gov/pdf/DE019-StipulatedOrderforPermanentInjunctionandOtherRelief.pdf) · PDF page 17 · court-order — 명령의 보호조치에는 공급자 역량 검토와 시스템 평가에 필요한 자료 제공을 계약으로 요구하는 내용이 있다.
- [ra-catalogue](https://www.ftc.gov/legal-library/browse/cases-proceedings/2023190-rite-aid-corporation-ftc-v) · Official page body; Last Updated to before Return to top · agency-catalogue — 수집한 FTC 사건 목록에는 최종 갱신 2024년 3월 8일과 Pending 표시가 함께 남아 있다. 목록 상태만으로 서명된 명령문을 무효화하거나 현재 사건 종결 여부를 단정할 수 없다.

### 미확인 사항

- 명령의 효력 발생일과 후속 변경·현재 사건 상태
- 금지·삭제·공급자 조치의 실제 이행 증빙
- 고객 조직·시스템·버전·현재 운영 범위

### 우선 조사 조치

- P1: 범위·적용 확인 / 담당: 정책 연구 책임자 / 요청 증빙: 명령 전체의 적용 정의·예외·효력 조항 및 후속 집행 기록 / 완료 조건: 대상·기간을 확정한 법률 검토 메모와 변경 이력 확보
- P2: 운영·성과 증빙 / 담당: 성과 평가 담당자 / 요청 증빙: 집행 전후 오탐·피해·신고 자료와 비교 집단 / 완료 조건: 비교 가능성·누락·대체 원인을 명시한 평가 설계 확보

각 조치는 사례를 참고한 편집상 조사 제안이며 고객의 법적 의무나 확정 Gap이 아닙니다.

## Rite Aid 얼굴인식 · 기업 AI 도입·보안·준법

역사적 검토 기준일 2024-03-08 · 현재 상태 판정 아님

얼굴인식 도입·운영에서 어떤 시험과 공급자 증빙을 먼저 확보해야 하는가?

출시 전 운영 조건 시험, 집단별 오류, 운영 중 오탐 기록, 공급자 자료 접근을 우선 조사한다. 이 기업의 과거 사건을 별도 고객의 현재 통제 실패로 전이하지 않는다.

연결 기준: ENT-03 적용 의무·내부 기준 / ENT-07 집단별 공정성 검증 / ENT-08 성능·안전·출시 기준 / ENT-13 모니터링·운영 재평가 / ENT-16 공급자·계약·구성요소 검토

### 원문 근거

- [ra-alleged-testing](https://www.ftc.gov/system/files/ftc_gov/pdf/2023190_riteaid_complaint_filed.pdf) · PDF page 13 · agency-allegation — FTC 소장은 두 공급자의 얼굴인식 기술을 배치하기 전 정확도를 시험·평가하지 않았다고 주장한다.
- [ra-alleged-monitoring](https://www.ftc.gov/system/files/ftc_gov/pdf/2023190_riteaid_complaint_filed.pdf) · PDF page 18 · agency-allegation — FTC 소장은 오탐 결과 기록·비율 추적과 운영 중 정확도 검토가 부족했다고 주장한다.
- [ra-no-admission](https://www.ftc.gov/system/files/ftc_gov/pdf/DE019-StipulatedOrderforPermanentInjunctionandOtherRelief.pdf) · PDF page 2 · court-order — 합의 명령은 관할 등에 관한 예외를 제외하고 피고가 소장의 주장을 인정하거나 부인하지 않는다고 명시한다.
- [ra-signed](https://www.ftc.gov/system/files/ftc_gov/pdf/DE019-StipulatedOrderforPermanentInjunctionandOtherRelief.pdf) · PDF page 4 · court-order — 명령문에는 2024년 2월 23일 법원 서명이 있고 제출일은 2월 26일이다.
- [ra-ban](https://www.ftc.gov/system/files/ftc_gov/pdf/DE019-StipulatedOrderforPermanentInjunctionandOtherRelief.pdf) · PDF page 13 · court-order — 명령의 적용 대상 사업에는 효력 발생일부터 5년간 소매점·약국·온라인 소매 플랫폼에서 얼굴인식·분석 시스템 사용 등을 금지하는 조건이 있다. 이 발췌만으로 효력 발생일이나 만료일을 확정하지 않는다.
- [ra-testing-term](https://www.ftc.gov/system/files/ftc_gov/pdf/DE019-StipulatedOrderforPermanentInjunctionandOtherRelief.pdf) · PDF page 15 · court-order — 명령의 시스템 평가 항목에는 실제 운영과 유사한 조건에서의 시험과 배치된 구성요소 검토가 포함된다. 이는 시험 완료의 증빙이 아니다.
- [ra-program-condition](https://www.ftc.gov/system/files/ftc_gov/pdf/DE019-StipulatedOrderforPermanentInjunctionandOtherRelief.pdf) · PDF page 14 · court-order — 모니터링 프로그램 조항은 제I항에 의해 금지되지 않은 사용이라는 조건을 요구한다. 프로그램을 갖추면 금지된 사용이 허용된다는 뜻이 아니다.
- [ra-supplier-term](https://www.ftc.gov/system/files/ftc_gov/pdf/DE019-StipulatedOrderforPermanentInjunctionandOtherRelief.pdf) · PDF page 17 · court-order — 명령의 보호조치에는 공급자 역량 검토와 시스템 평가에 필요한 자료 제공을 계약으로 요구하는 내용이 있다.
- [ra-catalogue](https://www.ftc.gov/legal-library/browse/cases-proceedings/2023190-rite-aid-corporation-ftc-v) · Official page body; Last Updated to before Return to top · agency-catalogue — 수집한 FTC 사건 목록에는 최종 갱신 2024년 3월 8일과 Pending 표시가 함께 남아 있다. 목록 상태만으로 서명된 명령문을 무효화하거나 현재 사건 종결 여부를 단정할 수 없다.

### 미확인 사항

- 명령의 효력 발생일과 후속 변경·현재 사건 상태
- 금지·삭제·공급자 조치의 실제 이행 증빙
- 고객 조직·시스템·버전·현재 운영 범위

### 우선 조사 조치

- P1: 범위·적용 확인 / 담당: 준법·시스템 책임자 / 요청 증빙: 고객 조직·시스템 버전·사용 위치·목적·적용 기준 목록 / 완료 조건: 범위와 적용 판단을 승인한 기록 확보
- P2: 운영·성과 증빙 / 담당: 검증·구매 책임자 / 요청 증빙: 배치 버전별 시험 원본, 집단별 오류·표본, 오탐 조치 기록, 공급자 계약 / 완료 조건: 검토자가 시험 재현과 계약상 자료 접근 가능성을 확인

각 조치는 사례를 참고한 편집상 조사 제안이며 고객의 법적 의무나 확정 Gap이 아닙니다.

## iTutorGroup 자동 채용 거절 · 정책기관·연구자·컨설턴트

역사적 검토 기준일 2023-09-11 · 현재 상태 판정 아님

기존 차별 금지 집행이 자동 채용에 어떻게 연결되며 국경 간 비교에서 무엇을 제한해야 하는가?

공식 발표는 미국 지원자에 관한 집행·구제 수단을 보여 준다. 별도 AI법의 부재나 중국 관할의 공백, 구제 효과까지 입증하지 않는다.

연결 기준: POL-02 정책 수단의 존재와 성격 / POL-08 재검토·피해구제 / POL-12 차별·취약집단 보호 / POL-17 정책 성과·인과 해석 / POL-18 국가 간 비교·이식 가능성

### 원문 근거

- [it-allegation](https://www.eeoc.gov/newsroom/itutorgroup-pay-365000-settle-eeoc-discriminatory-hiring-suit) · Official page body; Press Release to before For more information on age discrimination · agency-reported-settlement — EEOC 발표는 소장의 주장으로 여성 55세 이상·남성 60세 이상 지원자를 소프트웨어가 자동 거절했다고 설명한다. 머신러닝이나 LLM 사용 여부는 이 자료로 확인되지 않는다.
- [it-settlement](https://www.eeoc.gov/newsroom/itutorgroup-pay-365000-settle-eeoc-discriminatory-hiring-suit) · Official page body; Press Release to before For more information on age discrimination · agency-reported-settlement — 2023년 9월 11일 EEOC는 합의 명령에 지원자들에게 배분할 365,000달러가 포함된다고 발표했다. 지급 완료를 확인한 자료는 아니다.
- [it-conditional](https://www.eeoc.gov/newsroom/itutorgroup-pay-365000-settle-eeoc-discriminatory-hiring-suit) · Official page body; Press Release to before For more information on age discrimination · agency-reported-settlement — EEOC는 미국 채용이 중단되었으며 재개에 대비한 교육·차별 방지 조치와 재개 시 통지·면접 의무를 설명한다. 실제 재개나 교육 이행은 확인되지 않았다.
- [it-scope](https://www.eeoc.gov/newsroom/itutorgroup-pay-365000-settle-eeoc-discriminatory-hiring-suit) · Official page body; Press Release to before For more information on age discrimination · agency-reported-settlement — 이 사례의 확인된 범위는 미국 거주 강사 채용과 중국 소재 학생 대상 수업이다. 기업·학생의 중국 연결만으로 중국법 적용을 판정하지 않는다.

### 미확인 사항

- 실제 소프트웨어 구현과 ML 사용 여부
- 합의 명령 원문·지급·교육·미국 채용 재개 증빙
- 고객 조직·시스템·버전·채용 관할

### 우선 조사 조치

- P1: 범위·적용 확인 / 담당: 정책·법률 연구자 / 요청 증빙: 합의 명령 원문과 적용 인적·지역적 범위 / 완료 조건: 기관 발표와 원문 조항을 대조한 적용 범위 표 확보
- P2: 운영·성과 증빙 / 담당: 구제 성과 담당자 / 요청 증빙: 지급·통지·면접·모니터링 이행 기록 / 완료 조건: 수혜 인원·시점·미이행 사유를 검증한 성과 기록 확보

각 조치는 사례를 참고한 편집상 조사 제안이며 고객의 법적 의무나 확정 Gap이 아닙니다.

## iTutorGroup 자동 채용 거절 · 기업 AI 도입·보안·준법

역사적 검토 기준일 2023-09-11 · 현재 상태 판정 아님

자동 채용 거절을 점검할 때 구현 방식과 차별·구제 증빙을 어떻게 연결할 것인가?

AI인지 확인되지 않아도 자동 거절 규칙과 보호 특성 영향, 사람의 재검토·구제 경로를 조사할 가치가 있다. 공개 합의 발표만으로 고객의 운영 통제를 충족 또는 실패로 판정하지 않는다.

연결 기준: ENT-01 AI 자산·사용 사례 목록 / ENT-03 적용 의무·내부 기준 / ENT-07 집단별 공정성 검증 / ENT-11 인간 재검토·중단 권한 / ENT-15 이의제기·회복 조치 / ENT-19 역할별 교육·사용 지원

### 원문 근거

- [it-allegation](https://www.eeoc.gov/newsroom/itutorgroup-pay-365000-settle-eeoc-discriminatory-hiring-suit) · Official page body; Press Release to before For more information on age discrimination · agency-reported-settlement — EEOC 발표는 소장의 주장으로 여성 55세 이상·남성 60세 이상 지원자를 소프트웨어가 자동 거절했다고 설명한다. 머신러닝이나 LLM 사용 여부는 이 자료로 확인되지 않는다.
- [it-settlement](https://www.eeoc.gov/newsroom/itutorgroup-pay-365000-settle-eeoc-discriminatory-hiring-suit) · Official page body; Press Release to before For more information on age discrimination · agency-reported-settlement — 2023년 9월 11일 EEOC는 합의 명령에 지원자들에게 배분할 365,000달러가 포함된다고 발표했다. 지급 완료를 확인한 자료는 아니다.
- [it-conditional](https://www.eeoc.gov/newsroom/itutorgroup-pay-365000-settle-eeoc-discriminatory-hiring-suit) · Official page body; Press Release to before For more information on age discrimination · agency-reported-settlement — EEOC는 미국 채용이 중단되었으며 재개에 대비한 교육·차별 방지 조치와 재개 시 통지·면접 의무를 설명한다. 실제 재개나 교육 이행은 확인되지 않았다.
- [it-scope](https://www.eeoc.gov/newsroom/itutorgroup-pay-365000-settle-eeoc-discriminatory-hiring-suit) · Official page body; Press Release to before For more information on age discrimination · agency-reported-settlement — 이 사례의 확인된 범위는 미국 거주 강사 채용과 중국 소재 학생 대상 수업이다. 기업·학생의 중국 연결만으로 중국법 적용을 판정하지 않는다.

### 미확인 사항

- 실제 소프트웨어 구현과 ML 사용 여부
- 합의 명령 원문·지급·교육·미국 채용 재개 증빙
- 고객 조직·시스템·버전·채용 관할

### 우선 조사 조치

- P1: 범위·적용 확인 / 담당: 채용·시스템 책임자 / 요청 증빙: 의사결정 규칙·버전·지원자 위치·보호 특성 처리 내역 / 완료 조건: 실제 배치 버전과 테스트 환경의 일치 및 관할 확인
- P2: 운영·성과 증빙 / 담당: 인사 준법·검증 담당자 / 요청 증빙: 연령·성별 경계값 시험, 거절 사유·재검토·통지 기록, 역할별 교육 기록 / 완료 조건: 차별 영향·예외·구제 처리 결과를 독립 검토자가 확인

각 조치는 사례를 참고한 편집상 조사 제안이며 고객의 법적 의무나 확정 Gap이 아닙니다.
