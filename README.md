# Luiss_Audience_Decode_319201
Audience Decode Project 319201
Audience Decode 319201

Team:
Gianni Dacchille 313201
Lorenzo Molinari 320811
Aldo Ramezzana 319201

The Audience Decode Project explores how users interact with movies, with the goal of understanding different audience behaviors. By analayzing user-movie interaction data, the project identifies distinct user profiles using unsupervisex machine leanring techniques.

Methodology:

1) Loading and cleaning the dataset
2) Explonatory Data Analysis (EDA) to understand overall trends
3) Feature engineering at the user level to capture behavior patterns
4) Feature scaling to ensure comparability
5) Dimensionally reduction unsing PCA
6) Clustering users with KMeans to uncover distinct profiles

Key Finding

The results show that engagement level is the main factor distinguishing users.
Several cluser emerge, ranging from occasional viewers to highly engaged power users, each with different rating habits and interaction patterns.
These cluster provide a meaningful way to segment users and better understand how different types of audience consume movies.

Limitations and future work

This analysis is based on a limited set of user-level features and on KMeans,
which assumes spherical clusters and may not capture more complex structures in
the data. Future work could include richer behavioral features and alternative
clustering approaches to further refine audience segmentation.
