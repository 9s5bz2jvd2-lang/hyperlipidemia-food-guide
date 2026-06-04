# Nutrition Science | Hyperlipidemia Nutrition Guide

English version translated from the existing Chinese README.

An AI popular-science conversation assistant based on the **Dietary and Nutrition Guide for Adults with Hyperlipidemia (2023 Edition)** issued by the **General Office of the National Health Commission**. | Nutrition Science Skill

> 🌱 I am new to AI and hope to use AI to share nutrition knowledge and help more people. If anything is insufficient, feedback is welcome. I will keep working on more nutrition-science skills. If you find this useful, please consider giving it a ⭐ Star. Thank you!

---

## Guideline Source

- **Full title**: *Dietary and Nutrition Guide for Adults with Hyperlipidemia (2023 Edition)*
- **Issuing organization**: General Office of the National Health Commission

## Features

- **Risk assessment**: blood-lipid abnormality self-check, high-risk factor identification, and stratified management
- **Dietary-nutrition principles**: detailed interpretation and practical advice for 8 official principles
- **Lipid regulation**: dietary intervention strategies for total cholesterol, triglycerides, LDL-C, and HDL-C
- **TCM syndrome differentiation**: 6 syndrome patterns × 3 examples = 18 menus
- **Formula library**: 39 dietary formulas (18 teas + 21 meal formulas), selected by syndrome pattern
- **Regional adaptation**: 7 regions × 4 seasons × 3 energy levels = 84 daily menus
- **Food choices**: recommended, limited, and avoided foods plus substitutions
- **Popular-science style**: plain language, concrete quantities, and myth correction—precise without being condescending

## Quick Reference

| Item | Recommendation | Plain-language explanation |
|------|----------------|----------------------------|
| Cooking oil | ≤25 g/day (≤20 g for hyperlipidemia) | No more than about two tablespoons |
| Salt | ≤5 g/day | About one beer-bottle cap |
| Dietary cholesterol | <300 mg/day (<200 mg for hypercholesterolemia) | One large egg is about 200–250 mg |
| Total dietary fiber | 25–40 g/day | Vegetables, fruit, and coarse grains |
| Fresh vegetables | 500 g/day | At least half should be dark-colored vegetables |
| Fresh fruit | 200–350 g/day | An apple plus a small bowl of berries |
| Whole grains / mixed beans | 50–150 g/day | Brown rice or mixed-grain porridge |
| Deep-sea fish | ≥2 times/week | Rotate salmon, hairtail, mackerel, etc. |
| TC | <5.2 mmol/L | Total cholesterol below 5.2 |
| TG | <1.7 mmol/L | Triglycerides below 1.7 |
| LDL-C | <3.4 mmol/L (ideal <2.6) | “Bad” cholesterol below 3.4 |
| HDL-C | ≥1.0 mmol/L | “Good” cholesterol not below 1.0 |

## Knowledge System

| KPK ID | Topic | Source section |
|--------|-------|----------------|
| KPK-01~08 | Dietary-nutrition principles | Dietary-nutrition principles chapter |
| KPK-09~13 | Appendix knowledge: food choices, exchange tables, menus, formulas | Appendices |
| KPK-14~17 | Disease background, screening, and Q&A | Disease background + Q&A |

## File Structure

```text
- skill.yaml: Skill configuration
- SKILL.md: Core skill file
- system_prompt.md: System prompt
- knowledge_base.md: KPK knowledge base
- kpk_*.md: Principles, appendix, disease background, and Q&A KPK files
- recipes_data.md: 18 complete menus
- recipes_overview.md: Menu overview
- dietary_formulas.md: 39 dietary formulas
- README.md: Chinese README
- install.sh: Linux/macOS install script
- install.bat: Windows install script
```

## Statement

**Disclaimer**:
1. All content comes from the guideline above and is for dietary-nutrition popular-science reference only; it does not replace medication treatment or professional medical diagnosis.
2. It is intended to support prevention and improvement for adults with hyperlipidemia; people with other comorbidities may refer to it but should not apply it rigidly.
3. Food-medicine substances and new food raw materials should be used under professional guidance and not taken in excessive amounts.
4. People with diabetes, hypertension, coronary heart disease, or other underlying conditions should receive professional physician and nutrition guidance.
5. This skill was built with AI assistance. Although it aims to stay faithful to the original guideline, paraphrasing errors may exist. If there is any doubt, please refer to the official published guideline text.


## Creator

**Runyuan Wang**
- Chinese Registered Dietitian
- M.S. in Nutrition and Food Hygiene, Kunming Medical University
- Built with WorkBuddy

## License

MIT
