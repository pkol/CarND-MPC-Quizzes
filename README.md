# Simplified state in MPC
This repo contains version of MPC in which state space was vastly reduced.

New state contains only a0..aN and delta0..deltaN. Constraints are very simple
(-max..+max). There are no constraints for g(x) because there is no g(x). 

New version of MPC is in file [./mpc_to_line/src/MPC.cpp](). You can copmpare it with official
solution (by Udacity) in [./mpc_to_line/solution/MPC.cpp]().

