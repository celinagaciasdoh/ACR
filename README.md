# ACR

[For Dr. Ron]

Identifying the five most probable ACR classes (out of 345) for 18,000+ clinical diagnoses.
Used bag-of-words representation for the diagnoses and a random forest classifier to obtain the class probabilities. A support vector machine model might have been better but I need to read more on it for fine-tuning because it took too much memory to run.

Did not get to evaluate model accuracy given the timeframe and purpose (to assist specialists with the classification process) but from a brief appraisal of the results, it seems that the algorithm performed poorly on categories that were not previously represented by an ACR group (e.g. assault, persons with potential health hazards or dependencies, etc.)
