## About

Based on the nonlinear differential evolution algorithm for global optimization, this is an improved differential evolution with dynamic mutation parameters. 

This is the official implementation of the non-linear differential evolution algorithm with dynamic parameters for global optimization, which has been published in the following paper. 

```
Lin Y, Yang Y, Zhang Y. Improved differential evolution with dynamic mutation parameters[J]. Soft Computing, 2023: 1-19.
```

Please use the following BibTeX to cite this paper if you wish to. 

```
@article{lin2023improved,
  title={Improved differential evolution with dynamic mutation parameters},
  author={Lin, Yifeng and Yang, Yuer and Zhang, Yinyan},
  journal={Soft Computing},
  volume={27},
  number={23},
  pages={17923--17941},
  year={2023},
  publisher={Springer}
}
```

## Usage

The main code is available in `differentialEvolution.m` file. There are options to specify various parameters in the `de.m` file. 

To run the program via the following command line. 

```
> run
```

The default objective function used is in `config.csv`. Custom scheme can be specified in `de.m` under `options.use_mutation_scheme`. All the objective functions would be tested after a scheme is specified. 

## Acknowledgements

This project is optimized from [https://github.com/iskunalpal/Differential-Evolution](https://github.com/iskunalpal/Differential-Evolution). 

The improved version can also be found at [https://github.com/BatchClayderman/DifferentialEvolution](https://github.com/BatchClayderman/DifferentialEvolution). 
