# Changes in v0.2.4
(2023/07/28)
- new code for Validation_curve.py, and also changed usage of this widget. Validation_curve.py is now connected to the output of Test & score widget and uses the calculations of Test & score.
- changed documentation for Validation_curve.py
- added 2 flows in folder example-flow to show usage of Validation_curve.py

# Changes in v0.2.3
(2023/05/10)
- bug fix in Diagram_target_predictions.py
- added script Evaluation_results.py
  (Which is like to Evaluation_results_binary.py, but can handle also multiclass problems and show the real labels in confusion matrix.)

# Changes in v0.2.2
(2022/07/18)
- bugfix in Learning_curve.py: compute RMSE instead of MSE for Test score
- optimize code in Learning_curve.py
- harmonize look of diagram in Learning_curve.py and Diagram_target_predictions.py
- new script Evaluation_Results_binary.py for display of performance criteria when adjusting the decision Threshold
- new documentation for Evaluation_Results_binary.py
- some minor changes in documentation
- new: some example flows in folder example-flows

