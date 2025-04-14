# potential-octo-mango

1. g++ -fdump-tree-original-raw factorial_code.cpp -o factorial_code

2. g++ -fdump-tree-cfg-graph factorial_code.cpp -o factorial_code

3. dot -Tpng factorial_code.cpp.012t.cfg -o factorial_program.png

4. dot -Tpng factorial_program.dot -o factorial_program.png

