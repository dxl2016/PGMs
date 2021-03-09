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
