# Final Evaluation Report: Model Performance and Selection

**1. Model Recommendation and Forecast Accuracy**

AutoARIMA is the recommended model based on the cross-validation results. It performed better than the baseline, with a MASE of 0.65 and an RMSSE of 0.68. Since both values are below 1.0, the model provides more accurate forecasts than the naive baseline.

**2. Prediction Intervals and 80% Coverage**

Although AutoARIMA performs well in predicting future values, its coverage rate is only 70%, below the expected 80%. This means the prediction intervals are not wide enough to capture the actual values at the expected rate.

**3. Conclusion and Next Steps**

Overall, AutoARIMA provides accurate point forecasts, but its prediction intervals need further improvement. The next step is to investigate ways to improve coverage, such as adjusting the prediction intervals or analyzing the residuals using ACF to check for patterns that the model may have missed.
