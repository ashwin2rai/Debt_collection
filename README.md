# Debt_collection
Project implementing regression discontinuity to inform decisions on debt collection

## Application of regression discontinuity: banking recovery
<p> Regression discontinuity searches for jumps in the target variable such that if the target variable were modeled using a regression function, which is usually at least C<sup>0</sup> continuous, loses its property of continuity at these jump regions. This region can be homogenized within a window to regain continuity and properties of this window can then be utilized to quantify the effects of the discontinuity. </p>
<p>This methodology can be used to model processes that exhibit certain jumps caused due to a change in the underlying mechanisms where location and properties of such jumps may be of interest. One such process is debt recovery in banks where the recovery amount depends on recovery strategies. In general, more expensive recovery strategies can lead to higher proportion of recovered funds. Profitability of these decisions hinges on optimizing appropriate recovery strategies to acheive a balance of recovery expenses incurred and recovered funds. Regression discontinuity can be applied to such problems in order to determine the effect of the recovery strategy and the profitability of it. </p>
<p>In this example, the bank has implemented different recovery strategies at different thresholds (\$0, \$1000, \$2000, \$3000 and \$5000) where the greater the Expected Recovery Amount, the more effort the bank puts into contacting the customer. </p>
<p><img src="https://github.com/ashwin2rai/Debt_collection/blob/master/src/images/disgraph.png",width="400",height="400"></p>
<p>In the included notebook, EDA is first performed on the example dataset, then a rudimentary analysis is done based on which certain conclusions are made.</p>
<sub>Sources for data, and images:</sub>
<sub>Howard Friedman, "Which Debts Are Worth the Bank's Effort?", Datacamp </sub>
