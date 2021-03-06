# Online-Recommender-System
This project contains implementation of tendency based and slope one approach for online recommendation system.<br/><br/>
A recommendation system can be called as an online recommendation system if it satisfies following criteria:<br/>
• The algorithm/model should be fast/efficient while answering users’ query.<br/>
• We should be able to update the model dynamically as and when new ratings are added<br/>
into the system or old rating values are changed. The model should not be retrained<br/>
from scratch.<br/>
• The model should be scalable. As the number of users and items in a recommendation<br/>
system grows, the model should be able to adjust itself<br/>
<br/>

# Algorithms Implemented<br/>
1- Tendency based<br/>
2- Slope One<br/>
3- Combination of slope one and tendency based(Proposed approach)<br/>
The proposed approach was found out to be working better in a sparse scenario<br/>

<br/>

# Metrics:<br/>
MAE, MSE, GIM, GPIM, Precision, Recall<br/><br/>

# References:<br/>
1 - Q.-X. Wang, X. Luo, Y. Li, X.-Y. Shi, L. Gu, and M.-S. Shang, ‘‘Incremental slope-one recommenders,’’<br/>
Neurocomputing, vol. 272, pp. 606–618, 2018.<br/><br/>
2 - D. Lemire and A. Maclachlan, ‘‘Slope one predictors for online rating-based collaborative filtering,’’ in<br/>
Proceedings of the 2005 SIAM International Conference on Data Mining. SIAM, 2005, pp. 471–475.<br/><br/>
3 - F. Cacheda, V. Carneiro, D. Fernández, and V. Formoso, ‘‘Comparison of collaborative filtering<br/>
algorithms: Limitations of current techniques and proposals for scalable, high-performance recommender<br/>
systems,’’ ACM Transactions on the Web (TWEB), vol. 5, no. 1, p. 2, 2011.<br/>
<br/>
