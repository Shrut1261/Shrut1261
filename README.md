# ABC Company: Customer Online Shopping Behavior Analysis

## Author
**Shrut Dineshbhai Prajapati**  
 Statistics Lab

---

## 1. Overview of the Problem
ABC Company aims to understand customer shopping behavior on its online platform. The primary objective is to analyze the impact of:
- The **day of the week** on customer activity and spending patterns.
- The **browser type** used for accessing the website.

By leveraging these insights, the company can optimize marketing strategies and better target specific customer segments.

---

## 2. Graphical and Numerical Summaries
### **Summary Statistics**
#### **Length of Time on Website**
- **Mean:** 12.1 minutes  
- **Median:** 11.3 minutes  
- **Minimum:** 3.2 minutes  
- **Maximum:** 32.9 minutes  
- **Standard Deviation:** 6.2 minutes  
  _Most shoppers browse the website for a short and focused period._

#### **Number of Pages Viewed**
- **Mean:** 4.5 pages  
- **Median:** 4 pages  
- **Minimum:** 2 pages  
- **Maximum:** 10 pages  
- **Standard Deviation:** 1.8 pages  
  _Some customers engage more deeply than others, browsing more pages._

#### **Mean Amount Spent**
- **Mean:** $66.87  
- **Median:** $59.20  
- **Minimum:** $17.84  
- **Maximum:** $158.51  
- **Standard Deviation:** $30.71  
  _There is a significant variation in spending, indicating a diverse customer base._

- **Correlation between browsing time, pages viewed, and spending:** _Moderate (0.3 - 0.5)_  
  _Engaged shoppers tend to spend more money._

**Graphical Representation:**
![Summary Statistics](https://github.com/user-attachments/assets/b1a4addb-4c35-41c5-a8b5-b667a9cf8702)

---

## 3. Day of the Week Analysis

**Key Findings:**
- **Higher Activity & Spending on Weekends:** Fridays lead in both activity and spending, possibly due to payday shopping. Saturdays see slightly lower activity but similar spending.
- **Monday Surprises:** Despite lower visits, Monday sees the highest average spending, indicating potentially loyal, high-value customers.
- **Weekdays Show Mixed Trends:** Tuesday and Thursday exhibit moderate activity, while Wednesday has the lowest spending, possibly indicating more browsing than buying.
- **Sundays Underperform:** Lowest activity and spending suggest the need for alternative marketing strategies.

**Graphical Representation:**
![Day of the Week Analysis](https://github.com/user-attachments/assets/81380a73-1c6f-4c51-a3e7-6b41fb6329f8)

---

## 4. Relationship Between Time Spent and Customer Spending
**Scatter Plot Analysis:**

![Time vs. Spending](https://github.com/user-attachments/assets/56c4a818-3677-48cb-bb9b-f93c7f6249bb)

**Key Observations:**
- A weak positive correlation suggests customers who browse longer tend to spend slightly more.
- Some high-spending customers have short browsing times, indicating that time alone is not a strong predictor of spending.
- Outliers suggest unique purchase patterns worth further exploration.
- Correlation coefficient **~0.2**, confirming a weak relationship.

---

## 5. Relationship Between Number of Pages Viewed and Amount Spent
**Scatter Plot Analysis:**

![Pages Viewed vs. Amount Spent](https://github.com/user-attachments/assets/eaa0583a-3e78-4cc4-b1dc-71216d1485e4)

**Key Observations:**
- A moderate positive correlation (**0.59**) suggests that customers who browse more pages tend to spend more money.
- However, spending habits vary, indicating other influential factors.

---

## 6. Relationship Between Time Spent on Website and Number of Pages Viewed
**Scatter Plot Analysis:**

![Time vs. Pages Viewed](https://github.com/user-attachments/assets/eaa0583a-3e78-4cc4-b1dc-71216d1485e4)

- **Moderate positive correlation (~0.45)** between pages viewed and time spent.
- Customers who explore more pages generally stay longer.
- Additional segmentation by user type could provide deeper insights into browsing behavior.

---

## 7. Conclusion
This analysis provides valuable insights into customer behavior at ABC Company:
- **Spending is moderately correlated with browsing activity**, though some customers make quick, high-value purchases.
- **Fridays and Mondays are key revenue days**, while Sundays require targeted strategies.
- **Customers engaging with more pages tend to spend more**, suggesting opportunities for content optimization to boost conversions.

### Recommendations:
1. **Targeted marketing campaigns** on **Fridays and Mondays**.
2. **Refined website layout** to encourage deeper browsing.
3. **Special promotions on Sundays** to increase engagement.
4. **Further segmentation analysis** to identify different customer behaviors.

### References:
[Scatter Plot Guide – Stack Overflow](https://stackoverflow.com/questions/10336614/scatter-plot-in-matplotlib)

