Predict the loan sanction amount
-------------------------------

Buying a house requires a lot of careful planning. Once you have finalized your budget and the house that you want to buy, you must ensure that you have sufficient funds to pay the seller.

With rising property rates, most people avail home loans to buy their dream houses. The bank only lends up to _81%_ of the total amount based on a person's finances (salary, outgoing expenses, existing loans, etc.). You will need to make the rest of the payment yourself after the bank tells you how much they can lend.

**Task**

You work for XYZ bank. Predict the loan amount that can be sanctioned to customers who have applied for a home loan using the features provided in the dataset.

**Data description**

The dataset folder contains the following:

*   _train.csv_: (30000, 24)
*   _test.csv_: (20000, 23)
*   _sample\_submission.csv_: (5, 2)

The columns in the dataset are as follows:



|Column name|Description|
|--- |--- |
|Customer ID|Represents a unique identification number of a customer|
|Name|Represents the name of a customer|
|Gender|Represents the gender of a customer|
|Age|Represents the age of a customer|
|Income (USD)|Represents the income of a customer|
|Income Stability|Represents whether a customer has a stable source of income|
|Profession|Represents the profession of a customer|
|Type of Employment|Represents the type of employment of a customer|
|Location|Represents the current location that a customer resides|
|Loan Amount Request (USD)|Represents the loan amount requested by a customer|
|Current Loan Expenses (USD)|If a customer has any current active loans, then this represents the amount that a customer spends on these loans (monthly)|
|Expense Type 1|Represents a type of expense that a customer spends on (monthly)|
|Expense Type 2|Represents a type of expense that a customer spends on (monthly)|
|Dependents|Represents whether a customer has any dependencies (spouse, parents, siblings, children, etc.)|
|Credit Score|Represents the credit score of a customer|
|No. of Defaults|Represents the number of time a customer has defaulted|
|Has Active Credit Card|Represents if a customer has any active credit cards or not|
|Property ID|Represents an identification number of a property|
|Property Age|Represents the age of a property|
|Property Type|Represents the type of property|
|Property Location|Represents the location of a property|
|Co-Applicant|Represents whether a customer has co-applicants|
|Property Price|Represents the selling price of a property|
|Loan Sanction Amount (USD)|Represents the loan sanctioned amount for a customer|



**Evaluation metric**

    score = max(0, 100*metrics.r2_score(actual, predicted))

**Result submission guidelines**

*   The index is _Customer ID_. 
*   The target is the _Loan Sanction Amount (USD)_ column. 
*   The submission file must be submitted in _.csv_ format only.
*   The size of this submission file must be _20000 x 2_.

_Notes_ 

Ensure that your submission file contains the following:

*   Correct index values as per the test file
*   Correct names of columns as provided in the _sample\_submission.csv_ file

**Instructions** 

*   Click _Download dataset_ to download the dataset.
*   Solve the problem in your local environment.
*   Save the predictions in a _.csv_ file.
*   Click _Upload File_ (under the _Upload File_ section) to upload your prediction file (_.csv_).
*   Click _Upload File_ (under the _Upload Source Code_ section) to upload your _.ipynb_ file along with any presentation file.
*   Add any instructions or comments in the _Your Answer_ section.
*   Click _Submit_.


