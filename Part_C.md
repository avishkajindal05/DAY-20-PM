Q1 — What is the difference between normal distribution and standard normal distribution?
> 
Normal → any mean/std
Standard → mean=0, std=1

Q2 (Coding) — Implement a function: z_score(x, mean, std)
● Return standardized value
● Apply on a dataset
>
def z_score(x, mean, std):
    return (x - mean) / std

Q3 — What is hypothesis testing? Explain:
● Null hypothesis
● Alternative hypothesis
● p-value
● Significance level (α)
>
H₀: assumption (no effect)
H₁: alternative
p-value: probability of result under H₀
a(alpha): threshold (0.05)