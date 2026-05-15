UK 电商 A/B Test 数据分析项目
UK E-commerce A/B Test Analysis Project
项目简介 | Project Overview

本项目基于英国某电商平台的 A/B Test 实验数据，使用 SQL、Python 与 Power BI 对网站改版效果进行完整的数据分析。

This project analyzes A/B Test experiment data from a UK-based e-commerce platform using SQL, Python, and Power BI to evaluate website redesign performance.

项目主要目标：

Main objectives of the project:

分析新版网站是否提升转化率
Analyze whether the new website version improves conversion rate
对用户行为进行统计分析
Perform statistical analysis on user behavior
评估实验结果是否具有统计显著性
Evaluate whether experiment results are statistically significant
输出商业洞察与优化建议
Generate business insights and optimization recommendations
项目技术栈 | Tools & Technologies
Python（Pandas、NumPy、SciPy）
SQL（SQLite）
Power BI
Jupyter Notebook
数据集说明 | Dataset Information

数据集包含以下用户行为信息：

The dataset includes the following user behavior information:

用户实验组别（A/B Group）
地区（Location）
设备类型（Device Type）
页面浏览量（Page Views）
网站停留时间（Time Spent）
是否转化（Conversion）
项目流程 | Project Workflow
1. 数据清洗与预处理 | Data Cleaning & Preprocessing

使用 Python 对数据进行清洗与处理，包括：

Used Python for data preprocessing, including:

缺失值检查
Missing value checking
数据类型转换
Data type formatting
转化字段处理
Conversion encoding
SQL 数据表创建
SQL table creation
2. SQL 数据分析 | SQL Data Analysis

使用 SQL 完成核心业务指标分析，包括：

Used SQL to analyze key business metrics, including:

转化率分析
Conversion rate analysis
地区转化率分析
Regional conversion analysis
设备转化率分析
Device-level conversion analysis
平均停留时间分析
Average time spent analysis
平均浏览量分析
Average page views analysis
Uplift 提升率分析
Uplift percentage analysis
3. 统计检验 | Statistical Testing
独立样本 T 检验 | Independent Sample T-Test

用于检验 A/B 两组用户行为是否存在显著差异。

Used to determine whether there are significant differences in user behavior between Group A and Group B.

检验结果 | Results
指标 Metric	统计量 Statistic	P值 P-value	结论 Conclusion
页面浏览量 Page Views	0.779	0.436	无显著差异 No significant difference
停留时间 Time Spent	-0.470	0.639	无显著差异 No significant difference
卡方检验 | Chi-Square Test

用于检验转化率差异是否具有统计显著性。

Used to test whether the conversion rate difference is statistically significant.

指标 Metric	卡方统计量 Chi-square	P值 P-value	结论 Conclusion
转化率 Conversion	106.228	0.000	存在显著提升 Significant improvement
核心分析结果 | Key Findings
转化率显著提升 | Significant Conversion Improvement

实验组（Group B）的转化率明显高于对照组（Group A），且统计检验结果显示该提升具有显著性。

Group B achieved a significantly higher conversion rate compared to Group A, and the improvement was statistically significant.

用户浏览行为变化较小 | Minimal Change in User Browsing Behavior

页面浏览量与停留时间未出现明显变化，说明新版网站主要优化了转化效率，而非增加用户浏览时长。

Page views and time spent showed minimal differences, indicating that the redesign improved conversion efficiency rather than increasing browsing behavior.

地区与设备存在差异 | Regional and Device-Level Differences

不同地区与设备的转化表现存在明显差异，为后续精细化运营提供方向。

Different regions and device types showed varying conversion performance, providing opportunities for further optimization.

Power BI 可视化 | Power BI Dashboard

项目使用 Power BI 构建商业化数据仪表盘，包括：

Built interactive Power BI dashboards including:

KPI 指标卡片
KPI cards
转化率分析图
Conversion analysis charts
Uplift 提升率分析
Uplift analysis
地区分析
Regional performance analysis
设备分析
Device performance analysis
用户行为分析
User behavior analysis
商业建议 | Business Recommendations

基于分析结果，建议：

Based on the analysis, the following recommendations are proposed:

推广新版网站设计
Deploy the new website version
继续优化移动端体验
Continue optimizing mobile experience
对高表现地区进行重点营销
Focus marketing efforts on high-performing regions
进一步开展用户分层实验
Conduct deeper user segmentation experiments
项目能力展示 | Skills Demonstrated
A/B Testing
SQL 数据分析 | SQL Analytics
Python 数据处理 | Python Data Processing
统计检验 | Statistical Testing
数据可视化 | Data Visualization
Power BI Dashboard
商业分析 | Business Analytics
后续优化方向 | Future Improvements


作者 | 麦恒铟 Author

数据分析作品集项目

Data Analytics Portfolio Project

聚焦商业数据分析、实验分析与数据可视化。

Focused on business analytics, experimentation analysis, and dashboard visualization.
