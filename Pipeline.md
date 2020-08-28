# Pipeline

With each new reading of the meter:
1. Meter works? In other words, the data is missing for the timestamp.

Then look at four time scales:
1. 15 minutes (single measurement)
2. 1 hour
3. 8 hours
4. 24 hours back

Every Sunday ( = last day of the week), retrain the models on the data from the last three months.
