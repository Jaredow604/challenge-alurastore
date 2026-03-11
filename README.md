Retail Chain Performance Analysis (EDA)
Strategic Divestment Decision Support System
This repository contains a comprehensive Exploratory Data Analysis (EDA) focused on the operational and financial performance of a 4-branch retail chain. Using Python, raw transactional data was transformed into high-level business insights to guide executive-level restructuring.

🎯 Project Objective
The stakeholder, Mr. João, requires a data-backed recommendation to decide which branch to divest from in order to fund a new venture. This analysis evaluates each location through three critical performance pillars:

Financial Performance: Total gross revenue per branch.

Customer Experience: Average satisfaction ratings and consumer sentiment.

Logistics Efficiency: Correlation and distribution of shipping costs across the network.

📈 Key Insights
💰 Revenue Leadership
Top Performer: Store 2 consistently leads the chain in total invoicing.

Underperformers: Store 4 and Store 1 report the lowest revenue levels, indicating market saturation or operational friction.

⭐ Customer Sentiment
Critical Gap: Store 4 recorded the lowest average customer ratings. This suggests a direct correlation between poor service quality and stagnant revenue growth.

🚚 Logistics & Scalability
Standardized Modeling: Through scatter plot analysis, we confirmed a uniform shipping cost model across all branches (proportional to product price).

Conclusion: No single branch suffers from unique logistical inefficiencies; the operational costs are consistent chain-wide.

💡 Strategic Conclusion: The Divestment Choice
Recommendation: Proceed with the sale of Store 4.

The data confirms that Store 4 is the weakest link in the chain. It suffers from the "double-burden" of lowest revenue and lowest customer satisfaction, without offering any competitive advantage in shipping or operational costs to justify its retention.

🛠️ Technical Stack
Language: Python 3.10+

Data Manipulation: Pandas (Cleaning, merging, and aggregation).

Statistical Visualization: Matplotlib & Seaborn (Advanced distribution and correlation plotting).

Environment: Jupyter Notebook / Google Colab.

🚀 Getting Started
Clone the repository:

Bash
git clone https://github.com/JociasOrt/store-performance-eda.git
Install dependencies:

Bash
pip install pandas matplotlib seaborn
Run the Analysis: Open analysis.ipynb in your preferred notebook environment.
