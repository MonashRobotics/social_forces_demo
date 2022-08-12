# Social forces demo

Playing around with a social forces model 

https://arxiv.org/pdf/cond-mat/9805244.pdf

This implentation assumes agents are point masses moving towards a goal $x_g$

$\mathbf{u_t} = K_p(x_t-x_g) + K_i {\sum}^t_{i=0} (x_i - x_g) - F_r + F_a$

where $F_r$ and $F_a$ are repulsive and attractive forces proportional to the weighted distance to other agents in the scene
