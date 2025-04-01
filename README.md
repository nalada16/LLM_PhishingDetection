## 利用 LLM 辨識釣魚信件
該專案運用大語言模型（LLM）來判斷電子郵件是否為釣魚信件，並結合多種技術以提升辨識準確率。

1. LangChain 與 Huggung Face：透過 LangChain 串接 Hugging Face 上的語言模型。
2. RAG（Retrieval-Augmented Generation）：結合向量資料庫，增強模型對釣魚信件特徵的檢索能力，提高辨識準確率。
3. Prompt Engineering：運用以下技術優化模型的輸出：
    * Few-shot Learning
    * Chain of Thought（CoT）
    * Self-Consistency*