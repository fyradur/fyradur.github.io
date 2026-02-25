
Normalization is changing the schema of data in order to avoid redundancy and update anomalies.  
Common forms are **1NF, 2NF, 3NF and BCNF**.

### 1NF
No field can contain a list of values (all attributes are atomic).

### 2NF
Forbids any **non-prime attribute** from depending on only part of a **candidate key**  
(i.e. no partial dependency on a composite key).

### 3NF
Forbids any **non-prime attribute** from depending on something that is **not a superkey**  
(i.e. no dependency $X \to A$ where $X$ is not a superkey and $A$ is non-prime).

### BCNF
Forbids any dependency where the left side is not a superkey  
(i.e. for every $X \to A$, $X$ must be a superkey).

[[Superkey]]
[[Candidate key]]
[[Prime attribute]]