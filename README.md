# TLSN_TestU01

## TestU01
TestU01 is a standard test suite for testing the randomness of PRN, which can test much longer random sequences and is much more stringent than NIST. The test suite is available at http://simul.iro.umontreal.ca/testu01/tu01.html.

## Experiments
In our randomness test, the eight batteries, including FIPS-140-2, PseudoDIEHARD, Alphabit, Rabbit, BlockAlphabit, SmallCrush, Crush, BigCrush, are utilized to test the randomness of the proposed PRNG.

We first focus on the influence of control parameter $c$ on the PRNGs for both cases of TLSN, shown in **Table III**. The initial conditions are determined as ($x_{0}$, $y_{0}$) = (0.1, 0) and accompanied by tiny perturbation as ambient noise. As can be observed, the PRNGs for $Case 1$ and $Case 2$ can be passed through all batteries of TestU01. Afterwards, the control parameters are fixed as ($a$, $b$, $c$) = (0.6, 0.4, −3.3) and different factor $m$ is chosen as the initial condition parameter. **Table IV** presents the results of TestU01 experiments under different initial conditions, once more passing all the batteries.