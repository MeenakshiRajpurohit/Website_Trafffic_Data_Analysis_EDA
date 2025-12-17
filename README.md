# Website_Trafffic_Data_Analysis_EDA
This project explores website traffic through a comprehensive Exploratory Data Analysis (EDA) to decode user engagement and conversion dynamics. The primary business objective is to generate actionable intelligence to optimize marketing spend and improve overall website performance.
By identifying distinct behavior patterns—distinguishing between highly engaged and low-intent users—this analysis informs marketing strategies to maximize Return on Investment (ROI).


Dataset and Methodology
The analysis was conducted on a dataset of 2,000 sessions with 7 key features, including Page Views, Session Duration, Bounce Rate, and Traffic Source.




Data Cleaning: 14 invalid sessions with zero page views were removed to ensure data integrity, resulting in a final sample of 1,986 valid sessions.



Feature Engineering: Severe right-skewness in engagement metrics was corrected using log transformations. New behavioral features were engineered, including Page_View_Intensity (browsing pace), Last_Page_Share (late-stage engagement), and is_Returning_User (loyalty indicator).






Preprocessing: Categorical traffic sources were converted via One-Hot Encoding, and numerical features were standardized using Z-score scaling to prepare the matrix for machine learning.




Outlier Management: Extreme values were handled using the Interquartile Range (IQR) rule and Winsorizing (capping) to stabilize the data without losing high-engagement insights.
