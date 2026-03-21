## 一、 基础语法规则

在 Obsidian 中，公式主要分为两种呈现方式：

1. **行内公式**（夹在文字中间）：使用 `$公式$`。
    
    - 示例：当变量趋近于零时，求 $f(x)$ 的极限。
        
2. **独立公式块**（单独占一行并居中）：使用 `$$公式$$`。
    

---

## 二、 常用数学符号与希腊字母

|**符号名称**|**渲染效果**|**LaTeX 代码**|
|---|---|---|
|分数|$\frac{a}{b}$|`\frac{a}{b}`|
|根号|$\sqrt{x}$|`\sqrt{x}`|
|无穷大|$\infty$|`\infty`|
|偏导数|$\partial$|`\partial`|
|乘积|$\prod$|`\prod`|
|阿尔法|$\alpha$|`\alpha`|
|贝塔|$\beta$|`\beta`|
|德尔塔|$\Delta$|`\Delta`|

---

## 三、 高数核心公式模板（直接复制粘贴）

### 1. 极限与洛必达法则

求极限时经常需要用到趋近于某个值的符号，以及洛必达法则的推导过程：
$$
\lim_{x \to 0} \frac{\sin x}{x} = 1
$$
代码段
```
$$
\lim_{x \to 0} \frac{\sin x}{x} = 1
$$
```

$$\lim_{x \to x_0} \frac{f(x)}{g(x)} \overset{\text{洛必达}}{=} \lim_{x \to x_0} \frac{f'(x)}{g'(x)}$$
代码段
```
$$
\lim_{x \to x_0} \frac{f(x)}{g(x)} \overset{\text{洛必达}}{=} \lim_{x \to x_0} \frac{f'(x)}{g'(x)}
$$
```

### 2. 微积分与积分号

一元函数微积分的标准写法，包括定积分和多重积分：
$$
\int_{a}^{b} f(x) dx = F(b) - F(a)
$$
代码段
```
$$
\int_{a}^{b} f(x) dx = F(b) - F(a)
$$
```
$$
\iint\limits_D f(x,y) \,dx\,dy
$$
代码段
```
$$
\iint\limits_D f(x,y) \,dx\,dy
$$
```

### 3. 一元二次方程求根公式

处理复杂方程时的标准书写格式：
$$
x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}
$$
代码段
```
$$
x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}
$$
```

### 4. 分段函数

用于表示函数在不同区间的取值，非常适合做函数图象分析和连续性判断的笔记：
$$
f(x) =
\begin{cases}
x^2 & \text{当 } x < 0 \\
2x & \text{当 } x \ge 0
\end{cases}
$$
代码段
```
$$
f(x) =
\begin{cases}
x^2 & \text{当 } x < 0 \\
2x & \text{当 } x \ge 0
\end{cases}
$$
```

---

## 四、 408 数据结构常用符号

在梳理单链表等数据结构、绘制逻辑图的替代文本时，经常需要用到箭头来表示指针的指向。

| **符号名称** | **渲染效果**          | **LaTeX 代码**          |
| -------- | ----------------- | --------------------- |
| 向右箭头     | $\rightarrow$     | `\rightarrow` 或 `\to` |
| 向左箭头     | $\leftarrow$      | `\leftarrow`          |
| 双向箭头     | $\leftrightarrow$ | `\leftrightarrow`     |
| 推出符号     | $\Rightarrow$     | `\Rightarrow`         |

**示例：单链表节点关系表示**
$$
\text{Head} \rightarrow \text{Node}_1 \rightarrow \text{Node}_2 \rightarrow \text{NULL}
$$
代码段
```
$$
\text{Head} \rightarrow \text{Node}_1 \rightarrow \text{Node}_2 \rightarrow \text{NULL}
$$