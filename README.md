# world-value-survey-segmentation
This project segments socioeconomic groups using World Values Survey (Wave 7) data (90,000+ records). After preprocessing, MiniBatch K-Means identifies four clusters, achieving a silhouette score of 0.120 and Davies-Bouldin index of 1.539, outperforming DBSCAN.

PCA (72% variance) and t-SNE reveal distinct groups: "Rural Poor" (avg. income $4,000), "Urban Middle Class" ($18,000), and "Elite" ($45,000), with education levels following the same trend. Compared to global benchmarks, Kazakhstan’s middle class lags in income and education.

This study shows unsupervised learning effectively uncovers socioeconomic patterns, offering insights for policy, market research, and social planning.

IEEE Machine Learning 24-hour hackathon organized by NU IEEE SB, KPMG, Sergek Group, and Desht Lab.
