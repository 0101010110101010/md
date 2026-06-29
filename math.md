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
        - 数列极限的定义：$\lim_{n \to \infty} a_n = A \Leftrightarrow \forall \epsilon > 0, \exists N \in \mathbb{N}, \forall n > N, |a_n - A| < \epsilon$
      - 函数极限的基本定义
        - 懂得 $ x \to 0 $ 和 $x \to a$ 的区别，以及 $\lim$ 算符 
      - 极限运算法则
        - 掌握极限四则运算法则
      - ==两个特殊极限==
        - 推导 $$\lim_{x\to 0} \frac{\sin x}{x} = 1 $$ 和 $$\lim_{n\to \infty} (1 + \frac{1}{x}) = e$$
        - 掌握极限准则：夹逼准则、单调有界准则
        - 推广到更多极限结果
      - ==无穷小与无穷大==
        - 明晰无穷小的高阶、低阶、同阶、等价等概念
        - 掌握常用的等价无穷小代换
        - 掌握无穷大变量的大小关系
      - ==极限求解思路==
        - 求解极限三步骤：代入、分类、化解
- 线性代数