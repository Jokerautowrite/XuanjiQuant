# XuanjiQuant 全套量化公式

## 一、全局总控进化母公式

$$\Delta Q = \frac{C_{tick} \cdot \Lambda_{gene} \cdot \Omega_{market}}{H_{noise} \cdot T_{cycle}} \cdot \eta_{evo} \cdot \sigma_{valid}$$

| 符号 | 含义 |
|------|------|
| ΔQ | 量化系统进化增益 |
| C_tick | 行情数据质量系数 |
| Λ_gene | 基因策略适应度 |
| Ω_market | 市场状态适配度 |
| H_noise | 系统噪声干扰 |
| T_cycle | 进化周期时间 |
| η_evo | 进化效率因子 |
| σ_valid | 策略有效性系数 |

## 二、GitHub量化项目核心公式

### 1. 因子标准化公式

$$F_{std} = \frac{F_{raw} - \mu_{period}}{\sigma_{period}} \cdot \rho_{market}$$

### 2. 多因子信号合成公式

$$S_{signal} = \alpha_1 T_{trend} + \alpha_2 F_{fund} + \alpha_3 M_{flow} + \alpha_4 V_{vol}$$

### 3. 多智能体共识打分公式

$$S_{score} = \frac{S_1+S_2+S_3}{3} \times \lambda_{conf}$$

### 4. 多周期趋势共振公式

$$R_{resonate} = T_{short} \cap T_{mid} \cap T_{long}$$

### 5. 金融时序预测公式

$$P_{forecast} = X_{hist} \cdot W_{time} + \varepsilon_{bias}$$

### 6. 风险校正夏普比率公式

$$Sharpe_{adj} = \frac{R_{annual} - R_{free}}{\sigma_{max\_drawdown}}$$

### 7. 个股真实复权公式

$$P_{real} = P_{origin} \times K_{forward} \times K_{backward}$$

### 8. 全自动参数寻优公式

$$\theta_{opt} = \mathop{\arg\max}_{\theta} f(\theta \mid D_{history})$$

### 9. 资金强弱判定公式

$$F_{power} = \frac{Buy_{big} - Sell_{big}}{Volume_{total}} \times 100\%$$

### 10. 大盘走势相关性公式

$$Corr = Corr(S_{strategy}, I_{market})$$

## 三、防虚假回测公式

$$B_{valid} = Data_{unseen} \cap Cost_{real} \cap \neg Future_{func}$$

## 四、强弱个股双向验证公式

$$R_{strong} - R_{weak} \geq \tau_{min}$$

## 五、策略自主进化公式

$$S_{next} = S_{current} \oplus S_{optimize} \ominus S_{invalid}$$

## 六、算法有效性约束公式

$$\begin{cases} S_{calc} & \sigma_{error} < \sigma_{limit} \\ 0 & \sigma_{error} \geq \sigma_{limit} \end{cases}$$
