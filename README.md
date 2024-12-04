# SimNDT2b

The batch processor version of SimNDT Version 2

The batch processor reads the entire simulation scenario from a json file and performs a simulation. Output can be saved in numpy format by enabling snapshots.
Either each snapshot step is svaed in one file, or the snapshots (matrix of specific field variables) are accumulated in a three-dimensional volume, saved in on numpy file.

## Authors

1. Miguel Molero
2. Stefan Bosse
3. Sanjeev Kumar

## Batch processing run

1. Update the path to save the simulation data in the JOSN file under the key name ["Snapshot"]["Save_filepath"].
2. Run and save simulation command: python main.py "path_to_json_file"


