# Can a Team of Trees Beat One Tree?

**The business question:** Can we predict customer churn more accurately than with a single decision tree?

**What I did:** I trained a random forest: hundreds of decision trees that each vote, and the majority wins.

**What I found:** The forest was more accurate on new customers than one tree, because the trees' mistakes cancel out.

**Why it matters:** Better predictions mean the company calls the right customers and wastes less money.

**Tools:** Python, scikit-learn (RandomForestClassifier)
