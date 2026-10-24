# autograd-from-scratch

day6
While testing grad_check with MDP, the resulted error was 0.75, and at first I considered that there are bugs in my code. But actually there were no bugs, but after the model learned, grads were greatly close to 0, which caused the relative error to be bumped.