# Eurovision_Contest_Analysis

In this work we analyze the Eurovision Song Contest (ESC). Europe’s multicultural diversity suggests that voting preferences between countries could be
influenced by factors such as language, political relationships, or ideological similarities. Then, in this work we try to answer the following questions:

- **Are there voting biases between countries?**
- **Do voting patterns suggest consistent alliances or blocs among countries?**

Therefore, we divide the project into the following parts:

- **Data exploration:** In this section we load the data, clean it and extract the most basic information and metrics to familiarize and understand the data.
- **Country analyzer:** We display a layout of the points given by a country (jury votes and televotes) since a given year (in this case 1975) and their distributions.
- **Country voting analysis:** We perform a full analysis of the voting portfolios of each country throughout a time interval:
    - **Bias dyads**: It is the smallest possible social group. We study the bias in voting quality between pair of countries and their statistical significance.
    - **Correlation in voting paterns**: We analyze how similar are the voting patterns among the different countries. Thus, we compute a correlation matrix from data and perfom an hierarchical clustering. Then, we provide a graph visualization of the clusters.
    - **Random contest comparison**: Finally we compare the real voting frequency among the members of the obtained clusters with a random contest to study if voting similar implies vote exchanges (also we compute the bias among the members of each cluster).

The results are plotted in this notebook and presented in the pdf file presentation of this repository. All the citations are displayed in the pdf presentation.
