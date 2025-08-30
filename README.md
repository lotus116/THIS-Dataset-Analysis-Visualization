## 项目概述
本项目是《数据可视化技术》课程设计成果，针对Twitter History and Image Sharing (THIS)数据集进行全流程分析，包括数据预处理、多维度分析及可视化呈现，完成8个核心分析点与8种可视化图表类型的课程要求。


## 数据集说明
THIS数据集包含4个核心表（2006-2023年）：
- **IS_availability.csv**：图像使用与可用性数据（约80万条）
- **TH_country_day.csv**：国家日级推文与用户数据（约80万条）
- **TH_country_lang_day.csv**：国家-语言推文分布（约1500万条）
- **TH_num_new_user.csv**：新增用户注册数据（约94万条）


## 技术栈
- **数据处理**：numpy、pandas（清洗、转换、特征工程）
- **数据分析**：scipy（相关性分析）、3σ异常检测、移动平均
- **可视化**：matplotlib、seaborn（静态图表）、pyecharts（地理热力图）、plotly（3D图表）


## 核心分析成果
1. **图像使用行为**：发展中国家图像使用频率高于发达国家，中国居首（0.40）
2. **图像可达性**：2016年后各国稳定性提升，印度外部链接图像优势显著
3. **活跃度趋势**：美国推文量长期领先，中国数据受网络环境影响呈特殊波动
4. **用户参与度**：巴西人均推文数最高，与语言多样性无显著关联
5. **语言多样性**：美国最突出，印度以英语（45.2%）和印地语（25.6%）为主
6. **新增用户趋势**：美国累计超1.8亿（趋于饱和），印度2010-2020年增长显著
7. **事件驱动分析**：美国2008-2010年新增用户爆发，印度2020年峰值与功能迭代相关
8. **联合分析**：人均推文数与图像密度呈强负相关（-0.51），中国指标单独聚类


## 文件结构
```
THIS-Dataset-Analysis/
├─ 课程设计报告.docx
├─ data_preprocessing.ipynb
├─ visualization_analysis.ipynb
└─ README.md
```


# English Brief Introduction
This project is the course design outcome of "Data Visualization Technology" at Guangdong University of Finance & Economics, analyzing the Twitter History and Image Sharing (THIS) dataset (2006-2023) through data preprocessing, multi-dimensional analysis, and visualization.

Key analyses include image usage behavior, activity trends, user engagement, language diversity, and new user patterns across 4 core datasets. Technical tools include pandas for data processing, scipy for analysis, and matplotlib/seaborn/pyecharts/plotly for visualization.

Findings highlight developing countries' higher image usage rates, the US leading in overall activity, Brazil's high per capita tweets, and significant growth potential in India's new user market. The project fulfills course requirements with 8 analysis points and 8 visualization types.
