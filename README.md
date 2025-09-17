# US Election 2016 Data Analysis

In this project, we analyze polling data from the **2016 United States presidential election** to predict who might win.  

---

## 📊 Dataset Description
The dataset includes the following features:

- **Pollster** → Name of the polling organization  
- **Start Date / End Date** → Dates when the poll was conducted  
- **Entry Date/Time (ET)** → Time the poll was entered into the database  
- **Number of Observations** → Sample size of the poll  
- **Population** → Group of respondents (e.g., registered voters, likely voters)  
- **Mode** → Method of polling (e.g., phone, online)  
- **Trump** → Percentage of respondents supporting Trump  
- **Clinton** → Percentage of respondents supporting Clinton  
- **Other** → Support for other candidates  
- **Undecided** → Percentage of undecided voters  
- **Pollster URL / Source URL** → References to original polls  
- **Partisan / Affiliation** → Whether the poll has partisan leanings  
- **Question Text / Iteration** → Details of the survey questions  

---

## 📐 Methodology

We used **hypothesis testing** to evaluate whether Trump was likely to win.  

- **Null Hypothesis (H₀):** Trump will win.  
- **Alternative Hypothesis (H₁):** Trump will not win.  
- **Confidence Level:** 95%  

Based on the confidence interval and hypothesis test, the **null hypothesis was rejected**, leading to the prediction that **Clinton would win**.  

---

## 🔎 Key Concepts

### ✅ Hypothesis Testing
Hypothesis testing is a statistical method used to determine whether there is enough evidence to reject a **null hypothesis (H₀)**.  
- If the probability (p-value) of observing the data under H₀ is very low, we reject H₀.  
- In this project, we tested whether polling data supported the claim that Trump would win.

### ✅ Confidence Interval
A confidence interval gives a range of values that is likely to contain the **true population parameter** with a given level of confidence (e.g., 95%).  
- A 95% confidence interval means that if we repeated the polling many times, **95% of the intervals would contain the true value**.  
- In our case, the interval suggested that Clinton had the advantage.

### ✅ Shy Voter Effect
The **Shy Voter Effect** (or "Shy Trump Effect") refers to voters who support a candidate but do not openly admit it in polls due to social pressure or stigma.  
- In 2016, many analysts believe that some Trump supporters did not express their preference in surveys.  
- This led to **underestimation of Trump’s actual support** in polls.  

---

## 🎯 Conclusion
- Statistical analysis of the polls predicted **Clinton as the winner**.  
- However, due to the **Shy Voter Effect**, polling data underestimated Trump’s support, which contributed to the unexpected election outcome.  
