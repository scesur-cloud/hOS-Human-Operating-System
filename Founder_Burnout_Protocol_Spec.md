# Founder Burnout Protocol — Export Spec (hOS)

Version: v1  
Date: 2025-12-13

## 1) Filter Logic (The Net)

**Persona (include):**
- `P.FOUNDER` OR `P.HIGH_ACHIEVER` OR `P.TECH_LEAD`

**Situation (include):**
- `S.BURNOUT` OR `S.STARTUP_VOLATILITY` OR `S.DECISION_OVERLOAD`

**Intensity cap (exclude):**
- Exclude `I4.EXPOSURE` and `I5.CLINICAL_INTAKE`

**Risk safety (exclude):**
- Exclude any question tagged `R.TRAUMA_SENSITIVE` or `R.SELF_HARM_CHECK`
- Optional: exclude `R.DISSOCIATION_RISK` for entry-level products

## 2) Domain Distribution (The Balance)

**Total Questions:** 50

- **20% Hardware (10 Qs)** — sleep, stimulants, somatic shutdown tells  
  Target tags: `BIO.SLEEP`, `BIO.CAFFEINE_NICOTINE`, `BIO.DISSOCIATION_TELL`, `BIO.BREATH_SIGNATURE`

- **25% OS / Cognitive (12–13 Qs)** — decision fatigue, impostor, control  
  Target tags: `PERF.DECISION_FATIGUE`, `M.CONTROL_STRATEGY`, `PERF.METRICS_OBSESSION`, `M.RUMINATION_ENGINE`

- **15% Identity / Self (7–8 Qs)** — identity fusion, worth, meaning  
  Target tags: `M.IDENTITY_FUSION`, `SYM.SHAME`, `G.MEANING`, `M.EXTERNAL_VALIDATION`

- **15% Output / Habits (7–8 Qs)** — busywork, recovery deficit, avoidance  
  Target tags: `PERF.BUSYWORK`, `PERF.RECOVERY_DEFICIT`, `M.AVOIDANCE_LOOP`, `PERF.LATE_NIGHT_GRIND`

- **15% Network / Relationships (7–8 Qs)** — isolation, boundaries, trust defaults  
  Target tags: `REL.LONELY_IN_ROOM`, `REL.TRUST_DEFAULT`, `REL.BOUNDARY_LEAKS`, `REL.CO_REGULATION`

- **10% Toolkit / Strengths (5 Qs)** — recovery, agency, proof of resilience  
  Target tags: `G.AGENCY`, `G.RECOVERY`, `G.CONFIDENCE`, `D.IX_TOOLKIT`

## 3) Sequencing Rule (The Flow)

- **Start (Qs 1–5):** Hardware/Somatic (low threat, credibility, “easy wins”)  
- **Middle (Qs 6–35):** OS + Identity + Network (core dynamics and meaning)  
- **End (Qs 36–50):** Output + Toolkit (actionable changes + agency)

## 4) Product Safety Defaults

- Include at least **1 grounding instruction** per section (30–60 seconds)
- Add a “stop rule”: pause if intensity spikes; return to `I1.PING` questions
- Provide crisis language only in clinician-facing versions (B2B), not consumer PDFs
