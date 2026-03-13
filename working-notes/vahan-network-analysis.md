# Working Notes: Vahan Network Analysis

**Status:** In Progress
**Target:** Working Paper / arXiv preprint

## Research Question

Does the Vahan vehicle registration network exhibit scale-free or small-world properties?
Can we predict market concentration and EV adoption tipping points from network structure?

## Data Plan

1. Extract monthly state-wise MSIL registration data (2017-2024)
2. Build bipartite network: states × models
3. Analyze degree distribution (power law test)
4. Calculate clustering coefficients

## Key Hypotheses

- H1: Top 5 states account for >50% of registrations (Pareto distribution)
- H2: EV adoption follows S-curve with network-driven acceleration
- H3: Fuel-type transitions exhibit critical threshold behavior

## Literature Review

- Bassett & Sporns (2017) - network neuroscience methods (adaptable)
- Abrahamson & Rosenkopf (1997) - social network effects on technology diffusion
- Rogers (2003) - Diffusion of Innovations

## Methods

```python
import networkx as nx
import pandas as pd
import powerlaw

# Load Vahan data
df = pd.read_csv('data/vahan_2024.csv')

# Build state-model bipartite network
B = nx.Graph()
# ... analysis code
```

## Next Steps

- [ ] Download 3 years of Vahan data
- [ ] Build initial network graph
- [ ] Run power law fit
- [ ] Write abstract for SSRN submission
