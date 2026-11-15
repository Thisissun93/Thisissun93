## 안녕하세요, 김태양입니다 👋

FC-BGA 기판 양산 라인에서 **6년간 공정·품질 엔지니어**로 일했습니다.
현장에서 겪은 문제를 데이터로 풀어 보는 도구를 만들고 있습니다.

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
- **설비 데이터 자동 수집**: 믹서를 OPC UA로 수집해 Step별 FDC 판정, 설비 이상 로트는 출하 보류
- **출하 승인**: QA 검토 → 승인자 승인 두 전자서명, 서명 근거를 해시로 보존, 수정 불가 감사 추적
- **AI 어시스턴트**: 사내 LLM이 시스템 데이터·SOP로만 답하고 출처와 근거 검사 표시 (34문항 평가 21% → 76%)
- **서비스 구성**: PostgreSQL · REST API · Docker Compose, 테스트 91개를 두 DB로 CI 검증

[▶ 앱 실행](https://materialqualityintelligence-dknsnjemfstfko4zluzplu.streamlit.app/) · [GitHub](https://github.com/Thisissun93/Material_Quality_Intelligence)

</td>
<td width="50%" valign="top">

**[CMP Manufacturing Intelligence](https://github.com/Thisissun93/CMP-Manufacturing-Intelligence)**
CMP 슬러리 Batch 이탈 원인 조사
<a href="https://github.com/Thisissun93/CMP-Manufacturing-Intelligence"><img src="https://raw.githubusercontent.com/Thisissun93/CMP-Manufacturing-Intelligence/main/docs/images/02_ph_additive_lot.png" alt="CMP Manufacturing Intelligence"></a>
원료 LOT·공정·설비·QC 이력 연결 → 원인 후보 좁히기 → 영향 범위(출하분) 추적 → CAPA 효과 검증

[▶ 앱 실행](https://thisissun93.github.io/CMP-Manufacturing-Intelligence/) · [GitHub](https://github.com/Thisissun93/CMP-Manufacturing-Intelligence)

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[Real Manufacturing Intelligence](https://github.com/Thisissun93/Real_Manufacturing_AI)**
ABF 제조 이력 조사 · 예방보전
<a href="https://github.com/Thisissun93/Real_Manufacturing_AI"><img src="https://raw.githubusercontent.com/Thisissun93/Real_Manufacturing_AI/main/images/dashboard_main.png" alt="Real Manufacturing Intelligence"></a>
LOT 이력·온도 프로파일·AOI 불량 지도 → 원인 후보와 확인 시험 → Random Forest·SHAP 기반 예방보전, 조사 보고서

[▶ 앱 실행](https://realmanufacturingai-gqmhke2ybcjhdrsndjsh2e.streamlit.app/) · [GitHub](https://github.com/Thisissun93/Real_Manufacturing_AI)

</td>
<td width="50%" valign="top">

**[Semiconductor Wet Cleaning System](https://github.com/Thisissun93/semiconductor_wet_cleaning_system)**
반도체 습식 세정 공정 모니터링
<a href="https://github.com/Thisissun93/semiconductor_wet_cleaning_system"><img src="https://raw.githubusercontent.com/Thisissun93/semiconductor_wet_cleaning_system/main/images/dashboard_main.png" alt="Semiconductor Wet Cleaning System"></a>
MES 데이터 → 이상 감지·원인 분석·조치 추천 → SPC(Cp/Cpk) → 설비 이상 예측(SHAP), PDF 보고서

[▶ 앱 실행](https://semiconductor-wet-cleaning-system.streamlit.app) · [GitHub](https://github.com/Thisissun93/semiconductor_wet_cleaning_system)

</td>
</tr>
</table>

---

### 💼 경력

**대덕전자** · FC-BGA / ABF Package Substrate 공정·품질 엔지니어 (2020 – 2026)
- 검사 협력사 이물 판정 기준 통일, FT-IR 라이브러리 구축 → 후이물 불량률 **1.1% → 0.4%**
- ABF Annealing을 Batch 오븐에서 Vertical Oven으로 전환, 투입·배출 자동화 → 생산량 **1,300 → 1,800 m²/월**
- 습식 전처리 약품 신규 평가·표준화 → 국내 2번째 Automotive向 양산 승인
- 고객 8D 대응(ABF Delamination), JMP 기반 DOE·ANOVA·SPC, 소재 Qualification

### 📜 자격
6시그마 Black Belt · Professional Scrum Master I

### 📫 연락
phaeton4890@gmail.com
