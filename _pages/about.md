---
permalink: /
title: "About Me"
excerpt: "A brief introduction to Junjie Hu, a Master's student focused on transport engineering, data analysis, and traffic safety."
author_profile: true
lang: en
---

<style>
/* 基础样式（轻量、响应式） */
:root{--max-w:980px;--accent:#2b7bd3;--muted:#666}
body{font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,"Helvetica Neue",Arial,"Noto Sans","PingFang SC","Microsoft Yahei",sans-serif;margin:0;color:#222;line-height:1.6;background:#fff}
.container{max-width:var(--max-w);margin:0 auto;padding:28px}
.site-header{display:flex;align-items:center;justify-content:space-between;padding:12px 0;border-bottom:1px solid #eee}
.site-title{margin:0;font-size:1.15rem}
.site-title a{text-decoration:none;color:inherit}
.lang-switch{display:flex;gap:8px;align-items:center}
.lang-switch button{border:1px solid #ddd;background:#fafafa;padding:6px 10px;border-radius:6px;cursor:pointer}
.lang-switch button.active{background:var(--accent);color:#fff;border-color:var(--accent)}
.hero{margin-top:18px}
.h-list{display:flex;gap:10px;flex-wrap:wrap;margin:8px 0;list-style:none;padding:0}
.h-list li{display:inline-block}
.contact-links{margin:8px 0}
.section{margin-top:26px}
h2{margin:14px 0 8px}
.publications{list-style:none;padding-left:0;margin:0}
.publication-item{margin-bottom:18px;padding-bottom:8px;border-bottom:1px dashed #eee}
.publication-item strong{display:block}
.publication-item em.title{display:block;margin-top:6px}
.publication-item .doi{margin-left:8px;font-size:0.95rem}
.details-summary{cursor:pointer}
.contribution{margin-top:8px;font-style:normal;color:#333}
.site-footer{margin-top:40px;padding-top:18px;border-top:1px solid #eee;color:var(--muted);font-size:0.9rem}
.hide{display:none !important}

/* 当 JS 未运行时，默认显示英文（noscript 已设置同样的规则） */
.lang-en{display:inline}
.lang-zh{display:none}

/* 小屏优化 */
@media (max-width:640px){
  .container{padding:18px}
  .site-title{font-size:1rem}
}
</style>

<header class="site-header container" role="banner">
  <h1 class="site-title"><a href="{{ site.baseurl | default: '/' }}">Junjie Hu</a></h1>

  <div class="lang-switch" role="navigation" aria-label="Language switch">
    <button id="btn-en" class="active" aria-pressed="true" title="English">EN</button>
    <button id="btn-zh" aria-pressed="false" title="中文">中文</button>
  </div>
</header>

<main class="container" role="main">
  <!-- Greeting -->
  <section class="hero">
    <p class="greeting">
      <span class="lang-en">👋 Hello! I'm <strong>Junjie Hu (胡俊杰)</strong>, a second-year Master's student at the <a href="https://stte.csu.edu.cn/" target="_blank" rel="noopener">School of Transport &amp; Transportation Engineering</a>, <a href="https://www.csu.edu.cn/" target="_blank" rel="noopener">Central South University</a> (CSU). I am advised by <a href="https://www.researchgate.net/profile/Jaeyoung-Lee-26" target="_blank" rel="noopener">Prof. Jaeyoung Jay Lee</a>, a researcher recognized among the top 2% globally in road safety.</span>
      <span class="lang-zh">👋 你好！我是 <strong>胡俊杰 (Junjie Hu)</strong>，中南大学交通运输工程学院在读硕士（第二年）。我的导师是 <a href="https://www.researchgate.net/profile/Jaeyoung-Lee-26" target="_blank" rel="noopener">Jaeyoung Jay Lee 教授</a>，在道路安全领域享有国际声誉。</span>
    </p>

    <p>
      <span class="lang-en">My research passion lies at the dynamic intersection of:</span>
      <span class="lang-zh">我的研究兴趣包括：</span>
    </p>

    <ul class="h-list">
      <li> <span class="lang-en">📊 <strong>Traffic Spatio-Temporal Data Analysis</strong></span><span class="lang-zh">📊 <strong>交通时空数据分析</strong></span></li>
      <li> <span class="lang-en">🚗 <strong>Vehicular Decision-Making &amp; Control</strong></span><span class="lang-zh">🚗 <strong>车辆决策与控制</strong></span></li>
      <li> <span class="lang-en">🧠 <strong>Deep Learning Applications in Transportation Systems</strong></span><span class="lang-zh">🧠 <strong>深度学习在交通系统中的应用</strong></span></li>
      <li> <span class="lang-en">🛡️ <strong>Advanced Traffic Safety Methodologies</strong></span><span class="lang-zh">🛡️ <strong>交通安全先进方法学</strong></span></li>
    </ul>

    <div class="contact-links">
      <strong><span class="lang-en">Connect &amp; Explore:</span><span class="lang-zh">联系与更多：</span></strong>
      <ul style="list-style:none;padding-left:0;margin:6px 0;">
        <li><span class="lang-en">Email:</span><span class="lang-zh">邮箱：</span> <a href="mailto:junjie_hu@csu.edu.cn">junjie_hu@csu.edu.cn</a></li>
        <li><span class="lang-en">WeChat:</span><span class="lang-zh">微信：</span> <img src="{{ site.baseurl }}/assets/images/wechat.jpg" alt="WeChat QR" style="height:80px;vertical-align:middle;margin-left:6px"></li>
        <li><span class="lang-en">Curriculum Vitae:</span><span class="lang-zh">简历下载：</span> <a href="{{ site.baseurl }}/assets/JunjieHu_CV.pdf" target="_blank" rel="noopener">Download My CV</a></li>
      </ul>
    </div>
  </section>

  <!-- Experience -->
  <section class="section" id="experience">
    <h2><span class="lang-en">Experience</span><span class="lang-zh">经历</span> 💼</h2>

    <h3><span class="lang-en">Education</span><span class="lang-zh">教育背景</span></h3>
    <ul>
      <li>
        <strong><span class="lang-en">Master of Engineering, Transportation Engineering</span><span class="lang-zh">交通工程 硕士</span></strong><br>
        <small><span class="lang-en">School of Transportation Engineering, Central South University — Changsha, China — September 2023 - Present</span><span class="lang-zh">中南大学 交通运输工程学院 — 长沙，中国 — 2023年9月 - 至今</span></small>
      </li>
      <li style="margin-top:8px">
        <strong><span class="lang-en">Bachelor of Engineering, Logistics Engineering</span><span class="lang-zh">物流工程 本科</span></strong><br>
        <small><span class="lang-en">School of Transportation Engineering, Central South University — Changsha, China — September 2019 - June 2023</span><span class="lang-zh">中南大学 交通运输工程学院 — 长沙，中国 — 2019年9月 - 2023年6月</span></small>
      </li>
    </ul>

    <h3 style="margin-top:14px"><span class="lang-en">Professional Experience</span><span class="lang-zh">工作经历</span></h3>
    <ul>
      <li>
        <strong><span class="lang-en">Business Risk Modeling Intern</span><span class="lang-zh">业务风控建模实习生</span></strong><br>
        <small><span class="lang-en">Magic Engine Technology Co., Ltd., Shenzhen, China — July 2024 - September 2024</span><span class="lang-zh">魔引擎科技（深圳）有限公司 — 2024年7月 - 2024年9月</span></small>
        <ul>
          <li><span class="lang-en">Assisted in developing and validating credit risk models for bank partners using Python (Pandas, Scikit-learn).</span><span class="lang-zh">协助使用 Python（Pandas、Scikit-learn）开发与验证银行合作方的信用风控模型。</span></li>
          <li><span class="lang-en">Pre-processed large-scale transaction data and engineered features to improve model accuracy.</span><span class="lang-zh">对大规模交易数据进行预处理并构建特征以提升模型性能。</span></li>
          <li><span class="lang-en">Contributed to a risk analysis report that provided data-driven insights for business strategy.</span><span class="lang-zh">参与编写风险分析报告，为业务决策提供数据支持。</span></li>
        </ul>
      </li>
    </ul>

    <h3 style="margin-top:14px"><span class="lang-en">Volunteer &amp; Community Engagement</span><span class="lang-zh">志愿与社区贡献</span></h3>
    <ul>
      <li>
        <strong><span class="lang-en">Volunteer Researcher</span><span class="lang-zh">志愿研究者</span></strong><br>
        <small><span class="lang-en">Changsha Accessibility Enhancement Promotion Association — March 2025 - June 2025</span><span class="lang-zh">长沙无障碍提升促进会 — 2025年3月 - 2025年6月</span></small>
        <ul>
          <li><span class="lang-en">Investigated transportation barriers for people with disabilities through field visits and surveys.</span><span class="lang-zh">通过实地走访与问卷调查调研残障人士出行障碍。</span></li>
          <li><span class="lang-en">Co-developed a crowdsourced mapping platform for accessible facilities.</span><span class="lang-zh">参与开发众包式无障碍设施地图平台。</span></li>
          <li><span class="lang-en">Project Demo:</span><span class="lang-zh">项目演示：</span> <a href="https://junjiehu.pythonanywhere.com/" target="_blank" rel="noopener">View Live Project</a></li>
        </ul>
      </li>
    </ul>
  </section>

  <!-- Publications -->
  <section class="section" id="publications">
    <h2><span class="lang-en">Publications</span><span class="lang-zh">论文与著作</span> 📄</h2>

    <ul class="publications">
      <!-- 1 -->
      <li class="publication-item" id="pub-1">
        <strong>Hu, J., Hu, C., Yang, J., Bai, J., &amp; Lee, J. J.</strong>
        <em class="title"><span translate="no" lang="en">Do traffic flow states follow Markov properties? A high-order spatiotemporal traffic state reconstruction approach for traffic prediction and imputation.</span></em>
        <span translate="no" lang="en">Chaos, Solitons, and Fractals</span>, 2024.
        <a class="doi" href="https://doi.org/10.1016/j.chaos.2024.114965" target="_blank" rel="noopener">doi:10.1016/j.chaos.2024.114965</a>

        <details>
          <summary class="details-summary">
            <span class="lang-en">📝 <b>Contribution / Notes</b></span>
            <span class="lang-zh">📝 <b>贡献 / 说明</b></span>
          </summary>
          <div class="contribution">
            <div class="lang-en">Designed a high-order traffic state reconstruction method demonstrating traffic flow's Markov property. Leveraged Markov matrix prior knowledge in an auto-encoder framework for high-accuracy traffic imputation.</div>
            <div class="lang-zh">设计了一种高阶交通状态重构方法，验证交通流的马尔可夫性质，并基于马尔可夫矩阵先验在自编码器框架下实现高精度交通补全。</div>
          </div>
        </details>
      </li>

      <!-- 2 -->
      <li class="publication-item" id="pub-2">
        <strong>Hu, J., Bai, J., Yang, J., &amp; Lee, J.</strong>
        <em class="title"><span translate="no" lang="en">Crash Risk Prediction Using Sparse Collision Data: Causal Inference and Graph Convolutional Networks Approaches.</span></em>
        <span translate="no" lang="en">Expert Systems with Applications</span>, 2024.
        <a class="doi" href="https://doi.org/10.1016/j.eswa.2024.125315" target="_blank" rel="noopener">doi:10.1016/j.eswa.2024.125315</a>

        <details>
          <summary class="details-summary">
            <span class="lang-en">📝 <b>Contribution / Notes</b></span>
            <span class="lang-zh">📝 <b>贡献 / 说明</b></span>
          </summary>
          <div class="contribution">
            <div class="lang-en">Created a crash data enhancement strategy utilizing historic priori spatial and temporal knowledge and developed the Priori Spatial and Temporal Causal Graph Convolutional Network (PST-CGCN) for crash risk prediction.</div>
            <div class="lang-zh">提出基于历史先验时空知识的数据增强策略，并构建先验时空因果图卷积网络（PST-CGCN），结合因果推断与图卷积用于碰撞风险预测。</div>
          </div>
        </details>
      </li>

      <!-- 3 -->
      <li class="publication-item" id="pub-3">
        <strong>Hu, J., Zhang, J., Bai, J., &amp; Lee, J.</strong>
        <em class="title"><span translate="no" lang="en">Dynamic Correlation Analysis of Urban Crashes Using Tucker-Net Based SIRS Model: A Case Study in New York City.</span></em>
        <span translate="no" lang="en">Journal of the Franklin Institute</span>, 2025.
        <a class="doi" href="https://doi.org/10.1016/j.jfranklin.2025.107946" target="_blank" rel="noopener">doi:10.1016/j.jfranklin.2025.107946</a>

        <details>
          <summary class="details-summary">
            <span class="lang-en">📝 <b>Contribution / Notes</b></span>
            <span class="lang-zh">📝 <b>贡献 / 说明</b></span>
          </summary>
          <div class="contribution">
            <div class="lang-en">Designed a data-driven and transferable Tucker-Net based SIRS model (TNBSM) to explore dynamic correlations within crash zones using tensor decomposition.</div>
            <div class="lang-zh">提出数据驱动且可迁移的基于Tucker-Net的SIRS模型（TNBSM），结合张量分解用于分析事故区的动态相关性。</div>
          </div>
        </details>
      </li>

      <!-- 4 -->
      <li class="publication-item" id="pub-4">
        <strong>Hu, J., &amp; Lee, J.</strong>
        <em class="title"><span translate="no" lang="en">Car following dynamics in mixed traffic flow of autonomous and human-driven vehicles: complex networks approach.</span></em>
        <span translate="no" lang="en">Physica A: Statistical Mechanics and its Applications</span>, 2025.
        <a class="doi" href="https://doi.org/10.1016/j.physa.2025.130519" target="_blank" rel="noopener">doi:10.1016/j.physa.2025.130519</a>

        <details>
          <summary class="details-summary">
            <span class="lang-en">📝 <b>Contribution / Notes</b></span>
            <span class="lang-zh">📝 <b>贡献 / 说明</b></span>
          </summary>
          <div class="contribution">
            <div class="lang-en">Applied a coarse-grained phase space algorithm and introduced complex network techniques into vehicle-following behavior analysis, revealing differences between autonomous and human-driven vehicles.</div>
            <div class="lang-zh">应用粗粒度相空间算法，将复杂网络技术引入跟车行为分析，揭示自动驾驶车辆与人工驾驶车辆在跟车动力学上的差异特征。</div>
          </div>
        </details>
      </li>

      <!-- 5 -->
      <li class="publication-item" id="pub-5">
        <strong>Hu, J., Bai, J., &amp; Lee, J.</strong>
        <em class="title"><span translate="no" lang="en">Simplified and Efficient KNN-Based Method for High-Resolution Traffic Time-Space Diagram Imputation.</span></em>
        <span translate="no" lang="en">Manuscript under review</span>.
        <details>
          <summary class="details-summary">
            <span class="lang-en">📝 <b>Contribution / Notes</b></span>
            <span class="lang-zh">📝 <b>贡献 / 说明</b></span>
          </summary>
          <div class="contribution">
            <div class="lang-en">Proposed a modified K-Nearest Neighbors framework to reconstruct and impute Time-Space Diagrams from sparse data by matching similar spatiotemporal neighborhood features defined by Queen Contiguity spatial rule.</div>
            <div class="lang-zh">提出一种改进的K近邻（KNN）框架，通过匹配由Queen领接规则定义的相似时空邻域特征，实现从稀疏数据重建并插补高分辨率时空图。</div>
          </div>
        </details>
      </li>

      <!-- 6 -->
      <li class="publication-item" id="pub-6">
        <strong>Hu, J., Gao, D., Hu, C., Zhou, H., &amp; Lee, J.</strong>
        <em class="title"><span translate="no" lang="en">Rethinking driving style recognition: A prediction error-based driving behavior modeling.</span></em>
        <span translate="no" lang="en">Manuscript under review</span>.
        <details>
          <summary class="details-summary">
            <span class="lang-en">📝 <b>Contribution / Notes</b></span>
            <span class="lang-zh">📝 <b>贡献 / 说明</b></span>
          </summary>
          <div class="contribution">
            <div class="lang-en">Revisited an end-to-end approach for driving style recognition by exploring driver behavior heterogeneity through trajectory prediction model errors. Utilized spatial attention and convolutional social pooling and introduced a multi-modal distribution for future trajectories.</div>
            <div class="lang-zh">重新审视端到端的驾驶风格识别方法，通过轨迹预测模型误差刻画驾驶行为异质性。采用空间注意力与卷积社交池化学习车辆运动间的相互依赖，并引入多模态分布用于未来轨迹建模。</div>
          </div>
        </details>
      </li>

      <!-- 7 -->
      <li class="publication-item" id="pub-7">
        <strong>Hu, J., Gao, D., Lee, J., &amp; Wang, L.</strong>
        <em class="title"><span translate="no" lang="en">Vehicle dynamics analytics based on complex network techniques: a trajectory-based visibility graph approach.</span></em>
        <span translate="no" lang="en">Manuscript under review</span>.
        <details>
          <summary class="details-summary">
            <span class="lang-en">📝 <b>Contribution / Notes</b></span>
            <span class="lang-zh">📝 <b>贡献 / 说明</b></span>
          </summary>
          <div class="contribution">
            <div class="lang-en">Introduced an adaptive trajectory-based visibility graph (TVG) framework, transforming planar trajectory data into complex networks with a tunable visibility tolerance coefficient.</div>
            <div class="lang-zh">提出自适应的基于轨迹的可视性图（TVG）框架，将平面轨迹数据转换为复杂网络，并通过可调的可视性容差系数捕捉几何遮挡和机动相关的空间尺度。</div>
          </div>
        </details>
      </li>

      <!-- 8 -->
      <li class="publication-item" id="pub-8">
        <strong>Hu, J., Lee, J., &amp; Wang, L.</strong>
        <em class="title"><span translate="no" lang="en">Re-examining the Explanatory Boundaries of Car-Following Models: From a Systematic Decomposition of Fitting Errors to the Revelation of Adaptive Feedback Mechanisms.</span></em>
        <span translate="no" lang="en">Manuscript under review</span>.
        <details>
          <summary class="details-summary">
            <span class="lang-en">📝 <b>Contribution / Notes</b></span>
            <span class="lang-zh">📝 <b>贡献 / 说明</b></span>
          </summary>
          <div class="contribution">
            <div class="lang-en">Posited that car-following model residuals are a composite of structural and random errors, and used an Unobserved Components Model to decompose residual series from three calibrated car-following models.</div>
            <div class="lang-zh">提出跟车模型残差由结构误差与随机误差组成，并利用未观测分量模型对三个已校准跟车模型的残差序列进行分解。</div>
          </div>
        </details>
      </li>

      <!-- 9 -->
      <li class="publication-item" id="pub-9">
        <strong>Yang, J., Lee, J., Mao, S., &amp; Hu, J.</strong>
        <em class="title"><span translate="no" lang="en">Dynamic safety estimation of airport pick-up area based on video trajectory data.</span></em>
        <span translate="no" lang="en">IEEE Transactions on Intelligent Transportation Systems</span>, 2024.
        <a class="doi" href="https://doi.org/10.1109/TITS.2023.3275986" target="_blank" rel="noopener">doi:10.1109/TITS.2023.3275986</a>

        <details>
          <summary class="details-summary">
            <span class="lang-en">📝 <b>My Role / Notes</b></span>
            <span class="lang-zh">📝 <b>我的角色 / 说明</b></span>
          </summary>
          <div class="contribution">
            <div class="lang-en">Assisted in designing a modified CUSBoost algorithm for imbalanced trajectory data classification, leveraging four risk indicators and spatial distribution analysis.</div>
            <div class="lang-zh">参与设计改进的CUSBoost算法用于不平衡轨迹数据分类，基于四项风险指标与空间分布分析。</div>
          </div>
        </details>
      </li>

      <!-- 10 -->
      <li class="publication-item" id="pub-10">
        <strong>Wang, L., <strong>Hu, J.</strong>, Lee, J., Yang, Y., &amp; Mao, S.</strong>
        <em class="title"><span translate="no" lang="en">Analysis of injury severity of single-vehicle and two-vehicle crashes with lightweight vehicles (kei cars) in Japan: A random parameters approach with heterogeneity in means.</span></em>
        <span translate="no" lang="en">Manuscript under review</span>.

        <details>
          <summary class="details-summary">
            <span class="lang-en">📝 <b>My Role / Notes</b></span>
            <span class="lang-zh">📝 <b>我的角色 / 说明</b></span>
          </summary>
          <div class="contribution">
            <div class="lang-en">Contributed to investigating K-car crash injury severity using a random parameters probit model with heterogeneity in means and designed an out-of-sample prediction approach to clarify heterogeneity among severity mechanisms.</div>
            <div class="lang-zh">参与研究日本轻型车（Kei car）单车与二车碰撞的伤害严重度，采用随机参数Probit模型并考虑均值异质性，设计样本外预测方法以阐明不同严重度机制的异质性。</div>
          </div>
        </details>
      </li>

      <!-- 11 -->
      <li class="publication-item" id="pub-11">
        <strong>Wang, L., Lee, J., <strong>Hu, J.</strong>, &amp; Mao, S.</strong>
        <em class="title"><span translate="no" lang="en">Contributing Factors to the Severity of Crash Injury and Vehicle Damage Involving Japanese Lightweight K-cars: Considering Unobserved Heterogeneity.</span></em>
        <span translate="no" lang="en">Manuscript under review</span>.

        <details>
          <summary class="details-summary">
            <span class="lang-en">📝 <b>My Role / Notes</b></span>
            <span class="lang-zh">📝 <b>我的角色 / 说明</b></span>
          </summary>
          <div class="contribution">
            <div class="lang-en">Contributed to investigating factors influencing crash injury severity and vehicle damage for Japanese lightweight K-cars using random parameter bivariate probit models with heterogeneity in means.</div>
            <div class="lang-zh">参与研究影响日本轻型K车事故伤害严重度与车辆损伤的因素，采用随机参数双变量Probit模型并考虑均值异质性。</div>
          </div>
        </details>
      </li>
    </ul>

  </section>

  <footer class="site-footer">
    <p><span class="lang-en">© {{ site.time | date: "%Y" }} Junjie Hu. All rights reserved.</span><span class="lang-zh">© {{ site.time | date: "%Y" }} 胡俊杰。保留所有权利。</span></p>
  </footer>
</main>

<noscript>
  <style>
    /* 若用户禁用 JS，默认显示英文（尽量保证可读） */
    .lang-en{display:inline}
    .lang-zh{display:none}
    #btn-en{display:none}
    #btn-zh{display:none}
  </style>
  <div class="container"><small>JavaScript is disabled — page shown in English by default. 若需中文，请启用 JavaScript。</small></div>
</noscript>

<script>
/*
  简单客户端语言切换（单页），不会改变论文标题与期刊（这些使用 translate="no" lang="en"）
  使用方法：点击 EN / 中文 按钮切换，首选项保存在 localStorage。
*/
(function () {
  const BTN_EN = document.getElementById('btn-en');
  const BTN_ZH = document.getElementById('btn-zh');

  function setLang(lang) {
    const enEls = document.querySelectorAll('.lang-en');
    const zhEls = document.querySelectorAll('.lang-zh');

    if (lang === 'zh') {
      enEls.forEach(el => el.classList.add('hide'));
      zhEls.forEach(el => el.classList.remove('hide'));
      document.documentElement.lang = 'zh-Hans';
      // 控制按钮样式
      if (BTN_EN) BTN_EN.classList.remove('active'), BTN_EN.setAttribute('aria-pressed','false');
      if (BTN_ZH) BTN_ZH.classList.add('active'), BTN_ZH.setAttribute('aria-pressed','true');
    } else {
      zhEls.forEach(el => el.classList.add('hide'));
      enEls.forEach(el => el.classList.remove('hide'));
      document.documentElement.lang = 'en';
      if (BTN_EN) BTN_EN.classList.add('active'), BTN_EN.setAttribute('aria-pressed','true');
      if (BTN_ZH) BTN_ZH.classList.remove('active'), BTN_ZH.setAttribute('aria-pressed','false');
    }

    try { localStorage.setItem('site_lang', lang); } catch(e) { /* ignore */ }
  }

  // 初始化
  document.addEventListener('DOMContentLoaded', function () {
    const saved = (function(){
      try { return localStorage.getItem('site_lang'); } catch(e){ return null; }
    })() || 'en';
    setLang(saved);

    if (BTN_EN) BTN_EN.addEventListener('click', function(){ setLang('en'); });
    if (BTN_ZH) BTN_ZH.addEventListener('click', function(){ setLang('zh'); });
  });
})();
</script>
