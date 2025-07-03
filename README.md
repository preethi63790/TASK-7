7th day task is to Perform binary classification using Support Vector Machines (SVM).
Steps Involved:
1. Load an External Dataset
Use load_breast_cancer() from sklearn.datasets.
Select two features only (for 2D visualization).
2. Preprocessing
Split data into train/test sets.
Scale features using StandardScaler to improve SVM performance.
3. Train SVM Models
Train two models:
Linear Kernel
RBF Kernel (Radial Basis Function)
Use SVC() from sklearn.svm.
4. Visualize Decision Boundaries
Use mlxtend.plotting.plot_decision_regions() to plot classification regions.
Since only 2 features are used, boundaries can be visualized clearly.
5. Hyperparameter Tuning
Use GridSearchCV() to tune:
C (penalty parameter)
gamma (kernel coefficient for RBF)
Use 5-fold cross-validation during tuning.
6. Evaluate the Tuned Model
Use cross_val_score() to perform k-fold cross-validation on the best model.
Report mean accuracy and standard deviation as performance metrics.

