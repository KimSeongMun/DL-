# Modifications
1. I removed all args.hyperparameters. Because I felt more comfortable without it and I didn't want to use the part of experiment.  
2. I removed about gpu code(=cuda). I use colab.   This is because the code before the change cannot find the gpu device even though the runtime was changed to gpu when the code was run.  
3. I used the following blocks from the original code. (2, 3, 4, 6, 7, 10, 11, 12)  
4. I used the following blocks by removing args and cuda from the original code. (5, 8, 9, 14, 15, 16)  
5. The biggest change is block 13.  
6. In block 13. As the GCNblock class was deleted from original code, two gcn_layer was randomly added, tanh of pred3 was changed to ReLU, and the forward part was modified accordingly.  
7. I added the following blocks according to the situation. (1, 17, 18)
8. I added the following blocks to visualize. (19, 20)
