# Parallel Gate Simulation

This project emulates the AND, NAND, OR, NOR, XOR, XNOR logic gates. The input is a .txt file, on each line is three numbers which refers to the gate type and the 2 inputs. 
We compare the run time of evaluating the gates sequentially and evaluating them in two parallel manners. One parallel method uses an explicit memory allocation, and the other uses unified memory allocation.
This project is written using cuda-c. Input files and their solutions are included in the repo, the notebook also contains the code to run the comparisons. 