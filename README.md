# Calculated-Fields-Parameters-LOD-Expressions

Question 1: What is a Calculated Field and why is it important in business dashboards?

Answer: A calculated field is a custom field created using formulas in Tableau. It allows users to
derive new data from existing fields. It is important because it helps create KPIs, perform custom
calculations, and enable deeper insights without modifying the original dataset.

Question 2: Why can’t parameters change visuals directly in Tableau?

Answer: Parameters cannot directly change visuals because they are not linked to the data. They
act as input values and must be used inside calculated fields to influence charts or filters.

Question 3: When should EXCLUDE LOD be used?

Answer: EXCLUDE LOD is used when you want to remove a specific dimension from the view’s
level of detail. It is useful for comparing totals or averages independent of certain dimensions.

Question 4: Difference between FIXED and INCLUDE LOD expressions?

Answer: FIXED LOD computes values at a fixed level regardless of filters or view, while INCLUDE
LOD adds extra dimensions to the calculation even if they are not present in the view.
