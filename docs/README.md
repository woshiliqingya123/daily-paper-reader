<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-02-17 ~ 2026-03-18
- 运行时间：2026-03-18 09:04:12 UTC
- 运行状态：成功
- 本次总论文数：49
- 精读区：38
- 速读区：11

### 今日简报（AI）
本期深度研读 49 篇前沿论文，核心攻克 VLM 与长文本 LLM 在训练与推理阶段的效率瓶颈。
满分神作 DUET-VLM 与 CHESS 分别在统一 Token 缩减与层级化语义选择上实现重大突破。
建议优先关注 Token 剪枝与跨层聚合技术，这是当前突破大模型推理算力瓶颈的最前沿路径。
- 详情：[/20260217-20260318/README](/20260217-20260318/README)

### 精读区论文标签
1. [DUET-VLM: Dual stage Unified Efficient Token reduction for VLM Training and Inference](/20260217-20260318/2602.18846v1-duet-vlm-dual-stage-unified-efficient-token-reduction-for-vlm-training-and-inference)  
   标签：评分：10.0/10、query:tokencomp
   evidence：双阶段Token缩减及剪枝低信息量Token
2. [CHESS: Context-aware Hierarchical Efficient Semantic Selection for Long-Context LLM Inference](/20260217-20260318/2602.20732v1-chess-context-aware-hierarchical-efficient-semantic-selection-for-long-context-llm-inference)  
   标签：评分：10.0/10、query:tokencomp
   evidence：用于KV缓存管理的上下文感知动态Token选择
3. [SideQuest: Model-Driven KV Cache Management for Long-Horizon Agentic Reasoning](/20260217-20260318/2602.22603v1-sidequest-model-driven-kv-cache-management-for-long-horizon-agentic-reasoning)  
   标签：评分：10.0/10、query:tokencomp
   evidence：通过推理令牌有用性进行KV缓存压缩
4. [SideQuest: Model-Driven KV Cache Management for Long-Horizon Agentic Reasoning](/20260217-20260318/2602.22603v2-sidequest-model-driven-kv-cache-management-for-long-horizon-agentic-reasoning)  
   标签：评分：10.0/10、query:tokencomp
   evidence：长程推理任务中的KV缓存压缩
5. [Stateful Token Reduction for Long-Video Hybrid VLMs](/20260217-20260318/2603.00198v1-stateful-token-reduction-for-long-video-hybrid-vlms)  
   标签：评分：10.0/10、query:tokencomp
   evidence：混合视觉语言模型的渐进式标记减少
6. [LooComp: Leverage Leave-One-Out Strategy to Encoder-only Transformer for Efficient Query-aware Context Compression](/20260217-20260318/2603.09222v1-loocomp-leverage-leave-one-out-strategy-to-encoder-only-transformer-for-efficient-query-aware-context-compression)  
   标签：评分：10.0/10、query:tokencomp
   evidence：用于高效上下文压缩的查询驱动上下文剪枝
7. [UniCompress: Token Compression for Unified Vision-Language Understanding and Generation](/20260217-20260318/2603.11320v1-unicompress-token-compression-for-unified-vision-language-understanding-and-generation)  
   标签：评分：10.0/10、query:tokencomp
   evidence：减少标记数量的统一标记压缩算法
8. [SemantiCache: Efficient KV Cache Compression via Semantic Chunking and Clustered Merging](/20260217-20260318/2603.14303v1-semanticache-efficient-kv-cache-compression-via-semantic-chunking-and-clustered-merging)  
   标签：评分：10.0/10、query:tokencomp
   evidence：通过语义分块和聚类合并进行KV缓存压缩
9. [DASH: Dynamic Audio-Driven Semantic Chunking for Efficient Omnimodal Token Compression](/20260217-20260318/2603.15685v1-dash-dynamic-audio-driven-semantic-chunking-for-efficient-omnimodal-token-compression)  
   标签：评分：10.0/10、query:tokencomp
   evidence：全模态Token压缩的动态语义分块
10. [Fast KV Compaction via Attention Matching](/20260217-20260318/2602.16284v1-fast-kv-compaction-via-attention-matching)  
   标签：评分：9.0/10、query:tokencomp
   evidence：KV 缓存的潜空间快速上下文压缩
11. [EntropyPrune: Matrix Entropy Guided Visual Token Pruning for Multimodal Large Language Models](/20260217-20260318/2602.17196v1-entropyprune-matrix-entropy-guided-visual-token-pruning-for-multimodal-large-language-models)  
   标签：评分：9.0/10、query:tokencomp
   evidence：基于矩阵熵的视觉令牌剪枝
12. [ApET: Approximation-Error Guided Token Compression for Efficient VLMs](/20260217-20260318/2602.19870v1-apet-approximation-error-guided-token-compression-for-efficient-vlms)  
   标签：评分：9.0/10、query:tokencomp
   evidence：基于信息论的视觉Token压缩
13. [BFA++: Hierarchical Best-Feature-Aware Token Prune for Multi-View Vision Language Action Model](/20260217-20260318/2602.20566v1-bfa-hierarchical-best-feature-aware-token-prune-for-multi-view-vision-language-action-model)  
   标签：评分：9.0/10、query:tokencomp
   evidence：针对VLA模型的动态Token剪枝框架
14. [HiDrop: Hierarchical Vision Token Reduction in MLLMs via Late Injection, Concave Pyramid Pruning, and Early Exit](/20260217-20260318/2602.23699v1-hidrop-hierarchical-vision-token-reduction-in-mllms-via-late-injection-concave-pyramid-pruning-and-early-exit)  
   标签：评分：9.0/10、query:tokencomp
   evidence：分层视觉令牌减少与剪枝
15. [Task-Centric Acceleration of Small-Language Models](/20260217-20260318/2602.24174v1-task-centric-acceleration-of-small-language-models)  
   标签：评分：9.0/10、query:tokencomp
   evidence：针对小语言模型加速的任务自适应序列压缩
16. [EfficientPosterGen: Semantic-aware Efficient Poster Generation via Token Compression and Accurate Violation Detection](/20260217-20260318/2603.00155v1-efficientpostergen-semantic-aware-efficient-poster-generation-via-token-compression-and-accurate-violation-detection)  
   标签：评分：9.0/10、query:tokencomp
   evidence：用于高效多模态生成的Token压缩
17. [TP-Spikformer: Token Pruned Spiking Transformer](/20260217-20260318/2603.00527v1-tp-spikformer-token-pruned-spiking-transformer)  
   标签：评分：9.0/10、query:tokencomp
   evidence：用于脉冲Transformer的标记剪枝方法以减少开销
18. [TC-SSA: Token Compression via Semantic Slot Aggregation for Gigapixel Pathology Reasoning](/20260217-20260318/2603.01143v1-tc-ssa-token-compression-via-semantic-slot-aggregation-for-gigapixel-pathology-reasoning)  
   标签：评分：9.0/10、query:tokencomp
   evidence：Transformer中通过语义槽聚合进行Token压缩
19. [AgilePruner: An Empirical Study of Attention and Diversity for Adaptive Visual Token Pruning in Large Vision-Language Models](/20260217-20260318/2603.01236v1-agilepruner-an-empirical-study-of-attention-and-diversity-for-adaptive-visual-token-pruning-in-large-vision-language-models)  
   标签：评分：9.0/10、query:tokencomp
   evidence：自适应视觉令牌剪枝策略
20. [Token Reduction via Local and Global Contexts Optimization for Efficient Video Large Language Models](/20260217-20260318/2603.01400v1-token-reduction-via-local-and-global-contexts-optimization-for-efficient-video-large-language-models)  
   标签：评分：9.0/10、query:tokencomp
   evidence：冗余视觉标记的减少与剪枝
21. [Understanding the Physics of Key-Value Cache Compression for LLMs through Attention Dynamics](/20260217-20260318/2603.01426v1-understanding-the-physics-of-key-value-cache-compression-for-llms-through-attention-dynamics)  
   标签：评分：9.0/10、query:tokencomp
   evidence：通过注意力动态对LLM进行KV缓存压缩
22. [Cross-Family Speculative Prefill: Training-Free Long-Context Compression with Small Draft Models](/20260217-20260318/2603.02631v1-cross-family-speculative-prefill-training-free-long-context-compression-with-small-draft-models)  
   标签：评分：9.0/10、query:tokencomp
   evidence：针对长文本智能体工作负载的免训练提示词压缩
23. [EvoPrune: Early-Stage Visual Token Pruning for Efficient MLLMs](/20260217-20260318/2603.03681v1-evoprune-early-stage-visual-token-pruning-for-efficient-mllms)  
   标签：评分：9.0/10、query:tokencomp
   evidence：用于高效多模态大模型的早期视觉Token剪枝
24. [Stacked from One: Multi-Scale Self-Injection for Context Window Extension](/20260217-20260318/2603.04759v1-stacked-from-one-multi-scale-self-injection-for-context-window-extension)  
   标签：评分：9.0/10、query:tokencomp
   evidence：针对长序列的多粒度上下文压缩
25. [Prune Redundancy, Preserve Essence: Vision Token Compression in VLMs via Synergistic Importance-Diversity](/20260217-20260318/2603.09480v2-prune-redundancy-preserve-essence-vision-token-compression-in-vlms-via-synergistic-importance-diversity)  
   标签：评分：9.0/10、query:tokencomp
   evidence：剪枝视觉语言模型中的冗余视觉Token
26. [A Voronoi Cell Formulation for Principled Token Pruning in Late-Interaction Retrieval Models](/20260217-20260318/2603.09933v1-a-voronoi-cell-formulation-for-principled-token-pruning-in-late-interaction-retrieval-models)  
   标签：评分：9.0/10、query:tokencomp
   evidence：检索模型中的原则性令牌剪枝
27. [A Voronoi Cell Formulation for Principled Token Pruning in Late-Interaction Retrieval Models](/20260217-20260318/2603.09933v2-a-voronoi-cell-formulation-for-principled-token-pruning-in-late-interaction-retrieval-models)  
   标签：评分：9.0/10、query:tokencomp
   evidence：后期交互检索模型中的原则性标记剪枝
28. [DepthCache: Depth-Guided Training-Free Visual Token Merging for Vision-Language-Action Model Inference](/20260217-20260318/2603.10469v1-depthcache-depth-guided-training-free-visual-token-merging-for-vision-language-action-model-inference)  
   标签：评分：9.0/10、query:tokencomp
   evidence：深度引导的视觉Token合并与压缩
29. [Where Matters More Than What: Decoding-aligned KV Cache Compression via Position-aware Pseudo Queries](/20260217-20260318/2603.11564v1-where-matters-more-than-what-decoding-aligned-kv-cache-compression-via-position-aware-pseudo-queries)  
   标签：评分：9.0/10、query:tokencomp
   evidence：通过位置感知伪查询进行KV缓存压缩
30. [ZeroSense:How Vision matters in Long Context Compression](/20260217-20260318/2603.11846v1-zerosensehow-vision-matters-in-long-context-compression)  
   标签：评分：9.0/10、query:tokencomp
   evidence：用于长上下文建模的视觉文本压缩
31. [ForensicZip: More Tokens are Better but Not Necessary in Forensic Vision-Language Models](/20260217-20260318/2603.12208v1-forensiczip-more-tokens-are-better-but-not-necessary-in-forensic-vision-language-models)  
   标签：评分：9.0/10、query:tokencomp
   evidence：用于伪造检测的视觉Token剪枝与压缩
32. [BiGain: Unified Token Compression for Joint Generation and Classification](/20260217-20260318/2603.12240v1-bigain-unified-token-compression-for-joint-generation-and-classification)  
   标签：评分：9.0/10、query:tokencomp
   evidence：通过拉普拉斯门控Token合并实现统一Token压缩
33. [Structured Distillation for Personalized Agent Memory: 11x Token Reduction with Retrieval Preservation](/20260217-20260318/2603.13017v1-structured-distillation-for-personalized-agent-memory-11x-token-reduction-with-retrieval-preservation)  
   标签：评分：9.0/10、query:tokencomp
   evidence：长对话历史蒸馏实现11倍Token削减
34. [Language-Guided Token Compression with Reinforcement Learning in Large Vision-Language Models](/20260217-20260318/2603.13394v1-language-guided-token-compression-with-reinforcement-learning-in-large-vision-language-models)  
   标签：评分：9.0/10、query:tokencomp
   evidence：视觉Token缩减的自适应剪枝轨迹
35. [SecDTD: Dynamic Token Drop for Secure Transformers Inference](/20260217-20260318/2603.13670v1-secdtd-dynamic-token-drop-for-secure-transformers-inference)  
   标签：评分：9.0/10、query:tokencomp
   evidence：动态Token丢弃以降低推理成本
36. [ASAP: Attention-Shift-Aware Pruning for Efficient LVLM Inference](/20260217-20260318/2603.14549v1-asap-attention-shift-aware-pruning-for-efficient-lvlm-inference)  
   标签：评分：9.0/10、query:tokencomp
   evidence：针对LVLM中Token冗余的免训练剪枝方案
37. [Balancing Saliency and Coverage: Semantic Prominence-Aware Budgeting for Visual Token Compression in VLMs](/20260217-20260318/2603.14892v1-balancing-saliency-and-coverage-semantic-prominence-aware-budgeting-for-visual-token-compression-in-vlms)  
   标签：评分：9.0/10、query:tokencomp
   evidence：通过语义显著性在VLM中进行视觉Token压缩
38. [VQKV: High-Fidelity and High-Ratio Cache Compression via Vector-Quantization](/20260217-20260318/2603.16435v1-vqkv-high-fidelity-and-high-ratio-cache-compression-via-vector-quantization)  
   标签：评分：9.0/10、query:tokencomp
   evidence：通过矢量量化进行KV缓存压缩

### 速读区论文标签
1. [ToaSt: Token Channel Selection and Structured Pruning for Efficient ViT](/20260217-20260318/2602.15720v2-toast-token-channel-selection-and-structured-pruning-for-efficient-vit)  
   标签：评分：8.0/10、query:tokencomp
   evidence：视觉Transformer的Token压缩与结构化剪枝
2. [CLAA: Cross-Layer Attention Aggregation for Accelerating LLM Prefill](/20260217-20260318/2602.16054v1-claa-cross-layer-attention-aggregation-for-accelerating-llm-prefill)  
   标签：评分：8.0/10、query:tokencomp
   evidence：选择性地处理语义相关的标记子集
3. [OTPrune: Distribution-Aligned Visual Token Pruning via Optimal Transport](/20260217-20260318/2602.20205v2-otprune-distribution-aligned-visual-token-pruning-via-optimal-transport)  
   标签：评分：8.0/10、query:tokencomp
   evidence：通过最优传输进行视觉令牌剪枝
4. [Frequency-Ordered Tokenization for Better Text Compression](/20260217-20260318/2602.22958v1-frequency-ordered-tokenization-for-better-text-compression)  
   标签：评分：8.0/10、query:tokencomp
   evidence：用于文本压缩的频率排序分词
5. [On the Semantic and Syntactic Information Encoded in Proto-Tokens for One-Step Text Reconstruction](/20260217-20260318/2602.18301v1-on-the-semantic-and-syntactic-information-encoded-in-proto-tokens-for-one-step-text-reconstruction)  
   标签：评分：7.0/10、query:tokencomp
   evidence：从两个学习到的原型Token重建数百个Token
6. [UFO: Unifying Feed-Forward and Optimization-based Methods for Large Driving Scene Modeling](/20260217-20260318/2602.20943v1-ufo-unifying-feed-forward-and-optimization-based-methods-for-large-driving-scene-modeling)  
   标签：评分：7.0/10、query:tokencomp
   evidence：过滤机制以选择信息丰富的场景标记
7. [Multi-Vector Index Compression in Any Modality](/20260217-20260318/2602.21202v1-multi-vector-index-compression-in-any-modality)  
   标签：评分：7.0/10、query:tokencomp
   evidence：在恒定向量预算下压缩多向量文档表示
8. [Structured Prompt Language: Declarative Context Management for LLMs](/20260217-20260318/2602.21257v1-structured-prompt-language-declarative-context-management-for-llms)  
   标签：评分：7.0/10、query:tokencomp
   evidence：具有预算和限制约束的显式标记管理
9. [MoBiQuant: Mixture-of-Bits Quantization for Token-Adaptive Elastic LLMs](/20260217-20260318/2602.20191v1-mobiquant-mixture-of-bits-quantization-for-token-adaptive-elastic-llms)  
   标签：评分：6.0/10、query:tokencomp
   evidence：弹性大语言模型的Token自适应量化
10. [KnapSpec: Self-Speculative Decoding via Adaptive Layer Selection as a Knapsack Problem](/20260217-20260318/2602.20217v1-knapspec-self-speculative-decoding-via-adaptive-layer-selection-as-a-knapsack-problem)  
   标签：评分：6.0/10、query:tokencomp
   evidence：自适应层选择以提高Token吞吐量
11. [Polynomial Mixing for Efficient Self-supervised Speech Encoders](/20260217-20260318/2603.00683v1-polynomial-mixing-for-efficient-self-supervised-speech-encoders)  
   标签：评分：6.0/10、query:tokencomp
   evidence：作为自注意力替代方案的Token混合机制


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
