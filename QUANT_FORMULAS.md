# XuanjiQuant 全套量化公式

## 一、APEX自体认知迭代公式

$$\Phi = \frac{K \cdot H \cdot P \cdot \Delta R}{N \cdot \tau}$$

| 符号 | 含义 |
|------|------|
| Φ | APEX自体综合能力值 |
| K | 知识储备（算法/推理/代码/经验） |
| H | 历史记忆（轨迹/习惯/逻辑） |
| P | 自主研究能力 |
| ΔR | 核心内核（复盘/内化/提升） |
| N | 遗忘抑制因子 |
| τ | 自体迭代周期 |

## 二、融合主进化公式

$$\Delta G_{total} = \Delta G \cdot \Phi$$

## 二、核心神经-模型对齐公式

### 主公式（总损失）

$$L_{total} = \alpha \cdot L_{class} + (1-\alpha) \cdot L_{neural}$$

### 子公式

**分类损失：**
$$L_{class} = CrossEntropy(y_{pred}, y_{true})$$

**神经对齐损失：**
$$L_{neural} = MSE(f_{model}(x), f_{brain}(x))$$

### 关键说明

| 符号 | 含义 |
|------|------|
| α | 平衡系数 |
| f_model(x) | 模型多层特征 |
| f_brain(x) | 人脑EEG/fMRI神经表征 |
| 目标 | 联合优化，提升模型–大脑表征相似性 |

## 三、GitHub量化项目核心公式

### 1. 因子标准化公式

$$F_{std} = \frac{F_{raw} - \mu_{period}}{\sigma_{period}} \cdot \rho_{market}$$

### 2. 多因子信号合成公式

$$S_{signal} = \alpha_1 T_{trend} + \alpha_2 F_{fund} + \alpha_3 M_{flow} + \alpha_4 V_{vol}$$

### 3. 多周期趋势共振公式

$$R_{resonate} = T_{short} \cap T_{mid} \cap T_{long}$$

### 4. 风险校正夏普比率

$$Sharpe_{adj} = \frac{R_{annual} - R_{free}}{\sigma_{max\_drawdown}}$$

### 5. 资金强弱判定

$$F_{power} = \frac{Buy_{big} - Sell_{big}}{Volume_{total}} \times 100\%$$

### 6. 大盘走势相关性

$$Corr = Corr(S_{strategy}, I_{market})$$

## 四、防虚假回测公式

$$B_{valid} = Data_{unseen} \cap Cost_{real} \cap \neg Future_{func}$$

## 五、策略自主进化公式

$$S_{next} = S_{current} \oplus S_{optimize} \ominus S_{invalid}$$
