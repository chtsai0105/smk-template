import pandas as pd


### Configuration
configfile: "config.yaml"
data = pd.read_csv(config['Metadata'], keep_default_na=False, na_values=['_'], comment="#")

### Input settings
input_list = list()

### Entry point
rule all:
    input:
        input_list
