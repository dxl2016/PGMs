### Conditional probability queries
### Evidence: reduced factors by the evidence
### Inference of conditional probabilities  = sum-products, and marginalizing variables that are neither queries nor evidence out
### Renormalization at the end
### Algorithms: conditional probability
### 1. Push summations into factor products: variable elimination (DP) (exact inference)
### 2. Message passing over a graph: belief propagation (exact); variational approximations (approx.)
### 3. Random sampling instatiations: MCMC; importance sampling (approx.)
### It is intrinsically an optimization problem:
### 1. Push maximization into factor product: variable elimination
### 2. Message passing over a graph: max-product belief propagation
### 3. Using methods for IPs
### 4. For some networks: graph-cut methods
### 5. Combinatorial search
### Finding elimination orderings and VE are two NP-hard complexity questions
### Greedy search using heuristic cost function works well
### Belief propagation algorithm 
### MP-clusters; cluster graph must satisfy two properties
### 1. Family preservation: uniqueness tree
### 2. Running intersection property: without feedback loops
### Bethe cluster graph
### Reparametrization: un-normalized but more convenient sub-set forms
### Clique tree: passing messages from leaves to parents
### RIP and independence
### Separation related to minimal induced width of graph

### Algorithm for marginals:
### 1. Exact inference
### 2. Loopy message passing
### 3. Sampling methods

### Algorithm for MAP
### 1. Exact inference
### 2. Optimization methods (exact or approximate)
### 3. Search-based methods (including sampling)

### Factors in approximate inference
### Connectivity structure
### Strength of influence
### Opposing influences
### Multiple peaks in likelihood
