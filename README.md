This project presents a dual-scale coupled porous medium model developed to study airflow obstruction and oxygen exchange in lungs affected by Chronic Obstructive Pulmonary Disease (COPD) and Pulmonary Tuberculosis (TB). The computational framework integrates a global heterogeneous porous medium model of the lung airway network with a local alveolar gas-exchange model to analyze the effects of congestion on pulmonary oxygen transport.

The simulations were carried out using ANSYS Fluent, where transient mass, momentum, and species transport equations were solved over multiple breathing cycles. Custom User Defined Functions (UDFs) were developed to model disease progression, permeability variation, porosity changes, immune response effects, smoking influence, and time-dependent congestion growth.

The lung domain was divided into multiple porous regions with varying permeability to represent the heterogeneous airway structure. Disease progression was incorporated by dynamically modifying porous medium properties such as permeability and porosity using congestion-based relations and the Carman–Kozeny equation. The resulting airflow reduction in the alveolar region was coupled with the local oxygen transport model to estimate variations in blood oxygenation.
The model was used to simulate:

•	Airflow distribution in healthy and congested lungs
•	Oxygen exchange at the alveolar-capillary interface
•	Effects of COPD and TB progression on pulmonary function
•	Influence of immunity degradation and smoking patterns
•	Medication and recovery trends under different disease conditions

The study demonstrates the applicability of CFD-based porous medium modelling for investigating respiratory disease progression and evaluating treatment-related outcomes using simulation-driven approaches.
