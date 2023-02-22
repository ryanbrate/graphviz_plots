# graphviz_plots

Create head->dep plots via graphviz.

defined in terms of 'structure' and (optionally) 'properties', create a directed graph.

## Run configs in plot_configs.json
```

```

## configuration options (and example)

```
{
    "desc": "KB dataset breakdown",
    "switch": false,
    "struct": {
        "USA": ["Texas", "Arizona"]
    },
    "prop": {
        "USA": {"region": "USA", "population": "300M"},
        "Texas": {"region": "Texas", "population": "20M"}
    },  # optional. Where absent, the struct name will be used, otherwise property info used.
    "output_dir": "DATA/graphviz_plots/example"
},
}
`` 
