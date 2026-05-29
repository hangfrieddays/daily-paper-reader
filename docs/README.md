<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-05-20 ~ 2026-05-29
- 运行时间：2026-05-29 15:59:44 UTC
- 运行状态：成功
- 本次总论文数：15
- 精读区：11
- 速读区：4

### 今日简报（AI）
1) 今日精选聚焦扩散模型与流匹配生成模型的后训练优化，两份9分精读论文展示了偏好对齐与奖励引导的最新突破。
2) 最值得关注的方向：Linear-DPO将DPO直接适配到扩散模型，Hierarchical Variational Policies提出分层变分策略实现奖励引导，两者为文本到图像生成提供高效对齐方案。
3) 建议普通读者优先阅读精读列表，了解如何用偏好优化与奖励引导提升生成质量；速读中的公平性修正采样也值得关注。
- 详情：[/20260520-20260529/README](/20260520-20260529/README)

### 精读区论文标签
1. [Linear-DPO: Linear Direct Preference Optimization for Diffusion and Flow-Matching Generative Models](/20260520-20260529/2605.21123v1-linear-dpo-linear-direct-preference-optimization-for-diffusion-and-flow-matching-generative-models)  
   标签：评分：9.0/10、query:image-gen-rl
   evidence：将DPO扩展到扩散和流匹配模型用于文本到图像生成
2. [Hierarchical Variational Policies for Reward-Guided Diffusion](/20260520-20260529/2605.21661v1-hierarchical-variational-policies-for-reward-guided-diffusion)  
   标签：评分：9.0/10、query:image-gen-rl
   evidence：使用学习策略对齐扩散采样与奖励信号
3. [DRM: Diffusion-based Reward Model With Step-wise Guidance](/20260520-20260529/2605.25661v1-drm-diffusion-based-reward-model-with-step-wise-guidance)  
   标签：评分：9.0/10、query:image-gen-rl
   evidence：基于扩散的奖励模型，用于对齐图像生成与偏好
4. [DyCoRM: Dynamic Criterion-Aware Reward Modeling for Text-to-Image Generation](/20260520-20260529/2605.25876v1-dycorm-dynamic-criterion-aware-reward-modeling-for-text-to-image-generation)  
   标签：评分：9.0/10、query:image-gen-rl
   evidence：适应用户标准的文本到图像生成奖励模型
5. [AdvantageFlow: Advantage-Weighted Least Squares for RL in Flow Models](/20260520-20260529/2605.26013v1-advantageflow-advantage-weighted-least-squares-for-rl-in-flow-models)  
   标签：评分：9.0/10、query:image-gen-rl
   evidence：图像生成中针对整流流模型的强化学习算法
6. [Reinforcing Few-step Generators via Reward-Tilted Distribution Matching](/20260520-20260529/2605.26108v1-reinforcing-few-step-generators-via-reward-tilted-distribution-matching)  
   标签：评分：9.0/10、query:image-gen-rl
   evidence：将分布匹配与奖励引导的强化学习结合用于少步图像生成器
7. [Beyond Pairwise Preferences: Listwise Reward-Aware Alignment for Diffusion Models](/20260520-20260529/2605.26491v1-beyond-pairwise-preferences-listwise-reward-aware-alignment-for-diffusion-models)  
   标签：评分：9.0/10、query:image-gen-rl
   evidence：提出奖励感知的列表偏好优化用于扩散模型
8. [Explicit Critic Guidance for Aligning Diffusion Models](/20260520-20260529/2605.27736v1-explicit-critic-guidance-for-aligning-diffusion-models)  
   标签：评分：9.0/10、query:image-gen-rl
   evidence：用于对齐扩散模型的显式强化学习演员-评论家框架
9. [Compositional Text-to-Image Generation Via Region-aware Bimodal Direct Preference Optimization](/20260520-20260529/2605.28615v1-compositional-text-to-image-generation-via-region-aware-bimodal-direct-preference-optimization)  
   标签：评分：9.0/10、query:image-gen-rl
   evidence：直接偏好优化（RLHF变体）用于文本到图像生成，处理组合提示
10. [OSP-Next: Efficient High-Quality Video Generation with Sparse Sequence Parallelism, HiF8 Quantization, and Reinforcement Learning](/20260520-20260529/2605.28691v1-osp-next-efficient-high-quality-video-generation-with-sparse-sequence-parallelism-hif8-quantization-and-reinforcement-learning)  
   标签：评分：9.0/10、query:image-gen-rl
   evidence：使用强化学习提高视频生成效率
11. [Guidance Contrastive Token Credit Assignment for Discrete Policy Optimization](/20260520-20260529/2605.29198v1-guidance-contrastive-token-credit-assignment-for-discrete-policy-optimization)  
   标签：评分：9.0/10、query:image-gen-rl
   evidence：提出GCPO方法在文本到图像生成的强化学习中实现token级信用分配

### 速读区论文标签
1. [Conflict-Aware Additive Guidance for Flow Models under Compositional Rewards](/20260520-20260529/2605.20758v1-conflict-aware-additive-guidance-for-flow-models-under-compositional-rewards)  
   标签：评分：8.0/10、query:image-gen-rl
   evidence：提出用于流模型的加性引导方法，利用组合奖励纠正生成偏差
2. [Precise: SDE-Consistent Stochastic Sampling for RL Post-Training of Flow-Matching Models](/20260520-20260529/2605.23522v1-precise-sde-consistent-stochastic-sampling-for-rl-post-training-of-flow-matching-models)  
   标签：评分：8.0/10、query:image-gen-rl
   evidence：通过SDE采样对流匹配图像生成器进行RL后训练
3. [HoloFair: Unified T2I Fairness Evaluation and Fair-GRPO Debiasing](/20260520-20260529/2605.24687v1-holofair-unified-t2i-fairness-evaluation-and-fair-grpo-debiasing)  
   标签：评分：8.0/10、query:image-gen-rl
   evidence：Fair-GRPO使用强化学习进行文本到图像去偏
4. [Geo-Align: Video Generation Alignment via Metric Geometry Reward](/20260520-20260529/2605.23903v1-geo-align-video-generation-alignment-via-metric-geometry-reward)  
   标签：评分：7.0/10、query:image-gen-rl
   evidence：基于度量几何奖励的强化学习框架用于视频生成对齐


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
