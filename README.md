<div style="display: flex;">
  <div style="flex: 60%;">
    <h1>个人情况介绍</h1>
    <h2>基本信息</h2>
    <table>
      <tr>
        <td width="60%" valign="top">
          <ul>
            <li><strong>姓名</strong>：黄晓静</li>
            <li><strong>学校</strong>：东北大学（秦皇岛）</li>
            <li><strong>专业</strong>：计算机科学与技术</li>
            <li><strong>年级</strong>：2022级</li>
            <li><strong>电话</strong>：19565385900</li>
            <li><strong>邮箱</strong>：19565385900@163.com</li>
          </ul>
        </td>
        <td width="40%" valign="top" align="center">
          <img src="p1.jpg" width="180" style="border-radius: 8px;">
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
      <li><strong>英语水平</strong>：
        <ul>
          <li>CET4：613</li>
          <li>CET6：522</li>
        </ul>
      </li>
    </ul>

    <div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 15px; align-items: center;">
      <img src="image/rank.png" alt="架构图" style="width: 30%; object-fit: contain;">
      <img src="image/cet4.png" alt="流程图" style="width: 30%; object-fit: contain;">
      <img src="image/cet6.png" alt="数据图" style="width: 30%; object-fit: contain;">
    </div>

    <hr>

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
    <!-- 图片部分省略：会继续补充在 canvas 编辑器中 -->
  </div>
</div>
