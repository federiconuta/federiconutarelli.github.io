# Publications

## (Selected) Publications in Causal Machine-Learning

<table width="100%">
  <tr>
    <td valign="top" align="left" width="80%">
      <strong style="font-size: 28px;">Optimal data collection design in machine learning: the case of the fixed effects generalized least squares panel data model</strong><br>
      <em style="font-size: 20px;">
        Joint with <a href="[https://example.com](https://www.imtlucca.it/giorgiostefano.gnecco)">Giorgio Gnecco</a> and <a href="[https://example.com]([https://www.imtlucca.it/giorgiostefano.gnecco](https://www.deib.polimi.it/ita/personale/dettagli/1957454))">Daniela Selvi</a>
      </em><br>
      <span style="font-size: 18px; color: #555;">
        &gt; Rockwool Foundation Discussion Papers No. 081/26
      </span>
    </td>
    <td valign="top" align="right" nowrap width="20%">
      <a href="paper.pdf">PDF</a>&nbsp;&nbsp;|&nbsp;&nbsp;
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
