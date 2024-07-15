# FJSP
麻雀算法求解双目标（makespan和carbon emissions）FJSP问题，解是用pareto处理的，代码是用matlab写的。
里边的麻雀个体位置移动是同时向一个方向移动的，即X_new = X * rand，而不是X_new(i) = X(i) * rand(i)。 
