<!--
 * @Author: BDFD
 * @Date: 2022-01-21 13:17:17
 * @LastEditTime: 2022-01-23 00:19:42
 * @LastEditors: BDFD
 * @Description:
 * @FilePath: \00Matplotlib_Seaborn_Visualization_World\README.md
-->

# Welcome to Matplotlib & Seaborn Visualization World

Put into 7 groups server for different situation purpose with over 50+ visualization graph

## Important Characteristics for Make Effective Visualization:

- Convey correct and necessary information without distorting facts.
- Simple design make user easy to understand.
- Support the message aesthetically rather than obscure it.
- Dont overload information .

## Basic Setup Tempalte:

```
import numpy as np
import pandas as pd
import matplotlib as mpl
import matplotlib.pyplot as plt
import seaborn as sns
import warnings; warnings.filterwarnings(action='once')

large = 22; med = 16; small = 12
params = {'axes.titlesize': large,
          'legend.fontsize': med,
          'figure.figsize': (16, 10),
          'axes.labelsize': med,
          'axes.titlesize': med,
          'xtick.labelsize': med,
          'ytick.labelsize': med,
          'figure.titlesize': large}
plt.rcParams.update(params)
plt.style.use('seaborn-whitegrid')
sns.set_style("white")
%matplotlib inline

# Version
print(mpl.__version__)  #> 3.2.2
print(sns.__version__)  #> 0.11.2
```

notice: version show on Colab(Google Jupyternotebook on Date: 2022/01/21)

## Viz Graph Table of Contents

### 一、Correlation (关联)

- [x] **1. Scatter Plot (散点图)**
- [x] **2. Bubble Plot Within Scatter Plot (气泡图带边界)**
- [ ] **3. Scatter plot with linear regression line of best fit (带线性回归最佳拟合线的散点图)**
- [x] **4. Jittering with stripplot (抖动图)**
- [ ] **5. Counts Plot (计数图)**
- [x] **6. Marginal Histogram (边缘直方图)**
- [ ] **7 Marginal Boxplot (边缘箱形图)**
- [x] **8 Correllogram (相关图)**
- [x] **9 Pairwise Plot (矩阵图)**

### 二、Deviation （偏差）

- [ ] **10 Diverging Bars (发散型条形图)**
- [ ] **11 Diverging Texts (发散型文本)**
- [ ] **12 Diverging Dot Plot (发散型包点图)**
- [ ] **13 Diverging Lollipop Chart with Markers (带标记的发散型棒棒糖图)**
- [ ] **14 Area Chart (面积图)**

### 三、Ranking （排序）

- [ ] **15 Ordered Bar Chart (有序条形图)**
- [ ] **16 Lollipop Chart (棒棒糖图)**
- [ ] **17 Dot Plot (包点图)**
- [ ] **18 Slope Chart (坡度图)**
- [ ] **19 Dumbbell Plot (哑铃图)**

### 四、Distribution （分布）

- [ ] **20 Histogram for Continuous Variable (连续变量的直方图)**
- [ ] **21 Histogram for Categorical Variable (类型变量的直方图)**
- [ ] **22 Density Plot (密度图)**
- [ ] **23 Density Curves with Histogram (直方密度线图)**
- [ ] **24 Joy Plot**
- [ ] **25 Distributed Dot Plot (分布式包点图)**
- [ ] **26 Box Plot (箱形图)**
- [ ] **27 Dot + Box Plot (点+箱形图)**
- [ ] **28 Violin Plot (小提琴图)**
- [ ] **29 Population Pyramid (人口金字塔)**
- [ ] **30 Categorical Plots (分类图)**

### 五、Composition （组成）

- [ ] **31 Waffle Chart (华夫饼图)**
- [ ] **32 Pie Chart (饼图)**
- [ ] **33 Treemap (树形图)**
- [ ] **34 Bar Chart (条形图)**

### 六、Change （变化）

- [ ] **35 Time Series Plot (时间序列图)**
- [ ] **36 Time Series with Peaks and Troughs Annotated (带波峰波谷标记的时序图)**
- [ ] **37 Autocorrelation (ACF) and Partial Autocorrelation (PACF) Plot (自相关和部分自相关图)**
- [ ] **38 Cross Correlation plot (交叉相关图)**
- [ ] **39 Time Series Decomposition Plot (时间序列分解图)**
- [ ] **40 Multiple Time Series (多个时间序列)**
- [ ] **41 Plotting with different scales using secondary Y axis (使用辅助 Y 轴来绘制不同范围的图形)**
- [ ] **42 Time Series with Error Bands (带有误差带的时间序列)**
- [ ] **43 Stacked Area Chart (堆积面积图)**
- [ ] **44 Area Chart UnStacked (未堆积的面积图)**
- [ ] **45 Calendar Heat Map (日历热力图)**
- [ ] **46 Seasonal Plot (季节图)**

### 七、Groups （分组）

- [ ] **47 Dendrogram (树状图)**
- [ ] **48 Cluster Plot (簇状图)**
- [ ] **49 Andrews Curve (安德鲁斯曲线)**
- [ ] **50 Parallel Coordinates (平行坐标)**
