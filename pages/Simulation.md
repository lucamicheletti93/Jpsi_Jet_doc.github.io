## Simulation framework

### Pythia simulations
- Clone https://github.com/nzardosh/PYTHIA8_Simulations

- ```ruby
  source /home/pyadmin/setup-pythia8.sh
  ```
  
- ```ruby
  ./compile_pythia_aliceml.sh Pythia_jets
  ```
  
- ```ruby
  ./run_sim_parallel.sh -o Charm --pthard-low 0 4 8 12 15 --pthard-up 4 8 12 15 1000  --events-per-pthard 2000000 2000000 2000000 2000000 2000000 --flavour 1 --jetR 0.4 --mecorr 1 --charged 1 --unev 1 --tune 14 --number -1 --events-per-job 4329 -j 18
  ```
