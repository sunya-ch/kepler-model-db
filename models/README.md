# Power Models

Power models are stored with the following file structure.

```yaml
└── <version>
    ├── README.md
    └── <machine_id>
        ├── <pipeline_name>.zip # archived pipeline (optional)
        └── <pipeline_name>
            ├── README.md # validation results of pipeline
            ├── *_model_metadata.csv # summary of trained model 
            ├── metadata.json # pipeline metadata
            ├── <energy_source>/<output_type>/<feature_group>/* # model files
            ├── train_arguments.json
            └── preprocessed_data
                ├── *_data.csv # raw preprocess data (optional)
                └── preprocess_*.png # visualized preprocess data   
```

- standard pipeline named by `std_<version>_<benchmark type>`
- preprocessed data are optional to upload

## Train server information

Machine ID|CPU Architecture|CPU model (optional)|#sockets (optional)|OS|Kernel version
---|---|---|---|---|---
nx12|x86_64|[Intel® Xeon® Processor E5-2667 v3](https://ark.intel.com/content/www/us/en/ark/products/83361/intel-xeon-processor-e52667-v3-20m-cache-3-20-ghz.html)|2|Ubuntu|5.15.0-78-generic

