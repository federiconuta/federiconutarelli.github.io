# Publications

## (Selected) Publications in Causal Machine-Learning

<table width="100%">
  <tr>
    <td valign="top" align="left" width="80%">
      <strong style="font-size: 28px;">Optimal data collection design in machine learning: the case of the fixed effects generalized least squares panel data model </strong><br>
      <em style="font-size: 20px;">
        Joint with <a href="https://www.imtlucca.it/giorgiostefano.gnecco">Giorgio Gnecco</a> and <a href="https://www.deib.polimi.it/ita/personale/dettagli/1957454">Daniela Selvi</a>, Machine Learning, June 2021, DOI: 110:1549–1584
      </em><br>
      <span style="font-size: 18px; color: #555;" 
        &gt; June 2021, DOI: 110:1549–1584
      </span>
    </td>
    <td valign="top" align="right" nowrap width="20%">
      <a href="https://iris.imtlucca.it/retrieve/handle/20.500.11771/19778/20932/Gnecco2021_Article_OptimalDataCollectionDesignInM.pdf">PDF</a>
    </td>
  </tr>
</table>

<details>
  <summary style="font-size: 18px;">Abstract</summary>
  <br>
This work belongs to the strand of literature that combines machine learning, optimization,
and econometrics. The aim is to optimize the data collection process in a specific statistical
model, commonly used in econometrics, employing an optimization criterion inspired by
machine learning, namely, the generalization error conditioned on the training input data.
More specifically, the paper is focused on the analysis of the conditional generalization
error of the Fixed Effects Generalized Least Squares (FEGLS) panel data model, i.e., a
linear regression model with applications in several fields, able to represent unobserved
heterogeneity in the data associated with different units, for which distinct observations
related to the same unit are corrupted by correlated measurement errors. The framework
considered in this work differs from the classical FEGLS model for the additional possibility of controlling the conditional variance of the output variable given the associated
unit and input variables, by changing the cost per supervision of each training example.
Assuming an upper bound on the total supervision cost, i.e., the cost associated with the
whole training set, the trade-off between the training set size and the precision of supervision (i.e., the reciprocal of the conditional variance of the output variable) is analyzed and
optimized. This is achieved by formulating and solving in closed form suitable optimization problems, based on large-sample approximations of the generalization error associated
with the FEGLS estimates of the model parameters, conditioned on the training input data.
The results of the analysis extend to the FEGLS case and to various large-sample approximations of its conditional generalization error the ones obtained by the authors in recent
works for simpler linear regression models. They highlight the importance of how the precision of supervision scales with respect to the cost per training example in determining
the optimal trade-off between training set size and precision. Numerical results confirm the
validity of the theoretical findings.
</details>

<table width="100%">
  <tr>
    <td valign="top" align="left" width="80%">
      <strong style="font-size: 28px;">Assessing the Heterogeneous Impact of Economy-Wide Shocks: A Causal Machine Learning Approach Applied to Colombian Firms </strong><br>
      <em style="font-size: 20px;">
        Joint with <a href="https://www.imtlucca.it/francesco.serti">Francesco Serti</a>, <a href="https://www.imtlucca.it/massimo.riccaboni">Massimo Riccaboni</a>, Victor Ortiz and Marco Duenas (Forthcoming in Oxford Bullettin of Economics and Statistics)
      </em><br>
      <span style="font-size: 18px; color: #555;" 
        &gt; June 2021, DOI: 110:1549–1584
      </span>
    </td>
    <td valign="top" align="right" nowrap width="20%">
      <a href="https://iris.imtlucca.it/retrieve/handle/20.500.11771/19778/20932/Gnecco2021_Article_OptimalDataCollectionDesignInM.pdf">PDF</a>
    </td>
  </tr>
</table>


<details>
  <summary style="font-size: 18px;">Abstract</summary>
  <br>

Our paper presents a causal Machine Learning (ML) methodology to study the
heterogeneous effects of economy-wide shocks and applies it to the impact of the
COVID-19 crisis on exports. This method is applicable in scenarios where, due to
the pervasive nature of the shock, it is difficult to identify a control group that is
not affected by the shock and to determine ex ante differences in shock intensity
across units. In particular, our study investigates the effectiveness of different machine
learning techniques in predicting firms’ trade and, by building on recent developments
in causal ML, these predictions are used to reconstruct the counterfactual distribution
of firms’ trade under different COVID-19 scenarios and investigate the heterogeneity
of treatment effects. Specifically, we focus on the probability of Colombian firms
surviving in the export market under two different scenarios: a COVID-19 setting and
a non-COVID-19 counterfactual situation. On average, we find that the COVID-19
shock decreased a firm’s probability of surviving in the export market by about 20
percentage points in April 2020. We study the treatment effect heterogeneity by
employing a classification analysis that compares the characteristics of the firms on
the tails of the estimated distribution of the individual treatment effects.
</details>

## Publications in Machine-Learning

<table width="100%">
  <tr>
    <td valign="top" align="left" width="80%">
      <strong style="font-size: 28px;">Matrix completion of world trade: An analysis of interpretability through Shapley values </strong><br>
      <em style="font-size: 20px;">
        Joint with <a href="https://www.imtlucca.it/giorgiostefano.gnecco">Giorgio Gnecco</a> and <a href="https://www.imtlucca.it/massimo.riccaboni">Massimo Riccaboni</a> , The wrolds Economy, June 2023, DOI: 10.1111/twec.13457 
      </em><br>
      <span style="font-size: 18px; color: #555;" 
        &gt; June 2021, DOI: 110:1549–1584
      </span>
    </td>
    <td valign="top" align="right" nowrap width="20%">
      <a href="https://www.researchgate.net/profile/Federico-Nutarelli-2/publication/372558249_Matrix_completion_of_world_trade_An_analysis_of_interpretability_through_Shapley_values/links/64bf71e4c41fb852dd9913f9/Matrix-completion-of-world-trade-An-analysis-of-interpretability-through-Shapley-values.pdf">PDF</a>
    </td>
  </tr>
</table>


<details>
  <summary style="font-size: 18px;">Abstract</summary>
  <br>

Economic complexity and machine learning have recently become popular approaches for analysing international trade. However, for effective use of machine learning in relation to economic complexity and policymaking, it is important to understand what are the
key features for predictions. In this framework, this article addresses the issue of the interpretability of results
obtained with a machine learning technique—namely, matrix completion—when applied to economic complexity, specifically in predicting revealed comparative advantages (RCAs) of countries in different product categories. Shapley values are used to measure the role each country plays in predicting the RCAs of other countries. Countries relevant for prediction may differ from countries whose RCA values are similar to those of the country of interest when a standard similarity measure such as cosine similarity is used. We demonstrate the usefulness of our approach to identifying comparable countries by focussing our analysis on export diversification into complex goods of selected European countries.


##  Working papers








