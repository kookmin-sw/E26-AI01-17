# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Stack

Static HTML/CSS rendered to PDF with headless Chrome, converted to CMYK with Ghostscript. Confirmed by the user ("html 로 모두 진행하자").

## Users

- Other student teams (22 teams) who see the poster in the same room during the 11/6 presentation and the 11/13 Future Vision Day exhibition. Confirmed.
- Professors, judges and industry mentors who score the 5-minute poster presentation on 11/6. Confirmed.
- The team presents standing in front of the poster; the poster must also work unassisted for passers-by (inferred from the exhibition format).

## Product Purpose

A single A0 portrait poster for the 2026 Kookmin University Eureka Project, imagining the world of 2040–2050. The team's project, ORBIT 2050, proposes moving power-hungry AI training data centers into orbit, where solar power is nearly continuous, so ground power grids and neighborhoods stop absorbing AI's electricity demand. Success: a first-time viewer understands what ORBIT does within 30 seconds (course announcement), and the poster provokes comparison with the more predictable topics of other teams.

## Positioning

Other teams' 2050 topics (wearables, care robots, B2B automation) are framed as technology that already exists by 2030. ORBIT argues the real 2050 constraint is physical infrastructure, power first, and answers it in orbit. The argument is grounded in verified sources (IEA, Epoch AI, Google Project Suncatcher, Korean grid data) rather than prediction alone.

## Operating Context

- Printed on foam board at A0 (841×1189mm), viewed from 1–3 m in a room with many other posters.
- Course requires sections in order: ① 제목 및 요약 ② 문제와 사용자 ③ 미래 장면 ④ 기술 방식 ⑤ 검증 질문 ⑥ 팀 및 역할 (with references and AI-use disclosure).
- Mentor feedback: the first section must say concretely what the service does.

## Capabilities and Constraints

- PDF, one page, A0 portrait, minimum 150 DPI, CMYK, important text well inside the edges.
- Vector only: Chrome rasterizes CSS/SVG gradients and patterns at low resolution, so none are used.
- Editable source kept in the repo (poster/orbit2050.html).
- No disclaimer footer or version labels on the poster (user request, 10/30).

## Brand Commitments

Delegated to judgment by the user ("알아서 판단해"). Inferred and kept: project name ORBIT 2050, team name E26-AI01-17, slogan "Feel the AGI", the ①–⑥ section order, and the verified copy and figures.

## Evidence on Hand

Verified against originals on 10/30: IEA Energy and AI (415→945 TWh, 4–8 years per transmission line, 175 GW unlockable via AI grid tools); 동아일보 2025.7.30 (수도권 데이터센터 전력 신청 20GW, 심사 19건 중 4건 통과); 파이낸셜뉴스 2024.10.27 (김포 구래동 데이터센터 반대, 초등학교 100m 앞 특고압선); Google Research Project Suncatcher (8x solar output, 650 km dawn–dusk orbit, <$200/kg mid-2030s, 2 prototypes by early 2027); 뉴시스 2026.4.17 (우주항공청 K-문샷 우주 데이터센터, 2030년까지 누리호 실증); Epoch AI 2024 (power and chips are the most binding constraints). Personas (이수진, 박도윤) are fictional and must not be presented as real people.

## Product Principles

1. Thirty-second clarity beats completeness: what ORBIT does comes before why.
2. Every number on the poster is traceable to a verified source.
3. Provoke, but stay defensible: the critique of "2050 = 2030" topics is about technology readiness, not about teams.
4. The argument is the team's, not the tool's: avoid looking or reading like a generated template.
