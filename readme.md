# Financial Formulas Summary

This document summarizes key financial formulas related to returns, present value, bond pricing, and compounding interest. The formulas are written using LaTeX for ease of reading.

## 1. Gross Return (总回报率)

\[
R = \frac{\text{Amount Received}}{\text{Amount Invested}}
\]

## 2. Net Return (净回报率)

\[
r = R - 1
\]

## 3. Compounding Interest (复利公式)

### Annual Compounding (年复利)

\[
A = P \times (1 + r)^T
\]

### Quarterly Compounding (季度复利)

\[
A = P \times \left(1 + \frac{r}{4}\right)^{4T}
\]

### Continuous Compounding (连续复利)

\[
A = P \times e^{r \times T}
\]

## 4. Continuous Compounded Interest Rate (连续复利回报率转换)

To convert from discrete compounding interest rate to continuously compounded interest rate:

\[
r_{\text{cc}} = \ln(1 + r)
\]

## 5. Present Value (现值计算)

### 单期现值

\[
PV = \frac{FV}{1 + r}
\]

### 多期现值（离散）

\[
PV = \frac{FV}{(1 + r_0)(1 + r_1)}
\]

### 连续时间现值（连续复利）

\[
PV = FV \times e^{-rT}
\]

## 6. Zero-Coupon Bond Pricing (零息债券定价公式)

### 离散复利

\[
Z_{t,T} = \frac{1}{(1 + r)^T}
\]

### 连续复利

\[
Z_{t,T} = e^{-r(T - t)}
\]

### 一般形式（当利率不恒定时）

\[
Z_{t,T} = e^{-\int_t^T r(u) du}
\]

## 7. Yield to Maturity (到期收益率, YTM) for Zero-Coupon Bonds

\[
Y(T) = \frac{1}{T} \ln\left(\frac{1}{P_T}\right)
\]

## 8. Bond Pricing (债券定价公式)

\[
P_t = \sum_{j=1}^N \frac{CF_{t+j}}{(1 + Y)^j}
\]

## 9. Yield Curve (收益率曲线)

\[
r(t,T) = \frac{1}{T - t} \int_t^T r(u) du
\]

## 10. Perpetuity Bond (永续债券定价公式)

\[
P_0 = \frac{D_0}{r - \mu}
\]

## 11. Discount Factor (折现因子)

### 离散时间

\[
\text{折现因子} = \frac{1}{1 + r}
\]

### 连续时间

\[
\text{折现因子} = e^{-rT}
\]
