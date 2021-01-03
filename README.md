## Distribution of Respirators among Hospitals

### Problem Description

A rise in COVID infections strains the resources of health care facilities. Respirators are critical resources
that might be in shortage due to high demand. In an attempt to manage their critical resources, a group
of hospitals within the Beirut municipality decided to pool their resources to satisfy the demand for
respirators. </br>
Each hospital reports the number of respirators at its disposal. At the end of each week, the hospital
management boards (HMBs) provide an updated estimate on the projected demand for respirators at
each hospital and determines whether any of the respirators needs to be reassigned. There is a
transportation cost associated with reassigning a respirator to a different hospital. Therefore, the HMBs
need to determine a minimum cost assignment of respirators to hospitals that satisfies the next week’s
projected demand at each hospital. </br>
As an example, consider five hospitals with five locations within the Beirut municipality. The HMB
evaluates the need to relocate respirators based on the monthly projected demand for each hospital. The
cost of reassigning a respirator from hospital i to hospital j is 100,000 LBP per kilometer of travel of
distance for hospital i to hospital j. An extra setup cost (due to overhead costs) of 200,000 LBP is incurred
for each order from hospital i to j. For each of the hospital’s locations, the table below lists the X and Y
coordinates of the hospital, the number of respirators currently assigned, and the projected demand for
next period. </br>

| Hospital | X_Coordinate (km) | Y_Coordinate (km) | Respirators at Hospital | Projected Demand for next Week |
| :----------: | :--: | :--: | :--: | :--: |
| Hospital 1 | 36 | 20 | 30 | 35 |
| Hospital 2 | 23 | 30 | 10 | 15 |
| Hospital 3 | 23 | 56 | 15 | 10 |
| Hospital 4 | 10 | 15 | 15 | 20 |
| Hospital 5 | 5 | 5 |20 | 10 |

### Objective

1. *Formulate* an Integer Linear Program for the case with H=5 hospitals where Rh is the number of
respirators at hospital h, and Dh is the projected demand for hospital h (for h = 1,2,… H). Denote the
coordinates of hospital h by Xh and Yh. **A word file containing the problem formulation** should be generated from python code.
2. Using Excel Solver and the problem formulation, what is the optimal cost and decision?

