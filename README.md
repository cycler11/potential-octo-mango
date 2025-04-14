# potential-octo-mango

g++ -fdump-tree-original-raw factorial_code.cpp -o factorial_code
g++ -fdump-tree-cfg-graph factorial_code.cpp -o factorial_code
dot -Tpng factorial_code.cpp.012t.cfg -o factorial_program.png
dot -Tpng factorial_program.dot -o factorial_program.png

