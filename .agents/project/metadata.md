# Thesis Metadata & Domain Context

This document maintains the high-level research context of the Master of Science in Computer Science (MS CS) thesis. Future AI agents and tools will refer to this file to align slides, logic, notation, and explanations with your academic work.

---

## 1. Administrative Details

- **Thesis Title**: [Insert Specific Thesis Title here]
- **Candidate**: Christian Joseph Bunyi
- **Degree**: Master of Science in Computer Science
- **Advisor**: [Insert Advisor Name]
- **Committee Members**:
  - [Committee Member 1]
  - [Committee Member 2]
- **Institution**: [Insert Institution / Department]
- **Target Defense Date**: [Insert Target Date]

---

## 2. Research Problem & Questions

### Problem Statement

[Describe the core problem your thesis addresses in 1-2 paragraphs. Why does this problem matter, and why is existing literature insufficient?]

### Core Research Questions (RQs)

1. **RQ1**: [e.g., How can we optimize the aggregation speed of federated learning in heterogeneous network conditions?]
2. **RQ2**: [e.g., What are the privacy trade-offs of using gradient compression in local training updates?]

---

## 3. Core Contributions & Novelty

- **Contribution 1**: [Describe first major technical, algorithmic, or experimental contribution.]
- **Contribution 2**: [Describe second major contribution.]
- **Contribution 3**: [Describe third major contribution (if applicable).]

---

## 4. Key Terminology & Domain Vocabulary

_Provide standard terminology and preferred styles to ensure consistency throughout the slides._

| Term / Abbreviation | Definition                         | Slide Preference                                                       |
| :------------------ | :--------------------------------- | :--------------------------------------------------------------------- |
| **FL**              | Federated Learning                 | Prefer writing in full for slide headers, abbreviations for body text. |
| **FedAvg**          | Federated Averaging Algorithm      | Standard baseline algorithm; use standard formatting.                  |
| **Client / Node**   | A local training participant in FL | Consistent use of "Node" or "Client" (Choose one and stick to it).     |
| **Global Server**   | The central aggregator             | Capitalized as "Global Server" or "Server".                            |

---

## 5. Standard Mathematical Notation

_Maintain exact math symbol configurations so equations across slides are beautifully unified._

- **Data Samples**: $n$ total samples, $n_k$ samples on client $k$.
- **Model Weights**: Global weights at step $t$ are $w_t$.
- **Learning Rate**: $\eta$ (eta).
- **Gradient Update**: $g_k$ for client $k$.
- **Objective Function**: $f(w)$ or $F_k(w)$ for local objectives.
