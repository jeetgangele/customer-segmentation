## Overview


```
Why should you care about customer segmentation? To deliver personalized experiences to customers, segmentation is key. It can provide insights into your customers behavior, habits, and preferences, allowing you to offer tailored marketing campaigns increasing your odds of success as well as improving your customers experience with tailored content.


Customer Segmentation
What are we going to build? Using transactional purchasing data, we will be able to create a 2 x 2 value matrix to create 4 customers groups. Each group will defer f rom the other depending on 2 dimensions: (1) current customer value, and (2) potential customer value.

What technique are we going to use? We are going to use the RFM model to create the required features from transactional purchasing data. The RFM model stands for:

Recency: When was the last time they purchased?
Frequency: How often and for how long have they purchased?
Monetary Value/Sales: How much have they purchased?
It’s usually used to identify the Highest Value Customer at the intersection of each 3 questions. To build the 2 x 2 matrix we will only use the R & the M from RFM.