- 高数
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
            & \tan x = 
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
        - 求解极限三步骤：代入、分类、化解
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
    - 导数与微分
      - 导数基本定义
        定义
        $$
        dy/dx=\lim_{\Delta x \to 0}\frac{\Delta y}{\Delta x}
        $$
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
        - $$
          \begin{align*}
          & 设函数 y=f(x) 在[a,b] 上连续，在(a,b)内可导 \\
          & 如果在(a,b)内f'(x) \ge 0, 则称f(x)在[a,b]上单调递增 \\
          & 如果在(a,b)内f'(x) \le 0, 则称f(x)在[a,b]上单调递减 \\
          \end{align*}
          $$
        - $$
          \begin{align*}
          & 设函数f(x)在点x_0的某邻域U(x_0)内有定义，如果对于去心邻域内的任一x，有 \\
          & f(x) < f(x_0) 或 f(x) > f(x_0) \\
          & 那么就称f(x_0)是函数f(x)的一个极大值 或 极小值 \\
          & 函数f(x)在点x_0 处可导，且在该点处取得极值，则有f'(x_0) = 0 \\
          & 判断极值点的方法： \\
          & 一阶导数：在某一点处一阶导数为0，且在该点左右区间的导数异号 \\
          & 二阶导数：在某一点处一阶导数为0，二阶导为正则取极小值，二阶导为负则取极大值 \\
          & 设f(x) 在[a,b]上连续，在(a,b)内具有一阶和二阶导数，那么 \\
          & 1.若在(a,b)内f''(x) > 0, 则f(x)在[a,b]上的图形是凹的 \\
          & 2.若在(a,b)内f''(x) < 0, 则f(x)在[a,b]上的图形是凸的 \\
          & 如果曲线y=f(x)在经过点(x_0,f(x_0))时，曲线的凹凸性改变了，那么就称点(x_0,f(x_0))为这曲线的拐点
          \end{align*}
          $$
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
        - 三角代换（利用直角三角形）：
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
- 线性代数