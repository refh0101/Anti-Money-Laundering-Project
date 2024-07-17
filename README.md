# Anti-Money-Laundering-Project with Microsoft Fabric

Money laundering remains a significant global issue, driving the need for improved transaction monitoring methods. Current anti-money laundering (AML) procedures are inefficient, and access to data is difficult/restricted by legal and privacy issues. Moreover, existing data often lacks diversity and true labels. This study introduces a novel AML transaction generator, creating the SAML-D dataset with enhanced features and typologies, aiming to aid researchers in evaluating their models and developing more advanced monitoring methods.

The dataset incorporates 12 features and 28 typologies (split between 11 normal and 17 suspicious). These were selected based on existing datasets, the academic literature, and interviews with AML specialists. The dataset comprises 9,504,852 transactions, of which 0.1039% are suspicious. It also includes 15 graphical network structures to represent the transaction flow within these typologies. The structures, while sometimes shared among typologies, vary significantly in parameters to increase complexities and challenge detection efforts. More details about these typologies are available in the paper above. The dataset is an updated version compared to the paper.

# Features of the SAML-D dataset:

• Time and Date: Essential for tracking transaction chronology.

• Sender and Receiver Account Details: Helps uncover behavioural patterns and complex banking connections.

• Amount: Indicates transaction values to identify suspicious activities.

• Payment Type: Includes various methods like credit card, debit card, cash, ACH transfers, cross-border, and cheque.

• Sender and Receiver Bank Location: Pinpoints high-risk regions including Mexico, Turkey, Morocco, and the UAE.

• Payment and Receiver Currency: Align with location features, adding complexity when mismatched.

• 'Is Suspicious' Feature: Binary indicator differentiating normal from suspicious transactions.

• Type: Classifies typologies, offering deeper insights.

# Project Deliverables

1. Upload data info Microsoft Fabric lakehouse
2. Transfer the file to a table
3. load data as dataframe in Notebook(Fabric Data Science)
4. Clean the data
5. Change data-types
6. Perform exploratory analysis on the data
7. Create different visualizations within notebooks
8. Create reports in Power BI
