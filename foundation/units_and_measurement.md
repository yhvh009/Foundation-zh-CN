# 单位（Units）和度量（Measurement）

使用物理尺寸标注数字数量，以便允许在相关单位之间进行本地化（locale-aware）的格式化和转换。  
Label numeric quantities with physical dimensions to allow locale-aware formatting and conversion between related units.

---

### 主题

---

#### 首要步骤（First Steps）

> ```
> struct Measurement
> ```
> 一个有着测量单位的数值数量标签，有着单位转化和单位相关（unit-aware）计算的支持。

> ```
> class Unit
> ```
> 一个表示测量单位的抽象类（abstract class）。

> ```
> class Dimension
> ```
> 一个表示尺寸（dimensional）度量单位的抽象类。

---

#### 转换（Conversion）

> ```
> class UnitConverter
> ```
> 一个抽象类，提供一些关于如何在一个单位跟其维度<sup>1</sup>的基本单位之间进行转换的描述。

> ```
> class UnitConverterLinear
> ```
> 一个关于如何使用线性方程（linear equation）进行单位间转换的描述。

---

#### 物理维度（Physical Dimension）

> ```
> class UnitArea
> ```
> 一个衡量面积（area）的单位。

> ```
> class UnitLength
> ```
> 一个衡量长度的单位。

> ```
> class UnitVolume
> ```
> 一个衡量体积的单位。

> ```
> class UnitAngle
> ```
> 一个衡量旋转（rotation）的单位。

---

#### 质量（Mass），重量（Weight）和力量（Force）

> ```
> class UnitMass
> ```
> 一个衡量质量的单位。

> ```
> class UnitPressure
> ```
> 一个衡量压力的单位。

---

#### 时间跟运动（Motion）

> ```
> class UnitAcceleration
> ```
> 一个衡量加速度的单位

> ```
> class UnitDuration
> ```
> 一个衡量持续时间的单位

> ```
> class UnitFrequency
> ```
> 一个衡量频率的单位

> ```
> class UnitSpeed
> ```
> 一个衡量速度的单位

---

#### 能量（Energy）、热度（Heat）和光亮（Light）

> ```
> class UnitEnergy
> ```
> 一个衡量能量的单位

> ```
> class UnitPower
> ```
> 一个衡量功率的单位

> ```
> class UnitTemperature
> ```
> 一个衡量温度的单位

> ```
> class UnitIlluminance
> ```
> 一个衡量亮度的单位

---

#### 电（Electricity）

> ```
> class UnitElectricCharge
> ```
> 一个衡量电荷的单位

> ```
> class UnitElectricCurrent
> ```
> 一个衡量电流的单位

> ```
> class UnitElectricPotentialDifference
> ```
> 一个衡量电势差的单位

> ```
> class UnitElectricResistance
> ```
> 一个衡量电阻的单位

---

#### 浓度（Concentration）和分散度（Dispersion）

> ```
> class UnitConcentrationMass
> ```
> 一个衡量质量浓度的单位

> ```
> class UnitDispersion
> ```
> 一个衡量物质分散度的单位<sup>2</sup>

---

#### 燃料效率（Fuel Efficiency）

> ```
> class UnitFuelEfficiency
> ```
> 一个衡量燃料效率的单位

---

### 参见

---

#### 基础

> [数字（Numbers）, 数据（Data）, 和基本值（Basic Values）](/foundation/numbers_data_and_basic_values.md)
>
> 使用原始数据类型及其他基础类型贯穿整个Cocoa。

> [字符串（Strings）及文本（Text）](/foundation/strings_and_text.md)
>
> 创建和处理Unicode字符，使用正则表达式查找模式（patterns），以及进行文本的自然语言分析。

> [集合（Collections）](/foundation/collections.md)
>
> 使用数组（arrays），字典（dictionaries），集合（sets），和专门的集合来存储跟迭代（iterate）一组对象（Objects）或者值（Values）。

> [日期（Dates）和时间（Times）](/foundation/dates_and_times.md)
>
> 比较日期和时间，以及进行日历和时区的运算。

> [数据格式化（Data Formatting）](/foundation/data_formatting.md)
>
> 在数字，日期，度量（measurements）以及其他值与本地化（locale-aware）字符串表达式（string representations）之间进行相互转化。

> [过滤（Filters）和排序（Sorting）](/foundation/filters_and_sorting.md)
>
> 使用谓词（predicates），表达式（expressions）和排序描述式（sort descriptors）来检测在集合（collections）以及其他服务中的元素。

---

1. 或者翻译为尺寸，原词是dimension
2. 原文是 A unit of measure for an amount-of-substance fraction.大概意思就是衡量什么成分占了多少比例的这样的一个单位。比如100毫克/升这种。
