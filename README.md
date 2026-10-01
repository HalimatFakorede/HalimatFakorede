# Halimat H. Fakorede

Data analysis and business operations. Lagos, Nigeria.

**Portfolio: [halimatfakorede.github.io](https://halimatfakorede.github.io)**

---

## How I work

**I check my work against a simple guess first.** If a model cannot beat guessing the average, it is not a model.

**Every project states what it cannot tell you.** Knowing the limits of an analysis is part of the analysis.

**Nothing I build ever sees the future.** When time is involved, the model learns from the past only.

**I explain findings in plain words.** If someone outside my field cannot follow it, the work is not finished.

---

## Analysis

Everything here runs on data anyone can download, so my numbers can be checked.

### Nigeria Yield Gap Explorer

> Is Nigeria growing more food because farming got better, or because farmers cleared more land?

128% of the growth came from clearing more land. The amount harvested from each hectare actually fell. Food grown per person peaked in 2006 and is 10.5% lower now.

I worked it out two separate ways, using two different methods, to be sure they agreed. They did. I then tested whether more fertilizer would fix it, using farming records from 221 countries. It helps less than you would expect in countries that currently use very little, which is exactly where Nigeria sits.

Maize was the one crop that improved through better farming, so it can be done here.

**[Code](https://github.com/HalimatFakorede/nigeria-yield-gap)** · **[Live dashboard](https://nigeria-yield-gap.streamlit.app)** · `Python` `pandas` `statsmodels` `scikit-learn` `Streamlit`

### Price Early Warning System

> Which everyday foods are most likely to jump in price over the next few months?

A monthly score across 68 markets in 14 states, built from 88,545 price records.

My first version did not work. Instead of adjusting it until the result looked good, I tested each part on its own and found one part was pointing the wrong way. Nigerian food prices usually settle back down after a rise, and I had not allowed for that. I rebuilt it so it only ever learns from what already happened, never from anything it could not have known at the time.

The strongest warning sign turned out to be the naira to dollar rate, which I worked out from the price records themselves.

50% of the foods it flags do go on to jump sharply in price. Normally only 29% of months end that way.

**[Code](https://github.com/HalimatFakorede/nigeria-food-price-early-warning)** · **[Live dashboard](https://nigeria-food-price-early-warning.streamlit.app)** · `Python` `scikit-learn` `GARCH` `Streamlit`

### Import Disruption Risk

> If food imports were cut off, which countries would run short first?

Move a slider from a 10% cut to a 50% cut and the shortfall recalculates, country by country and crop by crop. A 35% drop would leave Japan short of 5.3 million tonnes of maize.

The score combines how much a country leans on imports with how unsteady both those imports and its own harvests are. I chose how much each of those counts rather than calculating it, and the page says so instead of presenting it as something measured.

**[Code](https://github.com/HalimatFakorede/food-import-risk-dashboard)** · **[Live dashboard](https://food-import-risk-dashboard.streamlit.app)** · `Python` `Altair` `Parquet` `Streamlit`

### Market Volatility Risk

> Is this market calm or shaky right now, and has that just changed?

It watches how sharply prices are moving, sets the market at low, medium or high risk, and raises an alert the moment that changes. Two separate methods judge the market and both are shown side by side, because when two reasonable methods disagree that is worth knowing about.

It can also be plugged into other software, so another system can check the risk level without a person having to sit and watch a screen.

**[Code](https://github.com/HalimatFakorede/volatility-risk-system)** · **[Live dashboard](https://volatility-risk-system.streamlit.app)** · `Python` `FastAPI` `GARCH` `HMM` `Streamlit`

---

## Operations

The other half of what I do, and it does not live on GitHub.

Supporting two businesses at once inside one group, coordinating suppliers across both. Keeping an online food market's product information accurate. Tracing where students were dropping off before finishing a sign up. Coordinating remote contributors and holding deadlines for a UK organization.

I also build and maintain two live WordPress sites: [opulentceramics.com](https://opulentceramics.com), a store with four wholesale price levels and a reseller route, and [funmilolabellonaire.com](https://funmilolabellonaire.com), a personal brand platform carrying a podcast, a book, events and a newsletter.

Two academies have brought me in to teach this work, Cirvee Academy and Next Switch Academy.

**[See the operations work &rarr;](https://halimatfakorede.github.io/#operations)**

---

## Background

Bachelor of Agriculture, Second Class Upper, University of Ilorin, 2022.

Data Scientist Certification, DataCamp, 2026.
Applied Data Science Lab, WorldQuant University, 2025.
Deep Learning Fundamentals Lab, WorldQuant University, in progress.
Virtual Assistant Course, ALX, 2022.

---

[fakoredehalimat1@gmail.com](mailto:fakoredehalimat1@gmail.com) · [LinkedIn](https://linkedin.com/in/halimatfakorede) · [Portfolio](https://halimatfakorede.github.io)
