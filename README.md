# SagTree: Towards Efficient Mutation in Evolutionary Circuit Approximation
This repository provides source codes in Verilog of the circuits used as seeds in experiments in our paper ___SagTree: Towards Efficient Mutation in Evolutionary Circuit Approximation___


For more details please follow this article:

ČEŠKA Milan, MATYÁŠ Jiří, MRÁZEK Vojtěch, SEKANINA Lukáš, VAŠÍČEK Zdeněk and VOJNAR Tomáš. SagTree: Towards Efficient Mutation in Evolutionary Circuit Approximation. Swarm and Evolutionary Computation, vol. 69, no. 100986, 2022, pp. 1-10. ISSN 2210-6502. Available from: https://www.sciencedirect.com/science/article/pii/S2210650221001486


## Circuits
The seed circuits are accurate - i.e., no error was injected to the code.


| Circuit             | Inputs bitwidth | Output bitwidth   | Function      | File link |
| ------------------- | --------------- | ----------------- | -----         | ----- |
| 8-bit adder         | 8, 8            | 9                 | A + B         | [add_8-8.v](add_8-8.v)
| 16-bit adder        | 16, 16          | 17                | A + B         | [add_16-16.v](add_16-16.v)
| 31-bit divider      | 31, 16          | 16                | A / B         | [div_31-16.v](div_31-16.v)
| 15-bit divider      | 15, 8           | 8                 | A / B         | [div_15-8.v](div_15-8.v)
| 8-bit MAC           | 8, 8, 16        | 17                | (A * B) + C   | [mac_8-8-16.v](mac_8-8-16.v)
| 16-bit MAC          | 16, 16, 32      | 33                | (A * B) + C   | [mac_16-16-32.v](mac_16-16-32.v)
| 8-bit multiplier    | 8, 8            | 16                | A * B         | [mult_8-8.v](mult_8-8.v)
| 16-bit multiplier   | 16, 16          | 32                | A * B         | [mult_16-16.v](mult_16-16.v)
| 8-bit square        | 8               | 16                | A^2           | [square_8.v](square_8.v)
| 16-bit square       | 16              | 32                | A^2           | [square_16.v](square_16.v)

