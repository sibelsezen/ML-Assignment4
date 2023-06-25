# ML-Assignment4
Consider the attached Ionosphere dataset from the UCI machine learning repository: &amp;#39; &amp;#39;http://archive.ics.uci.edu/ml/datasets/Ionosphere.

The system consists of a phased array of 16
high-frequency antennas with a total transmitted power on the order of 6.4 kilowatts. Received
signals were processed using an autocorrelation function whose arguments are the time of a pulse
and the pulse number. There were 17 pulse numbers for the system. Instances in this database are
described by 2 attributes per pulse number, corresponding to the complex values returned by the
function resulting from the complex electromagnetic signal. The targets were free electrons in
the ionosphere. &quot;Good&quot; (g) radar returns are those showing evidence of some type of structure in
the ionosphere. &quot;Bad&quot; (b) returns are those that do not; their signals pass through the ionosphere.
X is a 351x34 real-valued matrix of predictors. Y is a categorical response: &quot;b&quot; for bad radar
returns and &quot;g&quot; for good radar returns. This is a binary classification problem.
Use 5-fold cross-validation to evaluate the classification performance of an LDA and a QDA
classifier. Describe which classifier gives you the best performance. Provide the confusion matrix,
sensitivity, specificity, total accuracy, F1-score, Roc curve, and area under curve.
