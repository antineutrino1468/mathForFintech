## 1. Gross Return (总回报率)
R = (Amount Received) / (Amount Invested)

## 2. Net Return (净回报率)
r = R - 1

## 3. Compounding Interest (复利公式)

### Annual Compounding (年复利)
A = P * (1 + r)^T

### Quarterly Compounding (季度复利)
A = P * (1 + r/4)^(4T)

### Continuous Compounding (连续复利)
A = P * exp(r * T)

## 4. Continuous Compounded Interest Rate (连续复利回报率转换)
r_cc = ln(1 + r)

## 5. Present Value (现值计算)

### 单期现值
PV = FV / (1 + r)

### 多期现值（离散）
PV = FV / [(1 + r_0)(1 + r_1)]

### 连续时间现值（连续复利）
PV = FV * exp(-r * T)

## 6. Zero-Coupon Bond Pricing (零息债券定价公式)

### 离散复利
Z_{t,T} = 1 / (1 + r)^T

### 连续复利
Z_{t,T} = exp(-r * (T - t))

### 一般形式（当利率不恒定时）
Z_{t,T} = exp(- ∫_t^T r(u) du)

## 7. Yield to Maturity (到期收益率, YTM) for Zero-Coupon Bonds
Y(T) = (1/T) * ln(1 / P_T)

## 8. Bond Pricing (债券定价公式)
P_t = ∑_{j=1}^N [CF_{t+j} / (1 + Y)^j]

## 9. Yield Curve (收益率曲线)
r(t,T) = (1 / (T - t)) * ∫_t^T r(u) du

## 10. Perpetuity Bond (永续债券定价公式)
P_0 = D_0 / (r - μ)

## 11. Discount Factor (折现因子)

### 离散时间
Discount Factor = 1 / (1 + r)

### 连续时间
Discount Factor = exp(-r * T)
