# 代表作

1. FACTOOL: Factuality Detection in Generative AI A Tool Augmented Framework for Multi-Task and Multi-Domain Scenarios

   1. 首发时间：Tue, 25 Jul 2023 14:20:51 UTC (9,031 KB)
   2. 主要内容：该框架利用各种工具，如谷歌搜索、谷歌学术、代码解释器、Python等，来收集关于生成内容真实性的证据，并使用大型语言模型的推理能力来评估内容的真实性。
   3. code https://github.com/GAIR-NLP/factool
2. Generative AI for Math: Part I MATHPILE: A Billion-Token-Scale Pretraining Corpus for Math

   1. 首发时间：Dec 29, 2023
   2. 主要内容：开源了一个高质量数学领域的预训练数据集。
3. Generative AI for Math: Abel

   1. 首发时间：在 github 上最后一次更新时间是 Dec 12, 2023
   2. 主要内容：在没有 CPT 和 RLHF 的前提下，通过构建高质量 SFT 数据集，基于llama2 70B，训练出一个在数学方面性能比肩 GPT4的模型。
      1. 家长监督的原则：不同类型的数据及其表示格式(例如，逐步推理，迭代细化)可以被比作不同的教育方法。就像父母谨慎地选择最有效的方法来指导他们的孩子一样，GAI从业者也应该谨慎地选择最有效的数据处理方法来更好地指导他们的LLM。
      2. 模型存在 overfit。
      3. 对于模型不知道的知识，通过 SFT 注入。
   3. code https://github.com/GAIR-NLP/abel
4. Generative Judge for Evaluating Alignment

   1. 首发时间：Mon, 29 Apr 2024
   2. 主要内容：训练了一个包含 58个场景的 RM 模型（13B），在整体性能上弱于 GPT4
5. Benchmarking Benchmark Leakage in Large Language Models

   1. 首发时间：Mon, 9 Oct 2023； **Jan 2024** : Our paper has been accepted by ICLR 2024!
   2. 主要内容：训练了一个包含 58个场景的 RM 模型（13B），在整体性能上弱于 GPT4
6. Alignment for Honesty
7. https://github.com/GAIR-NLP/alignment-for-honesty
   RLHF？
