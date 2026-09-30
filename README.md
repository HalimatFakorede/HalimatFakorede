# Hi, I'm Halimat Fakorede

I studied agriculture, then learnt to work with data. Now I use both.

Most of what I build is about food. Why Nigerian farms grow less than they should. Why food prices jump the way they do. Who runs short when imports stop.

**Looking for:** data analyst and data science roles in agriculture, food security or development. Based in Lagos, Nigeria.

---

## How I work

**I check my work against a simple guess first.** If a model cannot beat guessing the average, it is not a model.

**Every project states what it cannot tell you.** Knowing the limits of an analysis is part of the analysis.

**Nothing I build ever sees the future.** When time is involved, the model learns from the past only.

**I explain findings in plain words.** If someone outside my field cannot follow it, the work is not finished.

---

## Projects

### Nigeria Yield Gap Explorer
> Are we growing more food because farming got better, or because farmers cleared more land?

I studied 33 years of data on eight Nigerian food crops. Nearly all the growth came from clearing more land. Output per hectare fell.

I then tested whether more fertilizer would fix it, using records from 221 countries. The gain is smaller in countries that use very little of it, like Nigeria. Fertilizer on its own is not the answer.

Maize was the one crop that improved, which proves it can be done here.

**[Code](https://github.com/HalimatFakorede/nigeria-yield-gap)** · **[Live dashboard](https://nigeria-yield-gap.streamlit.app)** · `Python` `pandas` `statsmodels` `Streamlit`

### Nigeria Food Price Early Warning System
> Which staple foods are about to get expensive?

A monthly risk score for nine foods across 68 markets in 14 states, built from 88,545 price records.

The first version scored barely better than chance. Rather than adjust it until it looked right, I tested each part separately and found that Nigerian food prices usually fall back after a rise, so one measure was pointing the wrong way.

I rebuilt it to learn from the past only, then worked out the naira to dollar rate from the price records themselves. It predicts food price jumps better than any price measure in the model.

Months the system flags as high risk are followed by a sharp price rise half the time, against 29% of months normally.

**[Code](https://github.com/HalimatFakorede/nigeria-food-price-early-warning)** · **[Live dashboard](https://nigeria-food-price-early-warning.streamlit.app
)** · `Python` `GARCH` `scikit-learn` `Streamlit`

### Food Import Risk Dashboard
> If food imports fall, which countries run short first?

Set an import shock between 10% and 50% and see the shortfall, country by country and crop by crop. Built on FAOSTAT trade and production data.

**[Code](https://github.com/HalimatFakorede/food-import-risk-dashboard)** · `Python` `Streamlit` `FAOSTAT`

### Volatility Risk System
> Is this market calm or stressed right now?

Measures how sharply prices are moving using GARCH, labels the market two different ways, and raises an alert when conditions change. Served through a REST API and a dashboard.

**[Code](https://github.com/HalimatFakorede/volatility-risk-system)** · `Python` `GARCH` `FastAPI` `Streamlit`

---

## Background

Bachelor of Agriculture, University of Ilorin.

Four years running reporting and operations for companies in Nigeria and the UK.

DataCamp Data Scientist Certification (2026). Applied Data Science Lab, WorldQuant University (2025).

---

fakoredehalimat1@gmail.com · [LinkedIn](https://linkedin.com/in/halimatfakorede)
