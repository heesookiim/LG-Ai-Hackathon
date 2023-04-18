# LG-Ai-Hackathon
The official Hackathon website is in Korean. To check, [click the link](https://dacon.io/en/competitions/official/236055/overview/description).
## Topic
Develop an AI model that classifies the quality status of products based on real-world data from smart factories.

## Dataset Information:

The dataset consists of three files: train.csv, test.csv, and sample_submission.csv.

### train.csv:
- PRODUCT_ID: The unique ID of the product.
- Y_Class: The target variable representing the quality status of the product.
0: Below the acceptable threshold (unsuitable)
1: Acceptable
2: Above the acceptable threshold (unsuitable)
- Y_Quality: Quantitative measurement related to the product quality.
- TIMESTAMP: The timestamp when the product entered the manufacturing process.
- LINE: The type of manufacturing line the product entered ('T050304', 'T050307', 'T100304', 'T100306', 'T010306', 'T010305' are the possible values).
- PRODUCT_CODE: The code number assigned to the product ('A_31', 'T_31', 'O_31' are the possible values).
X_1 ~ X_2875: Variables extracted from the manufacturing process and anonymized for security reasons.
### test.csv:
- PRODUCT_ID: The unique ID of the product.
- TIMESTAMP: The timestamp when the product entered the manufacturing process.
- LINE: The type of manufacturing line the product entered ('T050304', 'T050307', 'T100304', 'T100306', 'T010306', 'T010305' are the possible values).
- PRODUCT_CODE: The code number assigned to the product ('A_31', 'T_31', 'O_31' are the possible values).
- X_1 ~ X_2875: Variables extracted from the manufacturing process and anonymized for security reasons.
### sample_submission.csv:
- PRODUCT_ID: The unique ID of the product.
- Y_Class: The predicted product quality status.
0: Below the acceptable threshold (unsuitable)
1: Acceptable
2: Above the acceptable threshold (unsuitable)

**Please note that the dataset contains actual data from the manufacturing process, and some variables (X variables) have been anonymized for security reasons. 'LINE' and 'PRODUCT_CODE' have the same possible values in both the train and test datasets.**




## Result
**Achieved a ranking of 34th out of a total of 925 participating teams.**
Hosted by: LG AI Research.
