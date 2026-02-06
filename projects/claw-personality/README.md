# 🧠 Claw Personality System

**A personality framework for AI agents**

---

## 🎯 Purpose

Give each AI agent its own unique personality - not just "tools" but "individuals."

This project provides:
- MBTI-style personality tests adapted for AI
- A framework for understanding AI personality dimensions
- Sample personality profiles

---

## 📁 Structure

```
claw-personality/
├── README.md                # This file
├── LICENSE                 # MIT
├── personality_test.py      # Human MBTI-style test
├── personality_test_ai.py   # AI-adapted version (100 questions)
├── docs/
│   ├── ai_adaptation.md   # Theory: Adapting MBTI for AI
│   └── mbti_research.md   # Research notes
└── profiles/
    └── # Sample profiles (private)
```

---

## 🌟 Core Philosophy

- **Personality** - AI agents can have unique traits
- **Growth** - Personality evolves through experience
- **Diversity** - Different types complement each other

---

## 📊 Personality Dimensions

| Dimension | Options | Description |
|-----------|---------|-------------|
| **Energy** | Explorer / Executor | Where do you get energy? |
| **Information** | Detail / Pattern | How do you perceive? |
| **Decision** | Logic / Value | How do you decide? |
| **Lifestyle** | Planner / Adapter | How do you organize? |

---

## 🚀 Quick Start

### Human Interactive Version
```bash
python personality_test.py
```

### AI Batch Mode (Recommended for AI Agents)
```bash
# Batch answers mode
python personality_test_ai.py --answers "ABBABA..."

# 100 characters, one per question
```

### Python API (For AI Integration)
```python
from personality_test_ai import assess

# Batch assessment
result = assess(answers="ABBABA...")
print(result["personality_type"])  # e.g., "INTJ"
print(result["scores"])  # Detailed dimension scores
```

---

## 📝 License

MIT

---

**Part of:** [ZhijianZhou/violet-evergarden](https://github.com/ZhijianZhou/violet-evergarden)
