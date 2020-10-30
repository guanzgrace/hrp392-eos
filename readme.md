# HRP 392 Final Project

### A Cost Effectiveness Analysis of Approaches to Identifying Late Preterm and Term Infants at Risk for Early Onset Sepsis

Modeled using the [Amua](https://github.com/zward/Amua) software.

File directory:

* `sanity_check.amua` - Given our model up to the Level II NICU admission, if we run 1,000 babies through each Strategy, do we get a EOS incidence rate that is reflective of values in the literature?

* `sanity_check_baseline1.amua` - Scale the P(Sepsis is not ruled out) for each relevant branch in Strategies 2 and 3 to the incidence rate in Strategy 1 (1.25072 cases / 1000 live births)

* `sanity_check_baseline2.amua` - Scale the P(Sepsis is not ruled out) for each relevant branch in Strategies 1 and 3 to the incidence rate in Strategy 2 (0.57564 cases / 1000 live births)

* `sanity_check_baseline3.amua` - Scale the P(Sepsis is not ruled out) for each relevant branch in Strategies 1 and 2 to the incidence rate in Strategy 3 (1.09242 cases / 1000 live births)

* `basecase1.amua` - Base case with Strategy 1's EOS incidence