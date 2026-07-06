- 高数
    - 高中数学基础
        - 0.1 函数基础知识
            - 什么是函数
              函数定义：设数集 $ D \subset R $, 则称映射 $ f: D \rightarrow R $ 为定义在 $ D $上的函数,通常简记为 $ y = f(x)，x \in D $,其中 $ x $ 称为自变量, $ y $ 称为因变量，$D$ 称为定义域，对每个 $ x \in D $, 按对应法则 $f$ ，总有唯一确定的值$ y $ 与之对应。
            - 理解特殊形式的函数:隐函数、参数函数
            - 反函数相关概念
              反函数定义：设函数 $f:D \rightarrow f(D)$ 是单射，则它存在逆映射 $f^{-1}:f(D) \rightarrow D$，称此映射$f^{-1}$为 $f$ 的反函数，按此定义，对每个 $y \in f(D)$, 有唯一确定的值 $x \in D$ 与之对应，即 $f(x) = y$,于是有 $f^{-1}(y) = x$
              反函数的图像性质：一个函数和反函数之间的曲线是关于直线 $y = x$ 对称的
            - 求函数的定义域
              | 名称 | 形式 | 定义域 |
              | --- | --- | --- |
              | 幂函数 | $ y=x^a $ | 需要根据a的值来具体确定，比如：<br> $x^2,x^5,\cdots $,则 $x \in R$ <br> $x^{-1},x^{-2},\cdots $,则 $x \neq 0$ <br> $x^{\frac{1}{2}},x^{\frac{1}{4}},\cdots $,则 $x \geq 0$|
              | 指数函数 | $ y=a^x (a>0)$ |  $x \in R $|
              | 对数函数 | $ y=log_a^x$ |  $x > 0 $|
              | 三角函数 | $ y=\sin x, y=\cos x $ |  $x \in R $|
              | 三角函数 | $ y=\tan x= \frac{\sin x}{\cos x} $ |  $x \ne (k + \frac{1}{2} )\pi, k \in Z$|
              | 反三角函数 | $ y=\arcsin x, y = \arccos x$ |  $x \in [-1,1] $|
              | 反三角函数 | $ y=\arctan x$ |  $x \in R $|
        - 0.2 三角函数与反三角函数
            - $\arcsin(x) \quad \arccos(x) \quad \arctan(x)$
            - 基本公式：
              $\sin^2(x) + \cos^2(x) = 1$, $\tan^2(x) + 1 = \sec^2(x) $
              $\cos(A-B) = \cos A \cos B + \sin A \sin B $, $\cos(A+B) = \cos A \cos B - \sin A \sin B$
              $\cos(A-B - \frac{\pi}{2} + \frac{\pi}{2}) = \cos A \cos B + \sin A \sin B $
              $\cos(\frac{\pi}{2} + A-B - \frac{\pi}{2}) = \cos A \cos B + \sin A \sin B $
              $\cos(D -B - \frac{\pi}{2}) = \cos (D - \frac{\pi}{2}) \cos B + \sin (D - \frac{\pi}{2}) \sin B $
              $\cos(D -B - \frac{\pi}{2}) = \sin D \cos B - \cos D \sin B $
              $\sin(A-B) = \sin A \cos B - \cos A \sin B $, $\sin(A+B) = \sin A \cos B + \cos A \sin B$
              $\tan(A+B) = \frac{\tan A + \tan B}{1 - \tan A \tan B}$, $\tan(A-B) = \frac{\tan A - \tan B}{1 + \tan A \tan B}$
              倍角公式与半角公式：
              $\sin(2x) = 2 \sin(x) \cos(x)$, $\cos(2x) = \cos^2(x) - \sin^2(x) = 2 \cos^2(x) - 1 = 1 - 2\sin^2(x)$
              $\cos^2(\frac{x}{2}) = \frac{1 + \cos(x)}{2}$,
              $\sin^2(\frac{x}{2}) = \frac{1 - \cos(x)}{2}$

              和差化积：
              $\sin(A) + \sin(B) = 2 \sin(\frac{A+B}{2}) \cos(\frac{A-B}{2})$
              $\sin(A) - \sin(B) = 2 \cos(\frac{A+B}{2}) \sin(\frac{A-B}{2})$
              $\cos(A) + \cos(B) = 2 \cos(\frac{A+B}{2}) \cos(\frac{A-B}{2})$
              $\cos(A) - \cos(B) = 2 \sin(\frac{A+B}{2}) \sin(\frac{A-B}{2})$
              积化和差：
              $\sin(A) \cos(B) = \frac{sin(A + B) + sin(A - B)}{2}$
              $\cos(A) \sin(B) = \frac{sin(A + B) + sin(A - B)}{2}$
              $\cos(A) \cos(B) = \frac{cos(A + B) + cos(A - B)}{2}$
              $\sin(A) \sin(B) = \frac{cos(A + B) - cos(A - B)}{2}$
        - 0.3 指数函数与对数函数
            - $ a = e^{\ln(a)}, a^b = e^{b\ln(a)} \quad (a>0)$
            - 对数的性质：
              $\ln(a \times b) = \ln(a) + \ln(b)$, $\ln(\frac{a}{b}) = \ln(a) - \ln(b)$
              $\ln(a^b) = b\ln(a)$, $\ln{a^n}{M} = \frac{\ln{a}{M}}{n} $
              $\log{a}{b} = \frac{\ln{a}}{\ln{b}}$

              $ \boxed{ a^{\log{a}{b}} = b (a>0, a\ne 1,b>0) } $
              $ \boxed{ a = e^{ln(a)}, a^b =e^{b\ln(a)} } $
        - 0.4 排列组合与二项式定理
            - 复习排列数、组合数的运算
            - 巩固二项式定理，将其进行推广
              二项式定理：$(a+b)^n = \sum_{k=0}^{n} \binom{n}{k} a^{n-k} b^k$                   
        - 0.5 常用代数公式
            - 等比数列 等差数列 平方数列求和
              等差数列求和：$S_n = \frac{n(a_1 + a_n)}{2} = a_1n + \frac{n(n-1)d}{2}$
              等比数列求和：$S_n = \frac{a_1(1-q^n)}{1-q}$
              平方数列求和：$S_n = \frac{n(n+1)(2n+1)}{6} = 1 + 2^2 + 3^2 + \cdots + n^2$
            - n次方差 n次方和 n次方差根
              $a^n - b^n = (a-b)(a^{n-1} + a^{n-2}b + a^{n-3}b^2 + \cdots + b^{n-1}) n \in N^* $
              $ \frac{a^{n-1} \times (1 - (\frac{b}{a})^{n})}{1- \frac{b}{a}}$
              $ \frac{a^{n} \times (1 - (\frac{b}{a})^{n})}{a- b}$
              $a^n + b^n = (a+b)(a^{n-1} - a^{n-2}b + a^{n-3}b^2 - \cdots - ab^{n-2}+ b^{n-1}) n \in (2N^* + 1)$
              $\sqrt{a^n} - \sqrt{b^n} = \frac{(\sqrt{a} - \sqrt{b})(\sqrt{a} + \sqrt{b})}{\sqrt{a} + \sqrt{b}} = \frac{a - b}{\sqrt{a} + \sqrt{b}}$
              $\sqrt[3]{a} - \sqrt[3]{b} = \frac{(\sqrt[3]{a} - \sqrt[3]{b})(\sqrt[3]{a^2} + \sqrt[3]{ab} + \sqrt[3]{b^2})}{\sqrt[3]{a^2} + \sqrt[3]{ab} + \sqrt[3]{b^2}} = \frac{a - b}{\sqrt[3]{a^2} + \sqrt[3]{ab} + \sqrt[3]{b^2}}$
        - 0.6 极坐标
            - 理解极点 极轴 极径 极角
            - 清楚极坐标与直角坐标的转换
    - 微积分核心思想
        - 极限
        - 微分
        - 积分
    - 数列与函数极限
      - 数列极限的基本定义
        - 理解 $\epsilon - N$ 定义, 能够利用定义证明数列极限，懂得数列发散、有界、收敛之间的对比
        - 数列极限的定义
          - $\lim_{n \to \infty} a_n = A \Leftrightarrow \forall \epsilon > 0, \exists N \in \mathbb{N}, \forall n > N, |a_n - A| < \epsilon$
          - 设$\{x_n\}$为一数列，如果存在常数$a$,对于任意给定的正数$\epsilon$（无论它多么小）,总存在正整数$N$,使得当$n > N$时,不等式$|x_n-a| < \epsilon$都成立，那么就称常数$a$为数列$\{x_n\}$的极限，或者说数列$\{x_n\}$收敛于常数$a$，记作$\lim_{n \to \infty} x_n = a$ 或者 $x_n \to a (n \to \infty)$
        - 性质
          - 唯一性：如果数列$\{x_n\}$收敛于$a$，则其极限唯一
          - 有界性：如果数列$\{x_n\}$收敛，那么它一定有界
          - 保号性：如果 $lim_{n \to \infty} {x_n} = a$, 且$a > 0$, 那么存在正整数 $N$，当 $n > N$ 时，$x_n > 0$
          - 子列收敛：如果数列$\{x_n\}$收敛于$a$，那么它的任一子数列也收敛于$a$
      - 函数极限的基本定义
        - 懂得 $ x \to 0 $ 和 $x \to a$ 的区别，以及 $\lim$ 算符 
          - 设$f(x)$在点$x_0$的某一去心邻域内有定义，如果存在常数$A$,对于任意给定的正数$\epsilon$,总存在正数$\delta$,使得当$x$满足不等式$|x - x_0| < \delta$时,$|f(x)-a| < \epsilon$成立，那么就称常数$A$就叫做函数$f(x)$当 $x$ 趋近于$x_0$时的极限，记作$\lim_{x \to x_0} f(x) = A$ 或者 $f(x) \to A (x \to x_0)$
      - 极限运算法则
        - 有界函数与无穷小相乘，仍然是无穷小
        - 如果 $\lim f(x) = A, \lim g(x) = B$,注意A和B都是常数，那么 
          $\lim(f(x) \pm g(x)) = \lim f(x) \pm \lim g(x) = A \pm B$
          $\lim(f(x) \cdot g(x)) = \lim f(x) \cdot \lim g(x) = A \cdot B$
          $若又有B\ne 0,则$ $\lim(\frac{f(x)}{g(x)}) = \frac{A}{B}$
      - ==两个特殊极限==
        - 推导 $\lim_{x\to 0} \frac{\sin x}{x} = 1 $ 和 $\lim_{n\to \infty} (1 + \frac{1}{x}) = e$
        - 掌握极限准则：夹逼准则、单调有界准则
          - 夹逼准则：在 $x_0$ 的某去心邻域内，存在 $g(x) < f(x) < h(x)$, 且满足 $\lim_{x \to x_0} g(x) = \lim_{x \to x_0} h(x) = A$, 则 $\lim_{x \to x_0} f(x) = A$
        - 推广到更多极限结果
      - ==无穷小与无穷大==
        - 明晰无穷小的高阶、低阶、同阶、等价等概念
          - 下面的 $\alpha$ 和 $\beta$ 都是在同一个自变量的变化过程中的无穷小，且 $\alpha \ne 0$ :
          如果 $\lim \frac{\beta}{\alpha} = 0$,那么就说 $\beta$ 是比 $\beta$ 高阶的无穷小，记作 $\beta = o(\alpha)$
          如果 $\lim \frac{\beta}{\alpha} = \infty$,那么就说 $\beta$ 是比 $\alpha$ 低阶的无穷小
          如果 $\lim \frac{\beta}{\alpha} = c \ne 0$,那么就说 $\beta$ 与 $\alpha$ 是同阶无穷小
          如果 $\lim \frac{\beta}{\alpha^k} = c \ne 0,k > 0$,那么就说 $\beta$ 与 $\alpha$ 的$k$阶同阶无穷小
          如果 $\lim \frac{\beta}{\alpha} = 1$,那么就说 $\beta$ 与 $\alpha$ 是等价无穷小,记作 $\alpha \sim \beta$
        - 掌握常用的等价无穷小代换
          |||
          |---|---|
          |$\sin x$|$x$|
          |$\tan x$|$x$|
          |$\arcsin x$|$x$|
          |$\arctan x$|$x$|
          |$\ln(1+x)$|$x$|
          |$e^x - 1$|$x$|
          |$a^x - 1$|$x\ln{a}$|
          |$(1 + x)^a - 1$|$ax$|
          |$1 - \cos x$|$\frac{x^2}{2}$|
        - 例题
          - $$
            \begin{align*}
            \lim_{x \to 0} \frac{\sin 3x}{\arcsin x} &= \lim_{x \to 0} \frac{3x}{x} \\
            &= 3
            \end{align*} \text{(等价无穷小替换)}
            $$
          - $$
            \begin{align*}
            \lim_{x \to 0} \frac{\tan 3x}{\sqrt{1 + x} - 1} &= \lim_{x \to 0} \frac{x}{\frac{1}{2}x} \\
            &= 2
            \end{align*} \text{(等价无穷小替换)}
            $$
          - $$
            \begin{align*}
            \lim_{x \to 3} \frac{e^{x -3} - 1}{\sin(2x - 6)} &= \lim_{x \to 0} \frac{x - 3}{2x - 6} \\
            &= \frac{1}{2}
            \end{align*} \text{(等价无穷小替换)}
            $$
          - $$
            \begin{align*}
            \lim_{x \to 0} \frac{ln{(\cos x})}{x^2} &= \lim_{x \to 0} \frac{ln(1 + \cos x - 1)}{x^2} \\
            &= \lim_{x \to 0} \frac{\cos x - 1}{x^2} \\
            &= \lim_{x \to 0} \frac{-\frac{x^2}{2}}{x^2} \\
            &= -\frac{1}{2} \\
            \end{align*} \text{(等价无穷小替换)}
            $$
          - $$
            \begin{align*}
            \lim_{x \to 1} \frac{\cos (\frac{\pi}{2}x)}{x - 1} &= \lim_{x \to 1} \frac{\cos (\frac{\pi}{2}(x - 1 + 1))}{x - 1} \\
            &= \lim_{x \to 1} \frac{\cos (\frac{\pi}{2}(x - 1) + \frac{\pi}{2}))}{x - 1} \\
            &= \lim_{x \to 1} \frac{-\sin (\frac{\pi}{2}(x-1))}{x - 1} \\
            &= \lim_{x \to 1} \frac{-\frac{\pi}{2}(x-1)}{x - 1} \\
            &= -\frac{\pi}{2} \\
            &= 令t=x-1 x = t+1 \lim_{t \to 0} \frac{\cos(\frac{\pi}{2}(t-1))}{t}
            \end{align*} \text{(等价无穷小替换)}
            $$
          - $$
            \begin{align*}
            \lim_{x \to \infty} x\sin(\frac{1}{x})&= \lim_{x \to \infty} x\frac{1}{x} \\
            &= 1
            \end{align*} \text{(等价无穷小替换)}
            $$
          - $$
            \begin{align*}
            \lim_{x \to 0} \frac{\tan x - \sin x}{x^3} &= \lim_{x \to 0} \frac{\tan x(1 - \cos x)}{x^3} \\
            &= \frac{1}{2}
            \end{align*} \text{(等价无穷小替换)}
            $$
          
        - 掌握无穷大变量的大小关系
      - ==极限求解思路==
        - 求解极限三步骤：代入、分类、化解
      - 例题
        - $$
          \begin{align*}
          \lim_{x \to 2}\left( \frac{1}{x - 2} - \frac{4}{x^2 - 4} \right)
              &= \lim_{x \to 2}\left( \frac{x + 2}{x^2 - 4} - \frac{4}{x^2 - 4} \right) \\
              &= \lim_{x \to 2} \frac{x - 2}{x^2 - 4} \\
              &= \lim_{x \to 2} \frac{1}{x + 2} \\
              &= \frac{1}{4}
          \end{align*}
          $$
        - $$
          \begin{align*}
          \lim_{x \to 2}\left( \frac{x^2 - 5x + 6}{x^2 - 4} \right)
          &= \lim_{x \to 2}\left( \frac{(x-2)(x-3)}{(x-2)(x+2)} \right) \\
          &= \lim_{x \to 2}\left( \frac{x-3}{x+2} \right) \\
          &= \frac{2-3}{2+2} \\
          &= -\frac{1}{4}
          \end{align*}
          $$
        - $$
          \begin{align*}
          \lim_{x \to 1}\left( \frac{\sqrt{3-x} - \sqrt{1+x}}{x^2 +x - 2} \right) 
          &= \lim_{x \to 1}\left( \frac{(\sqrt{3-x} - \sqrt{1+x})\left( {\sqrt{3-x} + \sqrt{1+x}} \right)}{(x^2 +x - 2)\left( {\sqrt{3-x} + \sqrt{1+x}} \right)} \right) \\
          &= \lim_{x \to 1}\left( \frac{2 - 2x}{(x - 1)(x+2)\left( {\sqrt{3-x} + \sqrt{1+x}} \right)} \right) \\
          &= \lim_{x \to 1}\left( \frac{-2 (x -1)}{(x - 1)(x+2)\left( {\sqrt{3-x} + \sqrt{1+x}} \right)} \right) \\
          &= \lim_{x \to 1}\left( \frac{-2}{(x+2)\left( {\sqrt{3-x} + \sqrt{1+x}} \right)} \right) \\
          &=  \frac{-\sqrt{2}}{6} 
          \end{align*}
          $$
        - $$
          \begin{align*}
          \lim_{x \to +\infty}\left( \sqrt{x^2 + x}  - x\right) 
          &= \lim_{x \to +\infty}\left( \frac{x}{\sqrt{x^2 + x}  + x}\right) 
          &= \lim_{x \to +\infty}\left( \frac{1}{\sqrt{1 + \frac{1}{x}}  + 1}\right) 
          &= \frac{1}{2}
          \end{align*}
          $$
        - $$
          \begin{align*}
          \lim_{x \to \infty} \frac{5x^2 + 6x}{7x^2 + 8x}
          &= \frac{5}{7}
          \end{align*}
          $$
        - $$
          \begin{align*}
          \lim_{x \to \infty} \left( 1 + \frac{1}{x} \right) \left(2 - \frac{1}{x^2} \right)
          &= 2
          \end{align*}
          $$
        - $$
          \begin{align*}
          \lim_{x \to 0} \frac{\left(1 + x \right)^3 - 1}{x} 
          &= \lim_{x \to 0} \frac{\left(1 + 3x + 3x^3 + x^3  - 1\right)}{x} \\
          &= \lim_{x \to 0} \left(3 + 3x + x^2 \right)  \\
          &= 3 
          \end{align*}
          $$
        - $$
          \begin{align*}
          \lim_{x \to 0} \frac{ \sqrt{1 + x} - 1}{x} 
          &= \lim_{x \to 0} \frac{x}{x (\sqrt{1 + x} + 1)}  \\
          &= \lim_{x \to 0} \frac{1}{(\sqrt{1 + x} + 1)}  \\
          &= \frac{1}{2} 
          \end{align*}
          $$
        - $$
          \begin{align*}
          \lim_{x \to 3} \frac{x^2 - 5x + 6}{x^2 - 6x + 9}
          &= \lim_{x \to 3} \frac{(x-3)(x-2)}{(x-3)(x-3)}
          &= \lim_{x \to 3} \frac{(x-2)}{(x-3)}
          &= \infty 
          \end{align*}
          $$
    - 函数连续性
      - 连续函数的定义1:
        - 设函数 $f(x)$ 在点 $x_0 = a$ 的邻域内有定义，如果 $\lim_{x \to a} f(x) = f(a)$，则称 $f(x)$ 在 $x = a$ 处连续。
      - 连续函数的定义2:
        - 设函数 $f(x)$ 在点 $x = a$ 的邻域内有定义，如果 $\lim_{\Delta x \to a^-} f(x_0 + \Delta x) - f(x_0) = 0$，则称 $f(x)$ 在 $x = a$ 处连续。
      - 可去间断点：$\lim_{x \to a^-}f(x) = \lim_{x \to a^+}f(x) \ne f(x)$
      - 跳跃间断点：$\lim_{x \to a^-}f(x) \ne \lim_{x \to a^+}f(x)$
      - 无穷间断点：$\lim_{x \to a_0}f(x) = \infty$
      - 震荡间断点
      - 性质
        - 有界性与最大值最小值定理：在闭区间上连续的函数在该区间上有界且一定能取得它的最大值和最小值
        - 零点定理：设函数$f(x)$在闭区间$[a,b]$上连续，且$f(a)f(b)<0$，则$f(x)$在$(a,b)$上一定有零点$\xi$,且$f(\xi) = 0$
        - 介值定理：设函数$f(x)$在闭区间$[a,b]$上连续，且在这区间的端点取不同的函数值：$f(a) = A, f(b)=B$，则对于A与B之间的任意一个$C$ ，在开区间$(a,b)$内至少存在一个点$\xi$，使得$f(\xi) = C(a < \xi < b)$
      - 例题
        - $$
          \begin{align*}
          求 f(x) = \frac{x^2 -1}{x^2 - 3x + 2} 间断点
          \end{align*}
          $$
- 线性代数