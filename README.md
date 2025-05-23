<!DOCTYPE html>
<html lang="zh">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>黄晓静 - 个人简历</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      margin: 20px;
      background-color: #fdfdfd;
      color: #333;
    }
    h1, h2, h3 {
      color: #2c3e50;
    }
    table {
      width: 100%;
      border-collapse: collapse;
      margin-bottom: 20px;
    }
    td, th {
      padding: 10px;
      vertical-align: top;
    }
    img {
      max-width: 100%;
      height: auto;
      border-radius: 8px;
    }
    .grid {
      display: grid;
      gap: 15px;
      align-items: center;
    }
    .grid-2 {
      grid-template-columns: repeat(2, 1fr);
    }
    .grid-3 {
      grid-template-columns: repeat(3, 1fr);
    }
    .center {
      display: flex;
      justify-content: center;
    }
    hr {
      border: none;
      border-top: 1px solid #ccc;
      margin: 40px 0;
    }
  </style>
</head>
<body>

<h1>个人情况介绍</h1>
<h2>基本信息</h2>
<table>
<tr>
<td width="60%">
<ul>
  <li><strong>姓名</strong>：黄晓静</li>
  <li><strong>学校</strong>：东北大学（秦皇岛）</li>
  <li><strong>专业</strong>：计算机科学与技术</li>
  <li><strong>年级</strong>：2022级</li>
  <li><strong>电话</strong>：19565385900</li>
  <li><strong>邮箱</strong>：19565385900@163.com</li>
</ul>
</td>
<td width="40%" class="center">
  <img src="p1.jpg" width="180" />
</td>
</tr>
</table>

<h2>📊 学业成绩</h2>
<h3>GPA与排名</h3>
<ul>
  <li><strong>GPA</strong>：4.31/5.0（专业前1.5%）</li>
  <li><strong>核心课程成绩</strong>：
    <ul>
      <li>高等数学 100/100</li>
      <li>离散数学 100/100</li>
      <li>线性代数 99/100</li>
      <li>C++程序设计 99/100</li>
      <li>数据结构与算法：98/100</li>
      <li>数据库原理：98/100</li>
      <li>操作系统：95/100</li>
    </ul>
  </li>
  <li><strong>英语水平</strong>：CET4 613，CET6 522</li>
</ul>
<div class="grid grid-3">
  <img src="image/rank.png" alt="GPA排名" />
  <img src="image/cet4.png" alt="CET4" />
  <img src="image/cet6.png" alt="CET6" />
</div>

<hr />

<h2>🔬 科创经历</h2>

<h3>项目1：多模态乳腺影像融合分析：乳腺癌早期筛查与智能诊断研究</h3>
<ul>
  <li><strong>时间</strong>：2024.12 - 至今</li>
  <li><strong>背景</strong>：针对单一类型医学影像难以辅助疾病诊断的难题，多模态医学图像融合技术可以将多幅图像中的病理信息结合到一幅图像中，利用了不同模态图像的优势，为病情的诊断提供了更加合理可靠的依据。</li>
  <li><strong>职责</strong>：图像配准工作</li>
  <li><strong>任务</strong>：
    <ul>
      <li>在 UNet 网络架构的基础上，通过对 fixed-image 和 moving-image 进行编码和解码生成一个形变场；</li>
      <li>通过空间变换网络（STN）根据形变场对待配准图像进行每个像素的重塑（利用双线性插值）得到 moved-image；</li>
      <li>最终，计算 fixed-image 与 moved-image 的 Dice Score 值为 0.823，表明模型较好地实现了图像配准。</li>
    </ul>
  </li>
</ul>

<div style="
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 15px;
  align-items: center;
  justify-content: center;
  width: fit-content;
  margin: 0 auto;
">
  <div style="display: flex; justify-content: center;">
    <img src="image/p1.png" alt="架构图" style="width: 80%; object-fit: contain; margin: 0 auto;">
  </div>
  <div style="display: flex; justify-content: center;">
    <img src="image/p2.png" alt="架构图" style="width: 80%; object-fit: contain; margin: 0 auto;">
  </div>
</div>

<h3>项目2：《Olympic Medal Table Prediction Model Based on LSTM-Transformer with Transfer Learning》</h3>
<ul>
  <li><strong>时间</strong>：2024.12 - 2024.02</li>
  <li><strong>背景</strong>：为实现奥运会奖牌的预测，为体育资源的规划提供科学依据，本论文开发了一个基于 LSTM-Transformer 模型的奥林匹克奖牌预测系统，并利用迁移学习技术针对不同国家定制预测模型。</li>
  <li><strong>任务</strong>：
    <ul>
      <li>通过构建 LSTM 层对奥运奖牌数据进行初步处理，捕捉局部时间依赖性；</li>
      <li>Transformer 层被应用于 LSTM 层的输出，利用自注意力机制来捕捉奥运奖牌数据中的全局依赖性；</li>
      <li>运用 SHAP 分析方法量化各个运动项目对奖牌分布的贡献，为国家体育委员会提供了战略规划和资源分配的科学依据。</li>
    </ul>
  </li>
</ul>

<div style="
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 15px;
  align-items: center;
  justify-content: center;
  width: fit-content;
  margin: 0 auto;
">
  <div style="display: flex; justify-content: center;">
    <img src="image/p3.png" alt="架构图" style="width: 100%; object-fit: contain; margin: 0 auto;">
  </div>
  <div style="display: flex; justify-content: center;">
    <img src="image/p4.png" alt="架构图" style="width: 100%; object-fit: contain; margin: 0 auto;">
  </div>
</div>

<h3>项目4：基于最大期望利润模型的生产决策优化</h3>
<ul>
  <li><strong>时间</strong>：2024.09 - 2024.11</li>
  <li><strong>背景</strong>：某电子产品生产企业在生产过程中面临零配件采购、装配及成品质量控制等多阶段决策问题。企业需要科学制定采购及生产策略，以实现生产利益最大化。</li>
  <li><strong>任务</strong>：
    <ul>
      <li>构建最大期望利润模型，设定决策目标为卖出单个成品获得的最大期望利润。建立目标函数，综合考虑零配件成本、检测成本、装配成本、次品率、调换损失、拆解费用等因素，找到最优决策方案，预测单个产品的最大期望利润为19.4元；</li>
    </ul>
  </li>
</ul>

<div style="
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 15px;
  align-items: center;
  justify-content: center;
  width: fit-content;
  margin: 0 auto;
">
  <div style="display: flex; justify-content: center;">
    <img src="image/a1.png" alt="架构图" style="width: 100%; object-fit: contain; margin: 0 auto;">
  </div>
</div>

<ul>
  <li><strong>任务（续）</strong>：
    <ul>
      <li>构建多工序生产决策模型，在最大期望利润模型的基础上，进一步考虑多工序生产的特点。将半成品和成品纳入决策分析中，分析其不合格概率，预测单个产品的最大期望利润为20.3元；</li>
    </ul>
  </li>
</ul>

<div style="
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 15px;
  align-items: center;
  justify-content: center;
  width: fit-content;
  margin: 0 auto;
">
  <div style="display: flex; justify-content: center;">
    <img src="image/a2.png" alt="架构图" style="width: 100%; object-fit: contain; margin: 0 auto;">
  </div>
</div>

<h3>项目5：中国宠物食品产业可持续发展战略研究与预测分析</h3>
<ul>
  <li><strong>时间</strong>：2025.01 - 2025.02</li>
  <li><strong>背景</strong>：随着社会的发展和人们生活水平的提高，宠物食品市场迎来了巨大的发展机遇。然而，面对全球市场竞争加剧以及国际贸易政策变化等挑战，如何制定科学合理的可持续发展战略，成为中国宠物食品产业亟待解决的问题。</li>
  <li><strong>任务</strong>：
    <ul>
      <li>对于市场数据使用 3-sigma 测试识别异常值，使用 Kolmogorov-Smirnov 检验验证数据变量 P 值均大于 0.05，数据服从正态分布；</li>
      <li>基于 Spearman 秩相关性检验建立岭回归模型（参数 k=0.188），分析各因素对宠物行业规模的影响，建立灰色预测模型，预测未来三年中国宠物市场的规模，预测值分别为 2674.97 亿元、2884.32 亿元和 3104.42 亿元；</li>
      <li>建立关税影响模型，通过比较预测值与实际值，得出结论高关税会降低中国宠物食品的出口量和在外国市场的份额，提出可持续发展战略。</li>
    </ul>
  </li>
</ul>

<h2>🏆 个人荣誉</h2>
<table border="1">
  <tr><th>奖项名称</th><th>颁发单位</th><th>时间</th></tr>
  <tr><td>校综合二等奖学金*3</td><td>东北大学秦皇岛分校</td><td>2023.10 2024.05 2024.11</td></tr>
  <tr><td>校综合三等奖学金</td><td>东北大学秦皇岛分校</td><td>2023.05</td></tr>
  <tr><td>优秀学生干部</td><td>东北大学秦皇岛分校</td><td>2023.11</td></tr>
  <tr><td>优秀团干部标兵</td><td>东北大学秦皇岛分校</td><td>2023.11</td></tr>
  <tr><td>三好学生</td><td>东北大学秦皇岛分校</td><td>2024.11</td></tr>
  <tr><td>优秀志愿者</td><td>共青团东北大学秦皇岛分校委员会</td><td>2024.04</td></tr>
</table>
<div class="grid grid-3">
  <img src="image/二等奖学金2.png" alt="二等奖学金2" />
  <img src="image/二等奖学金3.png" alt="二等奖学金3" />
  <img src="image/奖学金证书.png" alt="奖学金证书" />
  <img src="image/优秀学生干部.png" alt="优秀学生干部" />
  <img src="image/特发此证.png" alt="特发此证" />
  <img src="image/优秀志愿者.png" alt="优秀志愿者" />
</div>

<hr />

<h2>🏆 竞赛荣誉</h2>
<table border="1">
  <tr><th>奖项名称</th><th>颁发单位</th><th>时间</th></tr>
  <tr><td>全国大学生数学建模竞赛省级一等奖</td><td>中国工业与应用数学学会</td><td>2025.09</td></tr>
  <tr><td>国际大学生数学竞赛H奖</td><td>美国数学及其应用联合会</td><td>2024.05</td></tr>
  <tr><td>亚太地区大学生数学建模竞赛国家级三等奖</td><td>亚太地区大学生数学建模竞赛组委会</td><td>2025.01</td></tr>
  <tr><td>全国大学生数学竞赛省级三等奖</td><td>东北大学秦皇岛分校</td><td>2023.11</td></tr>
</table>
<div class="grid grid-3">
  <img src="image/全国大学生数学建模竞赛.png" alt="全国大学生数学建模竞赛" />
  <img src="image/亚太地区.png" alt="亚太地区" />
  <img src="image/数学竞赛.png" alt="数学竞赛" />
</div>

<hr />

<h2>📌 其他技能</h2>
<ul>
  <li><strong>编程语言</strong>：Python（熟练）、C++、Java</li>
  <li><strong>工具框架</strong>：PyTorch、TensorFlow、MySQL</li>
  <li><strong>硬件设计能力</strong>：Vivado</li>
</ul>

</body>
</html>
