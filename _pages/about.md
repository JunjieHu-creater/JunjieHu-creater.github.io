---
layout: page
title: "About Me"
permalink: /about/
excerpt: "A brief introduction to Junjie Hu, a Master's student focused on transport engineering, data analysis, and traffic safety."
redirect_from:
  - /about.html
---

<!-- ================= 样式与切换按钮 ================= -->
<style>
.lang-en { display: none; }
.lang-zh { display: block; }

:root[data-lang="en"] .lang-en { display: block; }
:root[data-lang="en"] .lang-zh { display: none; }

.lang-switch { position: fixed; top: 12px; right: 12px; z-index: 9999; font-family: system-ui; }
.lang-switch button { margin-left: 6px; padding: 6px 10px; border-radius: 6px; border: 1px solid #ddd; background: white; cursor: pointer; }
.lang-switch button.active { border-color: #4183C4; font-weight: 600; }
</style>

<div class="lang-switch">
  <button class="lang-btn" data-lang="zh" type="button">中文</button>
  <button class="lang-btn" data-lang="en" type="button">English</button>
</div>

<script>
(function(){
  function setLang(lang){
    document.documentElement.setAttribute('data-lang', lang);
    document.documentElement.lang = (lang === 'en' ? 'en-US' : 'zh-CN');
    localStorage.setItem('siteLang', lang);
    document.querySelectorAll('.lang-btn').forEach(b => {
      b.classList.toggle('active', b.dataset.lang === lang);
    });
  }
  document.addEventListener('DOMContentLoaded', function(){
    var saved = localStorage.getItem('siteLang') || 'zh';
    setLang(saved);
    document.querySelectorAll('.lang-btn').forEach(btn => {
      btn.addEventListener('click', function(){ setLang(this.dataset.lang); });
    });
  });
})();
</script>

<!-- ================= 中文内容 ================= -->
<div class="lang-zh">

👋 你好！我是 **胡俊杰 (Junjie Hu)**，中南大学运输工程学院硕士二年级研究生，导师是 [Jaeyoung Jay Lee 教授](https://www.researchgate.net/profile/Jaeyoung-Lee-26)。  

研究兴趣：  
* 📊 **交通时空数据分析**  
* 🚗 **车辆决策与控制**  
* 🧠 **深度学习在交通系统中的应用**  
* 🛡️ **先进的交通安全方法**  

我热衷于利用大规模交通数据揭示潜在规律，推动交通系统更安全、更智能、更可持续。  

🔗 **联系方式**  
* **邮箱：** [junjie_hu@csu.edu.cn](mailto:junjie_hu@csu.edu.cn)  
* **微信：** [扫码查看二维码](../images/wechat.jpg)  
* **简历：** [下载我的 CV](../assets/JunjieHu_CV.pdf)  

---

## 教育经历 🎓
* **硕士研究生（交通工程）** — 中南大学，长沙，中国 (2023年9月 - 至今)  
* **本科（物流工程）** — 中南大学，长沙，中国 (2019年9月 - 2023年6月)  

---

## 实习经历 💼
* **业务风险建模实习生** — Magic Engine Technology, 深圳，中国 (2024年7月 - 2024年9月)  
  - 使用 Python 进行信用风险模型开发与验证。  
  - 大规模数据预处理与特征工程。  
  - 参与撰写风险分析报告，支持战略决策。  

---

## 志愿经历 🌱
* **志愿研究员** — 长沙无障碍提升促进会，长沙，中国 (2025年3月 - 2025年6月)  
  - 调研残障人士出行障碍。  
  - 共同开发无障碍设施众包地图平台。  
  - 项目演示：[在线查看](https://junjiehu.pythonanywhere.com/)  

---

## 学术论文 📄  
*(论文题目与期刊保持英文不翻译)*  

1. **Hu, J.**, Hu, C., Yang, J., Bai, J., & Lee, J. J. (2024). *Do traffic flow states follow Markov properties?* Chaos, Solitons, and Fractals, 183, 114965.  
   <details><summary>📝 贡献</summary>  
   设计了一种高阶交通状态重建方法，证明了交通流的 Markov 特性；结合 Markov 矩阵先验知识，在自编码器框架中实现高精度交通插补。  
   </details>  

2. **Hu, J.**, Bai, J., Yang, J., & Lee, J. (2024). *Crash Risk Prediction Using Sparse Collision Data.* Expert Systems with Applications, 248, 125315.  
   <details><summary>📝 贡献</summary>  
   提出基于历史空间和时间先验知识的碰撞数据增强策略；开发了一种新的因果推断与图卷积网络方法 PST-CGCN，用于预测交通事故风险。  
   </details>  

3. **Hu, J.**, Zhang, J., Bai, J., & Lee, J. (2025). *Dynamic Correlation Analysis of Urban Crashes Using Tucker-Net Based SIRS Model.* Journal of the Franklin Institute.  
   <details><summary>📝 贡献</summary>  
   设计了可迁移的数据驱动模型——基于 Tucker-Net 的 SIRS 模型 (TNBSM)，利用张量分解与 SIRS 框架分析城市交通事故区域的动态相关性。  
   </details>  

4. **Hu, J.**, & Lee, J. (2025). *Car following dynamics in mixed traffic flow...* Physica A, 665, 130519.  
   <details><summary>📝 贡献</summary>  
   应用粗粒化相空间算法，引入复杂网络技术研究跟驰行为，揭示自动驾驶与人类驾驶车辆的差异特征。  
   </details>  

5. **Hu, J.**, Bai, J., & Lee, J. *Simplified and Efficient KNN-Based Method...* Manuscript under review.  
   <details><summary>📝 贡献</summary>  
   提出改进的 KNN 框架，基于空间邻接规则（Queen Contiguity）进行时空邻域匹配，实现稀疏数据下时空图（TSD）的重建与插补。  
   </details>  

6. **Hu, J.**, Gao, D., Hu, C., Zhou, H., & Lee, J. *Rethinking driving style recognition...* Manuscript under review.  
   <details><summary>📝 贡献</summary>  
   提出基于预测误差的驾驶行为建模方法，通过轨迹预测误差分析驾驶差异；利用空间注意力与卷积社交池化学习车辆运动的依赖关系，并引入多模态分布表征不同驾驶风格。  
   </details>  

7. **Hu, J.**, Gao, D., Lee, J., & Wang, L. *Vehicle dynamics analytics based on complex network techniques...* Manuscript under review.  
   <details><summary>📝 贡献</summary>  
   引入自适应轨迹可见图 (TVG) 框架，将车辆轨迹转化为复杂网络，利用可调节的可见性容忍系数刻画几何遮挡和特定驾驶操作的空间尺度。  
   </details>  

8. **Hu, J.**, Lee, J., & Wang, L. *Re-examining the Explanatory Boundaries of Car-Following Models...* Manuscript under review.  
   <details><summary>📝 贡献</summary>  
   提出将车-following 模型残差分解为结构性误差和随机误差，利用不可观测成分模型 (UCM) 对三类标定模型残差进行系统分解，揭示适应性反馈机制。  
   </details>  

9. Yang, J., Lee, J., Mao, S., & **Hu, J.** (2024). *Dynamic safety estimation of airport pick-up area...* IEEE T-ITS, 25(2), 1774–1786.  
   <details><summary>📝 我的角色</summary>  
   协助设计改进的 CUSBoost 算法用于不平衡轨迹数据分类；结合风险指标和空间分布分析提升模型性能。  
   </details>  

10. Wang, L., **Hu, J.**, Lee, J., Yang, Y., & Mao, S. *Analysis of injury severity of crashes with kei cars in Japan...* Manuscript under review.  
    <details><summary>📝 我的角色</summary>  
    基于随机参数 Probit 模型（均值异质性），研究日本 K-car 碰撞伤害严重性；设计了样本外预测方法揭示不同事故严重性机制的差异。  
    </details>  

11. Wang, L., Lee, J., **Hu, J.**, Yang, Y., & Mao, S. *Contributing Factors to the Severity of Crash Injury and Vehicle Damage...* Manuscript under review.  
    <details><summary>📝 我的角色</summary>  
    基于随机参数双变量 Probit 模型（均值异质性），研究日本 K-car 碰撞伤害严重性与车辆损伤因素。  
    </details>  

</div>

<!-- ================= 英文内容（保持原样，不赘述） ================= -->
<div class="lang-en">

👋 Hello! I'm **Junjie Hu (胡俊杰)**, a second-year Master's student at the [School of Transport & Transportation Engineering](https://stte.csu.edu.cn/), [Central South University](https://www.csu.edu.cn/) (CSU). I have the privilege of being advised by [Prof. Jaeyoung Jay Lee](https://www.researchgate.net/profile/Jaeyoung-Lee-26), a distinguished researcher recognized among the top 2% of scientists globally in road safety.

My research passion lies at the dynamic intersection of:
* 📊 **Traffic Spatio-Temporal Data Analysis**
* 🚗 **Vehicular Decision-Making & Control**
* 🧠 **Deep Learning Applications in Transportation Systems**
* 🛡️ **Advanced Traffic Safety Methodologies**

I am driven to analyze large-scale traffic data to uncover patterns that pave the way for safer, more intelligent, and sustainable transportation systems. I am always enthusiastic about collaborating on innovative ideas to advance our collective impact.

🔗 **Connect & Explore:**
* **Email:** [junjie_hu@csu.edu.cn](mailto:junjie_hu@csu.edu.cn)
* **WeChat:** [Scan QR Code](../images/wechat.jpg) 
* **Curriculum Vitae:** [Download My CV](../assets/JunjieHu_CV.pdf) 

## Experience 💼

### Education
* **Master of Engineering, Transportation Engineering**
    * *School of Transportation Engineering, Central South University*
    * *Changsha, China*
    * *September 2023 - Present*

* **Bachelor of Engineering, Logistics Engineering**
    * *School of Transportation Engineering, Central South University*
    * *Changsha, China*
    * *September 2019 - June 2023*

### Professional Experience
* **Business Risk Modeling Intern**
    * *Magic Engine Technology Co., Ltd., Shenzhen, China*
    * *July 2024 - September 2024*
    * Assisted in developing and validating credit risk models for bank partners using Python (Pandas, Scikit-learn).
    * Pre-processed large-scale transaction data and engineered features to improve model accuracy.
    * Contributed to a risk analysis report that provided data-driven insights for business strategy.

### Volunteer & Community Engagement
* **Volunteer Researcher**
    * *Changsha Accessibility Enhancement Promotion Association, Changsha, Hunan, China*
    * *March 2025 - June 2025*
    * Investigated transportation barriers for people with disabilities through field visits and surveys.
    * Co-developed a crowdsourced mapping platform for accessible facilities.
    * Project Demo: [View Live Project](https://junjiehu.pythonanywhere.com/)

## Publications 📄
*(Names in **bold** indicate my authorship)*

- <span style="display: inline-block; width: 22px; height: 22px; line-height: 23px; text-align: center; color: white; background-color: #4183C4; border-radius: 50%; font-weight: bold; margin-right: 10px;">1</span> **Hu, J.**, Hu, C., Yang, J., Bai, J., & Lee, J. J. (2024). Do traffic flow states follow Markov properties? A high-order spatiotemporal traffic state reconstruction approach for traffic prediction and imputation. *Chaos, Solitons, and Fractals*, 183, 114965. [https://doi.org/10.1016/j.chaos.2024.114965](https://doi.org/10.1016/j.chaos.2024.114965)
    <details>
    <summary>📝 <b>Contribution (Click to expand)</b></summary>
    <em>Designed a high-order traffic state reconstruction method demonstrating traffic flow's Markov property. Leveraged Markov matrix prior knowledge for high-accuracy traffic imputation tasks using an auto-encoder framework.</em>
    </details>

- <span style="display: inline-block; width: 22px; height: 22px; line-height: 23px; text-align: center; color: white; background-color: #4183C4; border-radius: 50%; font-weight: bold; margin-right: 10px;">2</span> **Hu, J.**, Bai, J., Yang, J., & Lee, J. (2024). Crash Risk Prediction Using Sparse Collision Data: Causal Inference and Graph Convolutional Networks Approaches. *Expert Systems with Applications*, 248, 125315. [https://doi.org/10.1016/j.eswa.2024.125315](https://doi.org/10.1016/j.eswa.2024.125315)
    <details>
    <summary>📝 <b>Contribution (Click to expand)</b></summary>
    <em>Created a crash data enhancement strategy utilizing historic priori spatial and temporal knowledge. Developed a novel method, Priori Spatial and Temporal Causal Graph Convolutional Network (PST-CGCN), for predicting crash risk based on causal inference and graph convolutional networks.</em>
    </details>

- <span style="display: inline-block; width: 22px; height: 22px; line-height: 23px; text-align: center; color: white; background-color: #4183C4; border-radius: 50%; font-weight: bold; margin-right: 10px;">3</span> **Hu, J.**, Zhang, J., Bai, J., & Lee, J. Dynamic Correlation Analysis of Urban Crashes Using Tucker-Net Based SIRS Model: A Case Study in New York City. *Journal of the Franklin Institute*, 107946, https://doi.org/10.1016/j.jfranklin.2025.107946
    <details>
    <summary>📝 <b>Contribution (Click to expand)</b></summary>
    <em>Designed a new data-driven and transferable analysis model, the Tucker-Net based Susceptible-Infectious-Recovered-Susceptible (SIRS) model (TNBSM), for exploring dynamic correlations within crash zones using tensor decomposition and the SIRS model.</em>
    </details>

- <span style="display: inline-block; width: 22px; height: 22px; line-height: 23px; text-align: center; color: white; background-color: #4183C4; border-radius: 50%; font-weight: bold; margin-right: 10px;">4</span> **Hu, J.**, & Lee, J. (2025). Car following dynamics in mixed traffic flow of autonomous and human-driven vehicles: complex networks approach. *Physica A: Statistical Mechanics and its Applications*, 665, 130519. [https://doi.org/10.1016/j.physa.2025.130519](https://doi.org/10.1016/j.physa.2025.130519)
    <details>
    <summary>📝 <b>Contribution (Click to expand)</b></summary>
    <em>Applied a coarse-grained phase space algorithm, introduced complex network technology into vehicle-following behavior analysis, and revealed distinct characteristics and differences between autonomous vehicles (AV) and human-driven vehicles (HV).</em>
    </details>

- <span style="display: inline-block; width: 22px; height: 22px; line-height: 23px; text-align: center; color: white; background-color: #4183C4; border-radius: 50%; font-weight: bold; margin-right: 10px;">5</span> **Hu, J.**, Bai, J., & Lee, J. Simplified and Efficient KNN-Based Method for High-Resolution Traffic Time-Space Diagram Imputation. *Manuscript under review*.
    <details>
    <summary>📝 <b>Contribution (Click to expand)</b></summary>
    <em>Proposed a modified K-Nearest Neighbors (KNN) framework for reconstructing and imputing Time-Space Diagrams (TSD) from sparse data by matching similar spatiotemporal neighborhood features defined by Queen Contiguity Spatial Rule.</em>
    </details>

- <span style="display: inline-block; width: 22px; height: 22px; line-height: 23px; text-align: center; color: white; background-color: #4183C4; border-radius: 50%; font-weight: bold; margin-right: 10px;">6</span> **Hu, J.**, Gao, D., Hu, C., Zhou, H., & Lee, J. Rethinking driving style recognition: A prediction error-based driving behavior modeling. *Manuscript under review*.
    <details>
    <summary>📝 <b>Contribution (Click to expand)</b></summary>
    <em>Revisited an end-to-end approach for driving style recognition by exploring driver behavior heterogeneity through trajectory prediction model errors. Utilized spatial attention and convolutional social pooling to learn interdependencies in vehicle motion and introduced a multi-modal distribution for future trajectories based on driving style.</em>
    </details>

- <span style="display: inline-block; width: 22px; height: 22px; line-height: 23px; text-align: center; color: white; background-color: #4183C4; border-radius: 50%; font-weight: bold; margin-right: 10px;">7</span> **Hu, J.**, Gao, D., Lee, J., & Wang, L. Vehicle dynamics analytics based on complex network techniques: a trajectory-based visibility graph approach. *Manuscript under review*.
    <details>
    <summary>📝 <b>Contribution (Click to expand)</b></summary>
    <em>Introduced an adaptive trajectory-based visibility graph (TVG) framework, a novel method for dissecting vehicle dynamics by transforming planar trajectory data into complex networks. This framework features a tunable visibility tolerance coefficient, dynamically scaled by lateral displacement, enabling the TVG to capture geometric occlusions and maneuver-specific spatial scales.</em>
    </details>

- <span style="display: inline-block; width: 22px; height: 22px; line-height: 23px; text-align: center; color: white; background-color: #4183C4; border-radius: 50%; font-weight: bold; margin-right: 10px;">8</span> **Hu, J.**, Lee, J., & Wang, L. Re-examining the Explanatory Boundaries of Car-Following Models: From a Systematic Decomposition of Fitting Errors to the Revelation of Adaptive Feedback Mechanisms. *Manuscript under review*.
    <details>
    <summary>📝 <b>Contribution (Click to expand)</b></summary>
    <em>Posited that residuals of car-following (cf) model are a composite of structural errors and random error and utilized an Unobserved Components Model to decompose the residual series from three calibrated CF models.</em>
    </details>

- <span style="display: inline-block; width: 22px; height: 22px; line-height: 23px; text-align: center; color: white; background-color: #4183C4; border-radius: 50%; font-weight: bold; margin-right: 10px;">9</span> Yang, J., Lee, J., Mao, S., & **Hu, J.** (2024). Dynamic safety estimation of airport pick-up area based on video trajectory data. *IEEE Transactions on Intelligent Transportation Systems*, 25(2), 1774–1786. [https://doi.org/10.1109/TITS.2023.3275986](https://doi.org/10.1109/TITS.2023.3275986)
    <details>
    <summary>📝 <b>My Role (Click to expand)</b></summary>
    <em>Assisted in designing a modified CUSBoost algorithm for imbalanced trajectory data classification, leveraging four risk indicators and spatial distribution analysis.</em>
    </details>

- <span style="display: inline-block; width: 22px; height: 22px; line-height: 23px; text-align: center; color: white; background-color: #4183C4; border-radius: 50%; font-weight: bold; margin-right: 10px;">10</span> Wang, L., **Hu, J.**, Lee, J, Yang, Y., & Mao, S. Analysis of injury severity of single-vehicle and two-vehicle crashes with lightweight vehicles (kei cars) in Japan: A random parameters approach with heterogeneity in means. *Manuscript under review*.
    <details>
    <summary>📝 <b>My Role (Click to expand)</b></summary>
    <em>Contributed to investigating K-car crash injury severity using a random parameters probit model with heterogeneity in means. Designed an out-of-sample prediction approach to clarify heterogeneity among various crash severity mechanisms.</em>
    </details>

- <span style="display: inline-block; width: 22px; height: 22px; line-height: 23px; text-align: center; color: white; background-color: #4183C4; border-radius: 50%; font-weight: bold; margin-right: 10px;">11</span> Wang, L., Lee, J, **Hu, J.**, Y & Mao, S. Contributing Factors to the Severity of Crash Injury and Vehicle Damage Involving Japanese Lightweight K-cars: Considering Unobserved Heterogeneity. *Manuscript under review*.
    <details>
    <summary>📝 <b>My Role (Click to expand)</b></summary>
    <em>Contributed to investigating K-car crash injury severity using a random parameter bivariate probit models with heterogeneity in means.</em>
    </details>

</div>
