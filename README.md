# Hazard-Rate-Calculation-from-CDS-Spread

**** Disclaimer: This work is for learning purpose only. The work cannot be used for publication or sa commercial products, etc without instructor's consent.****

Group Project for the courese MA477
(Financial Risk Management)

Instructor: Dr. Arabin Kumar Dey

Group Members: 
1. Jatin Dhingra (180123060)
2. Himanshu Rao (180123016)
3. Shravya (1801230)
4. Neeraja (1801230)
5. Samiksha Sachdeva (180123040)

We have calculated Hazard Rate and Survival Probability by bootstrapping on CDS Spread Dataset and drawn graph between Hazard Rate v/s CDS Maturity and Survival Probability v/s CDS Maturity.
Following steps were used to calculate Hazard Rate and Survival Probability:
* Finding Survival Probability (S(t)) for different time by bootstrapping on CDS Spread Dataset.
* Finding Hazard Rate (h(t)) using Survival Probability. h(t) = -log(S(t)).

We take a csv file as input with following variables
* Maturity
* DF
* Spread
* Recovery
And then calculate S(t) and H(t).
