# CRISP-DM (EN / DE / RU)

## 0. Business Context

| English | Deutsch | Русский |
|---|---|---|
| **0. Business Context and Constraints** | **0. Kontext und Einschränkungen (Business Context)** | **0. Контекст и ограничения (Business Context)** |
| **0.1 Business context and domain description** | **0.1 Beschreibung des Geschäftskontexts und der Fachdomäne** | **0.1 Описание бизнес-контекста и предметной области** |
| Industry: telecom, retail, manufacturing | Branche: Telekommunikation, Einzelhandel, Produktion | Область: телеком, розница, производство |
| Business problem and current situation | Geschäftsproblem und aktuelle Situation | Проблема бизнеса и текущая ситуация |
| Why analysis is important | Warum die Analyse wichtig ist | Почему анализ важен |
| Example: reduce customer churn | Beispiel: Kundenabwanderung reduzieren | Пример: снижение оттока клиентов |
| **0.2 Stakeholders and end users** | **0.2 Stakeholder und Endnutzer** | **0.2 Заинтересованные стороны и пользователи** |
| Management, marketing, sales, support | Management, Marketing, Vertrieb, Support | Менеджмент, маркетинг, продажи |
| End users: CRM, dashboards, BI tools | Endnutzer: CRM, Dashboards, BI-Tools | Пользователи: CRM, дашборды |
| **0.3 Business KPIs** | **0.3 Geschäftskennzahlen (KPI)** | **0.3 Бизнес-метрики (KPI)** |
| KPIs to measure success | KPIs zur Erfolgsmessung | KPI для оценки результата |
| Churn Rate, Retention Rate, ARPU | Churn Rate, Retention Rate, ARPU | Churn Rate, Retention Rate, ARPU |
| ROI, revenue per user, satisfaction | ROI, Umsatz pro Kunde, Zufriedenheit | ROI, доход, удовлетворённость |
| **0.4 Constraints and assumptions** | **0.4 Einschränkungen und Annahmen** | **0.4 Ограничения и допущения** |
| Data quality, completeness, delays | Datenqualität, Vollständigkeit, Verzögerungen | Качество данных, полнота |
| Time, team, computing resources | Zeit, Team, Rechenressourcen | Время, команда, ресурсы |
| Model requirements (interpretability) | Modellanforderungen (Interpretierbarkeit) | Требования к модели |
| Legal: GDPR, bias | Rechtlich: DSGVO, Bias | Юридические: GDPR, bias |

---

## 1. Business Understanding

| English | Deutsch | Русский |
|---|---|---|
| **1. Business Understanding** | **1. Aufgabenstellung (Business Understanding)** | **1. Постановка задачи (Business Understanding)** |
| **1.1 Objectives** | **1.1 Ziele** | **1.1 Цели анализа** |
| **1.1.1 Business problem** | **1.1.1 Geschäftsproblem** | **1.1.1 Бизнес-проблема** |
| Identify churn-risk customers | Kunden mit Abwanderungsrisiko identifizieren | Найти клиентов с риском оттока |
| **1.1.2 Success criteria** | **1.1.2 Erfolgskriterium** | **1.1.2 Критерий успеха** |
| Reduce churn by X% | Churn um X % reduzieren | Снижение оттока на X% |
| Increase retention rate | Retention Rate erhöhen | Рост удержания клиентов |
| **1.2 Key questions** | **1.2 Analysefragen** | **1.2 Вопросы анализа** |
| What factors influence churn? | Welche Faktoren beeinflussen Abwanderung? | Какие факторы влияют на отток? |
| Can behavior be predicted? | Verhalten vorhersagbar? | Можно ли прогнозировать поведение? |
| **1.2.2 Hypotheses** | **1.2.2 Hypothesen** | **1.2.2 Гипотезы** |
| Frequent support → higher churn | Häufiger Support → höhere Abwanderung | Частые обращения → отток |
| Behavior change indicates risk | Verhaltensänderung zeigt Risiko | Изменение поведения = риск |
| **1.3 Actions and decisions** | **1.3 Maßnahmen** | **1.3 Решения** |
| Retention campaigns | Retention-Kampagnen | Retention-кампании |
| Personalized offers | Personalisierte Angebote | Персональные предложения |
| Integration in CRM / BI | Integration in CRM / BI | Внедрение в CRM / BI |
