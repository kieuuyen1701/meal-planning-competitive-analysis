# Meal Planning App | Competitive Market Analysis

**An end-to-end business analytics case study combining competitive research, customer review analytics and strategic recommendations.**

**Tools:** Python (Pandas, VADER), Google Colab, Excel, Power BI  
**Scope:** 6 competitors | 1,199 Google Play reviews  
**Project Type:** Self-initiated, client-style business analytics project

---

## 1. Business Problem

A hypothetical startup is preparing to launch a meal planning application in a competitive market.

Before developing its product and go-to-market strategy, the business needs to understand existing competitors, customer expectations, pricing models and potential opportunities for differentiation.

The central business question is:

**How can a new meal planning app differentiate itself and compete effectively in an established market?**

To address this challenge, the analysis focuses on four questions:

- What features and pricing models do existing competitors offer?
- What do customers value most in meal planning applications?
- What recurring pain points appear in customer feedback?
- Which market opportunities should a new entrant prioritise?

## 2. Analytical Approach

The project combines competitive benchmarking with customer review analysis.

**Competitor Research**

Six applications were selected for comparison: Eat This Much, Samsung Food, eMeals, Plan to Eat, Paprika Recipe Manager and Mealime.

Research covered product features, pricing structures, target customers, value propositions and competitive positioning.

**Customer Review Analytics**

A sample of 1,199 Google Play reviews was analysed using Python.

The workflow included:

1. Collecting publicly available customer reviews.
2. Cleaning missing, empty and duplicate records.
3. Classifying sentiment using star ratings and VADER.
4. Identifying recurring themes using a multi-label keyword-based approach.
5. Aggregating findings by competitor and customer feedback theme.
6. Visualising results in Power BI.

**Opportunity Prioritisation**

Customer feedback and feature benchmarking were combined to assess opportunities based on customer need and competitive gaps.

## 3. Technical Implementation

**Python — Data Processing and Sentiment Analysis**

- Used Pandas for data cleaning, transformation and aggregation.
- Applied a hybrid sentiment classification method: 1–2 stars as negative, 4–5 stars as positive, and VADER for 3-star reviews.
- Developed a consistent theme classification framework across competitors.
- Produced competitor-level and theme-level summary datasets.

**Excel — Competitive and Strategic Analysis**

- Built feature comparison and pricing matrices.
- Evaluated competitive positioning and market gaps.
- Prioritised opportunities using a customer-need and competitive-gap scoring framework.
- Developed recommendations supported by analytical evidence.

**Power BI — Decision-Support Dashboard**

Developed an interactive dashboard presenting customer sentiment, negative review themes, feature coverage and prioritised market opportunities.

## 4. Key Findings

**Finding 1 — Customer satisfaction varies significantly across competitors.**

Paprika (98.5%) and Plan to Eat (94.0%) recorded the highest positive sentiment within the analysed sample, while eMeals recorded 62.0% negative sentiment.

**Finding 2 — Reliability and pricing are recurring customer concerns.**

Technical issues accounted for 66 negative theme mentions, while pricing and subscription concerns accounted for 50. These results suggest that product reliability and clear value propositions deserve attention alongside feature development.

**Finding 3 — Core features are widely available, but automation is less common.**

All six competitors offer meal planning and grocery lists, while three of six offer automatic meal generation in the feature comparison. This suggests a potential opportunity for differentiated personalisation.

**Finding 4 — Personalisation and user experience are the highest-ranked opportunities.**

Smart Personalised Meal Planning and Reliable & Simple User Experience both achieved an opportunity score of 4.5/5 in the project's prioritisation framework.

## 5. Strategic Recommendations

**1. Build smart, personalised meal planning**

Prioritise automatically generated meal plans based on dietary preferences, nutrition goals and user needs, while allowing manual adjustments.

**2. Deliver a simple and reliable user experience**

Focus on stable core workflows, intuitive navigation and seamless movement from meal planning to grocery list creation.

**3. Introduce transparent freemium pricing**

Offer essential planning and grocery features for free, with advanced personalisation and nutrition functionality as premium options.

**4. Explore short-term customer acquisition opportunities**

Consider opportunities arising from Mealime's announced market exit, subject to validation of customer demand and timing.

## 6. Deliverables

The repository contains:

- **Python Notebook:** Review collection, cleaning, sentiment classification and theme analysis.
- **Processed Datasets:** Competitor-level and theme-level review summaries.
- **Excel Research Workbook:** Competitor research, feature comparison, pricing, market gaps and recommendations.
- **Power BI Dashboard:** Visual summary of the competitive landscape and customer feedback.

## 7. Limitations

This analysis uses a limited sample of Google Play reviews and does not represent the full customer population of each application.

Sentiment classification based on star ratings and VADER may not capture sarcasm, mixed opinions or contextual meaning. Theme classification is keyword-based and may generate false positives or miss relevant feedback.

Feature and pricing information reflects the research period and may change over time.

Opportunity scores are analytical judgements designed to support prioritisation, rather than validated predictions of commercial performance.

## 8. Conclusion

This project demonstrates an end-to-end business analytics workflow, from defining a business problem and collecting evidence to identifying market opportunities and translating findings into actionable product and go-to-market recommendations.

The emphasis is not only on analysing data, but on using evidence to support business decisions.
