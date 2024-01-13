---
aliases:
  - in series
  - in parallel
  - series
  - parallel
---
There are two fundamental ways to connect more than two circuit components: **series** and **parallel**.

## Series
Components in series are connected end-to-end, so that there is only one path for current to flow.
![[in series.png]]
For components in series:
- [[current]] is constant: $I_{total} = I_1 = I_2 = \dots = I_n$
- [[resistance]] is summed up: $R_{total} = R_1 + R_2 + \dots + R_n$
- the [[voltage|voltage drop]] is summed up: $V_{total} = V_1 + V_2 + \dots + V_n$
- [[power]] is summed up: $P_{total} = P_1 + P_2 + \dots + P_n$

A series circuit is often called a [[voltage divider]] for its ability to divide the total voltage into fractional portions of constant ratio.
## Parallel
Components in parallel are connected across each other's leads.
![[in parallel.png]]

For components in parallel:
- [[current]] is evenly divided: $I_{total} = I_1 + I_2 + \dots + I_n$
- [[voltage]] is constant: $V_{total} = V_1 = V_2 = \dots = V_n$
- [[resistance]] is less than any individual branch, and is calculated using the following formula: $$R_{total} = \frac{1}{1/R_1 + 1/R_2 + \dots + 1/R_n}$$
	- per [[Ohm's law]], total resistance can also be calculated using total current and voltage: $R_{total} = V_{total} / I_{total}$
	- [[conductance]] is actually added together, which explains the odd resistance behavior: $G_{total} = G_1 + G_2 + \dots + G_n$
- [[power]] is summed up: $P_{total} = P_1 + P_2 + \dots + P_n$