- 重点<!-- markmap: foldAll -->
  - [ ] 考研数学啊赞学长  反常积分敛散性判断，一个视频让他变成送分题
  - [ ] 二元函数极限不会求？1h全面入门到精通 学渣救星  一高数
  - 核心计算型 75+
    - 常用等式与不等式
      - 常用等式
        $$
        \begin{aligned}
        & a^n - b^n = (a - b)(a^{n-1} + a^{n-2}b + \cdots + ab^{n-2} + b^{n-1}) \\
        & \sqrt a - \sqrt b = \frac{a - b}{\sqrt{a} + \sqrt{b}} \\
        & \sqrt[3]{a} - \sqrt[3]{b} = \frac{{a} - {b}}{\sqrt[3]{a^2} + \sqrt[3]{ab} + \sqrt[3]{b^2}} \\
        & 1 + 2^2 + 3^2 + \cdots + n^2 = \frac{n(n+1)(2n+1)}{6} \\
        & a = \ln e ^a = e ^{ln^a} \\
        & a^b= e^{b \ln a}(a>0) \\
        & \arctan x + \arctan \frac{1}{x} = \frac{\pi}{2} (x>0)\\
        & \arcsin x + \arccos {x} = \frac{\pi}{2} (0 \le x \le 1)\\
        \end{aligned}
        $$
      - 常用不等式
        $$
        \begin{aligned}
        & \sin x < x < \tan x (0 < x < \frac{\pi}{2}) \\
        & - \left|x \right| < \left|\sin x \right| < \left|x \right| \\
        & \arctan x < x < \arcsin x (0 < x < \frac{\pi}{2}) \\
        & \ln (1 + x) < x < e^x - 1 \\
        & \big||a| - |b|\big| \le |a \pm b| \le |a| + |b| \\
        & \sqrt{ab} \le \frac{a + b}{2} \le \sqrt{\frac{a^2 + b^2}{2}} (a, b > 0) \\
        & \sqrt[3]{abc} \le \frac{a + b + c}{3} \le \sqrt{\frac{a^2 + b^2 + c^2}{3}} (a, b, c > 0) \\
        & 0 < a < x < b, 0 < c<y<d  \to \frac{c}{b} < \frac{y}{x} \to \frac{d}{a} \\
        & |x| < a \to - a < x < a
        \end{aligned}
        $$
    - 函数极限计算
    - 导数定义与计算
    - 不定积分与定积分
    - 微分方程求解
  - 专项总结型 110+
    - 导数应用
    - 泰勒公式
    - 变上限积分 
    - 广义积分
    - 多元函数的极限和导数
    - 重积分计算
    - 几何与物理应用
    - 无穷级数(仅数一数三)
  - 拔高挑战型 130+
    - 中值定理证明
      - 连续函数介值定理
      - 微分中值定理
        - 罗尔
        - 拉格朗日
        - 柯西
      - 积分中值定理
    - 傅立叶级数(仅数学一)
    - 曲线曲面积分(仅数学一)

- 高数<!-- markmap: foldAll -->
    - 高中数学基础
        - 0.1 函数基础知识
            - 什么是函数
              函数定义：设数集 $ D \subset R $, 则称映射 $ f: D \rightarrow R $ 为定义在 $ D $上的函数,通常简记为 $ y = f(x)，x \in D $,其中 $ x $ 称为自变量, $ y $ 称为因变量，$D$ 称为定义域，对每个 $ x \in D $, 按对应法则 $f$ ，总有唯一确定的值$ y $ 与之对应。
            - 理解特殊形式的函数:隐函数、参数函数
            - 反函数相关概念
              反函数定义：设函数 $f:D \rightarrow f(D)$ 是单射，则它存在逆映射 $f^{-1}:f(D) \rightarrow D$，称此映射$f^{-1}$为 $f$ 的反函数，按此定义，对每个 $y \in f(D)$, 有唯一确定的值 $x \in D$ 与之对应，即 $f(x) = y$,于是有 $f^{-1}(y) = x$
              反函数的图像性质：一个函数和反函数之间的曲线是关于直线 $y = x$ 对称的
            - 幂函数,指数函数,对数函数，三角函数，反三角函数
            - 基本初等函数和常数进行四则运算和复合
            - 奇偶性
            - 单调性
            - 有界性
            - 周期性
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
        - 数列极限的定义
          - $\lim_{n \to \infty} a_n = A \Leftrightarrow \forall \epsilon > 0, \exists N \in \mathbb{N}, \forall n > N, |a_n - A| < \epsilon$
          - 设$\{x_n\}$为一数列，如果存在常数$a$,对于任意给定的正数$\epsilon$（无论它多么小）,总存在正整数$N$,使得当$n > N$时,不等式$|x_n-a| < \epsilon$都成立，那么就称常数$a$为数列$\{x_n\}$的极限，或者说数列$\{x_n\}$收敛于常数$a$，记作$\lim_{n \to \infty} x_n = a$ 或者 $x_n \to a (n \to \infty)$
        - 函数极限的基本定义
          - 懂得 $ x \to 0 $ 和 $x \to a$ 的区别，以及 $\lim$ 算符 
            - 设$f(x)$在点$x_0$的某一去心邻域内有定义，如果存在常数$A$,对于任意给定的正数$\epsilon$,总存在正数$\delta$,使得当$x$满足不等式$|x - x_0| < \delta$时,$|f(x)-a| < \epsilon$成立，那么就称常数$A$就叫做函数$f(x)$当 $x$ 趋近于$x_0$时的极限，记作$\lim_{x \to x_0} f(x) = A$ 或者 $f(x) \to A (x \to x_0)$
        - 明晰无穷小的高阶、低阶、同阶、等价等概念
          - 下面的 $\alpha$ 和 $\beta$ 都是在同一个自变量的变化过程中的无穷小，且 $\alpha \ne 0$ :
          如果 $\lim \frac{\beta}{\alpha} = 0$,那么就说 $\beta$ 是比 $\alpha$ 高阶的无穷小，记作 $\beta = o(\alpha)$
          如果 $\lim \frac{\beta}{\alpha} = \infty$,那么就说 $\beta$ 是比 $\alpha$ 低阶的无穷小
          如果 $\lim \frac{\beta}{\alpha} = c \ne 0$,那么就说 $\beta$ 与 $\alpha$ 是同阶无穷小
          如果 $\lim \frac{\beta}{\alpha^k} = c \ne 0,k > 0$,那么就说 $\beta$ 与 $\alpha$ 的$k$阶同阶无穷小
          如果 $\lim \frac{\beta}{\alpha} = 1$,那么就说 $\beta$ 与 $\alpha$ 是等价无穷小,记作 $\alpha \sim \beta$
      - 性质
        - 唯一性：如果数列$\{x_n\}$收敛于$a$，则其极限唯一
        - 有界性：如果数列$\{x_n\}$收敛，那么它一定有界
        - 保号性：如果 $lim_{n \to \infty} {x_n} = a$, 且$a > 0$, 那么存在正整数 $N$，当 $n > N$ 时，$x_n > 0$
        - 子列收敛：如果数列$\{x_n\}$收敛于$a$，那么它的任一子数列也收敛于$a$
      - 极限运算法则
        - 如果 $\lim f(x) = A, \lim g(x) = B$,注意A和B都是常数，那么 
          $\lim(f(x) \pm g(x)) = \lim f(x) \pm \lim g(x) = A \pm B$
          $\lim(f(x) \cdot g(x)) = \lim f(x) \cdot \lim g(x) = A \cdot B$
          $若又有B\ne 0,则$ $\lim(\frac{f(x)}{g(x)}) = \frac{A}{B}$
          复合函数外层函数连续，lim符号可以放到内层的函数体上
        - ==两个特殊极限==
          - 推导 $\lim_{x\to 0} \frac{\sin x}{x} = 1 $ 和 $\lim_{n\to \infty} (1 + \frac{1}{x}) = e$
          - 掌握极限准则：夹逼准则、单调有界准则
            - 夹逼准则：在 $x_0$ 的某去心邻域内，存在 $g(x) < f(x) < h(x)$, 且满足 $\lim_{x \to x_0} g(x) = \lim_{x \to x_0} h(x) = A$, 则 $\lim_{x \to x_0} f(x) = A$
            - 单调有界准则
              $$
              a_1 = \sqrt2,a_{n+1} = \sqrt{2 + a_n}， 证明\lim_{n \to \infty} a_n 存在并求值 \\
              设f(x) = \sqrt{2+x} , f'(x) = \frac{1}{2\sqrt{2+x}}, |f'(x)| < \frac{1}{2}, f(2) = 2.\\
              |a_n -2| = |f(a_{n-1}) - f(2)| = |(a_{n-1} - 2)f'(\epsilon)|  < \frac{1}{2}|a_{n-1} - 2| \\
              |a_n - 2| < \frac{1}{2^{n-1}}|a_{1} - 2|,接着应用极限定义，带入a_1 算出n ，用\epsilon语言描述
              $$
          - 推广到更多极限结果
        - 洛必达法则
          当满足以下三点条件时：
          $$
          则有：\lim_{x \to a} \frac{f(x)}{g(x)} = \lim_{x \to a} \frac{f'(x)}{g'(x)}
          $$
           - $$
             当 x \to a 时，函数 f(x) 以及 g(x) 都趋于 0
             $$
           - $$
             在点a的某去心邻域内，函数f'(x) 以及 g'(x) 都存在且g(x) \ne 0
             $$
           - $$
             \lim_{x\to a} \frac{f'(x)}{g'(x)} 存在(或为无穷大)
             $$
        - 拉格朗日中值定理
          - 特点：一个函数减去另外一个函数
          
        - 泰勒公式
          - $$
            \begin{align*}
            & f(x) = f(a) + f'(a)(x-a) + \frac{f''(a)}{2!}(x-a)^2 + \cdots + \frac{f^{(n)}(a)}{n!}(x-a)^n + R_n(x) \\
            & e^x = 1+x+\frac{x^2}{2!} + \frac{x^3}{3!} + \frac{x^4}{4!} + \cdots + \frac{x^n}{n!} + R_n(x) \\
            & \ln(1+x) = x - \frac{x^2}{2} + \frac{x^3}{3} - \frac{x^4}{4} + \cdots + \frac{x^n}{n} + R_n(x) \\
            & \frac{1}{1+x} = 1 - x + x^2 - x^3 + \cdots + x^n + R_n(x) \\
            & \frac{1}{1-x} = 1 + x + x^2 + x^3 + \cdots + x^n + R_n(x) \\
            & \frac{1}{1+x^2} = 1 - x^2 + x^4 - x^6 + \cdots + x^n + R_n(x) \\
            & \arctan x = x - \frac{1}{3}x^3 + \frac{1}{5}x^5 - \frac{1}{7}x^7 + \cdots + x^n + R_n(x) \\
            & \sin x = x - \frac{x^3}{3!} + \frac{x^5}{5!} - \frac{x^7}{7!} + \cdots + \frac{x^{2n+1}}{2n+1!} + R_n(x) \\
            & \cos x = 1 - \frac{x^2}{2!} + \frac{x^4}{4!} - \frac{x^6}{6!} + \cdots + \frac{x^{2n}}{2n!} + R_n(x) \\
            & \tan x = x + \frac{1}{3}x^3 + \frac{2}{15}x^5 + \frac{17}{315}x^7 + \cdots + R_n(x) \\
            \end{align*}
            $$
        - 掌握常用的等价无穷小代换
          |||
          |---|---|
          |$\tan x$|$x$|
          |$\arcsin x$|$x$|
          |$a^x - 1$|$x\ln{a}$|
          |$(1 + x)^a - 1$|$ax$|
          
      - ==极限求解思路==
        - 求解极限三步骤：代入、分类、化解(抓致0因子,抓大头，泰勒展开，洛必达)
      - 例题
        - 掌握无穷大变量的大小关系
            $$
            \begin{align*}
            \lim_{x \to 0} \frac{\ln(\cos x)}{x^2}
            &= \lim_{x \to 0} \ln(\cos x)^{\frac{1}{x^2}}\\
            &= \lim_{x \to 0} \ln(1 + \cos x - 1)^{\frac{1}{x^2}}\\
            &= \lim_{x \to 0} \ln(1 + \cos x - 1)^{(\cos x - 1)\frac{1}{x^2(\cos x - 1)}}\\
            &= \lim_{x \to 0} \frac{1}{x^2(\cos x - 1)}\\
            \end{align*}
            $$ 
            $$
            \begin{align*}
            \lim_{x \to 0} (\cos x)^{\frac{1}{x^2}}
            &= \lim_{x \to 0} e^{{\frac{1}{x^2}}\ln {(1 + \cos x - 1)}}\\
            &= \lim_{x \to 0} e^{{\frac{\cos x - 1}{x^2}}\ln {(1 + \cos x - 1)^{\frac{1}{\cos x - 1}}}}\\
            &= e^{-\frac{1}{2}}
            \end{align*}
            $$ 
            $$
            \begin{align*}
            \lim_{x \to 0} (\cos x)^{\frac{1}{x^2}}
            &= \lim_{x \to 0} (1 + \cos x - 1)^{\frac{1}{\cos x - 1}\frac{\cos x - 1}{x^2}} \\
            &= \lim_{x \to 0} e^{\frac{\cos x - 1}{x^2}} \\
            &= e^{-\frac{1}{2}}
            \end{align*}
            $$ 
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
        - 介值定理：设函数$f(x)$在闭区间$[a,b]$上连续，且在这区间的端点取不同的函数值：$f(a) = A, f(b)=B$，则对于A与B之间的任意一个$C$ ，在闭区间$[a,b]$内至少存在一个点$\xi$，使得$f(\xi) = C(a < \xi < b)$
      - 例题
        - $$
          \begin{align*}
          求 f(x) = \frac{x^2 -1}{x^2 - 3x + 2} 间断点
          \end{align*}
          $$
    - 求渐近线
      - **垂直渐近线**（铅直渐近线）：若 $\lim_{x \to x_0} f(x) = \infty$，则 $x = x_0$ 是垂直渐近线
        - 找法：分母为零但分子不为零的点（函数的无定义点），如 $f(x) = \dfrac{1}{x-1}$，$x=1$ 为垂直渐近线
        - 需要分别检查 $x \to x_0^-$ 和 $x \to x_0^+$，只要一侧趋于 $\infty$ 就算
      - **水平渐近线**：若 $\lim_{x \to +\infty} f(x) = b$ 或 $\lim_{x \to -\infty} f(x) = b$，则 $y = b$ 是水平渐近线
        - 需要左右两侧（$+\infty$ 和 $-\infty$）分别检查，两侧渐近线可以不同
        - 分子分母同次有理函数：水平渐近线 $y = \dfrac{\text{最高次系数比}}{}$
      - **斜渐近线**：若 $\lim_{x \to \infty} \dfrac{f(x)}{x} = a \ (a \neq 0)$ 且 $\lim_{x \to \infty}\big[f(x) - ax\big] = b$，则 $y = ax + b$ 是斜渐近线
        - 找法：先求斜率 $a = \lim_{x \to \infty} \dfrac{f(x)}{x}$，再求截距 $b = \lim_{x \to \infty}\big[f(x) - ax\big]$
        - 水平渐近线是斜渐近线 $a = 0$ 的特例；存在水平渐近线时就不会再有斜渐近线
      - **做题步骤**：
        - 0. **求定义域**：先确定 $f(x)$ 的定义域（分母 $\neq 0$、根号内 $\ge 0$、$\ln$ 真数 $> 0$ 等），无定义点即垂直渐近线的候选
        - 1. 找无定义点，逐个检查 $\lim f(x) = \infty$？→ 垂直渐近线
        - 2. 分别求 $\lim_{x \to \pm\infty} f(x)$ → 水平渐近线
        - 3. 若 $x \to \infty$ 时 $f(x)$ 无水平极限，再求 $a = \lim \frac{f(x)}{x}$、$b = \lim[f(x)-ax]$ → 斜渐近线
    - 导数与微分
      - 导数基本定义
        定义
        $$
        dy/dx=\lim_{\Delta x \to 0}\frac{\Delta y}{\Delta x}
        $$
      - 导数性质
        可导一定连续，连续不一定可导
      - 导数基本运算
        - $$
          \begin{align*}
          \frac {\Delta y}{\Delta x} &= \lim_{\Delta x \to 0} \frac{\sin (x + \Delta x) - \sin x}{\Delta x} \\
          &= \lim_{\Delta x \to 0} \frac{\sin x \cos \Delta x + \cos x \sin \Delta x - \sin x}{\Delta x}\\
          &= \lim_{\Delta x \to 0} \frac{\sin x (\cos \Delta x - 1 )+ \cos x \sin \Delta x}{\Delta x}\\
          &= \lim_{\Delta x \to 0} \frac{-2\sin x \sin^2 \frac{\Delta x}{2} + \cos x \sin \Delta x}{\Delta x}\\
          &= \lim_{\Delta x \to 0} \frac{-2\sin x \sin^2 \frac{\Delta x}{2}}{\Delta x} + \lim_{\Delta x \to 0} \frac{\cos x \sin \Delta x}{\Delta x}\\
          &= \lim_{\Delta x \to 0} -\frac{\sin x \sin^2 \frac{\Delta x}{2}}{\frac{\Delta x}{2}} + \lim_{\Delta x \to 0} \frac{\cos x \sin \Delta x}{\Delta x}\\
          &= \lim_{\Delta x \to 0} -\sin x \sin \frac{\Delta x}{2} + \lim_{\Delta x \to 0} \frac{\cos x \sin \Delta x}{\Delta x}\\
          &= \cos x \\
          \end{align*}
          $$
        - $$
          \begin{align*}
          \frac {\Delta y}{\Delta x} &= \lim_{\Delta x \to 0} \frac{\cos (x + \Delta x) - \cos x}{\Delta x} \\
          &= \lim_{\Delta x \to 0} \frac{\cos x \cos \Delta x - \sin x \sin \Delta x - \cos x}{\Delta x}\\
          &= \lim_{\Delta x \to 0} \frac{\cos x (\cos \Delta x - 1 )- \sin x \sin \Delta x}{\Delta x}\\
          &= \lim_{\Delta x \to 0} \frac{-2\cos x \sin^2 \frac{\Delta x}{2} - \sin x \sin \Delta x}{\Delta x}\\
          &= \lim_{\Delta x \to 0} \frac{-2\cos x \sin^2 \frac{\Delta x}{2}}{\Delta x} - \lim_{\Delta x \to 0} \frac{\sin x \sin \Delta x}{\Delta x}\\
          &= \lim_{\Delta x \to 0} \frac{-\cos x \sin^2 \frac{\Delta x}{2}}{\frac{\Delta x}{2}} - \lim_{\Delta x \to 0} \frac{\sin x \sin \Delta x}{\Delta x}\\
          &= \lim_{\Delta x \to 0} -\cos x \sin \frac{\Delta x}{2} - \lim_{\Delta x \to 0} \frac{\sin x \sin \Delta x}{\Delta x}\\
          &= -\sin x \\
          \end{align*}
          $$
        - $$
          \begin{align*}
          \frac {\Delta y}{\Delta x} &= \lim_{\Delta x \to 0} \frac{e^{x + \Delta x} - e^x}{\Delta x} \\
          &= \lim_{\Delta x \to 0} \frac{e^{x}(e^{\Delta x} - 1)}{\Delta x}\\
          &= e^{x}
          \end{align*}
          $$
        - $$
          \begin{align*}
          \frac {\Delta y}{\Delta x} &= \lim_{\Delta x \to 0} \frac{a^{x + \Delta x} - a^x}{\Delta x} \\
          &= \lim_{\Delta x \to 0} \frac{a^{x}(a^{\Delta x} - 1)}{\Delta x}\\
          &= \lim_{\Delta x \to 0} \frac{a^{x}(e^{{\Delta x}ln a} - 1)}{\Delta x}\\
          &= a^{x}\ln a
          \end{align*}
          $$
        - $$
          \begin{align*}
          \frac {\Delta y}{\Delta x} &= \lim_{\Delta x \to 0} \frac{a^{x + \Delta x} - a^x}{\Delta x} \\
          &= \lim_{\Delta x \to 0} \frac{a^{x}(a^{\Delta x} - 1)}{\Delta x}\\
          &= \lim_{\Delta x \to 0} \frac{a^{x}(e^{{\Delta x}ln a} - 1)}{\Delta x}\\
          &= a^{x}\ln a
          \end{align*}
          $$
        - $$
          \begin{align*}
          \frac {\Delta y}{\Delta x} &= \lim_{\Delta x \to 0} \frac{\log_a^{x + \Delta x} - \log_a^x}{\Delta x} \\
          &= \lim_{\Delta x \to 0} \frac{\log_a^{1 + \frac{\Delta x}{x}}}{\Delta x} \\
          &= \lim_{\Delta x \to 0} \frac{\log_a^{(1 + \frac{\Delta x}{x})^{\frac{x}{\Delta x}\times{\frac{\Delta x}{x}}}}}{\Delta x} \\
          &= \lim_{\Delta x \to 0} \frac{{\frac{\Delta x}{x}}\log_a^{(1 + \frac{\Delta x}{x})^{\frac{x}{\Delta x}}}}{\Delta x} \\
          &= \lim_{\Delta x \to 0} \frac{{\frac{1}{x}}\log_a^{(1 + \frac{\Delta x}{x})^{\frac{x}{\Delta x}}}}{1} \\
          &= \lim_{\Delta x \to 0} {\frac{1}{x}}\log_a^{(1 + \frac{\Delta x}{x})^{\frac{x}{\Delta x}}} \\
          &= {\frac{1}{x}}\log_a^{e} \\
          &= {\frac{1}{x\ln^a}} \\
          \end{align*}
          $$
        - $$
          \begin{align*}
          \frac {\Delta y}{\Delta x} &= \lim_{\Delta x \to 0} \frac{(x+ \Delta x)^{n} - x^n}{\Delta x} \\
          &= \lim_{\Delta x \to 0} \frac{x^n + nx^{n -1}\Delta x - x^n}{\Delta x}\\
          &= nx^{n -1}
          \end{align*}
          $$
      - 基本求导公式
        - 常数：$(C)' = 0$
        - 幂函数：$(x^n)' = n x^{n-1}$
        - 三角函数：
          $(\sin x)' = \cos x$,
          $(\cos x)' = -\sin x$,
          $(\tan x)' = \sec^2 x$,
          乘除法法则
          $(\cot x)' = -\csc^2 x$,
          $(\sec x)' = \sec x \tan x$,
          $(\csc x)' = -\csc x \cot x$
        - 指数函数：$(a^x)' = a^x \ln a$，$(e^x)' = e^x$
        - 对数函数：$(\log_a x)' = \frac{1}{x \ln a}$，$(\ln |x|)' = \frac{1}{x}$
        - 反三角函数：
          $(\arcsin x)' = \frac{1}{\sqrt{1 - x^2}}$,
          $x = \sin y$,
          $(\arccos x)' = -\frac{1}{\sqrt{1 - x^2}}$,
          $(\arctan x)' = \frac{1}{1 + x^2}$,
          $x = \tan y$,
          $(\operatorname{arccot} x)' = -\frac{1}{1 + x^2}$
      - 运算法则
        如果函数$f(x)$与$g(x)$各自存在导数，则有：
        $$
        \begin{align*}
        & [f(x) \pm g(x)]' = f'(x) + g'(x) \\
        & \left[f(x) \cdot g(x) \right]' = f'(x)g(x) + f(x)g'(x) \\
        & 连乘每个项单独求个导 加在一起,多项相乘也一样 \\
        & (uvw)' = u'vw + uv'w + uvw'\\
        & \left[\frac{f(x)}{g(x)}\right]' = \frac{f'(x)g(x) - f(x)g'(x)}{g^2(x)} (g(x)\ne 0)
        \end{align*}
        $$
        
      - 复合函数求导
        如果函数$f(x)$ 与 $g(x)$ 各自存在导数，则有：$[f(g(x))]' = f'(g(x))\cdot g'(x)$
      - 隐函数求导
      - 参数方程求导
      - 反函数求导
        - 已知$y=f(x)$,且$f(x)$有对应的反函数$g(x)=f^{-1}(x)$,有$x=g(y)$,试用$g(x)、g'(x)、g''(x)$来分别表示$\frac{\mathrm{d}y}{\mathrm{d}x}$和$\frac{\mathrm{d}^2y}{\mathrm{d}x^2}$ 
      - 高阶导数
        - 莱布尼茨公式：如果函数$u(x)、v(x)$分别具有n阶导数，那么两者乘积的$n$阶导数为如下形式：
          $$
          \begin{align*}
          [u(x)\cdot v(x)]^{(n)} = C_n^0u^nv + C_n^1u^{(n-1)}v' + C_n^2u^{(n-2)}v'' + \cdots + C_n^{n-1}u'v^{(n-1)} + C_n^nvu^{(n)}
          \end{align*}
          $$
      - 例题
        - $$
          \begin{align*}
          & y = \frac{e^x}{x^2} + ln3 \\
          & y' = e^xx^{-2} - e^x2x^{-3} \\
          & y' = \frac{e^xx^{2} - e^x2x^{1}}{x^4}
          \end{align*}
          $$
        - $$
          \begin{align*}
          & y = x^2\ln x\cos x \\
          & y' = 2x\ln x\cos x + x^2(\ln x \cos x)' \\
          & y' = 2x\ln x\cos x + x^2(\frac{1}{x}\cos x - \ln x\sin x) \\
          连乘每个项单独求个导
          \end{align*}
          $$
        - 判断函数$y = \sqrt[3]{x}\sin x$ 在 $x =0$ 处是否可导
          $$
          \begin{align*}
          lim_{x \to 0} \frac{\sqrt[3]x - 0}{x}&= \\
          &= lim_{x \to 0} \sqrt[3]{x^2}
        - 已知函数$f(x)$在$x=0$处可导，且$f(0)=1$，$f'(0)=2$，求$lim_{x \to 0} \frac{f(x) - e^x}{\sin x}$
          $$
          \begin{align*}
          =& lim_{x \to 0} \frac{f(x) - e^x}{\sin x} \\
          =& lim_{x \to 0} \frac{f(x) - e^x}{x} \frac{x}{\sin x}\\
          =& lim_{x \to 0} \frac{f(x) - 1 - (e^x - 1)}{x} \frac{x}{\sin x}\\
          =& lim_{x \to 0} (\frac{f(x) - 1}{x} - \frac{e^x - 1}{x} )\frac{x}{\sin x}\\
          =& lim_{x \to 0} (2 - 1)1 \\
          =& 1
          \end{align*}
          $$
        - 已知连续函数$f(x)$有 $lim_{x \to 1} \frac{f(x)}{x^3 -1 } = 1$, 求 $x=1$处的函数切线
          $$
          \begin{align*}
          =& lim_{x \to 1} \frac{f(x)}{x^3 -1 } = 1\\
          =& lim_{x \to 1} \frac{f(x)}{(x - 1)(x^2 + x + 1) } = 1\\
          =& lim_{x \to 1} \frac{f(x) - f(1)}{(x - 1)(x^2 + x + 1) } = 1\\
          =& lim_{x \to 1} \frac{f(x) - f(1)}{(x - 1)} \frac{1}{(x^2 + x + 1) } = 1\\
          =& lim_{x \to 1} \frac{f(x) - f(1)}{(x - 1)} \frac{1}{3} = 1\\
          =& lim_{x \to 1} \frac{f(x) - f(1)}{(x - 1)} = 3\\
          (1,0)
          \end{align*}
          $$
    - 导数与微分的应用
      - 基于微分的近似计算
        $$
        \begin{align*}
        & \mathrm{d}y = y'\mathrm{d}x \\
        & \mathrm{d}(u\pm v) = \mathrm{d}u \pm \mathrm{d}v \\
        & \mathrm{d}(Cu) = C\mathrm{d}u \\
        & \mathrm{d}(uv) =  v\mathrm{d}u + u\mathrm{d}v \\
        & \mathrm{d}\left(\frac{u}{v}\right) = \frac{v\mathrm{d}u - u{\mathrm{d}v}}{v^2} (v\ne 0)
        \end{align*}
        $$
      - 相关变化率问题
        - 列等式，然后注入动态信息
        - 一个路灯高为5.4m，人高1.8m， 当人以2m/s的速度径直朝远离路灯的方向移动时，人影子头顶部分的移动速度时多少？
          $$
          \begin{align*}
          & \frac {\mathrm{d}x_1}{\mathrm{d}t} = 2 \\
          & \frac{x_2}{x_2 - x_1} = 3 \\
          & {x_2} = 3x_2 - 3x_1 \\
          & \frac{2}{3}{x_2} = x_1 \\
          & \frac{2}{3}\frac {\mathrm{d}x_2}{\mathrm{d}t} = 2 \\
          & \frac {\mathrm{d}x_2}{\mathrm{d}t} = 3 \\
          \end{align*}
          $$
      - 函数单调性 凹凸性
        - 步骤
          导数存在或者不存在
          求正负
          一阶导数为0 ，二阶导数正负
        - 单调性
          - 驻点
          - 极值点
            - 一阶导数导数为0或者不存在
              $$
              \begin{align*}
              & 设函数f(x)在点x_0的某邻域U(x_0)内有定义，如果对于去心邻域内的任一x，有 \\
              & f(x) < f(x_0) 或 f(x) > f(x_0) \\
              & 那么就称f(x_0)是函数f(x)的一个极大值 或 极小值 \\
              & 函数f(x)在点x_0 处可导，且在该点处取得极值，则有f'(x_0) = 0 \\
              & 判断极值点的方法： \\
              & 一阶导数：在某一点处一阶导数为0，且在该点左右区间的导数异号 \\
              & 二阶导数：在某一点处一阶导数为0，二阶导为正则取极小值，二阶导为负则取极大值 \\
              \end{align*}
              $$
          - 最值点
        - 凹凸性
          - 拐点
            - $$
              \begin{align*}
              & 设f(x) 在[a,b]上连续，在(a,b)内具有一阶和二阶导数，那么 \\
              & 1.若在(a,b)内f''(x) > 0, 则f(x)在[a,b]上的图形是凹的 \\
              & 2.若在(a,b)内f''(x) < 0, 则f(x)在[a,b]上的图形是凸的 \\
              & 如果曲线y=f(x)在经过点(x_0,f(x_0))时，曲线的凹凸性改变了，那么就称点(x_0,f(x_0))为这曲线的拐点
              \end{align*}
              $$
        - $$
          \begin{align*}
          & 设函数 y=f(x) 在[a,b] 上连续，在(a,b)内可导 \\
          & 如果在(a,b)内f'(x) \ge 0, 则称f(x)在[a,b]上单调递增 \\
          & 如果在(a,b)内f'(x) \le 0, 则称f(x)在[a,b]上单调递减 \\
          \end{align*}
          $$
      - 曲率(数12)
        - **定义**：曲率 $K$ 描述曲线弯曲的程度，越大弯得越厉害
          - 直线：$K = 0$（不弯）
          - 圆：$K = \dfrac{1}{r}$（半径越小，弯得越厉害）
        - **曲率公式**（$y = f(x)$ 显式方程）：
          $$K = \frac{|y''|}{\left(1 + y'^2\right)^{3/2}}$$
        - **参数方程** $\begin{cases} x = x(t) \\ y = y(t) \end{cases}$ 的曲率：
          $$K = \frac{|x'y'' - y'x''|}{\left(x'^2 + y'^2\right)^{3/2}}$$
        - **曲率半径**：$R = \dfrac{1}{K} \ (K \neq 0)$，即与该点弯曲程度相同的圆（密切圆）的半径
          - $R$ 越大，曲线越平坦；$R$ 越小，弯得越急
        - **曲率中心与密切圆**：过该点且与曲线在该点相切、曲率相同的圆，圆心称为曲率中心
    - 不定积分
      - 积分的本质以及牛顿-莱布尼茨公式
        - $$
          \begin{align*}
          & \int_a^b f(x) \, dx = F(b) - F(a) \\
          & \text{其中 } F(x) \text{ 是 } f(x) \text{ 的原函数}
          \end{align*}
          $$
      - 不定积分的基本求解方法
        $$
        \begin{align*}
        & \int k \,\mathrm{d}x = kx + C \\
        & \int x^\mu \,\mathrm{d}x = \frac{x^{\mu+1}}{\mu+1} + C \quad (\mu \neq -1) \\
        & \int \frac{1}{x} \,\mathrm{d}x = \ln|x| + C \\
        & \int e^x \,\mathrm{d}x = e^x + C \\
        & \int a^x \,\mathrm{d}x = \frac{a^x}{\ln a} + C \\
        & \int \sin x \,\mathrm{d}x = -\cos x + C \\
        & \int \cos x \,\mathrm{d}x = \sin x + C \\
        & \int \sec^2 x \,\mathrm{d}x = \tan x + C \\
        & \int \csc^2 x \,\mathrm{d}x = -\cot x + C \\
        & \int \sec x \tan x \,\mathrm{d}x = \sec x + C \\
        & \int \csc x \cot x \,\mathrm{d}x = -\csc x + C \\
        & \int \sec x \,\mathrm{d}x = \ln|\sec x + \tan x| + C \\
        & \int \csc x \,\mathrm{d}x = \ln|\csc x - \cot x| + C \\
        & \int \frac{1}{\sqrt{1 - x^2}} \,\mathrm{d}x = \arcsin x + C \\
        & \int \frac{1}{1 + x^2} \,\mathrm{d}x = \arctan x + C \\

        & \int [f(x) \pm g(x)] \,\mathrm{d}x = \int f(x) \,\mathrm{d}x \pm \int g(x) \,\mathrm{d}x \\
        & \int kf(x)\mathrm d x = k \int f(x) \mathrm d x(x \ne 0) \\

        & \int \frac{1}{x^2 + a^2} \mathrm d x \\
        &= \frac{1}{a^2}\int \frac{1}{(\frac{x}{a})^2 + 1} \mathrm d x \\
        &= \frac{1}{a} \arctan(\frac{x}{a}) + C \\
        & \int \frac{1}{\sqrt {a^2 - x^2}} \mathrm d x \\
        &=\frac{1}{|a|} \int \frac{1}{\sqrt {1 - (\frac{x}{a})^2}} \mathrm d x \\ 
        &= \arcsin\frac{x}{|a|} + C
        \end{align*}
        $$
      - 凑微分法：找到一部分作为另一部分的导数
        - $\mathrm d y = y' \mathrm d x$
        - $$
          \begin{align*}
          & 三角积分函数中的凑微分小技巧，若被积函数表达式R(\sin x, \cos x)存在下列条件： \\
          & R(-\sin x, \cos x) = -R(\sin x, \cos x), 凑出\sin x \mathrm d x = -\mathrm d \cos x \\
          & R(\sin x, -\cos x) = -R(\sin x, \cos x), 凑出\cos x \mathrm d x = \mathrm d \sin x \\
          & R(-\sin x, -\cos x) = R(\sin x, \cos x), 凑出\sec^2 x \mathrm d x = \mathrm d \tan x

          \end{align*}
          $$
      - 有关根号的常见处理：第二类换元法
        - $$
          \begin{align*}
          & \sqrt {2x + 1} = t \\
          & \sqrt[3] {x} = t \\
          & \sqrt {e^x + 1} = t \\
          \end{align*}
          $$
        - 三角代换（利用直角三角形，新老变量取值范围要写出来）：
          $$
          \begin{array}{c|c|c|c}
          \text{被积函数含} & \text{令 } x = & \mathrm{d}x = & \text{根号化为} \\
          \hline
          \sqrt{a^2 - x^2} & a\sin\theta & a\cos\theta\,\mathrm{d}\theta & a\cos\theta \\
          \sqrt{a^2 + x^2} & a\tan\theta & a\sec^2\theta\,\mathrm{d}\theta & a\sec\theta \\
          \sqrt{x^2 - a^2} & a\sec\theta & a\sec\theta\tan\theta\,\mathrm{d}\theta & a\tan\theta
          \end{array}
          $$
        - 直角三角形示意图：

          <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 840 200" width="100%" height="200">
            <defs>
              <marker id="arrow" markerWidth="6" markerHeight="6" refX="6" refY="3" orient="auto">
                <path d="M0,0 L6,3 L0,6 Z" fill="#333"/>
              </marker>
            </defs>

            <!-- 第1个: sqrt(a^2-x^2) -->
            <g transform="translate(40,20)">
              <polygon points="0,140 200,140 200,60" fill="#FFD700" stroke="#333" stroke-width="2"/>
              <rect x="185" y="140" width="15" height="15" fill="#fff" stroke="#333" stroke-width="1" transform="rotate(0,192,147)"/>
              <path d="M 0,140 L 15,125" fill="none" stroke="#333" stroke-width="1.5"/>
              <text x="100" y="160" text-anchor="middle" font-size="16">√(a²-x²)</text>
              <text x="210" y="100" text-anchor="start" font-size="16">x</text>
              <text x="80" y="85" text-anchor="middle" font-size="16">a</text>
              <text x="15" y="130" text-anchor="middle" font-size="14" fill="#666">θ</text>
              <text x="100" y="180" text-anchor="middle" font-size="12" fill="#888" font-style="italic">x = a sinθ</text>
              <text x="100" y="195" text-anchor="middle" font-size="13" font-weight="bold">√(a²-x²) 型</text>
            </g>

            <!-- 第2个: sqrt(a^2+x^2) -->
            <g transform="translate(320,20)">
              <polygon points="0,140 160,140 160,70" fill="#FFD700" stroke="#333" stroke-width="2"/>
              <rect x="145" y="140" width="15" height="15" fill="#fff" stroke="#333" stroke-width="1"/>
              <path d="M 0,140 L 15,128" fill="none" stroke="#333" stroke-width="1.5"/>
              <text x="80" y="160" text-anchor="middle" font-size="16">a</text>
              <text x="170" y="105" text-anchor="start" font-size="16">x</text>
              <text x="60" y="85" text-anchor="middle" font-size="16">√(a²+x²)</text>
              <text x="15" y="130" text-anchor="middle" font-size="14" fill="#666">θ</text>
              <text x="80" y="180" text-anchor="middle" font-size="12" fill="#888" font-style="italic">x = a tanθ</text>
              <text x="80" y="195" text-anchor="middle" font-size="13" font-weight="bold">√(a²+x²) 型</text>
            </g>

            <!-- 第3个: sqrt(x^2-a^2) -->
            <g transform="translate(600,20)">
              <polygon points="0,140 130,140 130,75" fill="#FFD700" stroke="#333" stroke-width="2"/>
              <rect x="115" y="140" width="15" height="15" fill="#fff" stroke="#333" stroke-width="1"/>
              <path d="M 0,140 L 15,128" fill="none" stroke="#333" stroke-width="1.5"/>
              <text x="65" y="160" text-anchor="middle" font-size="16">a</text>
              <text x="140" y="110" text-anchor="start" font-size="16">√(x²-a²)</text>
              <text x="45" y="85" text-anchor="middle" font-size="16">x</text>
              <text x="15" y="130" text-anchor="middle" font-size="14" fill="#666">θ</text>
              <text x="65" y="180" text-anchor="middle" font-size="12" fill="#888" font-style="italic">x = a secθ</text>
              <text x="65" y="195" text-anchor="middle" font-size="13" font-weight="bold">√(x²-a²) 型</text>
            </g>
          </svg>
      - 分部积分：用于处理多种类型函数组合搭配
        - $$
          \int u\mathrm d v = uv - \int v\mathrm d u
          $$
      - 特定类型的积分：有理分式积分
        - 变真分式
        - 拆分母 留数法 （乘分母，分母为0）
      - 例题
        - $$
          \begin{align*}
          & \int e^x(3 - \frac{e^{-x}}{\sqrt{x}}) \mathrm d x \\
          &= \int 3e^x - \frac{1}{\sqrt{x}} \mathrm d x \\
          &= 3\int e^x\mathrm d x - \int\frac{1}{\sqrt{x}} \mathrm d x \\
          &= 3e^x - 2x^{\frac{1}{2}} + C\\
          \end{align*}
          $$
        - $$
          \begin{align*}
          & \int \cos^{2}\frac{x}{2} \mathrm d x \\
          &= \int \frac{\cos x + 1}{2} \mathrm d x \\
          &= \int \frac{\cos x}{2} \mathrm d x  + \int \frac{1}{2} \mathrm d x \\
          &= \frac{\sin x}{2} + \frac{x}{2} + C
          \end{align*}
          $$
        - $$
          \begin{align*}
          & \int \frac{1}{3x + 2} \mathrm d x \\
          &= \frac{1}{3} \int \frac{1}{3x + 2} \cdot 3 \mathrm d x \\
          &= \frac{1}{3} \ln|3x + 2| + C
          \end{align*}
          $$
        - $$
          \begin{align*}
          & \int \frac{3x - 1}{x^2 - 2x - 3} \mathrm d x \\
          &=  \int \frac{2x - 2 + x + 1}{x^2 - 2x - 3} \mathrm d x \\
          &=  \int \frac{2x - 2}{x^2 - 2x - 3} \mathrm d x + \int \frac{x + 1}{x^2 - 2x - 3} \mathrm d x \\
          &=  \ln|x^2 - 2x - 3| + \int \frac{1}{x - 3} \mathrm d x + C \\
          &=  \ln|x^2 - 2x - 3| + \ln|x - 3| + C\\
          \end{align*}
          $$
        - $$
          \begin{align*}
          & \int \frac{1}{x^2 + 4x + 5} \mathrm d x \\
          &=  \int \frac{1}{(x+2)^2 + 1} \mathrm d x \\
          &= \arctan (2+x) + C
          \end{align*}
          $$
        - $$
          \begin{align*}
          & \int \frac{1}{x^2 + a^2} \mathrm d x \\
          &= \frac{1}{a^2}\int \frac{1}{(\frac{x}{a})^2 + 1} \mathrm d x \\
          &= \frac{1}{a} \arctan(\frac{x}{a}) + C
          \end{align*}
          $$
        - $$
          \begin{align*}
          & \int \frac{1}{\sqrt {a^2 - x^2}} \mathrm d x \\
          &=\frac{1}{|a|} \int \frac{1}{\sqrt {1 - (\frac{x}{a})^2}} \mathrm d x \\ 
          &= \arcsin\frac{x}{|a|} + C
          \end{align*}
          $$
    - 定积分
      - 定积分的含义与基本性质
        - 与变量无关
      - 定积分运算
        - 奇偶性
        - $$
          \int_a^{b} f(x) \,\mathrm{d}x 
          =\int_a^{b} f(a+b-x) \,\mathrm{d}x 
          $$
        - 华莱士（Wallis）公式（点火公式）
          $$
          \int_0^{\frac{\pi}{2}} \sin^n x \,\mathrm{d}x 
          = \int_0^{\frac{\pi}{2}} \cos^n x \,\mathrm{d}x 
          = 
          \begin{cases}
            \displaystyle \frac{n-1}{n} \cdot \frac{n-3}{n-2} \cdots \frac{1}{2} \cdot \frac{\pi}{2}, & n \text{ 为偶数} \\[8pt]
            \displaystyle \frac{n-1}{n} \cdot \frac{n-3}{n-2} \cdots \frac{2}{3} \cdot 1, & n \text{ 为奇数}
          \end{cases}
          $$
      - 变上限积分
        - $$
          \int_0^x f(t) \mathrm{d}t = f(x) \\
          \int_0^x e^{t^2} \mathrm{d}t \quad S'(x)=e^{x^2} \\
          \int_0^{\sin x} e^{t} \mathrm{d}t \quad S'(x)=e^{\sin x}\cos x \\
          \int_0^{x} xe^{t} \mathrm{d}t \quad S'(x)=x'\int_0^{x} xe^{t} \mathrm{d}t + x\left(\int_0^{x} xe^{t} \mathrm{d}t \right)'\\
          \int_0^x \sin(x+t)\mathrm d t \quad u=x+t \quad \int_x^{2x} \sin(u)\mathrm d u \quad S'=2\sin 2x - \sin x
          $$
      - 广义积分
        - $$
          \int_a^b f(x) \,\mathrm{d}x \quad a,b固定，存在c \in [a,b]使得 \lim_{x\to c} f(x)= \infty \\
          \int_a^{+\infty} f(x) \,\mathrm{d}x  \\
          \int_{-\infty}^a f(x) \,\mathrm{d}x  \\
          \int_{-\infty}^{+\infty} f(x) \,\mathrm{d}x  \\
          $$
        - $p$ 积分的敛散性（$x^p$ 的广义积分判据）
          $$
          \begin{aligned}
          &\int_0^1 \frac{1}{x} \,\mathrm{d}x \quad &\text{发散（} \ln x \to -\infty \text{）}\\[4pt]
          &\int_0^1 \frac{1}{x^2} \,\mathrm{d}x \quad &\text{发散（} -\frac{1}{x} \to \infty \text{）}\\[4pt]
          &\int_0^1 \frac{1}{\sqrt{x}} \,\mathrm{d}x \quad &p=\tfrac{1}{2}<1,\ \text{收敛}=2\\[4pt]
          &\int_1^{+\infty} \frac{1}{x} \,\mathrm{d}x \quad &\text{发散（} \ln x \to +\infty \text{）}\\[4pt]
          &\int_1^{+\infty} \frac{1}{x^2} \,\mathrm{d}x \quad &p=2>1,\ \text{收敛}=1\\[4pt]
          &\int_1^{+\infty} \frac{1}{\sqrt{x}} \,\mathrm{d}x \quad &p=\tfrac{1}{2}<1,\ \text{发散（} 2\sqrt{x} \to +\infty \text{）}
          \end{aligned}
          $$
      - 积分应用 旋转体体积
          $$
          \begin{aligned}
          &\int_a^b \pi f^2(x) \mathrm{d}x\\[4pt]
          \end{aligned}
          $$
      - 利用定积分进行数列求和
        $$
        \begin{aligned}
        &\int_3^5 x^2 \mathrm{d}x = \\[4pt]
        \end{aligned}
        $$
    - 常微分方程
      - 一阶微分方程
        - 分离变量法 一阶线性齐次微分方程
          $$
          \begin{aligned}
          & y' = 2xy \\
          & \frac{\mathrm{d}y}{\mathrm{d}x} = 2xy \\
          & \frac{\mathrm{d}y}{y} = 2x\mathrm{d}x \\
          & \int\frac{\mathrm{d}y}{y} = \int 2x\mathrm{d}x \\
          & \ln |y| = x^2 + C  \\
          & |y| = e^{x^2 + C} \\
          & y = Ce^{x^2} \\
          \end{aligned}
          $$

          $$
          \boxed{
          \begin{aligned}
          & y' = P(x)y \\
          & y = Ce^{\int P(x)\mathrm{d}x}
          \end{aligned}
          }
          $$
        - 一阶线性非齐次微分方程
          $$
          \begin{aligned}
          & y' + P(x)y = Q(x)\\
          & y = e^{-\int P(x)\mathrm{d}x} \left[\int {Q(x)e^{\int P(x)\mathrm{d}x}}\mathrm{d}x + C\right] \\[6pt]
          \end{aligned}
          $$
          
          **推导过程：**
          $$
          \boxed{
          \begin{aligned}
          &\frac {(e^{\int P(x)\mathrm{d}x} y)'}{e^{\int P(x)\mathrm{d}x}} = Q(x) \\[4pt]
          &{(e^{\int P(x)\mathrm{d}x} y)'} = e^{\int P(x)\mathrm{d}x}Q(x) \\[4pt]
          &(e^{\int P(x)\mathrm{d}x} y) = \int e^{\int P(x)\mathrm{d}x}Q(x) \,\mathrm{d}x + C \\[4pt]
          &y = e^{-\int P(x)\mathrm{d}x} \left[\int {Q(x)e^{\int P(x)\mathrm{d}x}}\,\mathrm{d}x + C\right]
          \end{aligned}
          }
          $$
          
          **说明：**
          1. 积分因子 $e^{\int P(x)\mathrm{d}x}$ 中，$\int P(x)\mathrm{d}x$ **不加绝对值**也不加常数，因为 $e^{\ln|f(x)|} = |f(x)|$ 带绝对值反而麻烦，且积分因子只需一个特解，正负号可被后续常数 $C$ 吸收。
          2. 通解公式推导中，积分因子里的 $\int P(x)\mathrm{d}x$ **不加 $C$**；最终结果中的 $C$ 来自右边积分，已经够用。
        - 一阶线性非齐次微分方程
          $$
          \begin{aligned}
          &u = \frac{y}{x} \\
          &ax + by + C = U
          \end{aligned}
          $$
      - 二阶微分方程
        - $$
          \begin{aligned}
          &y'' = f(x)
          \end{aligned}
          $$
        - 可降阶的微分方程
          $$
          \begin{aligned}
          &y'' = f(x,y') \\
          &y'' = f(y,y')
          \end{aligned}
          $$
          - $$
            \begin{aligned}
            &(1+x^2)y'' = 2xy' \\
            &令 y'=p, \frac{\mathrm{d}y}{\mathrm{d}x} = p, y'' = \frac{\mathrm{d}p}{\mathrm{d}x} = p'\\
            &(1+x^2)y'' = 2xp \\
            &(1+x^2)p' = 2xp \\
            \end{aligned}
            $$
          - $$
            \begin{aligned}
            &2yy'' + (y')^2 = 0 \\
            &令 y'=p , \frac{\mathrm{d}p}{\mathrm{d}x} = y'' = \frac{\mathrm{d}p}{\mathrm{d}y}\frac{\mathrm{d}y}{\mathrm{d}x}\\
            &2y\frac{\mathrm{d}p}{\mathrm{d}y}p + p^2 = 0 \\
            \end{aligned}
            $$
        - 二阶常系数线性齐次微分方程
          $$
          \begin{aligned}
          &y'' + py' + qy = 0 \\
          &r^2 + pr + q = 0
          \end{aligned}
          $$
          令判别式 $\Delta = p^2 - 4q$，通解分三种情况：
          $$
          y = \begin{cases}
          C_1 e^{r_1 x} + C_2 e^{r_2 x}, & \Delta > 0 \quad (r_1 \neq r_2) \\[6pt]
          (C_1 + C_2 x) e^{r x},           & \Delta = 0 \quad (r_1 = r_2 = r) \\[6pt]
          e^{\alpha x}(C_1 \cos \beta x + C_2 \sin \beta x), & \Delta < 0 \quad (r = \alpha \pm \beta i)
          \end{cases}
          $$
        - 性齐次微分方程
          $$
          y = y_1 \quad y=y_2 都是某个微分方程的解
          y = \begin{cases}
          y = y_1 + y_2 \\[6pt]
          y = Cy_1 \\[6pt]
          y = ay_1 + by_2 \\[6pt]
          \end{cases} \\
          $$
        - 二阶常系数线性非齐次微分方程
          $$
          \begin{aligned}
          &y'' + py' + qy = f(x)
          \end{aligned}
          $$
          解的结构：$y = y_h + y_p$，其中 $y_h$ 为齐次通解，$y_p$ 为非齐次特解。

          待定系数法求 $y_p$（根据 $f(x)$ 形式设解）：
          $$
          \begin{array}{c|c}
          f(x) \text{ 的形式} & y_p \text{ 的试设形式} \\
          \hline
          e^{\lambda x}                      & A e^{\lambda x} \\
          P_n(x)                             & Q_n(x) \\
          P_n(x) e^{\lambda x}               & Q_n(x) e^{\lambda x} x^{\lambda等于通解几个值}\\
          A \cos \beta x + B \sin \beta x    & M \cos \beta x + N \sin \beta x \\
          e^{\alpha x}(A \cos \beta x + B \sin \beta x) & e^{\alpha x}(M \cos \beta x + N \sin \beta x)
          \end{array}
          $$
          注意：若 $y_p$ 的试设形式与齐次解 $y_h$ 的项**重合**，则乘以 $x$（或 $x^k$）以提高次数。
      - 高阶微分方程
  - 空间向量与解析几何
    - 向量点乘（内积）
      $$
      \vec{a} \cdot \vec{b} = a_x b_x + a_y b_y + a_z b_z
      $$
      $$
      \vec{a} \cdot \vec{b} = |\vec{a}| |\vec{b}| \cos \theta
      $$
      结果为一个**数**，用于判断夹角、求投影长度。
    - 向量叉乘（外积）
      $$
      \vec{a} \times \vec{b} =
      \begin{vmatrix}
      \vec{i} & \vec{j} & \vec{k} \\
      a_x & a_y & a_z \\
      b_x & b_y & b_z
      \end{vmatrix}
      = (a_y b_z - a_z b_y,\; a_z b_x - a_x b_z,\; a_x b_y - a_y b_x)
      $$
      或 $|\vec{a} \times \vec{b}| = |\vec{a}| |\vec{b}| \sin \theta$，
      方向满足**右手定则**，垂直于 $\vec{a}$ 和 $\vec{b}$ 所在平面。
      结果为一个**向量**，用于求法向量、面积、力矩。
    - 几何意义对比

      |  | 点乘 $\cdot$ | 叉乘 $\times$ |
      |---|---|---|
      | 结果类型 | 标量 | 向量 |
      | 公式 | $\lVert\vec{a}\rVert \lVert\vec{b}\rVert \cos\theta$ | $\lVert\vec{a}\rVert \lVert\vec{b}\rVert \sin\theta$ |
      | $\theta=90^\circ$ | $=0$（垂直判定） | 最大 |
      | $\theta=0^\circ$   | 最大 | $=0$（平行判定） |
    - 平面的点法式方程
      - 已知平面 $\pi$ 上一点 $M_0(x_0, y_0, z_0)$ 及法向量 $\vec{n} = (A, B, C)$，则平面方程为：

        $$A(x - x_0) + B(y - y_0) + C(z - z_0) = 0$$

        展开得**一般式**：$Ax + By + Cz + D = 0$，其中法向量即为 $\vec{n} = (A, B, C)$。
    - 平面的截距式方程
      - 平面在 $x, y, z$ 轴上的截距分别为 $a, b, c$（$abc \neq 0$），则方程为：

        $$\frac{x}{a} + \frac{y}{b} + \frac{z}{c} = 1$$

        适用于已知三轴截距时快速写出平面方程。

        **推导原理**：

        截距 $a, b, c$ 意味着平面过三点 $(a, 0, 0), (0, b, 0), (0, 0, c)$。设平面一般式 $Ax + By + Cz + D = 0$，代入三点：

        $$\begin{aligned}
        (a, 0, 0) &\text{ 代入：} & A \cdot a + D &= 0 &\Rightarrow A &= -\frac{D}{a} \\[4pt]
        (0, b, 0) &\text{ 代入：} & B \cdot b + D &= 0 &\Rightarrow B &= -\frac{D}{b} \\[4pt]
        (0, 0, c) &\text{ 代入：} & C \cdot c + D &= 0 &\Rightarrow C &= -\frac{D}{c}
        \end{aligned}$$

        将 $A, B, C$ 代回一般式：

        $$-\frac{D}{a}x - \frac{D}{b}y - \frac{D}{c}z + D = 0$$

        $$\Rightarrow D\left(-\frac{x}{a} - \frac{y}{b} - \frac{z}{c} + 1\right) = 0$$

        平面不通过原点时 $D \neq 0$（若 $D=0$ 则平面过原点，截距全为零无意义），两边除以 $D$ 整理得：

        $$\frac{x}{a} + \frac{y}{b} + \frac{z}{c} = 1$$

        > **注意**：截距是**有符号的**，不是距离。例如截距 $a = -3$ 表示平面与 $x$ 轴负半轴相交。
    - 两平面的夹角
      - 设两平面 $\pi_1: A_1x + B_1y + C_1z + D_1 = 0$，$\pi_2: A_2x + B_2y + C_2z + D_2 = 0$，
        法向量分别为 $\vec{n}_1 = (A_1, B_1, C_1)$，$\vec{n}_2 = (A_2, B_2, C_2)$。

        两平面的夹角 $\theta$（锐角）由法向量夹角确定：

        $$\cos\theta = \frac{|\vec{n}_1 \cdot \vec{n}_2|}{\lVert\vec{n}_1\rVert \, \lVert\vec{n}_2\rVert}
        = \frac{|A_1A_2 + B_1B_2 + C_1C_2|}{\sqrt{A_1^{2} + B_1^{2} + C_1^{2}} \, \sqrt{A_2^{2} + B_2^{2} + C_2^{2}}}$$

        - **垂直**：$A_1A_2 + B_1B_2 + C_1C_2 = 0$
        - **平行**：$\displaystyle\frac{A_1}{A_2} = \frac{B_1}{B_2} = \frac{C_1}{C_2}$
    - 空间平面向坐标面的投影面积
      - 设空间平面面积为 $S$，法向量 $\vec{n} = (A, B, C)$，$\alpha, \beta, \gamma$ 为法向量与 $x, y, z$ 轴的夹角。

        法向量的方向余弦：

        $$\cos\alpha = \frac{A}{\sqrt{A^{2}+B^{2}+C^{2}}},\quad
          \cos\beta = \frac{B}{\sqrt{A^{2}+B^{2}+C^{2}}},\quad
          \cos\gamma = \frac{C}{\sqrt{A^{2}+B^{2}+C^{2}}}$$

        投影面积等于原面积乘以平面与投影面夹角的余弦（即法向量与投影面垂直轴的夹角余弦的绝对值）：

        $$\begin{aligned}
        S_{xy} &= S \cdot |\cos\gamma| = S \cdot \frac{|C|}{\sqrt{A^{2}+B^{2}+C^{2}}} \quad &\text{（向 }xOy\text{ 面投影）} \\[6pt]
        S_{yz} &= S \cdot |\cos\alpha| = S \cdot \frac{|A|}{\sqrt{A^{2}+B^{2}+C^{2}}} \quad &\text{（向 }yOz\text{ 面投影）} \\[6pt]
        S_{zx} &= S \cdot |\cos\beta| = S \cdot \frac{|B|}{\sqrt{A^{2}+B^{2}+C^{2}}} \quad &\text{（向 }zOx\text{ 面投影）}
        \end{aligned}$$

        且有关系：$S^{2} = S_{xy}^{2} + S_{yz}^{2} + S_{zx}^{2}$（类比勾股定理在三维空间的推广）。
    - 点到平面的距离
      - 点 $P_0(x_0, y_0, z_0)$ 到平面 $\pi: Ax + By + Cz + D = 0$ 的距离：

        $$d = \frac{|Ax_0 + By_0 + Cz_0 + D|}{\sqrt{A^{2} + B^{2} + C^{2}}}$$

        **推导**：设 $P_1(x_1, y_1, z_1)$ 为平面上一点，则 $Ax_1 + By_1 + Cz_1 + D = 0$。
        距离为 $\overrightarrow{P_1P_0}$ 在法向量 $\vec{n} = (A, B, C)$ 上的投影长度：

        $$d = \frac{|\overrightarrow{P_1P_0} \cdot \vec{n}|}{\lVert\vec{n}\rVert} = \frac{|A(x_0 - x_1) + B(y_0 - y_1) + C(z_0 - z_1)|}{\sqrt{A^{2} + B^{2} + C^{2}}}$$

        利用 $Ax_1 + By_1 + Cz_1 = -D$ 代入即得公式。

        > 分子不加绝对值时，结果的正负号可判断点位于平面的哪一侧。
    - 空间直线的方程
      - **一般式（交面式）**：两平面交线

        $$\begin{cases}
        A_1x + B_1y + C_1z + D_1 = 0 \\
        A_2x + B_2y + C_2z + D_2 = 0
        \end{cases}$$

        方向向量为两法向量的叉乘：$\vec{s} = \vec{n}_1 \times \vec{n}_2$

      - **参数式**：过点 $M_0(x_0, y_0, z_0)$，方向向量 $\vec{s} = (m, n, p)$

        $$\begin{cases}
        x = x_0 + mt \\
        y = y_0 + nt \\
        z = z_0 + pt
        \end{cases} \quad (t \in \mathbb{R})$$

      - **点向式（对称式）**：由参数式消去 $t$

        $$\frac{x - x_0}{m} = \frac{y - y_0}{n} = \frac{z - z_0}{p}$$

        其中 $m, n, p$ 为直线的**方向数**，$\vec{s} = (m, n, p)$ 为**方向向量**。若某一分量为 $0$（如 $m=0$），则对应分子也为 $0$，理解为 $x = x_0$。
  - 多元函数微分学
    - 连续
    - 偏导数
    - 全微分
      - **四大概念关系**（二元函数）：

        <svg width="500" height="340" xmlns="http://www.w3.org/2000/svg">
          <!-- 偏导数连续 -->
          <rect x="160" y="10" width="160" height="50" rx="8" fill="#e8f5e9" stroke="#2e7d32" stroke-width="2"/>
          <text x="240" y="40" text-anchor="middle" font-size="15" fill="#2e7d32" font-weight="bold">偏导数连续</text>
          <!-- 可全微分 -->
          <rect x="160" y="130" width="160" height="50" rx="8" fill="#e3f2fd" stroke="#1565c0" stroke-width="2"/>
          <text x="240" y="160" text-anchor="middle" font-size="15" fill="#1565c0" font-weight="bold">可全微分</text>
          <!-- 连续 -->
          <rect x="60" y="260" width="130" height="50" rx="8" fill="#fff3e0" stroke="#e65100" stroke-width="2"/>
          <text x="125" y="290" text-anchor="middle" font-size="15" fill="#e65100" font-weight="bold">连续</text>
          <!-- 偏导数存在 -->
          <rect x="290" y="260" width="140" height="50" rx="8" fill="#fce4ec" stroke="#c62828" stroke-width="2"/>
          <text x="360" y="290" text-anchor="middle" font-size="15" fill="#c62828" font-weight="bold">偏导数存在</text>
          <!-- 箭头：偏导连续 → 可全微分 -->
          <line x1="240" y1="60" x2="240" y2="125" stroke="#2e7d32" stroke-width="2" marker-end="url(#arrowGreen)"/>
          <text x="260" y="95" font-size="12" fill="#2e7d32">充分条件</text>
          <!-- 箭头：可全微分 → 连续 -->
          <line x1="195" y1="180" x2="135" y2="255" stroke="#1565c0" stroke-width="2" marker-end="url(#arrowBlue)"/>
          <text x="130" y="225" font-size="12" fill="#1565c0">⇒</text>
          <!-- 箭头：可全微分 → 偏导存在 -->
          <line x1="285" y1="180" x2="345" y2="255" stroke="#1565c0" stroke-width="2" marker-end="url(#arrowBlue)"/>
          <text x="330" y="225" font-size="12" fill="#1565c0">⇒</text>
          <!-- 双向交叉线：连续 ⇏ 偏导存在 -->
          <line x1="190" y1="275" x2="290" y2="275" stroke="#999" stroke-width="1.5" stroke-dasharray="6,3"/>
          <text x="200" y="269" font-size="11" fill="#999">互不蕴含</text>
          <text x="250" y="269" font-size="11" fill="#999">✗</text>
          <!-- 箭头定义 -->
          <defs>
            <marker id="arrowGreen" markerWidth="10" markerHeight="7" refX="10" refY="3.5" orient="auto">
              <polygon points="0 0, 10 3.5, 0 7" fill="#2e7d32"/>
            </marker>
            <marker id="arrowBlue" markerWidth="10" markerHeight="7" refX="10" refY="3.5" orient="auto">
              <polygon points="0 0, 10 3.5, 0 7" fill="#1565c0"/>
            </marker>
          </defs>
        </svg>

        | 反例 | 说明 |
        |---|---|
        | 偏导存在但不可微 | $f(x,y)=\begin{cases}\frac{xy}{x^{2}+y^{2}},&(x,y)\neq(0,0)\\0,&(0,0)\end{cases}$：偏导存在但不连续，更不可微 |
        | 可微但偏导不连续 | $f(x,y)=\begin{cases}(x^{2}+y^{2})\sin\frac{1}{\sqrt{x^{2}+y^{2}}},&(x,y)\neq(0,0)\\0,&(0,0)\end{cases}$ |
        | 偏导存在但不连续 | 同上第一个反例，偏导存在说明不了连续性 |

      - **可微条件**（二元函数 $z = f(x, y)$）：

        - **必要条件**：偏导数 $f_x, f_y$ 存在（但反之不成立）
        - **充分条件**：偏导数 $f_x, f_y$ 连续 $\Rightarrow$ 可微
        - **充要条件（定义）**：全增量可表示为

          $$\Delta z = f_x\Delta x + f_y\Delta y + o(\rho)$$

          其中 $\rho = \sqrt{(\Delta x)^2 + (\Delta y)^2}$，即

          $$\lim_{(\Delta x, \Delta y) \to (0,0)} \frac{\Delta z - (f_x\Delta x + f_y\Delta y)}{\sqrt{(\Delta x)^2 + (\Delta y)^2}} = 0$$

      -   函数 $z = f(x, y)$ 在点 $(x, y)$ 可微，则全微分为：

          $$dz = \frac{\partial z}{\partial x}\,dx + \frac{\partial z}{\partial y}\,dy$$

          推广到 $n$ 元函数 $u = f(x_1, x_2, \ldots, x_n)$：

          $$du = \frac{\partial u}{\partial x_1}dx_1 + \frac{\partial u}{\partial x_2}dx_2 + \cdots + \frac{\partial u}{\partial x_n}dx_n$$

          > 偏导数连续 $\Rightarrow$ 函数可微 $\Rightarrow$ 偏导数存在，反方向不成立。
    - 方向导数
      - 函数 $z = f(x, y)$ 在点 $P_0(x_0, y_0)$ 沿单位向量 $\vec{l} = (\cos\alpha, \cos\beta)$ 的方向导数：

        $$\frac{\partial f}{\partial l}\bigg|_{P_0} = f_x(x_0, y_0)\cos\alpha + f_y(x_0, y_0)\cos\beta$$

        用**梯度** $\nabla f = \left(\dfrac{\partial f}{\partial x}, \dfrac{\partial f}{\partial y}\right)$ 表示为：

        $$\frac{\partial f}{\partial l} = \nabla f \cdot \vec{l}$$

        推广到 $n$ 元函数：$\displaystyle\frac{\partial f}{\partial l} = \nabla f \cdot \vec{l} = \sum_{i=1}^{n} \frac{\partial f}{\partial x_i}\cos\theta_i$

        > 梯度 $\nabla f$ 的方向是函数值**增长最快**的方向，梯度模长即为最大方向导数 $\lVert\nabla f\rVert$。
    - 多元复合函数求导
      **链式法则图**（变量依赖关系）：

      **情况 1**：$z = f(u, v),\ u = u(t),\ v = v(t)$

      <svg width="300" height="180" xmlns="http://www.w3.org/2000/svg">
        <!-- z -->
        <rect x="120" y="10" width="50" height="36" rx="6" fill="#e3f2fd" stroke="#1565c0" stroke-width="1.5"/>
        <text x="145" y="33" text-anchor="middle" font-size="16" fill="#1565c0" font-weight="bold">z</text>
        <!-- u -->
        <rect x="40" y="90" width="50" height="36" rx="6" fill="#fff3e0" stroke="#e65100" stroke-width="1.5"/>
        <text x="65" y="113" text-anchor="middle" font-size="16" fill="#e65100" font-weight="bold">u</text>
        <!-- v -->
        <rect x="200" y="90" width="50" height="36" rx="6" fill="#fff3e0" stroke="#e65100" stroke-width="1.5"/>
        <text x="225" y="113" text-anchor="middle" font-size="16" fill="#e65100" font-weight="bold">v</text>
        <!-- t -->
        <rect x="120" y="155" width="50" height="25" rx="6" fill="#e8f5e9" stroke="#2e7d32" stroke-width="1.5"/>
        <text x="145" y="172" text-anchor="middle" font-size="15" fill="#2e7d32" font-weight="bold">t</text>
        <!-- lines z-u, z-v, u-t, v-t -->
        <line x1="130" y1="46" x2="60" y2="88" stroke="#555" stroke-width="1.2"/>
        <line x1="160" y1="46" x2="225" y2="88" stroke="#555" stroke-width="1.2"/>
        <line x1="65" y1="126" x2="135" y2="153" stroke="#555" stroke-width="1.2"/>
        <line x1="225" y1="126" x2="155" y2="153" stroke="#555" stroke-width="1.2"/>
        <!-- derivative labels -->
        <text x="72" y="68" font-size="11" fill="#c62828">∂z/∂u</text>
        <text x="180" y="68" font-size="11" fill="#c62828">∂z/∂v</text>
        <text x="72" y="148" font-size="11" fill="#c62828">du/dt</text>
        <text x="232" y="148" font-size="11" fill="#c62828">dv/dt</text>
        <!-- formula -->
        <text x="150" y="195" text-anchor="middle" font-size="13" fill="#333">每条路径相乘，各路相加</text>
      </svg>

      $$\frac{dz}{dt} = \frac{\partial z}{\partial u}\frac{du}{dt} + \frac{\partial z}{\partial v}\frac{dv}{dt}$$

      **情况 2**：$z = f(u, v),\ u = u(x, y),\ v = v(x, y)$

      <svg width="380" height="200" xmlns="http://www.w3.org/2000/svg">
        <!-- z -->
        <rect x="155" y="5" width="50" height="36" rx="6" fill="#e3f2fd" stroke="#1565c0" stroke-width="1.5"/>
        <text x="180" y="28" text-anchor="middle" font-size="16" fill="#1565c0" font-weight="bold">z</text>
        <!-- u -->
        <rect x="50" y="80" width="50" height="36" rx="6" fill="#fff3e0" stroke="#e65100" stroke-width="1.5"/>
        <text x="75" y="103" text-anchor="middle" font-size="16" fill="#e65100" font-weight="bold">u</text>
        <!-- v -->
        <rect x="260" y="80" width="50" height="36" rx="6" fill="#fff3e0" stroke="#e65100" stroke-width="1.5"/>
        <text x="285" y="103" text-anchor="middle" font-size="16" fill="#e65100" font-weight="bold">v</text>
        <!-- x (shared) -->
        <rect x="100" y="155" width="40" height="28" rx="6" fill="#e8f5e9" stroke="#2e7d32" stroke-width="1.5"/>
        <text x="120" y="174" text-anchor="middle" font-size="15" fill="#2e7d32" font-weight="bold">x</text>
        <!-- y (shared) -->
        <rect x="220" y="155" width="40" height="28" rx="6" fill="#e8f5e9" stroke="#2e7d32" stroke-width="1.5"/>
        <text x="240" y="174" text-anchor="middle" font-size="15" fill="#2e7d32" font-weight="bold">y</text>
        <!-- lines z→u, z→v -->
        <line x1="165" y1="41" x2="72" y2="78" stroke="#555" stroke-width="1.2"/>
        <line x1="195" y1="41" x2="285" y2="78" stroke="#555" stroke-width="1.2"/>
        <!-- lines u→x, u→y -->
        <line x1="65" y1="116" x2="113" y2="153" stroke="#555" stroke-width="1.2"/>
        <line x1="82" y1="116" x2="233" y2="153" stroke="#555" stroke-width="1.2"/>
        <!-- lines v→x, v→y -->
        <line x1="278" y1="116" x2="128" y2="153" stroke="#555" stroke-width="1.2"/>
        <line x1="295" y1="116" x2="247" y2="153" stroke="#555" stroke-width="1.2"/>
        <!-- labels -->
        <text x="92" y="63" font-size="11" fill="#c62828">∂z/∂u</text>
        <text x="204" y="63" font-size="11" fill="#c62828">∂z/∂v</text>
        <text x="78" y="133" font-size="10" fill="#c62828">∂u/∂x</text>
        <text x="145" y="133" font-size="10" fill="#c62828">∂u/∂y</text>
        <text x="212" y="133" font-size="10" fill="#c62828">∂v/∂x</text>
        <text x="284" y="133" font-size="10" fill="#c62828">∂v/∂y</text>
        <!-- formula annotations -->
        <text x="10" y="27" font-size="12" fill="#333">z → x 共 2 条路径</text>
        <text x="10" y="44" font-size="12" fill="#c62828">z→u→x, z→v→x</text>
      </svg>

      $$\frac{\partial z}{\partial x} = \frac{\partial z}{\partial u}\frac{\partial u}{\partial x} + \frac{\partial z}{\partial v}\frac{\partial v}{\partial x}$$

      $$\frac{\partial z}{\partial y} = \frac{\partial z}{\partial u}\frac{\partial u}{\partial y} + \frac{\partial z}{\partial v}\frac{\partial v}{\partial y}$$

      > **口诀**：分叉相加，链上相乘。从因变量到自变量，每条路径上的偏导相乘，各路径结果求和。
    - $$
      \begin{align*}
      & w = f(x+y+z, xyz) ,\frac{\partial w}{\partial x}, \frac{\partial^2w}{\partial x \partial z} \\
      & \frac{\partial w}{\partial x} = f_1' \times 1 + f_2' \times yz\\
      & \frac{\partial^2 w}{\partial x\partial z} = \frac{\partial(f_{1}')}{\partial z} + \frac{\partial(f_2')}{\partial z} \times yz + f_2'y\\
      \end{align*}
      $$
    - 隐函数
      - 1 一元函数（全微分变形）
        由 $F(x, y) = 0$ 确定 $y = y(x)$，则：

        $$\frac{dy}{dx} = -\frac{F'_x}{F'_y} \quad (F'_y \neq 0)$$

      - 2 多元函数
        由 $F(x, y, z) = 0$ 确定 $z = z(x, y)$，则：

        $$\frac{\partial z}{\partial x} = -\frac{F'_x}{F'_z},\quad \frac{\partial z}{\partial y} = -\frac{F'_y}{F'_z} \quad (F'_z \neq 0)$$

      - 3 方程组
        由 $\begin{cases} F(x, y, u, v) = 0 \\ G(x, y, u, v) = 0 \end{cases}$ 确定 $u, v$ 为 $x, y$ 的函数。

        利用**雅可比行列式** $J = \dfrac{\partial(F, G)}{\partial(u, v)} = \begin{vmatrix} F'_u & F'_v \\ G'_u & G'_v \end{vmatrix} \neq 0$：

        $$\frac{\partial u}{\partial x} = -\frac{1}{J}\frac{\partial(F, G)}{\partial(x, v)},\quad
          \frac{\partial v}{\partial x} = -\frac{1}{J}\frac{\partial(F, G)}{\partial(u, x)}$$

      - > **梯度与法向量**：对于隐式曲面 $F(x, y, z) = 0$，梯度 $\nabla F = (F'_x, F'_y, F'_z)$ 即为曲面在该点的**法向量**。将显式 $z = f(x, y)$ 改写为 $F = f(x, y) - z = 0$，则 $\nabla F = (f_x, f_y, -1)$ 亦是法向量。而对 $z = f(x, y)$ 直接求 $\nabla f = (f_x, f_y)$，它是 $xy$ 平面内的**最速上升方向**，不是法向量。
    - 函数多元极值
      - 无条件
        **必要条件**：解 $\begin{cases} f_x(x,y) = 0 \\ f_y(x,y) = 0 \end{cases}$ 得驻点。

        **充分条件**：记 $A = f_{xx}''$, $B = f_{xy}''$, $C = f_{yy}''$，判别式 $\Delta = AC - B^2$，
        在驻点 $(x_0, y_0)$ 处：

        | $\Delta = AC - B^2$ | $A$ | 结论 |
        |---|---|---|
        | $\Delta > 0$ | $A > 0$ | **极小值** |
        | $\Delta > 0$ | $A < 0$ | **极大值** |
        | $\Delta < 0$ | — | **无极值**（鞍点） |
        | $\Delta = 0$ | — | 无法判定，需另法 |
      - 有条件（拉格朗日乘数法）
        **一个约束**：求 $z = f(x, y)$ 在 $\varphi(x, y) = 0$ 下的极值。

        构造拉格朗日函数 $L(x, y, \lambda) = f(x, y) + \lambda\,\varphi(x, y)$，
        解方程组：

        $$\begin{cases}
        L_x = f_x + \lambda\varphi_x = 0 \\
        L_y = f_y + \lambda\varphi_y = 0 \\
        L_\lambda = \varphi(x, y) = 0
        \end{cases}$$

        解出驻点 $(x_0, y_0)$，代入 $f$ 比较即得条件极值。

        **多个约束**：求 $u = f(x, y, z)$ 在 $\varphi_1 = 0,\ \varphi_2 = 0$ 下的极值：

        $$L(x, y, z, \lambda, \mu) = f + \lambda\varphi_1 + \mu\varphi_2$$

        对 $x, y, z, \lambda, \mu$ 分别求偏导令其为 $0$，联立求解。
    - 空间曲线的切线和法平面 显式得切，隐式得法
      - 参数方程形式
        设空间曲线 $\Gamma: \begin{cases} x = x(t) \\ y = y(t) \\ z = z(t) \end{cases}$ 在 $t = t_0$ 对应点 $M_0(x_0, y_0, z_0)$。

        **切向量**：$\vec{T} = (x'(t_0),\, y'(t_0),\, z'(t_0))$

        **切线方程**（点向式）：
        $$\frac{x - x_0}{x'(t_0)} = \frac{y - y_0}{y'(t_0)} = \frac{z - z_0}{z'(t_0)}$$

        若某分量导数为 $0$，如 $x'(t_0) = 0$，则切线方程为 $\begin{cases} x = x_0 \\ \dfrac{y - y_0}{y'(t_0)} = \dfrac{z - z_0}{z'(t_0)} \end{cases}$（理解：对应分母为 $0$ 时分子也应为 $0$）。

        **法平面方程**（以切向量为法向量）：
        $$x'(t_0)(x - x_0) + y'(t_0)(y - y_0) + z'(t_0)(z - z_0) = 0$$

        > **几何理解**：切向量 $\vec{T}$ 是曲线在 $M_0$ 处的方向向量；法平面是过 $M_0$ 且以 $\vec{T}$ 为法向量的平面。

      - 一般方程形式（两曲面交线）
        设空间曲线 $\Gamma: \begin{cases} F(x, y, z) = 0 \\ G(x, y, z) = 0 \end{cases}$，曲线为两曲面的交线。

        **切向量**为两曲面法向量的叉积：
        $$\vec{T} = \nabla F \times \nabla G = \begin{vmatrix}
        \vec{i} & \vec{j} & \vec{k} \\
        F'_x & F'_y & F'_z \\
        G'_x & G'_y & G'_z
        \end{vmatrix}_{M_0}$$

        记 $\vec{T} = (A, B, C)$，其中：
        $$A = \begin{vmatrix} F'_y & F'_z \\ G'_y & G'_z \end{vmatrix},\quad
          B = \begin{vmatrix} F'_z & F'_x \\ G'_z & G'_x \end{vmatrix},\quad
          C = \begin{vmatrix} F'_x & F'_y \\ G'_x & G'_y \end{vmatrix}$$

        **切线方程**：
        $$\frac{x - x_0}{A} = \frac{y - y_0}{B} = \frac{z - z_0}{C}$$

        **法平面方程**：
        $$A(x - x_0) + B(y - y_0) + C(z - z_0) = 0$$

        > **几何理解**：曲面 $F=0$ 在 $M_0$ 的法向量为 $\nabla F$，曲面 $G=0$ 的法向量为 $\nabla G$。曲线的切线同时垂直于两个法向量，故切向量为 $\nabla F \times \nabla G$。
  - 重积分
    - 二重积分直角坐标系运算
      - 投影, $\mathrm dx \mathrm dy(\mathrm d\sigma)$ 表示每个颗粒，$f(x,y)$ 表示属性 
        - 例：计算 $\displaystyle \iint_D xy \,\mathrm{d}x\mathrm{d}y$，$D: 0 \le x \le 1,\ 1 \le y \le 2$

          $$
          \begin{aligned}
          \iint_D xy \,\mathrm{d}x\mathrm{d}y
          &= \int_1^2 \int_0^1 xy \,\mathrm{d}x\mathrm{d}y \\[4pt]
          &= \int_1^2 \left[ \frac{1}{2}x^2 y \right]_0^1 \mathrm{d}y \\[4pt]
          &= \int_1^2 \frac{1}{2}y \,\mathrm{d}y \\[4pt]
          &= \left[ \frac{1}{4}y^2 \right]_1^2 \\[4pt]
          &= \frac{1}{4}(4 - 1) = \frac{3}{4}
          \end{aligned}
          $$
      - 1 画图 2 切割 3 二重积分改为二次积分 4 计算 (刀左右切一次，左侧是左右限，右侧是上下限，可以全部算每个轴左右界限，不必考虑上下)
      - 三维坐标系中，计算物体投影，比如xoy平面，则把没有z的表达式画出来，就可以了，然后把z有关的两个方程找出来，画出上盖和下底
    - 极坐标
      - 积分时候，左边是角度，右边是长度，直角坐标 → 极坐标转换过程：

        $$
        \begin{cases}
        x = r\cos\theta \\[2pt]
        y = r\sin\theta
        \end{cases}
        \qquad
        \mathrm{d}x\mathrm{d}y = r\,\mathrm{d}r\mathrm{d}\theta
        $$

        $$
        \iint_D f(x,y)\,\mathrm{d}x\mathrm{d}y
        = \iint_{D'} f(r\cos\theta,\ r\sin\theta) \cdot r \,\mathrm{d}r\mathrm{d}\theta
        $$

        > **注意**：千万不要漏掉 $r$（雅可比行列式 $|J| = r$），这是极坐标变换最容易扣分的地方。

        **$r$ 的含义：**
        1. **几何角度**：极坐标下面积微元是一个小扇形格，径向宽 $\mathrm{d}r$，弧长 $r\mathrm{d}\theta$，面积 $= r\,\mathrm{d}r\mathrm{d}\theta$。半径越大，同样的 $\mathrm{d}\theta$ 扫过的弧长越长，$r$ 补偿这个效应。
        2. **代数角度**：变量替换的雅可比行列式 $|J| = \begin{vmatrix} \cos\theta & -r\sin\theta \\ \sin\theta & r\cos\theta \end{vmatrix} = r$，面积元素必须乘上 $|J|$。
    - 被积函数关于轴对称，考虑值是否为0 
    - 二重积分对称性
      - **轮换对称性**：积分区域 $D$ 关于 $y = x$ 对称时，将被积函数中 $x$ 与 $y$ 互换，积分值不变。

        $$
        \iint_D f(x,y)\,\mathrm{d}\sigma = \iint_D f(y,x)\,\mathrm{d}\sigma
        $$

        常用技巧：当 $D$ 关于 $y=x$ 对称时，

        $$
        \iint_D f(x,y)\,\mathrm{d}\sigma
        = \frac{1}{2} \iint_D \big[f(x,y) + f(y,x)\big] \,\mathrm{d}\sigma
        $$

        特殊用法（偶函数）：

        $$
        \iint_D x^2 \,\mathrm{d}\sigma = \iint_D y^2 \,\mathrm{d}\sigma
        \quad\Longrightarrow\quad
        \iint_D x^2 \,\mathrm{d}\sigma 
        = \frac{1}{2} \iint_D (x^2 + y^2) \,\mathrm{d}\sigma
        $$

        > **注意**：轮换对称性要求积分区域 $D$ 关于 $y=x$ 对称，即 $(x,y)\in D \iff (y,x)\in D$。
    - 三重积分
      - **直角坐标系**
      - **柱坐标系**（三重积分常用变换）

        $$
        \begin{cases}
        x = \rho\cos\theta \\[2pt]
        y = \rho\sin\theta \\[2pt]
        z = z
        \end{cases}
        \qquad
        \mathrm{d}x\mathrm{d}y\mathrm{d}z = \rho \,\mathrm{d}\rho\mathrm{d}\theta\mathrm{d}z
        $$

        | 变量 | 含义 | 范围 |
        |------|------|------|
        | $\rho$ | $xy$ 平面投影到原点的距离 | $[0, +\infty)$ |
        | $\theta$ | $xy$ 平面投影与 $x$ 轴夹角 | $[0, 2\pi]$ |
        | $z$ | 竖坐标（不变） | $(-\infty, +\infty)$ |

        完整变换：

        $$
        \iiint_\Omega f(x,y,z)\,\mathrm{d}x\mathrm{d}y\mathrm{d}z
        = \iiint_{\Omega'} f(\rho\cos\theta,\ \rho\sin\theta,\ z) \cdot \rho \,\mathrm{d}\rho\mathrm{d}\theta\mathrm{d}z
        $$

        > **注意**：柱坐标本质是 $xy$ 平面用极坐标、$z$ 轴不变，体积元素 $\rho$ 就是极坐标的面积元素。
      - **球坐标系**（三重积分常用变换）

        $$
        \begin{cases}
        x = r\sin\varphi\cos\theta \\[2pt]
        y = r\sin\varphi\sin\theta \\[2pt]
        z = r\cos\varphi
        \end{cases}
        \qquad
        \mathrm{d}x\mathrm{d}y\mathrm{d}z = r^2 \sin\varphi \,\mathrm{d}r\mathrm{d}\varphi\mathrm{d}\theta
        $$

        | 变量 | 含义 | 范围 |
        |------|------|------|
        | $r$ | 点到原点的距离（径向） | $[0, +\infty)$ |
        | $\varphi$ | 与 $z$ 轴正方向的夹角（天顶角） | $[0, \pi]$ |
        | $\theta$ | $xy$ 平面投影与 $x$ 轴夹角（方位角） | $[0, 2\pi]$ |

        完整变换：

        $$
        \iiint_\Omega f(x,y,z)\,\mathrm{d}x\mathrm{d}y\mathrm{d}z
        = \iiint_{\Omega'} f(r\sin\varphi\cos\theta,\ r\sin\varphi\sin\theta,\ r\cos\varphi) \cdot r^2\sin\varphi \,\mathrm{d}r\mathrm{d}\varphi\mathrm{d}\theta
        $$

        > **注意**：球坐标体积元素是 $r^2\sin\varphi$，极坐标面积元素是 $r$，两者容易混淆。

        **$r^2\sin\varphi$ 的推导（雅可比行列式）：**

        $$
        \begin{aligned}
        J &= \frac{\partial(x,y,z)}{\partial(r,\varphi,\theta)}
        = \begin{vmatrix}
        \frac{\partial x}{\partial r} & \frac{\partial x}{\partial \varphi} & \frac{\partial x}{\partial \theta} \\[6pt]
        \frac{\partial y}{\partial r} & \frac{\partial y}{\partial \varphi} & \frac{\partial y}{\partial \theta} \\[6pt]
        \frac{\partial z}{\partial r} & \frac{\partial z}{\partial \varphi} & \frac{\partial z}{\partial \theta}
        \end{vmatrix} \\[8pt]
        &= \begin{vmatrix}
        \sin\varphi\cos\theta & r\cos\varphi\cos\theta & -r\sin\varphi\sin\theta \\
        \sin\varphi\sin\theta & r\cos\varphi\sin\theta &  r\sin\varphi\cos\theta \\
        \cos\varphi            & -r\sin\varphi        & 0
        \end{vmatrix} \\[8pt]
        \end{aligned}
        $$

        按第三行展开：

        $$
        \begin{aligned}
        |J| &= \cos\varphi \cdot 
        \begin{vmatrix} r\cos\varphi\cos\theta & -r\sin\varphi\sin\theta \\ r\cos\varphi\sin\theta & r\sin\varphi\cos\theta \end{vmatrix}
        \;+\; r\sin\varphi \cdot
        \begin{vmatrix} \sin\varphi\cos\theta & -r\sin\varphi\sin\theta \\ \sin\varphi\sin\theta & r\sin\varphi\cos\theta \end{vmatrix} \\[6pt]
        &= \cos\varphi \cdot r^2\sin\varphi\cos\varphi + r\sin\varphi \cdot r\sin\varphi \\[4pt]
        &= r^2\sin\varphi(\cos^2\varphi + \sin^2\varphi) \\[4pt]
        &= r^2\sin\varphi
        \end{aligned}
        $$

        > 直观理解：$r^2$ 是球面的面积缩放因子，$\sin\varphi$ 是因为越靠近 $z$ 轴（$\varphi \to 0$ 或 $\pi$），同样的 $\mathrm{d}\theta$ 扫过的弧长越短，体积微元越小。

        **几何推导（三边正交法）：**

        体积微元 $\mathrm{d}V$ 的三个正交边长：

        | 边 | 长度 | 说明 |
        |----|------|------|
        | 径向厚度 | $\mathrm{d}r$ | 沿半径方向直接变化 |
        | 经线弧长 | $r\,\mathrm{d}\varphi$ | 半径 × 天顶角微变 |
        | 纬线弧长 | $r\sin\varphi\,\mathrm{d}\theta$ | 纬线圈半径 $r\sin\varphi$ × 方位角微变 |

        三者相乘得体积元素：

        $$
        \mathrm{d}V = \mathrm{d}r \cdot (r\,\mathrm{d}\varphi) \cdot (r\sin\varphi\,\mathrm{d}\theta)
        = r^2\sin\varphi \,\mathrm{d}r\mathrm{d}\varphi\mathrm{d}\theta
        $$

        最终替换到三重积分：

        $$
        \begin{aligned}
        \iiint_\Omega f(x,y,z)\,\mathrm{d}V
        &\downarrow \ \mathrm{d}V = r^2\sin\varphi \,\mathrm{d}r\mathrm{d}\varphi\mathrm{d}\theta \\[4pt]
        \iiint_{\Omega'} f(r\sin\varphi\cos\theta,\ r\sin\varphi\sin\theta,\ r\cos\varphi) \cdot r^2\sin\varphi \,\mathrm{d}r\mathrm{d}\varphi\mathrm{d}\theta
        \end{aligned}
        $$
    - 积分应用
      - 空间曲面的面积

        $$
        S = \iint_D \sqrt{1 + \left(\frac{\partial z}{\partial x}\right)^2 + \left(\frac{\partial z}{\partial y}\right)^2} \,\mathrm{d}x\mathrm{d}y
        $$

        曲面 $z = z(x,y)$ 在区域 $D$ 上的表面积，本质是曲面微元 $\sqrt{1+z_x'^2+z_y'^2}\,\mathrm{d}x\mathrm{d}y$ 求和。

        **被积函数推导（法向量与 $z$ 轴的夹角）：**

        曲面微元 $\mathrm{d}S$（斜）与它在 $xy$ 平面的投影 $\mathrm{d}x\mathrm{d}y$（平）满足：

        $$
        \mathrm{d}S = \frac{\mathrm{d}x\mathrm{d}y}{|\cos\gamma|}
        $$

        其中 $\gamma$ 是曲面法向量 $\vec{n}$ 与 $z$ 轴正方向 $(0,0,1)$ 的夹角。

        曲面 $z = z(x,y)$ 的法向量：$\vec{n} = (-z_x',\ -z_y',\ 1)$

        $$
        \cos\gamma = \frac{\vec{n} \cdot (0,0,1)}{|\vec{n}| \cdot 1}
        = \frac{1}{\sqrt{(z_x')^2 + (z_y')^2 + 1}}
        $$

        代入：

        $$
        \mathrm{d}S = \frac{\mathrm{d}x\mathrm{d}y}{\frac{1}{\sqrt{1 + z_x'^2 + z_y'^2}}}
        = \sqrt{1 + z_x'^2 + z_y'^2} \;\mathrm{d}x\mathrm{d}y
        $$

        > 直观：曲面越"陡"（$z_x',z_y'$ 越大），法向量越偏离 $z$ 轴，$\cos\gamma$ 越小，同样的投影面积对应越大的真实曲面面积。
      - 平面区域绕直线旋转的体积（视为圆柱，微元是底面积，被积函数是长度）

        平面区域 $D$ 绕直线 $L$ 旋转，记点 $(x,y)$ 到 $L$ 的距离为 $r(x,y)$：

        $$
        V = 2\pi \iint_D r(x,y) \,\mathrm{d}\sigma
        $$

        其中 $r(x,y)$ 是点到转轴 $L: Ax+By+C=0$ 的距离：

        $$
        r(x,y) = \frac{|Ax + By + C|}{\sqrt{A^2 + B^2}}
        $$

        特例——绕 $x$ 轴旋转（$y = f(x)$ 在 $[a,b]$ 上）：

        $$
        V = \pi \int_a^b [f(x)]^2 \,\mathrm{d}x
        $$
      - 转动惯量

        $$
        I = \iint_D \rho(x,y) \cdot r^2(x,y) \,\mathrm{d}\sigma
        $$

        $r(x,y)$ 是点 $(x,y)$ 到转轴的距离，$\rho(x,y)$ 是面密度。

        **推导过程（微元法）：**

        **1. 质点**：一个质量为 $m$ 的质点，到转轴的距离为 $r$，其转动惯量定义为

        $$
        I = m r^2
        $$

        转动惯量衡量物体旋转时"抗拒角加速度"的能力，$r^2$ 说明质量离轴越远，惯性越大。

        **为什么是 $mr^2$？**

        由转动定律导出。质点在半径 $r$ 处以角加速度 $\alpha$ 转动：

        $$
        \text{切向加速度：}\ a = r\alpha \qquad
        \text{切向力：}\ F = ma = m \cdot r\alpha
        $$

        力矩 = 力 × 力臂：

        $$
        \tau = F \cdot r = m r\alpha \cdot r = mr^2 \cdot \alpha
        $$

        类比 $\tau = I \alpha$（转动版 $F=ma$），得 $I = mr^2$。

        > $r^2$ 中的两个 $r$ 来源不同：一个来自 $a = r\alpha$（加速度 → 角加速度），一个来自 $\tau = Fr$（力 → 力矩）。

        **2. 微元分割**：将平面区域 $D$ 细分为无数个面积微元 $\mathrm{d}\sigma$，每个微元看作一个质点：

        $$
        \mathrm{d}m = \rho(x,y) \cdot \mathrm{d}\sigma \qquad
        \mathrm{d}I = r^2 \cdot \mathrm{d}m = r^2(x,y) \cdot \rho(x,y) \cdot \mathrm{d}\sigma
        $$

        其中 $\rho(x,y)$ 是面密度（单位面积的质量），$r(x,y)$ 是该微元到转轴的距离。

        **3. 累加（积分）**：将所有微元的转动惯量求和，即二重积分：

        $$
        I = \sum \mathrm{d}I \;\longrightarrow\; I = \iint_D r^2(x,y) \cdot \rho(x,y) \,\mathrm{d}\sigma
        $$

        **各轴的具体形式：**

        $$
        I_x = \iint_D y^2 \rho \,\mathrm{d}\sigma, \qquad
        I_y = \iint_D x^2 \rho \,\mathrm{d}\sigma, \qquad
        I_O = \iint_D (x^2 + y^2) \rho \,\mathrm{d}\sigma
        $$

        > $I_O = I_x + I_y$（平面区域绕原点 = 绕 $x$ 轴 + 绕 $y$ 轴），因为 $r^2 = x^2 + y^2$。
  - 曲线积分曲面积分（数一）
    - 第一类曲线积分（对弧长）

      $$
      \int_L f(x,y) \,\mathrm{d}s
      $$

      弧长微元 $\mathrm{d}s = \sqrt{(\mathrm{d}x)^2 + (\mathrm{d}y)^2}$：
      - $y = y(x)$：$\displaystyle \mathrm{d}s = \sqrt{1 + (y')^2}\,\mathrm{d}x$
      - 参数形式：$\displaystyle \mathrm{d}s = \sqrt{[x'(t)]^2 + [y'(t)]^2}\,\mathrm{d}t$

      > **无方向性**：与积分路径方向无关，$\int_{AB} f\,\mathrm{d}s = \int_{BA} f\,\mathrm{d}s$。
    - 第二类曲线积分（对坐标）

      $$
      \int_L P(x,y)\,\mathrm{d}x + Q(x,y)\,\mathrm{d}y
      $$

      参数形式（$x = x(t),\ y = y(t)$）：

      $$
      \int_L P\,\mathrm{d}x + Q\,\mathrm{d}y
      = \int_\alpha^\beta \big[P \cdot x'(t) + Q \cdot y'(t)\big] \,\mathrm{d}t
      $$

      > **有方向性**：反向积分变号，$\int_{AB} = -\int_{BA}$。

      **两类积分的关系：**

      $$
      \int_L P\,\mathrm{d}x + Q\,\mathrm{d}y
      = \int_L (P\cos\alpha + Q\cos\beta)\,\mathrm{d}s
      $$

      其中 $(\cos\alpha,\cos\beta)$ 是曲线切向量的方向余弦。
    - 格林公式（Green）

      $$
      \oint_L P\,\mathrm{d}x + Q\,\mathrm{d}y
      = \iint_D \left(\frac{\partial Q}{\partial x} - \frac{\partial P}{\partial y}\right) \mathrm{d}x\mathrm{d}y
      $$

      要求 $L$ 为正向闭曲线、$D$ 内 $P,Q$ 有一阶连续偏导。

      **推导过程（小网格法）：**

      将区域 $D$ 划分为若干小矩形网格 $\Delta x \times \Delta y$，取其中一个网格：

      <pre>
       Q(x,y) ↖           ↗ Q(x+Δx, y)
                ┌────────┐
           P ↓  │ 网格   │ P ↑
                └────────┘
       Q(x,y+Δy) ↙    ↘ Q(x+Δx, y+Δy)
         方向：逆时针（正向）
      </pre>

      小网格上的环流量（四个边绕一圈）：

      $$
      \Delta\Gamma 
      = P(x,y)\Delta x \;+\; Q(x+\Delta x,y)\Delta y \;-\; P(x,y+\Delta y)\Delta x \;-\; Q(x,y)\Delta y
      $$

      > 解释：下边 $P\Delta x$（向右）+ 右边 $Q\Delta y$（向上）− 上边 $P\Delta x$（向左抵消）− 左边 $Q\Delta y$（向下抵消）

      重新排列，对 $P$ 项用垂直差、对 $Q$ 项用水平差：

      $$
      \begin{aligned}
      \Delta\Gamma 
      &= -\big[P(x,y+\Delta y) - P(x,y)\big]\Delta x \;+\; \big[Q(x+\Delta x,y) - Q(x,y)\big]\Delta y \\[4pt]
      &\approx -\frac{\partial P}{\partial y}\Delta y \cdot \Delta x \;+\; \frac{\partial Q}{\partial x}\Delta x \cdot \Delta y \\[4pt]
      &= \left(\frac{\partial Q}{\partial x} - \frac{\partial P}{\partial y}\right) \Delta x \Delta y
      \end{aligned}
      $$

      将所有小网格的环流量求和：

      - **内部边**：相邻网格共用边方向相反，互相抵消
      - **边界边**：只有最外层 $L$ 的边不被抵消

      故 $\displaystyle \sum\Delta\Gamma = \oint_L P\,\mathrm{d}x + Q\,\mathrm{d}y$，取极限 $\Delta x,\Delta y \to 0$：

      $$
      \oint_L P\,\mathrm{d}x + Q\,\mathrm{d}y
      = \iint_D \left(\frac{\partial Q}{\partial x} - \frac{\partial P}{\partial y}\right) \mathrm{d}x\mathrm{d}y
      $$
    - 积分与路径无关

      若在单连通区域 $D$ 内满足：

      $$
      \frac{\partial Q}{\partial x} = \frac{\partial P}{\partial y}
      $$

      则 $\int_L P\,\mathrm{d}x + Q\,\mathrm{d}y$ 在 $D$ 内**与路径无关**，等价于：

      1. $\displaystyle \oint_L P\,\mathrm{d}x + Q\,\mathrm{d}y = 0$（任意闭曲线积分为零）
      2. 存在势函数 $u(x,y)$，使得 $\mathrm{d}u = P\,\mathrm{d}x + Q\,\mathrm{d}y$，即 $\displaystyle \frac{\partial u}{\partial x} = P,\ \frac{\partial u}{\partial y} = Q$
      3. $\displaystyle \int_{A}^{B} P\,\mathrm{d}x + Q\,\mathrm{d}y = u(B) - u(A)$（类似牛顿-莱布尼茨公式）

      > **充分必要条件**：$\frac{\partial Q}{\partial x} = \frac{\partial P}{\partial y}$（格林公式直接推出）。
    - 第一类曲面积分（对面积）

      $$
      \iint_\Sigma f(x,y,z) \,\mathrm{d}S
      $$

      面积微元（$z = z(x,y)$）：

      $$
      \mathrm{d}S = \sqrt{1 + \left(\frac{\partial z}{\partial x}\right)^2 + \left(\frac{\partial z}{\partial y}\right)^2} \,\mathrm{d}x\mathrm{d}y
      $$

      参数形式（$\vec{r} = \vec{r}(u,v)$）：

      $$
      \mathrm{d}S = \left|\frac{\partial \vec{r}}{\partial u} \times \frac{\partial \vec{r}}{\partial v}\right| \mathrm{d}u\mathrm{d}v
      $$

      > **无方向性**：与曲面侧无关，只与面积有关（类比第一类曲线积分）。
    - 第二类曲面积分（对坐标）要不要加负号，算面的朝向和垂直于面的轴方向夹角，锐角为正，钝角为负

      $$
      \iint_\Sigma P\,\mathrm{d}y\mathrm{d}z + Q\,\mathrm{d}z\mathrm{d}x + R\,\mathrm{d}x\mathrm{d}y
      $$

      曲面 $\Sigma$：$z = z(x,y)$，取上侧，$R$ 项投影到 $xy$ 平面：

      $$
      \iint_\Sigma R(x,y,z)\,\mathrm{d}x\mathrm{d}y
      = \iint_{D_{xy}} R(x,y,z(x,y))\,\mathrm{d}x\mathrm{d}y
      $$

      > **有方向性**：取上侧为正、下侧为负（类比第二类曲线积分）。
    - 两类曲面积分的关系

      $$
      \iint_\Sigma P\,\mathrm{d}y\mathrm{d}z + Q\,\mathrm{d}z\mathrm{d}x + R\,\mathrm{d}x\mathrm{d}y
      = \iint_\Sigma (P\cos\alpha + Q\cos\beta + R\cos\gamma)\,\mathrm{d}S
      $$

      其中 $(\cos\alpha,\cos\beta,\cos\gamma)$ 是曲面单位外法向量的方向余弦。
    - 高斯公式（Gauss / 散度定理）

      $$
      \oiint_{\Sigma} P\,\mathrm{d}y\mathrm{d}z + Q\,\mathrm{d}z\mathrm{d}x + R\,\mathrm{d}x\mathrm{d}y
      = \iiint_\Omega \left(\frac{\partial P}{\partial x} + \frac{\partial Q}{\partial y} + \frac{\partial R}{\partial z}\right) \mathrm{d}x\mathrm{d}y\mathrm{d}z
      $$

      $\Sigma$ 为闭曲面取外侧，$\Omega$ 是 $\Sigma$ 围成的空间区域。
    - 斯托克斯公式（Stokes）

      $$
      \oint_L P\,\mathrm{d}x + Q\,\mathrm{d}y + R\,\mathrm{d}z
      = \iint_\Sigma 
      \begin{vmatrix} 
      \mathrm{d}y\mathrm{d}z & \mathrm{d}z\mathrm{d}x & \mathrm{d}x\mathrm{d}y \\[2pt]
      \frac{\partial}{\partial x} & \frac{\partial}{\partial y} & \frac{\partial}{\partial z} \\[2pt]
      P & Q & R
      \end{vmatrix}
      $$

      $L$ 是曲面 $\Sigma$ 的边界曲线，方向满足右手法则。
  - 无穷级数
    - 常数项级数
      $\displaystyle\sum_{n=1}^{\infty} a_n$，部分和 $S_n = \sum_{k=1}^{n} a_k$，若 $\lim_{n\to\infty} S_n = S$ 存在，则级数**收敛**于 $S$。
      - **收敛必要条件**：$\lim_{n\to\infty} a_n = 0$（反之不成立，如调和级数 $\sum\frac{1}{n}$ 发散）。

      - **常见级数**：
        - $p$-级数 $\displaystyle\sum\frac{1}{n^p}$：$p > 1$ 收敛，$p \le 1$ 发散
        - 几何级数 $\displaystyle\sum_{n=0}^{\infty} ar^n$：$|r| < 1$ 收敛于 $\frac{a}{1-r}$，$|r| \ge 1$ 发散

      - **判别法**（正项级数）：
        - ==比值判别法==：$\displaystyle\lim_{n\to\infty}\left|\frac{a_{n+1}}{a_n}\right| = \rho$，$\rho<1$ 收敛，$\rho>1$ 发散，$\rho=1$ 方法失效
        - 比较判别法（与已知收敛/发散级数比较）
          - **放缩形式**：$0 \le a_n \le b_n$（$n$ 充分大）$\quad
          \begin{cases}
            \sum b_n \text{ 收敛} \Rightarrow \sum a_n \text{ 收敛} \\[4pt]
            \sum a_n \text{ 发散} \Rightarrow \sum b_n \text{ 发散}
          \end{cases}$
          - ==极限形式==：$\displaystyle\lim_{n\to\infty} \frac{a_n}{b_n} = l \quad
          \begin{cases}
            0 < l < +\infty, & \sum a_n \text{ 与 } \sum b_n \text{ 同敛散} \\[4pt]
            l = 0, & \sum b_n \text{ 收敛} \Rightarrow \sum a_n \text{ 收敛} \\[4pt]
            l = +\infty, & \sum b_n \text{ 发散} \Rightarrow \sum a_n \text{ 发散}
          \end{cases}$
        - 根值判别法：$\displaystyle\lim_{n\to\infty}\sqrt[n]{|a_n|} = \rho$
      - 交错级数判别法（Leibniz）：$a_n$ 单调递减趋于 $0$ 则 $\sum(-1)^{n-1}a_n$ 收敛
      - **绝对收敛与条件收敛**：
        - **绝对收敛**：把每一项取绝对值后，级数仍然收敛。这意味着一开始就收敛得"很稳"——正负项再怎么排列，和都不变。就像攒够了一笔钱，怎么花都够用。
        - **条件收敛**：原级数收敛，但取绝对值后就发散了。这种收敛靠的是正负项互相抵消——一旦打乱顺序，和可能变成任何数！就像一个天平，左边和右边刚好平衡，但随便动一个砝码就翻了。
        - 例子：$1 - \frac{1}{2} + \frac{1}{3} - \frac{1}{4} + \cdots$（交错调和级数），原级数收敛到 $\ln 2$，但取绝对值后变成 $\sum\frac{1}{n}$（调和级数）就发散了 → **条件收敛**。而 $1 - \frac{1}{4} + \frac{1}{9} - \cdots$，取绝对值后是 $\sum\frac{1}{n^2}$（$p=2$）仍然收敛 → **绝对收敛**。
    - 幂级数
      $\displaystyle\sum_{n=0}^{\infty} a_n (x - x_0)^n$，收敛半径 $R$：

      $$R = \lim_{n\to\infty} \left|\frac{a_n}{a_{n+1}}\right| \quad\text{或}\quad R = \frac{1}{\lim_{n\to\infty}\sqrt[n]{|a_n|}}$$

      - $|x - x_0| < R$：**绝对收敛**
      - $|x - x_0| > R$：**发散**
      - 端点处需单独判别

      - **泰勒级数**（$x_0 = 0$ 时为麦克劳林级数）：
        $$f(x) = \sum_{n=0}^{\infty} \frac{f^{(n)}(x_0)}{n!}(x - x_0)^n$$
        **常用展开**：
        $$\begin{aligned}
        e^x &= \sum_{n=0}^{\infty} \frac{x^n}{n!} \quad (-\infty < x < \infty) \\[4pt]
        \sin x &= \sum_{n=0}^{\infty} (-1)^n \frac{x^{2n+1}}{(2n+1)!} \\[4pt]
        \cos x &= \sum_{n=0}^{\infty} (-1)^n \frac{x^{2n}}{(2n)!} \\[4pt]
        \ln(1+x) &= \sum_{n=1}^{\infty} (-1)^{n-1} \frac{x^n}{n} \quad (-1 < x \le 1) \\[4pt]
        \frac{1}{1-x} &= \sum_{n=0}^{\infty} x^n \quad (|x| < 1)
        \end{aligned}$$

        幂级数在收敛区间内可**逐项求导**和**逐项积分**，收敛半径不变。

        **为什么 $e^x$、$\sin x$、$\cos x$ 可以代入任意值？** 因为分母有 $n!$，收敛半径 $R=+\infty$：

        $$R = \lim_{n\to\infty} \left|\frac{a_n}{a_{n+1}}\right| = \lim_{n\to\infty} \frac{(n+1)!}{n!} = +\infty$$

        $n!$ 的增长速度碾压任何 $x^n$——不管 $x$ 多大，$n$ 足够大时 $\frac{x^n}{n!} \to 0$，余项必趋于 $0$。

        对比：$\ln(1+x)$ 分母只有 $n$ 没有阶乘，$R=1$；$\frac{1}{1-x}$ 连 $n$ 都没有，$R=1$。**分母有阶乘 $\Rightarrow$ 全实数轴收敛；没阶乘 $\Rightarrow$ 只在收敛半径内能用。**
    - 傅立叶级数
      周期 $2\pi$ 的函数 $f(x)$ 可展开为：

      $$f(x) = \frac{a_0}{2} + \sum_{n=1}^{\infty} \bigl(a_n \cos nx + b_n \sin nx\bigr)$$

      其中傅立叶系数：

      $$\begin{aligned}
      a_n &= \frac{1}{\pi}\int_{-\pi}^{\pi} f(x)\cos nx\,dx \quad (n = 0, 1, 2, \ldots) \\[4pt]
      b_n &= \frac{1}{\pi}\int_{-\pi}^{\pi} f(x)\sin nx\,dx \quad (n = 1, 2, \ldots)
      \end{aligned}$$

      - $f(x)$ 为**偶函数** $\Rightarrow$ $b_n = 0$，得**余弦级数**
      - $f(x)$ 为**奇函数** $\Rightarrow$ $a_n = 0$，得**正弦级数**

      周期为 $2l$ 时，将积分区间和三角函数参数换为 $\frac{n\pi x}{l}$ 即可。

      **狄利克雷收敛定理**：若 $f(x)$ 在一个周期内分段单调且只有有限个第一类间断点，则傅立叶级数收敛于 $\frac{f(x^+) + f(x^-)}{2}$。
    - 例题
      - $$
        \begin{aligned}
        \sum_{n=0}^{+\infty} 3^n\sin\frac{\pi}{4^n}
        \end{aligned}
        $$ 
      - $$
        \begin{aligned}
        \sum_{n=0}^{+\infty} \frac{x^{2n+1}}{2n + 1}
        \end{aligned}
        $$ 
      - **例**：将 $\sin x$ 展开成 $x - \frac{\pi}{4}$ 的幂级数。
        $$
        \begin{aligned}
        & t = x - \frac{\pi}{4} \\
        & \sin x= \sin(x+ \frac{\pi}{4}) \\
        & \sin(x+ \frac{\pi}{4}) = \sin x \cos {\frac{\pi}{4}} + sin {\frac{\pi}{4}} \cos x
        \end{aligned}
        $$ 
- 线性代数
  - $f(ax) = af(x) \quad f(x+y) = f(x)+f(y)$
  - 线性方程组
    $m$ 个方程、$n$ 个未知数的线性方程组：$A\vec{x} = \vec{b}$，其中 $A$ 为 $m \times n$ 系数矩阵。
    - 定义
      - **行阶梯形**：通过初等行变换化为如下形式——① 零行在非零行下方；② 每行第一个非零元（主元）的列标随行递增；③ 主元下方全为零。例如 $\begin{pmatrix} 1 & 2 & 3 \\ 0 & 1 & 4 \\ 0 & 0 & 0 \end{pmatrix}$
      - **行最简形**：在行阶梯形基础上进一步要求：① 主元全为 $1$；② 主元所在列的其余元素全为 $0$。例如 $\begin{pmatrix} 1 & 0 & -5 \\ 0 & 1 & 4 \\ 0 & 0 & 0 \end{pmatrix}$。行最简形是唯一的，可直接读出解。
    - 性质
      - **齐次方程组** $A\vec{x} = \vec{0}$：
        $$
        \begin{cases}
          \text{仅有零解（唯一解）}, & r(A) = n \text{（列满秩）} \\[4pt]
          \text{有无穷多非零解}, & r(A) < n，\text{基础解系含 } n - r(A) \text{ 个向量}
        \end{cases}
        $$
      - **非齐次方程组** $A\vec{x} = \vec{b}$：
        $$
        \begin{cases}
          \text{无解}, & r(A) \neq r(A \mid \vec{b}) \\[6pt]
          \text{唯一解}, & r(A) = r(A \mid \vec{b}) = n \\[6pt]
          \text{无穷多解}, & r(A) = r(A \mid \vec{b}) < n
        \end{cases}
        $$
        **解的结构**：$\vec{x} = \vec{x}_h + \vec{x}_p$（非齐次通解 = 齐次通解 + 非齐次特解）
        - **解的运算性质**：
          | 组合 | 结果 |
          |------|------|
          | 齐次解 + 齐次解 | 齐次解 ✓ |
          | 齐次解 $\times$ 常数 | 齐次解 ✓ |
          | 非齐次解 + 齐次解 | 非齐次解 ✓ |
          | 非齐次解 $-$ 非齐次解 | 齐次解 ✓ |
          | 非齐次解 + 非齐次解 | 不是原方程的解 ❌ |
    - 步骤
      - **如何从行最简形直接写出解（三步口诀）**：
        - **找主元列 → 定主变量**：主元所在列的变量写在左边
        - **非主元列 → 自由变量**：剩下的变量取任意常数 $t_1, t_2, \ldots$
        - **反解**：把自由变量移到右边，系数取相反数即为基础解系向量；常数项抄下来即为特解
      - **单自由变量示例**：增广矩阵 $(A \mid b) = \left(\begin{array}{ccc|c} 1 & 0 & 2 & 3 \\ 0 & 1 & -1 & 4 \\ 0 & 0 & 0 & 0 \end{array}\right)$，主变量 $x_1,x_2$，自由变量 $x_3=t$，解得 $\begin{pmatrix} x_1 \\ x_2 \\ x_3 \end{pmatrix} = \begin{pmatrix} 3 \\ 4 \\ 0 \end{pmatrix} + t\begin{pmatrix} -2 \\ 1 \\ 1 \end{pmatrix}$（特解 + 基础解系）
      - **主元不挨着的示例**：增广矩阵 $(A \mid b) = \left(\begin{array}{cccc|c} 1 & 3 & 0 & 2 & 5 \\ 0 & 0 & 1 & -1 & 4 \\ 0 & 0 & 0 & 0 & 0 \end{array}\right)$，主元在第 1 和 3 列，主变量 $x_1,x_3$，自由变量 $x_2=t_1,\ x_4=t_2$，反解：$x_1 = 5 - 3t_1 - 2t_2,\ x_3 = 4 + t_2$，$\begin{pmatrix} x_1 \\ x_2 \\ x_3 \\ x_4 \end{pmatrix} = \begin{pmatrix} 5 \\ 0 \\ 4 \\ 0 \end{pmatrix} + t_1\begin{pmatrix} -3 \\ 1 \\ 0 \\ 0 \end{pmatrix} + t_2\begin{pmatrix} -2 \\ 0 \\ -1 \\ 1 \end{pmatrix}$
        - **规律不变**：自由变量列对应的系数反号填到主变量行，自由变量行仍填"自己位置=1、其他=0"
        - 特解定位置，自由变量取负号，空位补01
    - 公式
      - **克拉默法则**（$A$ 为 $n$ 阶方阵且 $\det A \neq 0$）：$\displaystyle x_i = \frac{\det A_i}{\det A}$，其中 $A_i$ 为用 $\vec{b}$ 替换 $A$ 第 $i$ 列所得矩阵。
  - 矩阵运算
    - **加减**：$A \pm B = (a_{ij} \pm b_{ij})$（同型矩阵逐元素相加减）
    - **数乘**：$kA = (k \cdot a_{ij})$（常数 $k$ 乘每个元素）
    - **矩阵乘法**：$A_{m\times s} \cdot B_{s\times n} = C_{m\times n}$，$c_{ij} = \sum_{k=1}^{s} a_{ik}b_{kj}$（左列数 = 右行数才能乘）
      - **满足的运算律**：
        $$
        \begin{cases}
          (AB)C = A(BC) & \text{结合律} \\[4pt]
          A(B+C) = AB + AC & \text{左分配律} \\[4pt]
          (A+B)C = AC + BC & \text{右分配律} \\[4pt]
          k(AB) = (kA)B = A(kB) & \text{数乘结合律}
        \end{cases}
        $$
      - **不满足的规律（易错）**：
        - 不满足交换律：一般 $AB \neq BA$
        - $AB = 0 \nRightarrow A=0$ 或 $B=0$（有非零的零因子）
        - $AB = AC \nRightarrow B=C$（消去律不总成立，除非 $A$ 可逆）
        - $(A+B)^2 \neq A^2 + 2AB + B^2$（因 $AB \neq BA$，正确应为 $A^2 + AB + BA + B^2$）
    - **转置** $(A^T)_{ij} = a_{ji}$，性质：
      $$
      \begin{cases}
        (A^T)^T = A \\[4pt]
        (A+B)^T = A^T + B^T \\[4pt]
        (kA)^T = kA^T \\[4pt]
        (AB)^T = B^T A^T
      \end{cases}
      $$
    - **方阵的幂**：$A^k = A \cdot A \cdots A$（$k$ 个），$A^0 = I$，$(A^k)^T = (A^T)^k$
    - **特殊矩阵**：零矩阵 $O$、单位矩阵 $I$、对角矩阵 $\text{diag}(\lambda_1,\ldots,\lambda_n)$、对称矩阵 $A=A^T$、反对称矩阵 $A=-A^T$
    - **矩阵等价**：$A$ 与 $B$ 等价 $\iff$ 存在可逆矩阵 $P,Q$ 使 $B = PAQ$

      等价具有：反身性（$A \sim A$）、对称性（$A \sim B \iff B \sim A$）、传递性（$A \sim B,\ B \sim C \implies A \sim C$）。

      **充要条件**：$A$ 与 $B$ 等价 $\iff$ $A$ 与 $B$ 有相同的秩 $\iff$ $A$ 与 $B$ 可通过初等变换互化。

      **标准形**：任意 $m \times n$ 矩阵 $A$ 等价于

      $$
      \begin{pmatrix} I_r & O \\ O & O \end{pmatrix}_{m \times n}, \quad r = \operatorname{rank}(A)
      $$

      即存在可逆 $P,Q$，使得 $PAQ = \begin{pmatrix} I_r & O \\ O & O \end{pmatrix}$。

      > **注意区分**：等价（秩相同，$B = PAQ$）→ 相似（特征值相同，$B = P^{-1}AP$）→ 合同（二次型，$B = C^TAC$），三者的共同特征：都是等价关系。
    - **初等矩阵**：单位矩阵 $I$ 经过**一次**初等变换得到的矩阵

      三种初等变换对应三类初等矩阵：

      | 类型 | 变换操作 | 初等矩阵 | 行列式 |
      |------|----------|----------|--------|
      | 倍乘 | 第 $i$ 行乘 $k \neq 0$ | $E_i(k)$：$I$ 的 $(i,i)$ 位置改为 $k$ | $k$ |
      | 倍加 | 第 $i$ 行加 $j$ 行的 $k$ 倍 | $E_{ij}(k)$：$I$ 的 $(i,j)$ 位置补 $k$ | $1$ |
      | 互换 | 交换第 $i$ 行与第 $j$ 行 | $E_{ij}$：交换 $I$ 的 $i,j$ 两行 | $-1$ |

      核心性质：

      - **左乘行变、右乘列变**：$E_{ij}(k) A$ 将 $A$ 的第 $j$ 行乘 $k$ 加到第 $i$ 行；$A E_{ij}(k)$ 将 $A$ 的第 $i$ 列乘 $k$ 加到第 $j$ 列。
      - 初等矩阵均可逆，逆矩阵仍为初等矩阵：
        $$E_i(k)^{-1} = E_i(\tfrac{1}{k}),\qquad E_{ij}(k)^{-1} = E_{ij}(-k),\qquad E_{ij}^{-1} = E_{ij}$$

      > 任意可逆矩阵 $A$ 可分解为有限个初等矩阵的乘积：$A = E_1 E_2 \cdots E_k$。
    - **求逆矩阵的方法**

      $A$ 可逆 $\iff |A| \neq 0$，逆矩阵记为 $A^{-1}$，满足 $AA^{-1} = A^{-1}A = I$。

      **方法一：伴随矩阵法**

      $$
      A^{-1} = \frac{1}{|A|} A^*, \qquad A^* = \begin{pmatrix}
      A_{11} & A_{21} & \cdots & A_{n1} \\
      A_{12} & A_{22} & \cdots & A_{n2} \\
      \vdots  & \vdots  & \ddots & \vdots  \\
      A_{1n} & A_{2n} & \cdots & A_{nn}
      \end{pmatrix}
      $$

      其中 $A_{ij}$ 是 $a_{ij}$ 的代数余子式。注意 $A^*$ 是**转置**排列的：$(i,j)$ 位置是 $A_{ji}$。

      > 适用于低阶（2 阶、3 阶）方阵，高阶矩阵计算量太大。

      **方法二：初等变换法（最常用）**

      $$
      (A \mid I) \xrightarrow{\text{初等行变换}} (I \mid A^{-1})
      $$

      将 $A$ 和 $I$ 并排拼接，仅用**行变换**把左边消成 $I$，右边即得 $A^{-1}$。若左边化不出 $I$（出现全零行），则 $A$ 不可逆。

      **方法三：分块矩阵求逆**
      - 对角分块：$\displaystyle \begin{pmatrix} A & O \\ O & B \end{pmatrix}^{-1} = \begin{pmatrix} A^{-1} & O \\ O & B^{-1} \end{pmatrix}$
      - 三角分块：$\displaystyle \begin{pmatrix} A & C \\ O & B \end{pmatrix}^{-1} = \begin{pmatrix} A^{-1} & -A^{-1}CB^{-1} \\ O & B^{-1} \end{pmatrix}$
  - 行列式
    $n$ 阶方阵 $A$ 的行列式记为 $|A|$ 或 $\det(A)$。
    - **余子式 $M_{ij}$**：划去 $A$ 的第 $i$ 行和第 $j$ 列，剩下元素按原顺序构成的 $n-1$ 阶行列式。
    - **代数余子式 $A_{ij}$**：$A_{ij} = (-1)^{i+j} M_{ij}$（加上符号 $+/-$，棋盘格从左上角 $(1,1)$ 开始为正）。
    - **按行（列）展开定理**：
      - 按第 $i$ 行展开：$\displaystyle |A| = \sum_{j=1}^{n} a_{ij} A_{ij}$
      - 按第 $j$ 列展开：$\displaystyle |A| = \sum_{i=1}^{n} a_{ij} A_{ij}$
      - **异行展开为零**：$\displaystyle \sum_{j=1}^{n} a_{ij} A_{kj} = 0$（$i \neq k$），即某行乘另一行的代数余子式之和为零。
    - **基本性质**：
      - $|A^T| = |A|$
      - 交换两行（列），行列式变号
      - 某行（列）乘 $k$，行列式乘 $k$；$|kA| = k^n|A|$
      - 某行（列）的 $k$ 倍加到另一行（列），行列式不变
      - 两行（列）成比例 $\Rightarrow$ $|A| = 0$
      - $|AB| = |A|\cdot|B|$，$|A^{-1}| = |A|^{-1}$
    - **特殊行列式**：
      - 三角行列式 = 对角元乘积
      - 范德蒙行列式：$\displaystyle |V| = \prod_{1 \le i < j \le n} (x_j - x_i)$
        例（$n=3$）：$\begin{vmatrix}
        1 & 1 & 1 \\
        x_1 & x_2 & x_3 \\
        x_1^2 & x_2^2 & x_3^2
        \end{vmatrix} = (x_2-x_1)(x_3-x_1)(x_3-x_2)$
        数值例：$x_1=1,x_2=2,x_3=4$，则行列式 $=(2-1)(4-1)(4-2)=1\times3\times2=6$
      - **主对角线 $a$，其余 $b$ 的行列式**：
        $$D_n = \begin{vmatrix}
        a & b & b & \cdots & b \\
        b & a & b & \cdots & b \\
        b & b & a & \cdots & b \\
        \vdots & \vdots & \vdots & \ddots & \vdots \\
        b & b & b & \cdots & a
        \end{vmatrix}$$
        **解法**：将第 $2,3,\ldots,n$ 列都加到第 $1$ 列，提出公因子 $a + (n-1)b$，再将第 $1$ 行的 $(-1)$ 倍加到其余各行，化为三角行列式：
        $$D_n = \bigl[a + (n-1)b\bigr](a-b)^{n-1}$$
      - **递推型行列式**（按行或列展开得递推关系）：
        按第 $1$ 行（或第 $1$ 列）展开，建立 $D_n$ 与 $D_{n-1}$、$D_{n-2}$ 的递推式，再求通项。
        - **三对角行列式**：$\begin{vmatrix}
          a & b & & & \\
          c & a & b & & \\
            & \ddots & \ddots & \ddots & \\
            & & c & a & b \\
            & & & c & a
          \end{vmatrix}_{n\times n}$，按第 $1$ 行展开得 $D_n = a D_{n-1} - bc D_{n-2}$。
        - 若为常系数线性递推，解特征方程 $\lambda^2 = a\lambda - bc$，得 $D_n = C_1\lambda_1^n + C_2\lambda_2^n$（$\lambda_1 \neq \lambda_2$），代入 $D_1, D_2$ 定系数。
  - 向量空间

    向量空间（线性空间）$V$：对加法和数乘封闭的非空集合。

    - **八条公理**：加法交换律、结合律、零元、负元；数乘结合律、分配律（两条）、单位元 $1 \cdot \alpha = \alpha$。
    - **子空间**：非空子集 $W \subseteq V$ 对加法和数乘封闭即为子空间。
    - **线性相关与无关**：$\sum k_i \alpha_i = 0$ 仅有零解 $\iff$ 线性无关；有非零解 $\iff$ 线性相关。
    - **基与维数**：极大线性无关组称为基，基向量的个数为维数 $\dim V$。任意 $n+1$ 个 $n$ 维向量必线性相关。
    - **坐标**：取基 $\alpha_1,\ldots,\alpha_n$，任意向量 $\beta = x_1\alpha_1 + \cdots + x_n\alpha_n$，$(x_1,\ldots,x_n)^T$ 即 $\beta$ 的坐标。
    - **基变换与坐标变换**：从基 $A$ 到基 $B$ 的过渡矩阵 $P$ 满足 $B = AP$，坐标变换 $y = P^{-1} x$。
    - **秩的重要关系**：
      $$\operatorname{rank}(A) = \operatorname{rank}(A^T) = \operatorname{rank}(A^TA) = \operatorname{rank}(AA^T)$$
    - **解空间维度**：齐次方程组 $Ax=0$ 解空间维数 $= n - \operatorname{rank}(A)$（未知数个数 − 秩）。
  - 特征值与相似

    - **特征值与特征向量**：$A\vec{x} = \lambda\vec{x}$（$\vec{x} \neq \vec{0}$）
      - 特征方程 $|\lambda I - A| = 0$ 求特征值
      - 代入 $(\lambda I - A)\vec{x} = 0$ 求特征向量
    - **两个重要概念**：
      - **代数重数**：特征方程 $|\lambda I - A| = 0$ 中 $\lambda_0$ 作为根的**重数**。例如 $(\lambda - 2)^3(\lambda - 5) = 0$，则 $\lambda = 2$ 的代数重数为 $3$，$\lambda = 5$ 的代数重数为 $1$
      - **几何重数**：特征值 $\lambda_0$ 对应的特征子空间 $V_{\lambda_0} = \{\vec{x} \mid A\vec{x} = \lambda_0\vec{x}\}$ 的**维数**，即 $(\lambda_0 I - A)\vec{x} = 0$ 解空间的维数 $= n - \operatorname{rank}(\lambda_0 I - A)$
      - **关系**：$1 \leq$ 几何重数 $\leq$ 代数重数（不可能为 $0$，至少有 $1$ 个特征向量）
    - **特征值的性质**：
      - $\sum\lambda_i = \operatorname{tr}(A)$（迹），$\prod\lambda_i = |A|$（行列式）
      - $A$ 可逆 $\iff$ 所有特征值 $\neq 0$；若 $A$ 可逆，则 $A^{-1}$ 的特征值为 $\frac{1}{\lambda}$
      - $A$ 与 $A^T$ 特征值相同
      - 若 $\lambda$ 是 $A$ 的 $k$ 重特征值（代数重数），则 $\lambda$ 的几何重数 $\leq k$，即最多有 $k$ 个线性无关的特征向量
    - **特征向量的性质**：
      - **不同特征值的特征向量线性无关**：$\lambda_1 \neq \lambda_2 \implies \vec{x}_1, \vec{x}_2$ 线性无关；推广到 $k$ 个互异特征值，对应 $k$ 个特征向量整体线性无关
      - **同一特征值的特征向量**：构成特征子空间 $V_\lambda = \{\vec{x} \mid A\vec{x} = \lambda\vec{x}\}$，其维数 = 几何重数 $\leq$ 代数重数
      - **不同特征值拼起来不再是特征向量**
      - **特征向量是否还是特征向量（常见判定）**（$A\vec{x} = \lambda\vec{x}$ 前提下）：

        | 新矩阵 | $\vec{x}$ 仍是特征向量？ | 特征值 |
        |--------|:---:|------|
        | $k\vec{x}\ (k \neq 0)$ | ✓ | $\lambda$（不变） |
        | $A^m$ | ✓ | $\lambda^m$ |
        | $A^{-1}$（$A$ 可逆时） | ✓ | $1/\lambda$ |
        | $A^*$（伴随矩阵，$A$ 可逆时） | ✓ | $\|A\|/\lambda$ |
        | $aA + kI$ | ✓ | $a\lambda + k$ |
        | $f(A)$（$f$ 为多项式） | ✓ | $f(\lambda)$ |
        | $A^T$ | ✗ | — |
        | $B = P^{-1}AP$（相似变换） | ✗ | $P^{-1}\vec{x}$ 才是，特征值 $\lambda$ |
    - **相似对角化**：$A \sim \Lambda \iff P^{-1}AP = \Lambda = \operatorname{diag}(\lambda_1,\ldots,\lambda_n)$
      - $n$ 阶方阵可对角化 $\iff$ 有 $n$ 个线性无关的特征向量 $\iff$ 每个特征值的几何重数 = 代数重数
      - **实对称矩阵**必可正交对角化：$Q^TAQ = \Lambda$，$Q$ 为正交矩阵
    - **相似不变性**：$A \sim B$ 则 $|A|=|B|$、$\operatorname{tr}(A)=\operatorname{tr}(B)$、特征值相同、秩相同
    - **实对称矩阵的特殊性质**（$A = A^T$，$A \in \mathbb{R}^{n \times n}$）：
      - **特征值全为实数**（不会出现复特征值）
      - **不同特征值的特征向量正交**：$\lambda_1 \neq \lambda_2 \implies \vec{x}_1 \perp \vec{x}_2$（不仅线性无关，更强：正交）
      - **一定可以正交对角化**：存在正交矩阵 $Q$（$Q^TQ = I$）使 $Q^TAQ = \Lambda = \operatorname{diag}(\lambda_1,\ldots,\lambda_n)$
      - **几何重数 = 代数重数**：不会出现几何重数小于代数重数的情况，每个 $k$ 重特征值恰好有 $k$ 个正交的特征向量
      - **秩 = 非零特征值个数**：$\operatorname{rank}(A) =$ 非零特征值的个数（含重数）
      - **做题 4 步（正交对角化）**：
        1. **求特征值**：解 $|\lambda I - A| = 0$，得 $\lambda_1,\lambda_2,\ldots,\lambda_n$
        2. **求特征向量**：对每个 $\lambda_i$，解 $(\lambda_i I - A)\vec{x} = 0$，得基础解系
        3. **正交化**：同一特征值的特征向量组若不止一个，用施密特正交化使其两两正交（不同特征值的自动正交，无需处理）
        4. **单位化**：将所有正交向量除以各自的模长，得单位正交向量，按列排成 $Q$，则 $Q^TAQ = \Lambda$
  - 二次型

    - **定义**：$f(x_1,\ldots,x_n) = x^T A x$，其中 $A$ 为实对称矩阵。
    - **做题步骤**：
      1. **写出对称矩阵 $A$**：平方项系数放主对角线，交叉项系数平分到对应位置。如 $f = x_1^2 + 4x_1x_2 + 3x_2^2$ → $A = \begin{pmatrix} 1 & 2 \\ 2 & 3 \end{pmatrix}$
      2. **求特征值**：解 $|\lambda I - A| = 0$，得 $\lambda_1,\lambda_2,\ldots,\lambda_n$。
      3. **求特征向量并正交单位化**：得正交矩阵 $Q$，使 $Q^T A Q = \Lambda$。
      4. **写出标准形**：$f = \lambda_1 y_1^2 + \lambda_2 y_2^2 + \cdots + \lambda_n y_n^2$，其中 $x = Qy$。
      5. **判定正定性**：所有 $\lambda_i > 0$ → 正定；所有 $\lambda_i < 0$ → 负定；有正有负 → 不定。
    - **标准形**：$x^T A x = \lambda_1 y_1^2 + \lambda_2 y_2^2 + \cdots + \lambda_n y_n^2$
    - **惯性定理**：标准形中正项、负项、零项个数唯一确定（正负惯性指数不变）。
    - **化标准形的两种方法**：
      - **正交变换法** $x = Qy$（$Q$ 为正交阵）：
        对实对称矩阵 $A$ 作正交对角化 $Q^T A Q = \Lambda$，则 $f = x^T A x = (Qy)^T A (Qy) = y^T \Lambda y = \lambda_1 y_1^2 + \cdots + \lambda_n y_n^2$。正交变换不改变几何形状（保距变换）。
      - **配方法**（无需特征值，直接配方）：
        每次选一个平方项 $x_i^2$，将所有含 $x_i$ 的项配成完全平方；若无平方项，先用 $x_1 = y_1+y_2, x_2 = y_1-y_2$ 造出平方项再配。变换矩阵 $C$ 可逆但不一定正交，最终 $f = d_1 z_1^2 + \cdots + d_n z_n^2$。
        例：$f = x_1^2 + 2x_1x_2 + 3x_2^2 = (x_1+x_2)^2 + 2x_2^2$，令 $y_1=x_1+x_2, y_2=x_2$，得 $f = y_1^2 + 2y_2^2$。
    - **正定性判定**：
      - $A$ 正定 $\iff$ 所有特征值 $> 0$ $\iff$ 各阶顺序主子式 $> 0$
      - $A$ 负定 $\iff$ 所有特征值 $< 0$ $\iff$ 奇数阶主子式 $< 0$，偶数阶 $> 0$
    - **合同**：$A$ 与 $B$ 合同 $\iff$ 存在可逆 $C$ 使 $B = C^T A C$。合同保持正负惯性指数不变。
    - **正定二次型与正定矩阵**：
      - **正定二次型**：对任意非零向量 $\vec{x} \neq \vec{0}$，恒有 $f(\vec{x}) = \vec{x}^T A \vec{x} > 0$。
      - **正定矩阵**：若 $A$ 满足正定二次型，则 $A$ 称为正定矩阵。
      - **充要条件**（以下等价）：
        $$
        \begin{cases}
          \text{所有特征值 } \lambda_i > 0 \\
          \text{各阶顺序主子式 } > 0 \text{（Sylvester 定理）} \\
          \text{存在可逆矩阵 } P \text{ 使 } A = P^T P \\
          \text{$A$ 与单位矩阵 $I$ 合同}
        \end{cases}
        $$
      - **性质**：正定矩阵的行列式 $> 0$，对角元 $> 0$，可逆，逆矩阵也正定。
      - **半正定**：$\vec{x}^T A \vec{x} \ge 0$（允许为 $0$），特征值 $\ge 0$，主子式 $\ge 0$。
  - 施密特正交化（Schmidt Orthogonalization）
    将线性无关向量组 $\alpha_1, \alpha_2, \ldots, \alpha_n$ 化为正交向量组 $\beta_1, \beta_2, \ldots, \beta_n$：

    $$\begin{aligned}
    \beta_1 &= \alpha_1 \\[4pt]
    \beta_2 &= \alpha_2 - \frac{(\alpha_2, \beta_1)}{(\beta_1, \beta_1)} \beta_1 \\[4pt]
    \beta_3 &= \alpha_3 - \frac{(\alpha_3, \beta_1)}{(\beta_1, \beta_1)} \beta_1 - \frac{(\alpha_3, \beta_2)}{(\beta_2, \beta_2)} \beta_2 \\[4pt]
    &\ \ \vdots \\[4pt]
    \beta_n &= \alpha_n - \sum_{i=1}^{n-1} \frac{(\alpha_n, \beta_i)}{(\beta_i, \beta_i)} \beta_i
    \end{aligned}$$

    其中 $(\alpha, \beta)$ 表示内积（点乘）。

    再**单位化**得标准正交基：$\displaystyle e_i = \frac{\beta_i}{\lVert\beta_i\rVert}$
  - 特征值与特征向量
    设 $A$ 为 $n$ 阶方阵，若 $A\vec{x} = \lambda\vec{x}$（$\vec{x} \neq \vec{0}$），则 $\lambda$ 为**特征值**，$\vec{x}$ 为对应的**特征向量**。

    由 $|\lambda E - A| = 0$ 求特征值，代入 $(\lambda E - A)\vec{x} = 0$ 求特征向量。

    - 特征值之和等于迹：$\sum\lambda_i = \operatorname{tr}(A)$
    - 特征值之积等于行列式：$\prod\lambda_i = |A|$
    - 不同特征值对应的特征向量线性无关
  - 矩阵相似对角化
    若 $A$ 有 $n$ 个线性无关的特征向量，则 $A$ 可对角化：

    $$P^{-1}AP = \Lambda = \begin{pmatrix}
    \lambda_1 & & \\
    & \ddots & \\
    & & \lambda_n
    \end{pmatrix}$$

    其中 $P$ 的列为对应的特征向量。**实对称矩阵必定可对角化**，且存在正交矩阵 $Q$ 使 $Q^{-1}AQ = \Lambda$。
  - 二次型
    $n$ 元二次齐次多项式 $f(\vec{x}) = \vec{x}^T A \vec{x}$（$A$ 为实对称矩阵）。

    通过正交变换 $\vec{x} = Q\vec{y}$ 化为**标准形**：

    $$f = \lambda_1 y_1^2 + \lambda_2 y_2^2 + \cdots + \lambda_n y_n^2$$

    正定判定：$A$ 的特征值全为正 $\Leftrightarrow$ 各阶顺序主子式 $> 0$。
- 计算机<!-- markmap: foldAll -->
  - 数据结构 45
    - 0 绪论
      - 数据结构的基本概念
        - 数据
          - 数据项(类似于变量)
          - 数据元素(类似于结构体)
          - 数据对象(元素的集合)
          - 数据结构(元素的关系)
      - 数据结构的三要素
        - 逻辑结构
          - 集合结构
          - 线性结构 1 - 1
          - 树形结构 1 - n
          - 图状结构 n - n
        - 数据的运算
        - 物理结构(存储结构)
          - 顺序存储
          - 链式存储
          - 索引存储
          - 散列存储
      - 算法的基本概念
        - 什么是算法
        - 算法的五个特性
          - 有穷性
          - 确定性
          - 可行性
          - 输入
          - 输出
        - 好算法的特质 
          - 正确性
          - 可读性
          - 健壮性
          - 高效率和低存储
      - 时间复杂度
      - 空间复杂度
    - 1 线性表
      - 定义(逻辑结构)：$n$ 个**相同特性**数据元素的**有限序列** $(a_1,a_2,\ldots,a_n)$。除首元素外每个有唯一前驱，除尾元素外每个有唯一后继。$n=0$ 为空表。
      - 基本操作(运算)：
        - 构造操作：**InitList(&L)**（初始化，分配空间）、**DestroyList(&L)**（销毁，释放空间）、**ClearList(&L)**（置空，逻辑清空不释放）。
        - **InsertList(&L, i, e)**：在第 $i$ 个位置插入元素 $e$，顺序表需移动后续元素 $O(n)$，单链表 $O(1)$（已知位置）。
        - **DeleteList(&L, i, &e)**：删除第 $i$ 个位置的元素，用 $e$ 返回被删值，顺序表需移动后续元素 $O(n)$，单链表 $O(1)$（已知位置）。
        - **GetElem(L, i, &e)**：按位置查找，获取第 $i$ 个元素用 $e$ 返回，顺序表 $O(1)$，单链表 $O(n)$。
        - **LocateElem(L, e)**：按值查找，返回第一个等于 $e$ 的元素位置，顺序表 $O(n)$，单链表 $O(n)$。
        - **ListLength(L)**：求表长，返回表中元素个数，顺序表 $O(1)$，单链表需遍历 $O(n)$。
        - **PrintList(L)**：打印表，依次输出所有元素，顺序表和单链表均为 $O(n)$。
        - **Empty(L)**：判空，表空返回真，否则返回假，$O(1)$。
        - 空间：顺序表预分配可能浪费，单链表动态有指针开销
      - 物理存储：
        - **顺序存储**（顺序表）：地址连续，随机存取 $O(1)$，插入删除需移动元素 $O(n)$。
          - **静态分配**：数组大小编译期确定，容量不可变。
            ```cpp
            #include <stdio.h>
            #define MaxSize 100
            typedef struct {
                ElemType data[MaxSize];  // 静态数组
                int length;              // 当前表长
            } SqList;
            ```
            - 初始化：
              ```cpp
              void InitList(SqList &L) {
                  L.length = 0;
              }
              ```
            - 插入：检查是否满以及 $i$ 合法性，从末尾到 $i$ 依次后移，放入新元素，`length++`。
              ```cpp
              bool InsertList(SqList &L, int i, ElemType e) {
                  if (i < 1 || i > L.length + 1)  // i 非法
                      return false;
                  if (L.length >= MaxSize)        // 表满
                      return false;
                  for (int j = L.length; j >= i; j--)
                      L.data[j] = L.data[j - 1];  // 后移
                  L.data[i - 1] = e;               // 放入
                  L.length++;
                  return true;
              }
              ```
              - 时间复杂度：
                - **最好** $O(1)$：插入表尾（$i = n+1$），无需移动元素
                - **最坏** $O(n)$：插入表头（$i = 1$），所有 $n$ 个元素后移
                - **平均** $O(n)$：设 $p_i$ 为插入到第 $i$ 个位置的等概率，$p_i = \frac{1}{n+1}$，需移动 $n-i+1$ 个元素，期望移动次数 $\displaystyle\sum_{i=1}^{n+1}\frac{1}{n+1}(n-i+1)=\frac{1}{n+1}\cdot\frac{n(n+1)}{2}=\frac{n}{2}$
            - 删除：检查是否空及 $i$ 合法性，取出 $i$ 位置值，$i+1$ 到末尾依次前移，`length--`。
              ```cpp
              bool DeleteList(SqList &L, int i, ElemType &e) {
                  if (i < 1 || i > L.length)       // i 非法
                      return false;
                  e = L.data[i - 1];               // 取值
                  for (int j = i; j < L.length; j++)
                      L.data[j - 1] = L.data[j];   // 前移
                  L.length--;
                  return true;
              }
              ```
              - 时间复杂度：
                - **最好** $O(1)$：删除表尾（$i = n$），无需移动元素
                - **最坏** $O(n)$：删除表头（$i = 1$），所有 $n-1$ 个元素前移
                - **平均** $O(n)$：等概率 $p_i = \frac{1}{n}$，期望移动次数 $\displaystyle\sum_{i=1}^{n}\frac{1}{n}(n-i)=\frac{1}{n}\cdot\frac{n(n-1)}{2}=\frac{n-1}{2}$
            - 按位查找：随机存取，直接通过下标访问。
              ```cpp
              bool GetElem(SqList L, int i, ElemType &e) {
                  if (i < 1 || i > L.length)       // i 非法
                      return false;
                  e = L.data[i - 1];               // 下标 = i - 1
                  return true;
              }
              ```
              - 时间复杂度：$O(1)$
            - 按值查找：遍历比较，返回第一个匹配位置（0 表示未找到）。
              ```cpp
              int LocateElem(SqList L, ElemType e) {
                  for (int i = 0; i < L.length; i++)
                      if (L.data[i] == e)
                          return i + 1;            // 返回位序(从1开始)
                  return 0;                         // 未找到
              }
              ```
              - 时间复杂度：
                - **最好** $O(1)$：第一个元素即命中
                - **最坏** $O(n)$：未找到或最后一个
                - **平均** $O(n)$：设等概率 $p_i = \frac{1}{n}$（查找各位置及未找到共 $n+1$ 种结果），期望比较次数 $\displaystyle\sum_{i=1}^{n}\frac{1}{n}\cdot i + \frac{1}{n}\cdot n = \frac{n+1}{2}+1 = \frac{n+3}{2}$（若只计成功查找则为 $\frac{n+1}{2}$）
            - 求表长：
              ```cpp
              int ListLength(SqList L) {
                  return L.length;      // 直接返回 length
              }
              ```
              - 时间复杂度：$O(1)$
            - 判空：
              ```cpp
              bool Empty(SqList L) {
                  return L.length == 0;
              }
              ```
              - 时间复杂度：$O(1)$
            - 打印表：
              ```cpp
              void PrintList(SqList L) {
                  for (int i = 0; i < L.length; i++)
                      printf("%d ", L.data[i]);
                  printf("\n");
              }
              ```
              - 时间复杂度：$O(n)$
            - 置空（逻辑清空，不释放空间）：
              ```cpp
              void ClearList(SqList &L) {
                  L.length = 0;
              }
              ```
              - 时间复杂度：$O(1)$
            - 销毁（静态分配无动态空间，无需 `free`）：
              ```cpp
              void DestroyList(SqList &L) {
                  // 静态数组由系统回收，无需手动释放
                  L.length = 0;
              }
              ```
              - 时间复杂度：$O(1)$
            - 优点：代码简单，无需内存分配
            - 缺点：MaxSize 需预估，开太大浪费空间，开太小不够用
          - **动态分配**：运行时分配空间，容量可扩展。
            ```cpp
            #include <stdio.h>
            #include <stdlib.h>
            #define InitSize 100
            typedef struct {
                ElemType *data;   // 指向动态分配数组的指针
                int MaxSize;      // 最大容量
                int length;       // 当前表长
            } SeqList;
            ```
            - 初始化：
              ```cpp
              void InitList(SeqList &L) {
                  L.data = (ElemType*)malloc(InitSize * sizeof(ElemType));
                  L.MaxSize = InitSize;
                  L.length = 0;
              }
              ```
            - 扩容：表满时用 `realloc` 或重新 `malloc` 一块更大的空间，数据拷贝过去，释放旧空间，更新 `MaxSize`（通常扩为原来的 $2$ 倍）。
              ```cpp
              void IncreaseSize(SeqList &L, int len) {
                  ElemType *p = L.data;
                  L.data = (ElemType*)malloc((L.MaxSize + len) * sizeof(ElemType));
                  for (int i = 0; i < L.length; i++)
                      L.data[i] = p[i];       // 拷贝旧数据
                  L.MaxSize += len;            // 更新最大容量
                  free(p);                     // 释放旧空间
              }
              ```
            - 插入删除操作逻辑与静态分配相同，多了扩容判断
            - 销毁（动态分配需释放堆空间）：
              ```cpp
              void DestroyList(SeqList &L) {
                  free(L.data);         // 释放堆区数组
                  L.data = NULL;        // 指针置空，防止野指针
                  L.MaxSize = 0;
                  L.length = 0;
              }
              ```
              - 时间复杂度：$O(1)$
            - 求表长、判空、打印、置空与静态分配相同（`ListLength` 返回 `L.length`、`Empty` 判断 `length == 0` 等）
            - 优点：容量可按需扩展，避免预判空间
            - 缺点：`malloc`/`realloc` 有时间开销，可能需移动大块数据
        - **链式存储**（链表）：结点 $=$ 数据域 $+$ 指针域，不要求连续空间，插入删除 $O(1)$（已知位置），查找需遍历 $O(n)$。分为单链表、双链表、循环链表、静态链表。
          - **单链表**：
            - **单链表结点定义**：
              ```cpp
              typedef struct LNode {
                  ElemType data;          // 数据域
                  struct LNode *next;     // 指针域
              } LNode, *LinkList;
              ```
            - **头结点**：不存储数据（或存长度），统一空表与非空表操作，方便在表头插入删除。不带头结点则需特殊处理。
            - 初始化：
              - 不带头结点：`L = NULL`（空表）。
              - 带头结点：
                ```cpp
                bool InitList(LinkList &L) {
                    L = (LNode*)malloc(sizeof(LNode));
                    if (L == NULL) return false;   // 分配失败
                    L->next = NULL;
                    return true;
                }
                ```
            - 建表（带头结点）：
              - **头插法**：每次新结点插入到表头（头结点之后），读入顺序与链表顺序**相反**，$O(n)$。
                ```cpp
                LinkList List_HeadInsert(LinkList &L) {
                    L = (LNode*)malloc(sizeof(LNode));
                    L->next = NULL;
                    LNode *s; ElemType x;
                    while (/* 读取x */) {
                        s = (LNode*)malloc(sizeof(LNode));
                        s->data = x;
                        s->next = L->next;
                        L->next = s;
                    }
                    return L;
                }
                ```
              - **尾插法**：每次新结点插入到表尾，需尾指针 `r`，读入顺序与链表顺序**相同**，$O(n)$。
                ```cpp
                LinkList List_TailInsert(LinkList &L) {
                    L = (LNode*)malloc(sizeof(LNode));
                    LNode *s, *r = L;    // r 指向尾结点
                    ElemType x;
                    while (/* 读取x */) {
                        s = (LNode*)malloc(sizeof(LNode));
                        s->data = x;
                        r->next = s;
                        r = s;           // r 指向新的尾结点
                    }
                    r->next = NULL;
                    return L;
                }
                ```
            - 插入（带头结点，在第 $i$ 个位置插 $e$）：用 `GetElem` 找到第 $i-1$ 个结点 $p$，再调用 `InsertNextNode` 后插。
              ```cpp
              bool InsertList(LinkList &L, int i, ElemType e) {
                  if (i < 1) return false;
                  LNode *p = GetElem(L, i - 1);      // 找第 i-1 个结点
                  if (p == NULL) return false;
                  return InsertNextNode(p, e);        // 后插
              }
              ```
              - 时间复杂度：
                - **最好** $O(1)$：插入表头（$i = 1$），仅需一次 `p = L` 即找到前驱
                - **最坏** $O(n)$：插入表尾（$i = n+1$），需遍历 $n$ 个结点找到第 $n$ 个结点
                - **平均** $O(n)$：等概率 $p_i = \frac{1}{n+1}$，查找前驱需比较 $i-1$ 次，期望 $\displaystyle\sum_{i=1}^{n+1}\frac{1}{n+1}(i-1)=\frac{1}{n+1}\cdot\frac{n(n+1)}{2}=\frac{n}{2}$
            - 插入（不带头结点）：$i=1$ 时需特殊处理，修改头指针 `L` 本身；$i>1$ 时找到第 $i-1$ 个结点后调用 `InsertNextNode`。
              ```cpp
              bool InsertList(LinkList &L, int i, ElemType e) {
                  if (i < 1) return false;
                  if (i == 1) {                        // 插入表头，特殊处理
                      LNode *s = (LNode*)malloc(sizeof(LNode));
                      s->data = e;
                      s->next = L;
                      L = s;
                      return true;
                  }
                  LNode *p = L;
                  int j = 1;                           // 从第1个结点开始
                  while (p != NULL && j < i - 1) {     // 找第 i-1 个结点
                      p = p->next;
                      j++;
                  }
                  if (p == NULL) return false;
                  return InsertNextNode(p, e);         // 后插
              }
              ```
              - **带头结点 vs 不带头结点**：带头结点统一了所有位置的插入逻辑，无需对 $i=1$ 特殊处理，代码更简洁。
              - **InsertNextNode(&p, e)**：在已知结点 `*p` 之后插入元素 $e$，$O(1)$。
                ```cpp
                bool InsertNextNode(LNode *p, ElemType e) {
                    if (p == NULL) return false;
                    LNode *s = (LNode*)malloc(sizeof(LNode));
                    if (s == NULL) return false;      // 分配失败
                    s->data = e;
                    s->next = p->next;
                    p->next = s;
                    return true;
                }
                ```
              - **InsertPriorNode(&p, e)**：在已知结点 `*p` 之前插入元素 $e$。由于单链表无法直接找到前驱，先执行后插，再交换 `p` 与新结点的 `data`，同样 $O(1)$。
                ```cpp
                bool InsertPriorNode(LNode *p, ElemType e) {
                    if (p == NULL) return false;
                    LNode *s = (LNode*)malloc(sizeof(LNode));
                    if (s == NULL) return false;
                    s->next = p->next;
                    p->next = s;                  // 后插
                    s->data = p->data;            // 交换数据
                    p->data = e;
                    return true;
                }
                ```
            - 删除（带头结点，删除第 $i$ 个位置，用 `e` 返回）：用 `GetElem` 找第 $i-1$ 个结点 $p$，再删除其后继。
              ```cpp
              bool DeleteList(LinkList &L, int i, ElemType &e) {
                  if (i < 1) return false;
                  LNode *p = GetElem(L, i - 1);      // 找第 i-1 个结点
                  if (p == NULL || p->next == NULL) return false;
                  LNode *q = p->next;                // q 指向被删结点
                  e = q->data;
                  p->next = q->next;
                  free(q);
                  return true;
              }
              ```
              - 时间复杂度：
                - **最好** $O(1)$：删除表头（$i = 1$），`p = L` 即找到前驱，无需遍历
                - **最坏** $O(n)$：删除表尾（$i = n$），需遍历 $n$ 个结点找到第 $n-1$ 个结点
                - **平均** $O(n)$：等概率 $p_i = \frac{1}{n}$，查找前驱需比较 $i-1$ 次，期望 $\displaystyle\sum_{i=1}^{n}\frac{1}{n}(i-1)=\frac{1}{n}\cdot\frac{n(n-1)}{2}=\frac{n-1}{2}$
            - **DeleteNode(&p, &e)**：删除指定结点 `*p`，用 `e` 返回被删值。将其后继数据复制到自身，再删后继，$O(1)$。
              ```cpp
              bool DeleteNode(LNode *p, ElemType &e) {
                  if (p == NULL || p->next == NULL) return false;  // 尾结点无法用此法
                  LNode *q = p->next;        // q 是后继
                  e = p->data;               // 返回 p 的值
                  p->data = q->data;         // 后继数据复制到 p
                  p->next = q->next;         // 跳过 q
                  free(q);
                  return true;
              }
              ```
              - 注意：若 `p` 是尾结点（`p->next == NULL`），则无法用此法，需从头遍历找前驱。
            - 查找：
              - 按位查找：
                ```cpp
                LNode* GetElem(LinkList L, int i) {
                    if (i < 0) return NULL;
                    LNode *p = L;
                    int j = 0;
                    while (p != NULL && j < i) {
                        p = p->next;
                        j++;
                    }
                    return p;    // 返回第 i 个结点指针，i=0 返回头结点
                }
                ```
                - 时间复杂度：$O(n)$
              - 按值查找：
                ```cpp
                LNode* LocateElem(LinkList L, ElemType e) {
                    LNode *p = L->next;              // 跳过头结点
                    while (p != NULL && p->data != e)
                        p = p->next;
                    return p;    // 找到返回结点指针，否则返回 NULL
                }
                ```
                - 时间复杂度：$O(n)$
            - 求表长（带头结点）：遍历计数，$O(n)$。
              ```cpp
              int ListLength(LinkList L) {
                  int len = 0;
                  LNode *p = L->next;
                  while (p != NULL) {
                      len++;
                      p = p->next;
                  }
                  return len;
              }
              ```
            - 判空（带头结点）：`L->next == NULL`，$O(1)$。
            - 逆置（原地翻转）：逐个头插法思想，$O(n)$。
              ```cpp
              void ReverseList(LinkList &L) {
                  LNode *p = L->next, *q;
                  L->next = NULL;
                  while (p != NULL) {
                      q = p->next;       // 暂存后继
                      p->next = L->next; // 头插
                      L->next = p;
                      p = q;
                  }
              }
              ```
            - 优缺点：
              - 优点：不需要连续空间，插入删除 $O(1)$（已知位置），动态分配不浪费
              - 缺点：查找需遍历 $O(n)$，指针域额外占用空间
          - **双链表**：每个结点有两个指针 `prior` 和 `next`，可双向遍历，但指针开销更大。
            - 结点定义：
              ```cpp
              typedef struct DNode {
                  ElemType data;
                  struct DNode *prior, *next;
              } DNode, *DLinkList;
              ```
            - 初始化（带头结点）：
              ```cpp
              bool InitDLinkList(DLinkList &L) {
                  L = (DNode*)malloc(sizeof(DNode));
                  if (L == NULL) return false;
                  L->prior = NULL;
                  L->next = NULL;
                  return true;
              }
              ```
            - 判空：
              ```cpp
              bool Empty(DLinkList L) {
                  return L->next == NULL;
              }
              ```
              - 时间复杂度：$O(1)$
            - 销毁（释放所有结点，包括头结点）：
              ```cpp
              void DestroyList(DLinkList &L) {
                  DNode *p = L, *q;
                  while (p != NULL) {
                      q = p->next;
                      free(p);
                      p = q;
                  }
                  L = NULL;
              }
              ```
              - 时间复杂度：$O(n)$
            - 插入（在 `*p` 之后插入 `*s`）：修改 4 根指针，注意顺序。
              ```cpp
              bool InsertNextDNode(DNode *p, DNode *s) {
                  if (p == NULL || s == NULL) return false;
                  s->next = p->next;        // ① s 后继
                  if (p->next != NULL)
                      p->next->prior = s;   // ② 原后继的前驱
                  s->prior = p;             // ③ s 前驱
                  p->next = s;              // ④ p 后继
                  return true;
              }
              ```
              - 时间复杂度：$O(1)$
            - 删除（删除 `*p` 的后继结点 `*q`）：修改 2 根指针。
              ```cpp
              bool DeleteNextDNode(DNode *p, ElemType &e) {
                  if (p == NULL || p->next == NULL) return false;
                  DNode *q = p->next;        // q 是被删结点
                  e = q->data;
                  p->next = q->next;         // 跳过 q
                  if (q->next != NULL)
                      q->next->prior = p;    // q 后继的前驱
                  free(q);
                  return true;
              }
              ```
              - 时间复杂度：$O(1)$
            - 遍历（从表头到尾）：
              ```cpp
              void Traverse(DLinkList L) {
                  DNode *p = L->next;
                  while (p != NULL) {
                      // 访问 p->data
                      p = p->next;
                  }
              }
              ```
              - 时间复杂度：$O(n)$
            - 双链表优点：可双向遍历，找前驱 $O(1)$，删除指定结点无需复制数据
            - 双链表缺点：每个结点多一个指针，存储密度更低
          - **循环链表**：表中最后一个结点的指针域指向头结点，整个链表形成一个环。
            - **循环单链表**：
              - 结点定义同单链表，区别在于表尾 `next` 指向头结点。
              - 初始化（带头结点）：
                ```cpp
                bool InitCLinkList(LinkList &L) {
                    L = (LNode*)malloc(sizeof(LNode));
                    if (L == NULL) return false;
                    L->next = L;       // 头结点 next 指向自身
                    return true;
                }
                ```
              - 判空：
                ```cpp
                bool Empty(LinkList L) {
                    return L->next == L;
                }
                ```
                - 时间复杂度：$O(1)$
              - 判表尾：当前结点 `p->next == L` 时为表尾。
              - 遍历：
                ```cpp
                void Traverse(LinkList L) {
                    LNode *p = L->next;
                    while (p != L) {     // p != L 作为结束条件
                        // 访问 p->data
                        p = p->next;
                    }
                }
                ```
                - 时间复杂度：$O(n)$
              - 循环单链表优点：从任意结点出发都可遍历全表，合并两个表只需修改两个尾结点指针 $O(1)$。
              - 循环单链表缺点：无 `NULL` 标记，遍历时需注意循环结束条件，否则会死循环。
            - **循环双链表**：
              - 结点定义同双链表，区别在于头结点的 `prior` 指向尾结点，尾结点的 `next` 指向头结点。
              - 初始化（带头结点）：
                ```cpp
                bool InitCDLinkList(DLinkList &L) {
                    L = (DNode*)malloc(sizeof(DNode));
                    if (L == NULL) return false;
                    L->prior = L;       // 头结点的 prior 指向自身
                    L->next = L;        // 头结点的 next 指向自身
                    return true;
                }
                ```
              - 判空：
                ```cpp
                bool Empty(DLinkList L) {
                    return L->next == L;
                }
                ```
                - 时间复杂度：$O(1)$
              - 判表尾（`*p` 是否为最后一个结点）：
                ```cpp
                bool isTail(DLinkList L, DNode *p) {
                    return p->next == L;
                }
                ```
                - 时间复杂度：$O(1)$
              - 插入（在 `*p` 之后插入 `*s`，无需判断 `p->next` 是否为 `NULL`）：
                ```cpp
                bool InsertNextDNode(DNode *p, DNode *s) {
                    if (p == NULL || s == NULL) return false;
                    s->next = p->next;
                    p->next->prior = s;   // 必有后继（至少是头结点）
                    s->prior = p;
                    p->next = s;
                    return true;
                }
                ```
                - 时间复杂度：$O(1)$
              - 删除（删除 `*p` 的后继结点，无需判断后继是否为 `NULL`）：
                ```cpp
                bool DeleteNextDNode(DNode *p, ElemType &e) {
                    if (p == NULL || p->next == p) return false;
                    DNode *q = p->next;
                    e = q->data;
                    p->next = q->next;
                    q->next->prior = p;
                    free(q);
                    return true;
                }
                ```
                - 时间复杂度：$O(1)$
              - 遍历：
                ```cpp
                void Traverse(DLinkList L) {
                    DNode *p = L->next;
                    while (p != L) {     // p != L 作为结束条件
                        // 访问 p->data
                        p = p->next;
                    }
                }
                ```
                - 时间复杂度：$O(n)$
              - 循环双链表优点：插入删除代码统一（无需判 `NULL`），双向 + 循环更灵活。
              - 循环双链表缺点：指针开销更大（两个指针域），存储密度较低。
          - **静态链表**：用数组描述链式结构，每个结点包含数据域和游标（`cur`，存下一结点在数组中的下标），插入删除与单链表一致，但无需动态分配。
            - 结点定义：
              ```cpp
              #define MaxSize 50
              typedef struct {
                  ElemType data;
                  int cur;    // 游标，指向下一结点在数组中的下标
              } SLinkList[MaxSize];   // 等价于 struct Node a[MaxSize]
              ```
            - 空闲结点与头结点：数组中未被使用的结点组成空闲链表，`cur = -1` 表示表尾（也有教材用 `0` 表示空指针）。头结点下标为 `0`。
            - 初始化（把所有结点的 `cur` 连成空闲链表）：
              ```cpp
              void InitSLinkList(SLinkList a) {
                  for (int i = 0; i < MaxSize - 1; i++)
                      a[i].cur = i + 1;   // 每个结点指向下一个
                  a[MaxSize - 1].cur = -1; // 末尾为空
              }
              ```
            - 分配空闲结点：
              ```cpp
              int MallocNode(SLinkList a) {
                  int p = a[0].cur;        // 第一个空闲结点
                  if (p != -1)
                      a[0].cur = a[p].cur; // 头结点指向下一个空闲结点
                  return p;
              }
              ```
            - 释放结点（把结点 `p` 归还空闲链表）：
              ```cpp
              void FreeNode(SLinkList a, int p) {
                  a[p].cur = a[0].cur;     // 头插回空闲链表
                  a[0].cur = p;
              }
              ```
            - 按位置查找第 $i$ 个结点：
              ```cpp
              int GetElem(SLinkList a, int i) {
                  int p = a[0].cur;        // 从第一个数据结点开始
                  int j = 1;
                  while (p != -1 && j < i) {
                      p = a[p].cur;
                      j++;
                  }
                  return p;   // 返回结点下标，-1 表示不存在
              }
              ```
              - 时间复杂度：$O(n)$
            - 插入（在第 $i$ 个位置插入 `e`）：
              ```cpp
              bool InsertSList(SLinkList a, int i, ElemType e) {
                  int q = MallocNode(a);
                  if (q == -1) return false;   // 空间已满
                  a[q].data = e;
                  int p = 0;                   // 从头结点开始找前驱
                  int j = 0;
                  while (p != -1 && j < i - 1) {
                      p = a[p].cur;
                      j++;
                  }
                  if (p == -1) { FreeNode(a, q); return false; } // 位置非法
                  a[q].cur = a[p].cur;
                  a[p].cur = q;
                  return true;
              }
              ```
              - 时间复杂度：$O(n)$
            - 删除（删除第 $i$ 个结点，用 `e` 返回被删值）：
              ```cpp
              bool DeleteSList(SLinkList a, int i, ElemType &e) {
                  int p = 0;                 // 从头结点开始找前驱
                  int j = 0;
                  while (p != -1 && j < i - 1) {
                      p = a[p].cur;
                      j++;
                  }
                  if (p == -1 || a[p].cur == -1) return false;
                  int q = a[p].cur;          // q 是被删结点
                  e = a[q].data;
                  a[p].cur = a[q].cur;
                  FreeNode(a, q);
                  return true;
              }
              ```
              - 时间复杂度：$O(n)$
            - 静态链表优点：无需动态分配内存，结点位置固定，适合不支持指针的语言（如早期 BASIC、FORTRAN）。
            - 静态链表缺点：容量固定（`MaxSize`）不能扩展；游标代替指针，逻辑上仍是顺序存取，查找仍需 $O(n)$；不便于表长变化大的场景。
        - 顺序表 vs 链表对比：
          - 逻辑结构：两者都是线性结构，元素之间都是一对一的线性关系，逻辑上完全相同。
          - 存储结构：
            - 顺序表：顺序存储，逻辑上相邻的元素在物理地址上也相邻，占用连续存储空间，存储密度大（$=1$），支持随机存取 $O(1)$；空间预分配/动态分配，可能浪费或需扩容搬运。
            - 链表：链式存储，逻辑上相邻的元素在物理地址上不一定相邻，通过指针链接，占用非连续空间，存储密度低（有指针开销），仅支持顺序存取 $O(n)$；空间动态分配，按需申请。
          - 基本操作：
            - 初始化：顺序表设置 `length = 0`（动态分配需 `malloc`）；链表分配头结点（带头结点）或置 `NULL`（不带头结点）
            - 插入：顺序表后移元素 $O(n)$（平均 $\frac{n}{2}$）；链表改指针 $O(1)$（已知位置，找前驱仍需 $O(n)$）
            - 删除：顺序表前移元素 $O(n)$（平均 $\frac{n-1}{2}$）；链表改指针 $O(1)$（已知位置）
            - 按位查找：顺序表下标直接访问 $O(1)$；链表从头遍历 $O(n)$
            - 按值查找：两者都需遍历比较，$O(n)$
            - 求表长：顺序表返回 `length` $O(1)$；链表需遍历计数 $O(n)$（带头结点表）
            - 判空：顺序表判断 `length == 0` $O(1)$；链表判断 `L->next == NULL`（带头结点）或 `L == NULL`（不带头结点）$O(1)$
            - 销毁：顺序表置空即可（动态分配需 `free`）；链表逐结点 `free` $O(n)$
          - 适用场景：表长固定且查找多 → 顺序表；表长变化大且插入删除多 → 链表；频繁取第 $i$ 个 → 顺序表
    - 2 栈和队列
      - 栈
        - 逻辑结构（定义）：**后进先出（LIFO）** 的受限线性表，只允许在一端（栈顶 `top`）插入和删除，另一端为栈底（`bottom`）。$n=0$ 为空栈。
        - 基本操作（运算）：
          - **InitStack(&S)**：初始化空栈
          - **StackEmpty(S)**：判空，空栈返回真
          - **Push(&S, e)**：入栈，元素 $e$ 压入栈顶
          - **Pop(&S, &e)**：出栈，栈顶元素弹出并用 $e$ 返回
            - 出栈序列个数（卡特兰数）：$n$ 个不同元素依次入栈，可能的出栈序列共有 $\displaystyle\frac{1}{n+1}\binom{2n}{n}=\frac{(2n)!}{(n+1)!\cdot n!}$ 种
              - 例：$n=3$ 时有 $\frac{1}{4}\binom{6}{3}=5$ 种，合法出栈序列为 $123, 132, 213, 231, 321$；而 $312$ 非法（$3$ 出栈时 $2$ 必在其上）
          - **GetTop(S, &e)**：读栈顶，仅读取不弹出
          - **DestroyStack(&S)**：销毁栈
        - 存储结构：
          - 顺序栈（数组 + 栈顶指针）：
            - 结点定义：
              ```cpp
              #define MaxSize 50
              typedef struct {
                  ElemType data[MaxSize];
                  int top;            // 栈顶指针，指向栈顶元素
              } SqStack;
              ```
            - 初始化（`top = -1` 表示空栈）：
              ```cpp
              void InitStack(SqStack &S) {
                  S.top = -1;
              }
              ```
            - 判空：
              ```cpp
              bool StackEmpty(SqStack S) {
                  return S.top == -1;
              }
              ```
              - 时间复杂度：$O(1)$
            - 入栈（先判栈满，`top` 加一后赋值）：
              ```cpp
              bool Push(SqStack &S, ElemType e) {
                  if (S.top == MaxSize - 1)   // 栈满（上溢）
                      return false;
                  S.data[++S.top] = e;
                  return true;
              }
              ```
              - 时间复杂度：$O(1)$
            - 出栈（先判栈空，取值后 `top` 减一）：
              ```cpp
              bool Pop(SqStack &S, ElemType &e) {
                  if (S.top == -1)            // 栈空（下溢）
                      return false;
                  e = S.data[S.top--];
                  return true;
              }
              ```
              - 时间复杂度：$O(1)$
            - 读栈顶：
              ```cpp
              bool GetTop(SqStack S, ElemType &e) {
                  if (S.top == -1) return false;
                  e = S.data[S.top];
                  return true;
              }
              ```
              - 时间复杂度：$O(1)$
            - 缺点：容量固定可能溢出；可用"共享栈"让两个栈共用一个数组，各自从两端向中间生长
          - 链栈（单链表实现，头插头删，不带头结点）：
            - 结点定义：
              ```cpp
              typedef struct SNode {
                  ElemType data;
                  struct SNode *next;
              } SNode, *LiStack;
              ```
            - 初始化（空栈 `S = NULL`）：
              ```cpp
              void InitStack(LiStack &S) {
                  S = NULL;
              }
              ```
            - 判空：
              ```cpp
              bool StackEmpty(LiStack S) {
                  return S == NULL;
              }
              ```
              - 时间复杂度：$O(1)$
            - 入栈（头插法）：
              ```cpp
              bool Push(LiStack &S, ElemType e) {
                  SNode *p = (SNode*)malloc(sizeof(SNode));
                  if (p == NULL) return false;
                  p->data = e;
                  p->next = S;
                  S = p;              // 新结点成为栈顶
                  return true;
              }
              ```
              - 时间复杂度：$O(1)$
            - 出栈（头删法）：
              ```cpp
              bool Pop(LiStack &S, ElemType &e) {
                  if (S == NULL) return false;
                  SNode *p = S;
                  e = p->data;
                  S = S->next;
                  free(p);
                  return true;
              }
              ```
              - 时间复杂度：$O(1)$
            - 优点：不会栈满（除非内存耗尽），容量动态扩展
        - 应用：
          - 括号匹配：扫描表达式，遇左括号 `(` `[` `{` 入栈，遇右括号时栈顶应为其匹配的左括号，否则不匹配；扫描结束栈空则全部匹配。
            - 实现：
              ```cpp
              bool BracketMatch(char str[], int n) {
                  SqStack S;
                  InitStack(S);
                  for (int i = 0; i < n; i++) {
                      if (str[i] == '(' || str[i] == '[' || str[i] == '{')
                          Push(S, str[i]);        // 左括号入栈
                      else if (str[i] == ')' || str[i] == ']' || str[i] == '}') {
                          if (StackEmpty(S)) return false;    // 右括号多
                          char top;
                          Pop(S, top);
                          if (!(top == '(' && str[i] == ')' ||
                                top == '[' && str[i] == ']' ||
                                top == '{' && str[i] == '}'))
                              return false;       // 类型不匹配
                      }
                  }
                  return StackEmpty(S);            // 栈空则全匹配
              }
              ```
              - 时间复杂度：$O(n)$
          - 表达式求值（中缀转后缀 + 后缀求值）后缀先算输入流左边的，前缀先算输入流右边的：
            - 中缀转后缀（从左到右扫描，操作数直接输出；运算符入栈，遇右括号弹出至左括号；栈顶优先级高于或等于当前运算符时弹出）：
              ```cpp
              int Priority(char op) {     // 优先级
                  if (op == '+' || op == '-') return 1;
                  if (op == '*' || op == '/') return 2;
                  return 0;
              }
              void InfixToPostfix(char infix[], int n, char postfix[], int &k) {
                  SqStack S;
                  InitStack(S);
                  k = 0;
                  for (int i = 0; i < n; i++) {
                      char c = infix[i];
                      if (c >= '0' && c <= '9') {          // 操作数直接输出
                          postfix[k++] = c;
                      } else if (c == '(') {
                          Push(S, c);
                      } else if (c == ')') {
                          while (!StackEmpty(S) && S.data[S.top] != '(') {
                              Pop(S, postfix[k++]);        // 弹出直到左括号
                          }
                          char t; Pop(S, t);               // 弹出 '('
                      } else {                             // 运算符
                          while (!StackEmpty(S) && S.data[S.top] != '(' &&
                                 Priority(S.data[S.top]) >= Priority(c))
                              Pop(S, postfix[k++]);
                          Push(S, c);
                      }
                  }
                  while (!StackEmpty(S))                   // 剩余运算符出栈
                      Pop(S, postfix[k++]);
                  postfix[k] = '\0';
              }
              ```
            - 后缀表达式求值（从左到右扫描，操作数入栈，遇运算符弹出两个操作数计算后压回）：
              ```cpp
              int EvalPostfix(char postfix[]) {
                  SqStack S;
                  InitStack(S);
                  for (int i = 0; postfix[i] != '\0'; i++) {
                      char c = postfix[i];
                      if (c >= '0' && c <= '9') {
                          Push(S, c - '0');                // 数字入栈
                      } else {
                          int a, b;
                          Pop(S, b);                       // 先出栈的是右操作数
                          Pop(S, a);                       // 后出栈的是左操作数
                          int r;
                          if (c == '+') r = a + b;
                          else if (c == '-') r = a - b;
                          else if (c == '*') r = a * b;
                          else r = a / b;
                          Push(S, r);
                      }
                  }
                  int res;
                  Pop(S, res);
                  return res;
              }
              ```
              - 时间复杂度：$O(n)$
          - 其他应用：递归转非递归、函数调用与返回、进制转换
      - 队列
        - 逻辑结构（定义）：**先进先出（FIFO）**的受限线性表，只允许在队尾（`rear`）插入、队头（`front`）删除。$n=0$ 为空队列。
        - 基本操作（运算）：
          - **InitQueue(&Q)**：初始化空队列
          - **QueueEmpty(Q)**：判空，空队列返回真
          - **EnQueue(&Q, e)**：入队，元素 $e$ 插入队尾
          - **DeQueue(&Q, &e)**：出队，队头元素删除并用 $e$ 返回
          - **GetHead(Q, &e)**：读队头元素，不删除
        - 存储结构：
          - 循环队列（顺序存储，解决"假溢出"）：
            - 结点定义（牺牲一个存储单元区分队空与队满）：
              ```cpp
              #define MaxSize 50
              typedef struct {
                  ElemType data[MaxSize];
                  int front, rear;    // 队头、队尾指针
              } SqQueue;
              ```
            - 初始化（`front = rear = 0`）：
              ```cpp
              void InitQueue(SqQueue &Q) {
                  Q.front = Q.rear = 0;
              }
              ```
            - 判空：
              ```cpp
              bool QueueEmpty(SqQueue Q) {
                  return Q.front == Q.rear;
              }
              ```
              - 时间复杂度：$O(1)$
            - 队满判断：`(Q.rear + 1) % MaxSize == Q.front`
            - 入队：
              ```cpp
              bool EnQueue(SqQueue &Q, ElemType e) {
                  if ((Q.rear + 1) % MaxSize == Q.front)  // 队满
                      return false;
                  Q.data[Q.rear] = e;
                  Q.rear = (Q.rear + 1) % MaxSize;        // 队尾指针循环后移
                  return true;
              }
              ```
              - 时间复杂度：$O(1)$
            - 出队：
              ```cpp
              bool DeQueue(SqQueue &Q, ElemType &e) {
                  if (Q.front == Q.rear)                   // 队空
                      return false;
                  e = Q.data[Q.front];
                  Q.front = (Q.front + 1) % MaxSize;       // 队头指针循环后移
                  return true;
              }
              ```
              - 时间复杂度：$O(1)$
            - 读队头（仅读取，不删除）：
              ```cpp
              bool GetHead(SqQueue Q, ElemType &e) {
                  if (Q.front == Q.rear)       // 队空
                      return false;
                  e = Q.data[Q.front];         // 队头元素
                  return true;
              }
              ```
              - 时间复杂度：$O(1)$
            - 队列长度（队中元素个数）：$(Q.rear - Q.front + MaxSize) \% MaxSize$
              - 推导：设 $f=front$，$r=rear$，$M=MaxSize$，$r \in [0,M-1]$，每入队一个元素 $r$ 循环加一。
                - 无回绕（$r \ge f$）：元素个数 $= r - f$
                - 有回绕（$r < f$）：$r$ 先走到 $M-1$ 又回到 $0$，元素个数 $= r + M - f$
                - 统一公式：$(r - f + M) \% M$（当 $r \ge f$ 时等于 $r-f$；当 $r < f$ 时等于 $r+M-f$）
              - 例：$M=8$，入队 $3$ 个后 $f=0,r=3$，个数 $=3$；再出队 $2$ 个 $f=2,r=3$，个数 $=1$；再入队 $6$ 个 $r$ 回绕到 $1$（$3+6=9 \to 9\%8=1$），$f=2,r=1$，个数 $=(1-2+8)\%8=7$
          - 链队列（带头结点，`front` 指向头结点）：
            - 结点定义：
              ```cpp
              typedef struct LNode {
                  ElemType data;
                  struct LNode *next;
              } LNode;
              typedef struct {
                  LNode *front, *rear;    // 队头、队尾指针
              } LinkQueue;
              ```
            - 初始化：
              ```cpp
              void InitQueue(LinkQueue &Q) {
                  Q.front = Q.rear = (LNode*)malloc(sizeof(LNode));
                  Q.front->next = NULL;
              }
              ```
            - 判空：
              ```cpp
              bool QueueEmpty(LinkQueue Q) {
                  return Q.front == Q.rear;
              }
              ```
              - 时间复杂度：$O(1)$
            - 入队（尾插法）：
              ```cpp
              bool EnQueue(LinkQueue &Q, ElemType e) {
                  LNode *p = (LNode*)malloc(sizeof(LNode));
                  if (p == NULL) return false;
                  p->data = e;
                  p->next = NULL;
                  Q.rear->next = p;       // 新结点链到队尾
                  Q.rear = p;             // 更新队尾指针
                  return true;
              }
              ```
              - 时间复杂度：$O(1)$
            - 出队（头删法）：
              ```cpp
              bool DeQueue(LinkQueue &Q, ElemType &e) {
                  if (Q.front == Q.rear) return false;    // 队空
                  LNode *p = Q.front->next;
                  e = p->data;
                  Q.front->next = p->next;
                  if (Q.rear == p)         // 队列中只有一个结点
                      Q.rear = Q.front;    // 置队尾 = 头结点
                  free(p);
                  return true;
              }
              ```
              - 时间复杂度：$O(1)$
        - 队列的应用：树的层次遍历、图的广度优先搜索（BFS）、操作系统进程调度（就绪队列）、打印机缓冲、消息队列
      - 双端队列（Deque）
        - 逻辑结构（定义）：允许在**两端**插入和删除的线性表，是栈和队列的推广。
          - 输出受限的双端队列：两端都可入队，但只有一端（如左端）可出队
          - 输入受限的双端队列：两端都可出队，但只有一端（如左端）可入队
        - 与栈、队列的关系：栈（一端插入一端删除）和队列（一端插入另一端删除）都是双端队列的**特例**
        - 基本操作（运算）：
          - **InitDeque(&D)**：初始化
          - **DequeEmpty(D)**：判空
          - **PushFront(&D, e) / PushBack(&D, e)**：左端/右端入队
          - **PopFront(&D, &e) / PopBack(&D, &e)**：左端/右端出队
        - 存储结构（基于循环数组实现，双端循环队列）：
          - 结点定义（`front` 指向队头，`rear` 指向队尾后一个位置）：
            ```cpp
            #define MaxSize 50
            typedef struct {
                ElemType data[MaxSize];
                int front, rear;    // 队头、队尾指针
            } Deque;
            ```
          - 初始化（`front = rear = 0`）：
            ```cpp
            void InitDeque(Deque &D) {
                D.front = D.rear = 0;
            }
            ```
          - 判空：
            ```cpp
            bool DequeEmpty(Deque D) {
                return D.front == D.rear;
            }
            ```
            - 时间复杂度：$O(1)$
          - 队满判断：`(D.rear + 1) % MaxSize == D.front`（牺牲一个单元）
          - 左端入队（`front` 循环前移）：
            ```cpp
            bool PushFront(Deque &D, ElemType e) {
                if ((D.rear + 1) % MaxSize == D.front)  // 队满
                    return false;
                D.front = (D.front - 1 + MaxSize) % MaxSize; // front 前移
                D.data[D.front] = e;
                return true;
            }
            ```
            - 时间复杂度：$O(1)$
          - 右端入队（`rear` 循环后移）：
            ```cpp
            bool PushBack(Deque &D, ElemType e) {
                if ((D.rear + 1) % MaxSize == D.front)  // 队满
                    return false;
                D.data[D.rear] = e;
                D.rear = (D.rear + 1) % MaxSize;        // rear 后移
                return true;
            }
            ```
            - 时间复杂度：$O(1)$
          - 左端出队：
            ```cpp
            bool PopFront(Deque &D, ElemType &e) {
                if (D.front == D.rear)                  // 队空
                    return false;
                e = D.data[D.front];
                D.front = (D.front + 1) % MaxSize;
                return true;
            }
            ```
            - 时间复杂度：$O(1)$
          - 右端出队：
            ```cpp
            bool PopBack(Deque &D, ElemType &e) {
                if (D.front == D.rear)                  // 队空
                    return false;
                D.rear = (D.rear - 1 + MaxSize) % MaxSize; // rear 前移
                e = D.data[D.rear];
                return true;
            }
            ```
            - 时间复杂度：$O(1)$
        - 应用：滑动窗口最大值（单调双端队列）、Linux 内核任务队列等
    - 3 串
    - 4 数与二叉树
    - 5 图
    - 6 查找
    - 7 排序
    - 算法 45
      - 算法基础
      - 分治策略
      - 动态规划
      - 贪心算法
      - 图算法
      - 查找算法
      - 排序算法
      - 数据结构与算法的应用
  - 计算机组成原理 45
  - 操作系统 35
  - 计算机网络 25
- 方法
  - 返工
    - 计划
    - 习惯
    - 失误
  - 0 - 100
    - 先给后要
      - 用技能换信任
      - 用信息换位置
      - 用资源换联盟
    - 建系统不建团队
      - 明确利益分配
      - 最小最战单元进行授权
      - 建立信息流通机制
      - 建立退出机制
  - 整体局部的分类和关系(图形表示)
    - 过程
      - 实践(微观)
        - 方案
        - 检错
        - 纠错
      - 认识(宏观)
      - 再实践(宏观)
    - 结果
      - 定义
      - 性质
      - 公式
      - 方法
- 书籍
  - [ ] DR_CAN 控制之美