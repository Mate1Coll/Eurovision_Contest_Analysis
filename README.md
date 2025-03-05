# Eurovision Song Contest Voting Analysis  

In this work, we analyze the Eurovision Song Contest (ESC). Europe’s multicultural diversity suggests that voting preferences between countries could be influenced by factors such as language, political relationships, or ideological similarities. Then, in this work, we try to answer the following questions:  

- **Are there voting biases between countries?**  
- **Do voting patterns suggest consistent alliances or blocs among countries?**  

## Project Structure  

We divide the project into the following parts:  

### Data Exploration  
In this section, we load the data, clean it, and extract the most basic information and metrics to familiarize ourselves with and understand the data.  

### Country Analyzer  
We display a layout of the points given by a country (jury votes and televotes) since a given year (in this case, 1975) and analyze their distributions.  

### Country Voting Analysis  
We perform a full analysis of the voting portfolios of each country throughout a time interval:  

- **Bias Dyads:** The smallest possible social group. We study the bias in voting tendencies between pairs of countries and their statistical significance.  
- **Correlation in Voting Patterns:** We analyze how similar the voting patterns are among different countries. Thus, we compute a correlation matrix from the data and perform hierarchical clustering. Then, we provide a graph visualization of the clusters.  
- **Random Contest Comparison:** Finally, we compare the real voting frequency among the members of the obtained clusters with a random contest to study whether voting similarity implies vote exchanges. Additionally, we compute the bias among the members of each cluster.  

## Results 

The results are plotted in this notebook and presented in the PDF file presentation of this repository.  

## Citation  

This project uses data from the [Eurovision Dataset](https://github.com/Spijkervet/eurovision-dataset) by [Spijkervet](https://github.com/Spijkervet). All citations are displayed at the end of the PDF presentation.

