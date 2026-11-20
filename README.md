# Network Heterogeneity and Epidemic Spreading

**Group members:** Gustaf Munther, Erik Hedström, Hugo Westberg
**Affiliation:** Complex Adaptive Systems, year 1, Chalmers University of Technology

## Abstract

## Introduction and approach

## Repository overview

## Usage

## Tutorials

1. **Clustering: Does Living in Close Groups Slow Down an Epidemic?**
    We simulate how clustering in contact networks affects the spread of an epidemic, using a stochastic SIR model. We generate Watts-Strogatz small-world networks and vary the rewiring probability p, which changes the clustering while the number of contacts per individual stays the same. For each value of p we measure the clustering coefficient and the average path length, and compare the results with Erdős–Rényi and Barabási–Albert networks. By varying the transmission probability and the level of clustering, we examine how clustering influences the final size, peak and speed of the outbreak, and wether the spread is controlled mainly by clustering or by short paths in the network. Multiple independent simulations are performed to account for stochastic variation. 
   
2.**Vaccination: Who should be vaccinated first?**
We investigate which vaccination strategy most efficiently prevents a large outbreak in a contact network, using a stochastic SIR model. We generate with Barabási–Albert networks. Where a few individuals have more contacts, and we compare them with Erdős–Rényi networks, where outbreaks are more evenly distributed. Before the outbreak, a small part of the population is vaccinated using three different methods: at random, by the highest number of contacts, and by acquaintance immunization, where a radnom neighbour of a randomly chosen individual is vaccinated. The last method uses the friendship paradox, which says that your friends tend to have more friends than you, to find  highly connected individuals without knowing the whole network. By varying the vaccinated fraction, we examine how the final outbreak size depends on the strategy and determine the critical fraction needed to prevent a large outbreak. Multiple inedepend simulations are performed to account for stochastic variation.

4. **Herd Immunity: Can a Second Epidemic Be Prevented?** 
    We investigate how network structure affects herd immunity and the risk of a second epidemic outbreak using a COVID-inspired stochastic SIR model. We generate Erdős–Rényi, Watts–Strogatz and Barabási–Albert networks to represent different contact distributions and clustering levels. After simulating an initial outbreak, recovered individuals remain immune, and a new infection is introduced among the remaining susceptible individuals. By varying transmission probability and network topology, we examine how the immunity acquired during the first outbreak influences the probability and size of a second outbreak. Multiple independent simulations are performed to account for stochastic variation.

## References

### Clustering: Does Living in Close Groups Slow Down an Epidemic?
1. Watts, D. J., & Strogatz, S. H. (1998). Collective dynamics of ‘small-world’ networks. Nature, 393, 440–442. [https://doi.org/10.1038/30918](https://www.nature.com/articles/30918)

2. Moore, C., & Newman, M. E. J. (2000). Epidemics and percolation in small-world networks. Physical Review E, 61, 5678–5682. https://journals.aps.org/pre/abstract/10.1103/PhysRevE.61.5678

3. Newman, M. E. J. (2002). Spread of epidemic disease on networks. Physical Review E, 66, 016128. https://journals.aps.org/pre/abstract/10.1103/PhysRevE.66.016128

### Vaccination: Who should be vaccinated first?
1. Cohen, R., Havlin, S., & ben-Avraham, D. (2003). Efficient Immunization Strategies for Computer Networks and Populations. Physical Review Letters, 91(24), 247901. https://doi.org/10.1103/PhysRevLett.91.247901

2. Pastor-Satorras, R., & Vespignani, A. (2002). Immunization of complex networks. Physical Review E, 65(3), 036104. https://doi.org/10.1103/PhysRevE.65.036104

3.Feld, S. L. (1991). Why Your Friends Have More Friends Than You Do. American Journal of Sociology, 96(6), 1464–1477. https://doi.org/10.1086/229693

### Herd Immunity: Can a Second Epidemic Be Prevented?
1. Pastor-Satorras, R., Castellano, C., Van Mieghem, P., & Vespignani, A. (2015). Epidemic processes in complex networks. *Reviews of Modern Physics, 87*, 925–979. https://doi.org/10.1103/RevModPhys.87.925

2. Newman, M. E. J. (2002). Spread of epidemic disease on networks. *Physical Review E, 66*, 016128. https://doi.org/10.1103/PhysRevE.66.016128

3. Britton, T., Ball, F., & Trapman, P. (2020). A mathematical model reveals the influence of population heterogeneity on herd immunity to SARS-CoV-2. *Science, 369*, 846–849. https://doi.org/10.1126/science.abc6810   


## Contributions

- **[Name 1]:**
- **Gustaf Munther** Lead author of Tutorial 2 - Vaccination
- **Hugo Westberg:** Lead author of Tutorial 3 – Herd Immunity.
