---
permalink: /
title: "About Me"
excerpt: "A brief introduction to Junjie Hu, a Master's student focused on transport engineering, data analysis, and traffic safety."
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<style>
.language-toggle-container {
  display: flex;
  align-items: center;
  justify-content: flex-end; /* Aligns the toggle to the right */
  margin-bottom: 20px;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
}
.language-toggle-label {
  margin: 0 10px;
  font-size: 16px;
  color: #333;
  font-weight: bold;
}
.language-toggle-switch {
  position: relative;
  display: inline-block;
  width: 60px;
  height: 34px;
}
.language-toggle-switch input {
  opacity: 0;
  width: 0;
  height: 0;
}
.language-slider {
  position: absolute;
  cursor: pointer;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background-color: #4183C4; /* Blue color to match publication numbers */
  -webkit-transition: .4s;
  transition: .4s;
  border-radius: 34px;
}
.language-slider:before {
  position: absolute;
  content: "";
  height: 26px;
  width: 26px;
  left: 4px;
  bottom: 4px;
  background-color: white;
  -webkit-transition: .4s;
  transition: .4s;
  border-radius: 50%;
}
input:checked + .language-slider {
  background-color: #4183C4;
}
input:checked + .language-slider:before {
  -webkit-transform: translateX(26px);
  -ms-transform: translateX(26px);
  transform: translateX(26px);
}

/* --- CORE LOGIC FOR SINGLE LANGUAGE DISPLAY --- */
/* By default, hide the Chinese elements */
.lang-zh { display: none; } 

/* When the body has the 'lang-zh-active' class... */
/* ...show the Chinese elements (as inline elements) */
body.lang-zh-active .lang-zh { display: inline; }
/* ...and hide the English elements */
body.lang-zh-active .lang-en { display: none; }

/* Special rules for block-level elements like divs or list items */
.lang-block-zh { display: none; }
body.lang-zh-active .lang-block-zh { display: block; }
body.lang-zh-active .lang-block-en { display: none; }
</style>

<div class="lang-en lang-block-en">
👋 Hello! I'm <strong>Junjie Hu (胡俊杰)</strong>, a second-year Master's student at the <a href="https://stte.csu.edu.cn/">School of Transport & Transportation Engineering</a>, <a href="https://www.csu.edu.cn/">Central South University</a> (CSU). I have the privilege of being advised by <a href="https://www.researchgate.net/profile/Jaeyoung-Lee-26">Prof. Jaeyoung Jay Lee</a>, a distinguished researcher recognized among the top 2% of scientists globally in road safety.
</div>
<div class="lang-zh lang-block-zh">
👋 你好！我是<strong>胡俊杰 (Junjie Hu)</strong>，一名就读于<a href="https://www.csu.edu.cn/">中南大学</a><a href="https://stte.csu.edu.cn/">交通运输工程学院</a>的硕士二年级学生。我的导师是<a href="https://www.researchgate.net/profile/Jaeyoung-Lee-26">Jaeyoung Jay Lee</a>教授，他是在道路安全领域全球排名前2%的杰出学者。
</div>

<div class="lang-en lang-block-en">
My research passion lies at the dynamic intersection of:
</div>
<div class="lang-zh lang-block-zh">
我的研究兴趣聚焦于以下几个前沿领域的交叉地带：
</div>
* 📊 <span class="lang-en">**Traffic Spatio-Temporal Data Analysis**</span><span class="lang-zh">**交通时空数据分析**</span>
* 🚗 <span class="lang-en">**Vehicular Decision-Making & Control**</span><span class="lang-zh">**车辆决策与控制**</span>
* 🧠 <span class="lang-en">**Deep Learning Applications in Transportation Systems**</span><span class="lang-zh">**深度学习在交通系统中的应用**</span>
* 🛡️ <span class="lang-en">**Advanced Traffic Safety Methodologies**</span><span class="lang-zh">**前沿交通安全方法论**</span>

<div class="lang-en lang-block-en">
I am driven to analyze large-scale traffic data to uncover patterns that pave the way for safer, more intelligent, and sustainable transportation systems. I am always enthusiastic about collaborating on innovative ideas to advance our collective impact.
</div>
<div class="lang-zh lang-block-zh">
我致力于通过分析大规模交通数据来揭示深层模式，为构建更安全、更智能、更可持续的交通系统铺平道路。我热衷于就创新想法进行合作，共同推动学术进步与社会影响。
</div>

<br>
<div class="language-toggle-container">
  <span class="language-toggle-label lang-en">EN</span>
  <span class="language-toggle-label lang-zh">中文</span>
  <label class="language-toggle-switch">
    <input type="checkbox" id="language-toggle-checkbox">
    <span class="language-slider"></span>
  </label>
</div>

🔗 **<span class="lang-en">Connect & Explore</span><span class="lang-zh">联系与探索</span>:**
* **<span class="lang-en">Email</span><span class="lang-zh">邮箱</span>:** [junjie_hu@csu.edu.cn](mailto:junjie_hu@csu.edu.cn)
* **<span class="lang-en">WeChat</span><span class="lang-zh">微信</span>:** [<span class="lang-en">Scan QR Code</span><span class="lang-zh">扫描二维码</span>](../images/wechat.jpg) 
* **<span class="lang-en">Curriculum Vitae</span><span class="lang-zh">个人简历</span>:** [<span class="lang-en">Download My CV</span><span class="lang-zh">下载简历</span>](../assets/JunjieHu_CV.pdf) 

## <span class="lang-en">Experience 💼</span><span class="lang-zh">个人经历 💼</span>

### <span class="lang-en">Education</span><span class="lang-zh">教育背景</span>
* **<span class="lang-en">Master of Engineering, Transportation Engineering</span><span class="lang-zh">工学硕士，交通运输工程</span>**
    * *<span class="lang-en">School of Transportation Engineering, Central South University</span><span class="lang-zh">中南大学，交通运输工程学院</span>*
    * *<span class="lang-en">Changsha, China</span><span class="lang-zh">中国，长沙</span>*
    * *<span class="lang-en">September 2023 - Present</span><span class="lang-zh">2023年9月 - 至今</span>*

* **<span class="lang-en">Bachelor of Engineering, Logistics Engineering</span><span class="lang-zh">工学学士，物流工程</span>**
    * *<span class="lang-en">School of Transportation Engineering, Central South University</span><span class="lang-zh">中南大学，交通运输工程学院</span>*
    * *<span class="lang-en">Changsha, China</span><span class="lang-zh">中国，长沙</span>*
    * *<span class="lang-en">September 2019 - June 2023</span><span class="lang-zh">2019年9月 - 2023年6月</span>*

### <span class="lang-en">Professional Experience</span><span class="lang-zh">实习与工作经历</span>
* **<span class="lang-en">Business Risk Modeling Intern</span><span class="lang-zh">业务风险建模实习生</span>**
    * *<span class="lang-en">Magic Engine Technology Co., Ltd., Shenzhen, China</span><span class="lang-zh">魔镜技术有限公司，中国，深圳</span>*
    * *<span class="lang-en">July 2024 - September 2024</span><span class="lang-zh">2024年7月 - 2024年9月</span>*
    <div class="lang-block-en">
    * Assisted in developing and validating credit risk models for bank partners using Python (Pandas, Scikit-learn).
    * Pre-processed large-scale transaction data and engineered features to improve model accuracy.
    * Contributed to a risk analysis report that provided data-driven insights for business strategy.
    </div>
    <div class="lang-block-zh">
    * 使用Python（Pandas, Scikit-learn）协助银行合作伙伴开发并验证信用风险模型。
    * 对大规模交易数据进行预处理，并构建特征工程以提升模型精度。
    * 参与撰写风险分析报告，为业务策略提供了数据驱动的洞见。
    </div>

### <span class="lang-en">Volunteer & Community Engagement</span><span class="lang-zh">志愿与社区服务</span>
* **<span class="lang-en">Volunteer Researcher</span><span class="lang-zh">志愿者研究员</span>**
    * *<span class="lang-en">Changsha Accessibility Enhancement Promotion Association, Changsha, Hunan, China</span><span class="lang-zh">长沙市无障碍环境促进会，中国，湖南，长沙</span>*
    * *<span class="lang-en">March 2025 - June 2025</span><span class="lang-zh">2025年3月 - 2025年6月</span>*
    <div class="lang-block-en">
    * Investigated transportation barriers for people with disabilities through field visits and surveys.
    * Co-developed a crowdsourced mapping platform for accessible facilities.
    * Project Demo: [View Live Project](https://junjiehu.pythonanywhere.com/)
    </div>
    <div class="lang-block-zh">
    * 通过实地考察和问卷调查，研究残障人士在交通出行中遇到的障碍。
    * 合作开发了一个用于无障碍设施的众包地图平台。
    * 项目演示：[查看在线项目](https://junjiehu.pythonanywhere.com/)
    </div>

## <span class="lang-en">Publications 📄</span><span class="lang-zh">学术发表 📄</span>
*(<span class="lang-en">Names in <strong>bold</strong> indicate my authorship</span><span class="lang-zh"><strong>加粗</strong>字体为本人</span>)*

- <span style="display: inline-block; width: 22px; height: 22px; line-height: 23px; text-align: center; color: white; background-color: #4183C4; border-radius: 50%; font-weight: bold; margin-right: 10px;">1</span> **Hu, J.**, Hu, C., Yang, J., Bai, J., & Lee, J. J. (2024). Do traffic flow states follow Markov properties? A high-order spatiotemporal traffic state reconstruction approach for traffic prediction and imputation. *Chaos, Solitons, and Fractals*, 183, 114965. [https://doi.org/10.1016/j.chaos.2024.114965](https://doi.org/10.1016/j.chaos.2024.114965)
    <details>
    <summary>📝 <b class="lang-en">Contribution (Click to expand)</b><b class="lang-zh">主要贡献 (点击展开)</b></summary>
    <em class="lang-en">Designed a high-order traffic state reconstruction method demonstrating traffic flow's Markov property. Leveraged Markov matrix prior knowledge for high-accuracy traffic imputation tasks using an auto-encoder framework.</em>
    <em class="lang-zh">设计了一种高阶交通状态重构方法，证明了交通流具有马尔可夫特性。利用马尔可夫矩阵的先验知识，在一个自编码器框架下完成了高精度的交通数据插补任务。</em>
    </details>

- <span style="display: inline-block; width: 22px; height: 22px; line-height: 23px; text-align: center; color: white; background-color: #4183C4; border-radius: 50%; font-weight: bold; margin-right: 10px;">2</span> **Hu, J.**, Bai, J., Yang, J., & Lee, J. (2024). Crash Risk Prediction Using Sparse Collision Data: Causal Inference and Graph Convolutional Networks Approaches. *Expert Systems with Applications*, 248, 125315. [https://doi.org/10.1016/j.eswa.2024.125315](https://doi.org/10.1016/j.eswa.2024.125315)
    <details>
    <summary>📝 <b class="lang-en">Contribution (Click to expand)</b><b class="lang-zh">主要贡献 (点击展开)</b></summary>
    <em class="lang-en">Created a crash data enhancement strategy utilizing historic priori spatial and temporal knowledge. Developed a novel method, Priori Spatial and Temporal Causal Graph Convolutional Network (PST-CGCN), for predicting crash risk based on causal inference and graph convolutional networks.</em>
    <em class="lang-zh">创建了一种利用历史时空先验知识的事故数据增强策略。基于因果推断和图卷积网络，开发了一种名为“先验时空因果图卷积网络 (PST-CGCN)”的新方法用于预测事故风险。</em>
    </details>

- <span style="display: inline-block; width: 22px; height: 22px; line-height: 23px; text-align: center; color: white; background-color: #4183C4; border-radius: 50%; font-weight: bold; margin-right: 10px;">3</span> **Hu, J.**, Zhang, J., Bai, J., & Lee, J. Dynamic Correlation Analysis of Urban Crashes Using Tucker-Net Based SIRS Model: A Case Study in New York City. *Journal of the Franklin Institute*, 107946, https://doi.org/10.1016/j.jfranklin.2025.107946
    <details>
    <summary>📝 <b class="lang-en">Contribution (Click to expand)</b><b class="lang-zh">主要贡献 (点击展开)</b></summary>
    <em class="lang-en">Designed a new data-driven and transferable analysis model, the Tucker-Net based Susceptible-Infectious-Recovered-Susceptible (SIRS) model (TNBSM), for exploring dynamic correlations within crash zones using tensor decomposition and the SIRS model.</em>
    <em class="lang-zh">设计了一种新的数据驱动且可迁移的分析模型——基于Tucker-Net的SIRS模型 (TNBSM)。该模型结合张量分解与SIRS模型，用于探索事故区域内的动态相关性。</em>
    </details>

- <span style="display: inline-block; width: 22px; height: 22px; line-height: 23px; text-align: center; color: white; background-color: #4183C4; border-radius: 50%; font-weight: bold; margin-right: 10px;">4</span> **Hu, J.**, & Lee, J. (2025). Car following dynamics in mixed traffic flow of autonomous and human-driven vehicles: complex networks approach. *Physica A: Statistical Mechanics and its Applications*, 665, 130519. [https://doi.org/10.1016/j.physa.2025.130519](https://doi.org/10.1016/j.physa.2025.130519)
    <details>
    <summary>📝 <b class="lang-en">Contribution (Click to expand)</b><b class="lang-zh">主要贡献 (点击展开)</b></summary>
    <em class="lang-en">Applied a coarse-grained phase space algorithm, introduced complex network technology into vehicle-following behavior analysis, and revealed distinct characteristics and differences between autonomous vehicles (AV) and human-driven vehicles (HV).</em>
    <em class="lang-zh">应用了粗粒化相空间算法，将复杂网络技术引入车辆跟驰行为分析，揭示了自动驾驶车辆(AV)与人类驾驶车辆(HV)之间的显著特性与差异。</em>
    </details>

- <span style="display: inline-block; width: 22px; height: 22px; line-height: 23px; text-align: center; color: white; background-color: #4183C4; border-radius: 50%; font-weight: bold; margin-right: 10px;">5</span> **Hu, J.**, Bai, J., & Lee, J. Simplified and Efficient KNN-Based Method for High-Resolution Traffic Time-Space Diagram Imputation. *Manuscript under review*.
    <details>
    <summary>📝 <b class="lang-en">Contribution (Click to expand)</b><b class="lang-zh">主要贡献 (点击展开)</b></summary>
    <em class="lang-en">Proposed a modified K-Nearest Neighbors (KNN) framework for reconstructing and imputing Time-Space Diagrams (TSD) from sparse data by matching similar spatiotemporal neighborhood features defined by Queen Contiguity Spatial Rule.</em>
    <em class="lang-zh">提出了一种改进的K最近邻(KNN)框架，通过匹配由“后”邻接空间规则定义的相似时空邻域特征，从稀疏数据中重构和插补时空图(TSD)。</em>
    </details>

- <span style="display: inline-block; width: 22px; height: 22px; line-height: 23px; text-align: center; color: white; background-color: #4183C4; border-radius: 50%; font-weight: bold; margin-right: 10px;">6</span> **Hu, J.**, Gao, D., Hu, C., Zhou, H., & Lee, J. Rethinking driving style recognition: A prediction error-based driving behavior modeling. *Manuscript under review*.
    <details>
    <summary>📝 <b class="lang-en">Contribution (Click to expand)</b><b class="lang-zh">主要贡献 (点击展开)</b></summary>
    <em class="lang-en">Revisited an end-to-end approach for driving style recognition by exploring driver behavior heterogeneity through trajectory prediction model errors. Utilized spatial attention and convolutional social pooling to learn interdependencies in vehicle motion and introduced a multi-modal distribution for future trajectories based on driving style.</em>
    <em class="lang-zh">通过探索轨迹预测模型的误差来研究驾驶员行为的异质性，以此重新审视了一种端到端的驾驶风格识别方法。利用空间注意力和卷积社交池化来学习车辆运动的相互依赖性，并基于驾驶风格为未来轨迹引入了多模态分布。</em>
    </details>

- <span style="display: inline-block; width: 22px; height: 22px; line-height: 23px; text-align: center; color: white; background-color: #4183C4; border-radius: 50%; font-weight: bold; margin-right: 10px;">7</span> **Hu, J.**, Gao, D., Lee, J., & Wang, L. Vehicle dynamics analytics based on complex network techniques: a trajectory-based visibility graph approach. *Manuscript under review*.
    <details>
    <summary>📝 <b class="lang-en">Contribution (Click to expand)</b><b class="lang-zh">主要贡献 (点击展开)</b></summary>
    <em class="lang-en">Introduced an adaptive trajectory-based visibility graph (TVG) framework, a novel method for dissecting vehicle dynamics by transforming planar trajectory data into complex networks. This framework features a tunable visibility tolerance coefficient, dynamically scaled by lateral displacement, enabling the TVG to capture geometric occlusions and maneuver-specific spatial scales.</em>
    <em class="lang-zh">引入了一种自适应的基于轨迹的可视图(TVG)框架，这是一种通过将平面轨迹数据转换为复杂网络来剖析车辆动力学的新方法。该框架具有一个可调的可见性容差系数，通过横向位移进行动态缩放，使TVG能够捕捉几何遮挡和特定于机动的空间尺度。</em>
    </details>

- <span style="display: inline-block; width: 22px; height: 22px; line-height: 23px; text-align: center; color: white; background-color: #4183C4; border-radius: 50%; font-weight: bold; margin-right: 10px;">8</span> **Hu, J.**, Lee, J., & Wang, L. Re-examining the Explanatory Boundaries of Car-Following Models: From a Systematic Decomposition of Fitting Errors to the Revelation of Adaptive Feedback Mechanisms. *Manuscript under review*.
    <details>
    <summary>📝 <b class="lang-en">Contribution (Click to expand)</b><b class="lang-zh">主要贡献 (点击展开)</b></summary>
    <em class="lang-en">Posited that residuals of car-following (cf) model are a composite of structural errors and random error and utilized an Unobserved Components Model to decompose the residual series from three calibrated CF models.</em>
    <em class="lang-zh">假设跟驰模型的残差是结构误差和随机误差的复合体，并利用一个非观测成分模型来分解来自三个已标定跟驰模型的残差序列。</em>
    </details>

- <span style="display: inline-block; width: 22px; height: 22px; line-height: 23px; text-align: center; color: white; background-color: #4183C4; border-radius: 50%; font-weight: bold; margin-right: 10px;">9</span> Yang, J., Lee, J., Mao, S., & **Hu, J.** (2024). Dynamic safety estimation of airport pick-up area based on video trajectory data. *IEEE Transactions on Intelligent Transportation Systems*, 25(2), 1774–1786. [https://doi.org/10.1109/TITS.2023.3275986](https://doi.org/10.1109/TITS.2023.3275986)
    <details>
    <summary>📝 <b class="lang-en">My Role (Click to expand)</b><b class="lang-zh">我的职责 (点击展开)</b></summary>
    <em class="lang-en">Assisted in designing a modified CUSBoost algorithm for imbalanced trajectory data classification, leveraging four risk indicators and spatial distribution analysis.</em>
    <em class="lang-zh">协助设计了一种改进的CUSBoost算法，用于不平衡轨迹数据的分类，该算法利用了四种风险指标和空间分布分析。</em>
    </details>

- <span style="display: inline-block; width: 22px; height: 22px; line-height: 23px; text-align: center; color: white; background-color: #4183C4; border-radius: 50%; font-weight: bold; margin-right: 10px;">10</span> Wang, L., **Hu, J.**, Yang, Y., & Lee, J. Analysis of injury severity of single-vehicle and two-vehicle crashes with lightweight vehicles (kei cars) in Japan: A random parameters approach with heterogeneity in means. *Manuscript under review*.
    <details>
    <summary>📝 <b class="lang-en">My Role (Click to expand)</b><b class="lang-zh">我的职责 (点击展开)</b></summary>
    <em class="lang-en">Contributed to investigating K-car crash injury severity using a random parameters probit model with heterogeneity in means. Designed an out-of-sample prediction approach to clarify heterogeneity among various crash severity mechanisms.</em>
    <em class="lang-zh">参与使用带有均值异质性的随机参数probit模型，研究日本轻型汽车（K-car）的事故伤害严重程度。设计了一种样本外预测方法，以阐明不同事故严重性机制之间的异质性。</em>
    </details>

<script>
document.addEventListener('DOMContentLoaded', function() {
  const toggle = document.getElementById('language-toggle-checkbox');
  const body = document.body;

  // Function to set language and save preference
  const setLanguage = (lang) => {
    if (lang === 'zh') {
      body.classList.add('lang-zh-active');
      toggle.checked = true;
    } else {
      body.classList.remove('lang-zh-active');
      toggle.checked = false;
    }
     localStorage.setItem('preferredLanguage', lang);
  };

  // On page load, check for saved language preference
  const savedLang = localStorage.getItem('preferredLanguage');
  if (savedLang) {
    setLanguage(savedLang);
  } else {
    // Default to English if no preference is saved
    setLanguage('en');
  }

  // Add event listener for the toggle switch
  toggle.addEventListener('change', function() {
    if (this.checked) {
      setLanguage('zh');
    } else {
      setLanguage('en');
    }
  });
});
</script>
