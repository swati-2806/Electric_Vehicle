follow the following steps to get desired output..
1. run all the jupyter cells (make sure emptycell=-1 )

output of graph will be saved in the same directory as "before-removing.png"

2. watch the social cost of the nodes ( output of cell having the only statement "print(costs)" )

3. identify the index of lowest cost node.

4. change "emptycell=<index of lowest cost node>".

5. re-run all the cells except the first cell (which is having imports and the statement "pos={}")

otherwise it will give error and you will not get the desired output. In that case restart from step 1.

6. output graph will be saved in the same directory as "after-removing<node index>.png"
