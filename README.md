## 안녕하세요, 김태양입니다 👋

FC-BGA 기판 양산 라인에서 **6년간 공정·품질 엔지니어**로 일했습니다.
현장에서 겪은 문제를 데이터로 풀어 보는 도구를 만들고 있습니다.

> **English** — I worked 6 years as a process and quality engineer on an FC-BGA substrate production line. I build tools that solve real shop-floor problems with data. Each project below has a short English summary at the top of its page.

`공정·품질` · `MSA·SPC·Cpk` · `8D·SCAR` · `JMP` · `Python` · `Streamlit`
`OPC UA·FDC` · `FastAPI·PostgreSQL·Docker` · `사내 LLM·RAG`

---

### 🗂 포트폴리오

모든 프로젝트는 **합성 데이터**로 만든 시연이고, 설치 없이 브라우저에서 바로 실행됩니다.

<table>
<tr>
<td width="50%" valign="top">

**[Material Quality Intelligence](https://github.com/Thisissun93/Material_Quality_Intelligence)**
반도체 패키징 소재(언더필) 품질 분석
<a href="https://github.com/Thisissun93/Material_Quality_Intelligence"><img src="https://raw.githubusercontent.com/Thisissun93/Material_Quality_Intelligence/main/docs/img/overview.png" alt="Material Quality Intelligence"></a>
장비 출력 파일 자동 인식 → MSA·Cpk·SPC·T² → 공급사 CoA 검증 → 데이터로 채운 8D·SCAR, 조치 추적 → 재시험이 최초 부적합을 덮지 못하게 막는 OOS 조사·출하 판정
- **업무 성과**: 클레임 로트 1건의 조사 자료(6개 시스템, 61건)를 0.2초 안에 모음. 수작업으로 반나절 가까이 걸리던 일 ([측정](https://github.com/Thisissun93/Material_Quality_Intelligence/blob/main/docs/benchmark_investigation.md))
- **검증**: Gage R&R·Cpk·EWMA·CUSUM·T² 등 28개 항목을 독립 계산과 대조해 모두 일치 ([검증표](https://github.com/Thisissun93/Material_Quality_Intelligence/blob/main/docs/stats_validation.md))
- **구성**: OPC UA 설비 수집·FDC, 전자서명 출하 승인·감사 추적, 사내 LLM 어시스턴트(34문항 21% → 76%), PostgreSQL·Docker, 테스트 100개 CI

[▶ 앱 실행](https://materialqualityintelligence-dknsnjemfstfko4zluzplu.streamlit.app/) · [GitHub](https://github.com/Thisissun93/Material_Quality_Intelligence)

</td>
<td width="50%" valign="top">

**[CMP Manufacturing Intelligence](https://github.com/Thisissun93/CMP-Manufacturing-Intelligence)**
CMP 슬러리 Batch 이탈 원인 조사
<a href="https://github.com/Thisissun93/CMP-Manufacturing-Intelligence"><img src="https://raw.githubusercontent.com/Thisissun93/CMP-Manufacturing-Intelligence/main/docs/images/02_ph_additive_lot.png" alt="CMP Manufacturing Intelligence"></a>
원료 LOT·공정·설비·QC 이력 연결 → 원인 후보 좁히기 → 영향 범위(출하분) 추적 → CAPA 효과 검증
- **업무 성과**: 이탈 Batch 1건에서 원인 후보 원료 LOT(pH 이탈 7건 100% 집중)과 그 LOT으로 만들어 이미 출하된 2건까지 약 0.07초 (CSV 6종 6,039행) ([측정](https://github.com/Thisissun93/CMP-Manufacturing-Intelligence/blob/main/docs/BENCHMARK.md))
- **검증**: 공정능력·회귀·Spearman·분산성분 23개 값을 pandas·scipy·statsmodels 독립 계산과 대조해 모두 일치 ([검증](https://github.com/Thisissun93/CMP-Manufacturing-Intelligence/blob/main/VALIDATION.md))
- **구성**: 설치 없는 정적 웹앱(JavaScript), 출하 판정 테스트와 독립 계산 대조를 커밋마다 CI 실행

[▶ 앱 실행](https://thisissun93.github.io/CMP-Manufacturing-Intelligence/) · [GitHub](https://github.com/Thisissun93/CMP-Manufacturing-Intelligence)

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[Real Manufacturing Intelligence](https://github.com/Thisissun93/Real_Manufacturing_AI)**
ABF 제조 이력 조사 · 예방보전
<a href="https://github.com/Thisissun93/Real_Manufacturing_AI"><img src="https://raw.githubusercontent.com/Thisissun93/Real_Manufacturing_AI/main/images/dashboard_main.png" alt="Real Manufacturing Intelligence"></a>
LOT 이력·온도 프로파일·AOI 불량 지도 → 원인 후보와 확인 시험 → Random Forest·SHAP 기반 예방보전, 8D·조사 보고서
- **업무 성과**: LOT ID 하나로 설비 이력 10건·AOI 1,600 유닛·동일 조건 LOT 74개를 대조해 원인 후보 4개까지 약 0.7초, 원인 유형 9종 시나리오 27/27 통과 ([측정](https://github.com/Thisissun93/Real_Manufacturing_AI/blob/main/docs/BENCHMARK.md))
- **검증**: ANOVA·Tukey·Cp/Cpk·Gage R&R·I-MR 164개 항목을 JMP 19 결과와 대조해 모두 일치 ([대조표](https://github.com/Thisissun93/Real_Manufacturing_AI/blob/main/docs/jmp_crosscheck.md))
- **구성**: 시간순 검증으로 학습·평가 누출 차단, 확인시험·검토 기록 게이트, 테스트 295개 CI

[▶ 앱 실행](https://realmanufacturingai-gqmhke2ybcjhdrsndjsh2e.streamlit.app/) · [GitHub](https://github.com/Thisissun93/Real_Manufacturing_AI)

</td>
<td width="50%" valign="top">

**[Semiconductor Wet Cleaning System](https://github.com/Thisissun93/semiconductor_wet_cleaning_system)**
반도체 습식 세정 공정 모니터링
<a href="https://github.com/Thisissun93/semiconductor_wet_cleaning_system"><img src="https://raw.githubusercontent.com/Thisissun93/semiconductor_wet_cleaning_system/main/images/dashboard_main.png" alt="Semiconductor Wet Cleaning System"></a>
MES 데이터 → 이상 감지·원인 분석·조치 추천 → SPC(I-MR, Cp/Cpk·Pp/Ppk) → 설비 이상 예측(SHAP), PDF 보고서
- **업무 성과**: LOT 120개 × 항목 17개(2,040건) 판정 → 원인 후보 → 조치 추천까지 약 0.15초 ([측정](https://github.com/Thisissun93/semiconductor_wet_cleaning_system/blob/main/docs/BENCHMARK.md))
- **검증**: SPC 84값·판정 등급 2,040건·예측 특징량 3,888값을 독립 재계산과 대조해 일치. 대조 중 등급 역전 8건을 찾아 수정 ([검증표](https://github.com/Thisissun93/semiconductor_wet_cleaning_system/blob/main/docs/stats_validation.md))
- **구성**: SQLite MES 스키마, 예측 모델 평가 한계(기준선 대비)를 수치로 공개, 테스트 45개 CI

[▶ 앱 실행](https://semiconductor-wet-cleaning-system.streamlit.app) · [GitHub](https://github.com/Thisissun93/semiconductor_wet_cleaning_system)

</td>
</tr>
</table>

---

### 💼 경력

**대덕전자** · FC-BGA / ABF Package Substrate 공정·품질 엔지니어 (2020 – 2026)
- 검사 협력사 Audit, FT-IR 라이브러리 구축 → 후이물 불량률 **1.1% → 0.4%**
- ABF Annealing을 Batch 오븐에서 Vertical Oven으로 전환, 투입·배출 자동화
- ABF 3rd Lamination Set-up
- 습식 전처리 약품 신규 평가·표준화 → 국내 2번째 Automotive向 양산 승인
- 고객 8D 대응(ABF Delamination etc), JMP 기반 DOE·ANOVA·SPC, 소재 Qualification
- 이물 설비 공통 제작 사양서, 양산 관리 규정, 클린룸/세정기 표준 제/개정
- FMEA, CP, OCAP, SOP 등 표준 제/개정

### 📜 자격
6시그마 Black Belt · Professional Scrum Master I

### 📫 연락
phaeton4890@gmail.com
