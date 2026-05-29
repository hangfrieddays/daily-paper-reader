<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-05-20 ~ 2026-05-29
- 运行时间：2026-05-29 15:43:45 UTC
- 运行状态：成功
- 本次总论文数：17
- 精读区：12
- 速读区：5

### 今日简报（AI）
本期日报推荐17篇论文，精读12篇，重点聚焦扩散/流匹配模型的后训练及文本-图像生成方向。最值得关注的两项工作分别是：《Precise》提出SDE一致随机采样用于流匹配模型RL后训练（10.0分），以及《RankE》实现离散文本-图像生成的后训练与解码器协同进化（9.0分）。建议普通读者优先精读这两篇，深入理解后训练中采样一致性与端到端优化的前沿思路。
- 详情：[/20260520-20260529/README](/20260520-20260529/README)

### 精读区论文标签
1. [Precise: SDE-Consistent Stochastic Sampling for RL Post-Training of Flow-Matching Models](/20260520-20260529/2605.23522v1-precise-sde-consistent-stochastic-sampling-for-rl-post-training-of-flow-matching-models)  
   标签：评分：10.0/10、query:image-gen-rl
   evidence：对流动匹配模型进行强化学习后训练以提升图像质量
2. [RankE: End-to-End Post-Training for Discrete Text-to-Image Generation with Decoder Co-Evolution](/20260520-20260529/2605.21195v1-ranke-end-to-end-post-training-for-discrete-text-to-image-generation-with-decoder-co-evolution)  
   标签：评分：9.0/10、query:image-gen-rl
   evidence：针对文本到图像生成中的强化学习后训练，解决奖励分数和图像质量之间的权衡
3. [Hierarchical Variational Policies for Reward-Guided Diffusion](/20260520-20260529/2605.21661v1-hierarchical-variational-policies-for-reward-guided-diffusion)  
   标签：评分：9.0/10、query:image-gen-rl
   evidence：使用分层变分策略实现奖励引导的扩散生成
4. [Geo-Align: Video Generation Alignment via Metric Geometry Reward](/20260520-20260529/2605.23903v1-geo-align-video-generation-alignment-via-metric-geometry-reward)  
   标签：评分：9.0/10、query:image-gen-rl
   evidence：首个专门为相机控制视频重渲染设计的强化学习框架，包含奖励函数设计
5. [HoloFair: Unified T2I Fairness Evaluation and Fair-GRPO Debiasing](/20260520-20260529/2605.24687v1-holofair-unified-t2i-fairness-evaluation-and-fair-grpo-debiasing)  
   标签：评分：9.0/10、query:image-gen-rl
   evidence：使用强化学习（GRPO）对文本到图像模型进行去偏，直接涉及图像生成中的强化学习和奖励设计。
6. [DRM: Diffusion-based Reward Model With Step-wise Guidance](/20260520-20260529/2605.25661v1-drm-diffusion-based-reward-model-with-step-wise-guidance)  
   标签：评分：9.0/10、query:image-gen-rl
   evidence：用于图像质量评估的扩散奖励模型
7. [DyCoRM: Dynamic Criterion-Aware Reward Modeling for Text-to-Image Generation](/20260520-20260529/2605.25876v1-dycorm-dynamic-criterion-aware-reward-modeling-for-text-to-image-generation)  
   标签：评分：9.0/10、query:image-gen-rl
   evidence：面向文本到图像生成的动态标准感知奖励模型
8. [AdvantageFlow: Advantage-Weighted Least Squares for RL in Flow Models](/20260520-20260529/2605.26013v1-advantageflow-advantage-weighted-least-squares-for-rl-in-flow-models)  
   标签：评分：9.0/10、query:image-gen-rl
   evidence：基于流的图像生成强化学习
9. [Reinforcing Few-step Generators via Reward-Tilted Distribution Matching](/20260520-20260529/2605.26108v1-reinforcing-few-step-generators-via-reward-tilted-distribution-matching)  
   标签：评分：9.0/10、query:image-gen-rl
   evidence：使用奖励引导的强化学习对齐少步图像生成器与人类偏好
10. [Explicit Critic Guidance for Aligning Diffusion Models](/20260520-20260529/2605.27736v1-explicit-critic-guidance-for-aligning-diffusion-models)  
   标签：评分：9.0/10、query:image-gen-rl
   evidence：使用在线强化学习（演员-评论家）对齐扩散模型
11. [Compositional Text-to-Image Generation Via Region-aware Bimodal Direct Preference Optimization](/20260520-20260529/2605.28615v1-compositional-text-to-image-generation-via-region-aware-bimodal-direct-preference-optimization)  
   标签：评分：9.0/10、query:image-gen-rl
   evidence：使用直接偏好优化（强化学习的一种）进行组合文本到图像生成
12. [Guidance Contrastive Token Credit Assignment for Discrete Policy Optimization](/20260520-20260529/2605.29198v1-guidance-contrastive-token-credit-assignment-for-discrete-policy-optimization)  
   标签：评分：9.0/10、query:image-gen-rl
   evidence：面向文本到图像生成的强化学习中的令牌级信用分配

### 速读区论文标签
1. [Linear-DPO: Linear Direct Preference Optimization for Diffusion and Flow-Matching Generative Models](/20260520-20260529/2605.21123v1-linear-dpo-linear-direct-preference-optimization-for-diffusion-and-flow-matching-generative-models)  
   标签：评分：8.0/10、query:image-gen-rl
   evidence：文本到图像生成中扩散与流匹配模型的直接偏好优化
2. [Beyond Pairwise Preferences: Listwise Reward-Aware Alignment for Diffusion Models](/20260520-20260529/2605.26491v1-beyond-pairwise-preferences-listwise-reward-aware-alignment-for-diffusion-models)  
   标签：评分：8.0/10、query:image-gen-rl
   evidence：使用列表偏好进行扩散模型的奖励感知对齐
3. [OSP-Next: Efficient High-Quality Video Generation with Sparse Sequence Parallelism, HiF8 Quantization, and Reinforcement Learning](/20260520-20260529/2605.28691v1-osp-next-efficient-high-quality-video-generation-with-sparse-sequence-parallelism-hif8-quantization-and-reinforcement-learning)  
   标签：评分：8.0/10、query:image-gen-rl
   evidence：强化学习用于视频生成，与图像生成直接相关
4. [Aligning Few-Step Generative Models by Amortizing Sample-based Variational Inference](/20260520-20260529/2605.26552v2-aligning-few-step-generative-models-by-amortizing-sample-based-variational-inference)  
   标签：评分：7.0/10、query:image-gen-rl
   evidence：通用对齐框架，使用奖励倾斜分布，可应用于图像生成
5. [Conflict-Aware Additive Guidance for Flow Models under Compositional Rewards](/20260520-20260529/2605.20758v1-conflict-aware-additive-guidance-for-flow-models-under-compositional-rewards)  
   标签：评分：6.0/10、query:image-gen-rl
   evidence：在组合奖励下对流模型进行推理时引导


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
