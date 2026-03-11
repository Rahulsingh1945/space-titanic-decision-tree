# How Decision Trees Work

A Decision Tree is a supervised machine learning algorithm used for classification and regression tasks.

The algorithm splits data into smaller groups based on feature values. Each split asks a question about the data, and the answer determines the next branch of the tree.

Example decision logic:

Is CryoSleep = True?
│
├─ Yes → Passenger likely Transported
│
└─ No
     │
     ├─ High VRDeck spending → Transported
     │
     └─ Low spending → Not Transported

The algorithm chooses the best splits using impurity metrics such as Gini Impurity.

Lower impurity means the data in that node is more homogeneous.

# Decision Tree – What Kind of Data It Works Best With

Decision Trees work well on structured tabular data where predictions can be made using decision rules based on feature values.

Good data for Decision Trees usually has:

• **Clear decision thresholds**  
Example: Age > 30, Spending > 100

• **Mixed feature types**  
Numerical data (Age, Spending) and categorical data (VIP, Planet)

• **Non-linear relationships**  
The target depends on conditions rather than a straight line relationship.

• **Feature interactions**  
Example rule:
If CryoSleep = True → Passenger likely transported

Because of this rule-based structure, Decision Trees are easy to interpret and work well for many tabular classification problems.
