---
layout: single
permalink: /about/
title: "About Me"
excerpt: "A bilingual about page with pure CSS/HTML language switch."
author_profile: true
---

<style>
/* 默认隐藏所有语言块 */
.lang { display: none; }

/* 默认显示中文 */
#zh:target ~ .content .lang-zh,
body:not(:target) .lang-zh {
  display: block;
}

/* 点击 #en 时显示英文 */
#en:target ~ .content .lang-en {
  display: block;
}

/* 切换按钮样式 */
.lang-switch {
  text-align: right;
  margin-bottom: 1rem;
}
.lang-switch a {
  margin-left: 0.5rem;
  text-decoration: none;
  color: #555;
  font-weight: normal;
}
.lang-switch a.active {
  color: #007acc;
  font-weight: bold;
}
</style>

<!-- 语言切换按钮 -->
<div class="lang-switch">
  <a href="#zh" id="btn-zh">中文</a> | 
  <a href="#en" id="btn-en">English</a>
</div>

<!-- 占位符，用于触发 :target -->
<span id="zh"></span>
<span id="en"></span>

<div class="content">
  <!-- ================= 中文 ================= -->
  <div class="lang lang-zh">

👋 你好！我是 **胡俊杰 (Junjie Hu)**，中南大学运输工程学院硕士二年级研究生，导师是 [Jaeyoung Jay Lee 教授](https://www.researchgate.net/profile/Jaeyoung-Lee-26)。  

研究兴趣：  
* 📊 **交通时空数据分析**  
* 🚗 **车辆决策与控制**  
* 🧠 **深度学习在交通系统中的应用**  
* 🛡️ **先进的交通安全方法**  

我热衷于利用大规模交通数据揭示潜在规律，推动交通系统更安全、更智能、更可持续。  

🔗 **联系方式**  
* **邮箱：** [junjie_hu@csu.edu.cn](mailto:junjie_hu@csu.edu.cn)  
* **微信：** [扫码查看二维码](/images/wechat.jpg)  
* **简历：** [下载我的 CV](/assets/JunjieHu_CV.pdf)  

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

## 学术论文 📄 *(论文题目与期刊保持英文不翻译)*  

1. **Hu, J.**, Hu, C., Yang, J., Bai, J., & Lee, J. J. (2024). *Do traffic flow states follow Markov properties?* Chaos, Solitons, and Fractals, 183, 114965.  
📝 贡献  

2. **Hu, J.**, Bai, J., Yang, J., & Lee, J. (2024). *Crash Risk Prediction Using Sparse Collision Data.* Expert Systems with Applications, 248, 125315.  
📝 贡献  

3. **Hu, J.**, Zhang, J., Bai, J., & Lee, J. (2025). *Dynamic Correlation Analysis of Urban Crashes Using Tucker-Net Based SIRS Model.* Journal of the Franklin Institute.  
📝 贡献  

4. **Hu, J.**, & Lee, J. (2025). *Car following dynamics in mixed traffic flow...* Physica A, 665, 130519.  
📝 贡献  

5. **Hu, J.**, Bai, J., & Lee, J. *Simplified and Efficient KNN-Based Method...* Manuscript under review.  
📝 贡献  

6. **Hu, J.**, Gao, D., Hu, C., Zhou, H., & Lee, J. *Rethinking driving style recognition...* Manuscript under review.  
📝 贡献  

7. **Hu, J.**, Gao, D., Lee, J., & Wang, L. *Vehicle dynamics analytics based on complex network techniques...* Manuscript under review.  
📝 贡献  

8. **Hu, J.**, Lee, J., & Wang, L. *Re-examining the Explanatory Boundaries of Car-Following Models...* Manuscript under review.  
📝 贡献  

9. Yang, J., Lee, J., Mao, S., & **Hu, J.** (2024). *Dynamic safety estimation of airport pick-up area...* IEEE T-ITS, 25(2), 1774–1786.  
📝 我的角色  

10. Wang, L., **Hu, J.**, Lee, J., Yang, Y., & Mao, S. *Analysis of injury severity of crashes with kei cars in Japan...* Manuscript under review.  
📝 我的角色  

11. Wang, L., Lee, J., **Hu, J.**, Yang, Y., & Mao, S. *Contributing Factors to the Severity of Crash Injury and Vehicle Damage...* Manuscript under review.  
📝 我的角色  

  </div>

  <!-- ================= English ================= -->
  <div class="lang lang-en">

👋 Hello! I'm **Junjie Hu (胡俊杰)**, a second-year Master's student at the [School of Transport & Transportation Engineering](https://stte.csu.edu.cn/), [Central South University](https://www.csu.edu.cn/), advised by [Prof. Jaeyoung Jay Lee](https://www.researchgate.net/profile/Jaeyoung-Lee-26).  

My research interests include:  
* 📊 **Traffic Spatio-Temporal Data Analysis**  
* 🚗 **Vehicular Decision-Making & Control**  
* 🧠 **Deep Learning Applications in Transportation Systems**  
* 🛡️ **Advanced Traffic Safety Methodologies**  

I am passionate about leveraging large-scale traffic data to uncover hidden patterns and to promote safer, smarter, and more sustainable transportation systems.  

🔗 **Connect with Me**  
* **Email:** [junjie_hu@csu.edu.cn](mailto:junjie_hu@csu.edu.cn)  
* **WeChat:** [Scan QR Code](/images/wechat.jpg)  
* **Curriculum Vitae:** [Download My CV](/assets/JunjieHu_CV.pdf)  

---

## Education 🎓  
* **M.Sc. in Transportation Engineering** — Central South University, Changsha, China (Sep 2023 - Present)  
* **B.Eng. in Logistics Engineering** — Central South University, Changsha, China (Sep 2019 - Jun 2023)  

---

## Internship Experience 💼  
* **Risk Modeling Intern** — Magic Engine Technology, Shenzhen, China (Jul 2024 - Sep 2024)  
  - Developed and validated credit risk models in Python.  
  - Conducted large-scale data preprocessing and feature engineering.  
  - Assisted in drafting risk analysis reports to support strategic decision-making.  

---

## Volunteering 🌱  
* **Volunteer Researcher** — Changsha Accessibility Promotion Association, Changsha, China (Mar 2025 - Jun 2025)  
  - Investigated mobility barriers for people with disabilities.  
  - Co-developed a crowdsourced accessible facilities mapping platform.  
  - Project Demo: [View Online](https://junjiehu.pythonanywhere.com/)  

---

## Publications 📄  

1. **Hu, J.**, Hu, C., Yang, J., Bai, J., & Lee, J. J. (2024). *Do traffic flow states follow Markov properties?* Chaos, Solitons, and Fractals, 183, 114965.  
📝 Contribution  

2. **Hu, J.**, Bai, J., Yang, J., & Lee, J. (2024). *Crash Risk Prediction Using Sparse Collision Data.* Expert Systems with Applications, 248, 125315.  
📝 Contribution  

3. **Hu, J.**, Zhang, J., Bai, J., & Lee, J. (2025). *Dynamic Correlation Analysis of Urban Crashes Using Tucker-Net Based SIRS Model.* Journal of the Franklin Institute.  
📝 Contribution  

4. **Hu, J.**, & Lee, J. (2025). *Car following dynamics in mixed traffic flow...* Physica A, 665, 130519.  
📝 Contribution  

5. **Hu, J.**, Bai, J., & Lee, J. *Simplified and Efficient KNN-Based Method...* Manuscript under review.  
📝 Contribution  

6. **Hu, J.**, Gao, D., Hu, C., Zhou, H., & Lee, J. *Rethinking driving style recognition...* Manuscript under review.  
📝 Contribution  

7. **Hu, J.**, Gao, D., Lee, J., & Wang, L. *Vehicle dynamics analytics based on complex network techniques...* Manuscript under review.  
📝 Contribution  

8. **Hu, J.**, Lee, J., & Wang, L. *Re-examining the Explanatory Boundaries of Car-Following Models...* Manuscript under review.  
📝 Contribution  

9. Yang, J., Lee, J., Mao, S., & **Hu, J.** (2024). *Dynamic safety estimation of airport pick-up area...* IEEE T-ITS, 25(2), 1774–1786.  
📝 My Role  

10. Wang, L., **Hu, J.**, Lee, J., Yang, Y., & Mao, S. *Analysis of injury severity of crashes with kei cars in Japan...* Manuscript under review.  
📝 My Role  

11. Wang, L., Lee, J., **Hu, J.**, Yang, Y., & Mao, S. *Contributing Factors to the Severity of Crash Injury and Vehicle Damage...* Manuscript under review.  
📝 My Role  

  </div>
</div>

<script>
  // 按钮高亮
  function highlightLang() {
    const hash = window.location.hash || "#zh";
    document.getElementById("btn-zh").classList.remove("active");
    document.getElementById("btn-en").classList.remove("active");
    if (hash === "#en") {
      document.getElementById("btn-en").classList.add("active");
    } else {
      document.getElementById("btn-zh").classList.add("active");
    }
  }
  window.addEventListener("hashchange", highlightLang);
  window.addEventListener("load", highlightLang);
</script>
