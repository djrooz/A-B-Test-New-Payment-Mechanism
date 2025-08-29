# A/B Test: New Payment Mechanism

## 📊 Overview
Analysis of A/B test for a new payment system on an educational platform.

## 📁 Data
- `groups.csv` - group assignment (A-control, B-test)
- `groups_add.csv` - additional users
- `active_studs.csv` - active users
- `checks.csv` - payment data

## 📈 Analyzed Metrics
1. **Conversion Rate (CR)**
2. **ARPU** - Average Revenue Per User
3. **ARPAU** - Average Revenue Per Active User

## 🔍 Results
| Metric | p-value | Statistical Significance |
|---------|---------|--------------------------|
| CR | 0.97 | ❌ No |
| ARPU | 0.09 | ❌ No |
| ARPAU | 0.22 | ❌ No |

## ⚠️ Issues
- Group imbalance (B is 4x larger than A)
- Payments without corresponding activity
- Possible data collection errors

## 🚀 Recommendation
**Do not launch** the new payment mechanism. Conduct a retest with improved experimental design.

## 🛠 Technologies
Python, Pandas, SciPy, Jupyter Notebook

# A/B тест: Новая механика оплаты

## 📊 Обзор
Анализ A/B теста новой системы оплаты на образовательной платформе.

## 📁 Данные
- `groups.csv` - распределение по группам (A-контроль, B-тест)
- `groups_add.csv` - дополнительные пользователи
- `active_studs.csv` - активные пользователи
- `checks.csv` - данные о платежах

## 📈 Метрики анализа
1. **Конверсия в оплату (CR)**
2. **ARPU** - средний доход на пользователя
3. **ARPAU** - средний доход на активного пользователя

## 🔍 Результаты
| Метрика | p-value | Стат. значимость |
|---------|---------|------------------|
| CR | 0.97 | ❌ Нет |
| ARPU | 0.09 | ❌ Нет |
| ARPAU | 0.22 | ❌ Нет |

## ⚠️ Проблемы
- Дисбаланс групп (B в 4 раза больше A)
- Найдены платежи без активности
- Возможные ошибки сбора данных

## 🚀 Рекомендация
**Не запускать** новую механику. Провести повторный тест с улучшенным дизайном.

## 🛠 Технологии
Python, Pandas, SciPy, Jupyter Notebook
