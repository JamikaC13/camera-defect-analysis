📘 Phase 1 – Manufacturing Defect Analysis

Pareto Analysis • Root Cause (Fishbone) Analysis • Problem Identification

🔍 Overview

This phase analyzes a rise in welding and assembly defects inside the Manual Finish welding area of an electronics manufacturing process. Using the provided defect dataset, I identified the top defective board models, the most common defect types, and the patterns that contribute to IPC-A-610E compliance failures.

This phase lays the foundation for deeper statistical analysis in later phases (ANOVA and hypothesis testing).

⸻

🎯 Business Problem

The organization produces electronic boards using Thru-Hole components, wave soldering, and manual inspection. Recently, there has been:
	•	An increase in demand, and
	•	A simultaneous spike in welding and assembly defects

These defects include:
	•	Solder bridges
	•	Missing or lifted components
	•	Reversed components
	•	Component misalignment
	•	Excessive or insufficient solder

Boards are failing several IPC-A-610E welding quality standards. Rework after final assembly is too costly and time-consuming, so defects must be corrected during Manual Finish.

The project goals:
	1.	Reduce welding defects by 20%
	2.	Increase line capacity by 20% without increasing defect rates

⸻

📈 Pareto Analysis Findings

Top models contributing to the majority of defects:
## 📈 Pareto Analysis Findings

Top models contributing to the majority of defects:

| Model        | Defects | Cumulative % |
|--------------|---------|--------------|
| 595130-195   | 888     | ~28%         |
| 595214-125   | 663     | ~51%         |
| 595242-854   | 630     | ~69%         |
| 595532-132   | 335     | ~81%         |

➡️ These four models represent 80% of all defects.

🔹 Top Defects by Model

Model 595130-195 (Assembly-related defects)
	•	Missing components
	•	Misalignment
	•	Not properly assembled
	•	Missing/unknown components

➡️ Indicates People and Method root causes.

Model 595214-125 & 595242-854 (Solder-related defects)
	•	Solder bridge
	•	Excessive solder
	•	Tilted/lifted components
	•	Pin hole defects

➡️ Indicates Machine, Material, and Method issues.

⸻

🪢 Root Cause (Fishbone) Analysis

The fishbone diagram highlights recurring causes across:

People
	•	Inspection errors
	•	Inconsistent training
	•	Incorrect placement

Machine
	•	Solder machine miscalibration
	•	Worn fixtures
	•	Tool wear

Method
	•	No standardized placement procedure
	•	Weak inspection prior to welding

Material
	•	Component inconsistency
	•	Component defects

Measurement
	•	No automated measurement or alignment tools
	•	Inconsistent defect criteria

➡️ Assembly-heavy models align with People/Method issues.
➡️ Solder-heavy models align with Machine/Method/Material issues.

⸻

💡 Phase 1 Key Insights
	•	Four models make up 80% of overall defects
	•	Assembly and soldering issues differ by model line
	•	Improvements must be customized by line, not uniform
	•	Process gaps exist in training, measurement, solder calibration, and component handling

⸻

🧭 Next Phase (Phase 2)

Phase 2 will include:
	•	ANOVA testing
	•	Hypothesis testing
	•	Statistical validation of defect differences
	•	Updated visuals
