Key patterns evaluated by the model:
* **Sensationalism & Clickbait:** Overuse of dramatic punctuation (`!!!`), ALL CAPS, and emotionally charged language.
* **Source Attribution:** Absence of verified citations, anonymous references, or fabricated quotes.
* **Semantic Inconsistency:** Discrepancies between the article headline and the actual body content.
</details>

<details>
<summary><b>4. Model Evaluation Metrics</b></summary>

<br>

To ensure precision without misclassifying legitimate news, models are evaluated using key performance metrics:

* **Precision:** Out of all articles flagged as *fake*, how many were genuinely fake?
* **Recall:** Out of all actual *fake news* articles in the dataset, how many did the system successfully catch?
* **F1-Score:** The harmonic balance between Precision and Recall.
* **ROC-AUC:** Measures the model's ability to distinguish between classes across different probability thresholds.
</details>

---

## 🔍 Key Indicators: Real vs. Fake News

<details>
<summary><b>📊 Linguistic Comparison Matrix (Click to expand)</b></summary>

<br>

| Attribute | 🚨 Misleading / Fake News | ✅ Authentic News |
| :--- | :--- | :--- |
| **Tone & Style** | Sensational, alarmist, emotionally provocative | Objective, neutral, balanced |
| **Headline Structure** | Clickbait (`"You won't believe what happened!"`) | Concise summary of facts |
| **Citations** | Vague, anonymous, or missing sources | Named experts, official quotes, verifiable data |
| **Formatting** | Typographical errors, excessive exclamation marks (`!!`) | Strict adherence to editorial standards |
| **Author Context** | Missing metadata or unverified authors | Verified journalists or clear newsroom bylines |

</details>

---

## 🛠️ Practical Applications

- 📱 **Social Media Moderation:** Automatically screening user posts for manual fact-checker review.
- 🔍 **Search Engine Ranking:** Lowering the visibility of low-credibility websites in search queries.
- 🛡️ **Browser Extensions:** Providing real-time trust scores and alerts while reading online news.
- 📰 **Journalistic Tools:** Assisting newsrooms in cross-referencing claims against verified databases.

---

## ❓ Frequently Asked Questions

<details>
<summary><b>Can AI achieve 100% accuracy in detecting fake news?</b></summary>

No automated system can achieve absolute perfection. Misinformation constantly evolves, using satire, nuance, and context that often require human evaluation. Machine learning serves as an efficient line of defense to flag high-risk content for verification.
</details>

<details>
<summary><b>Why is TF-IDF widely used for fake news classification?</b></summary>

TF-IDF is lightweight, fast, and highly effective at pinpointing specific vocabulary signatures and buzzwords that deceptive articles frequently rely on.
</details>
