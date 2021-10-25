
```commandline
├───components            # Store the spec yaml file of components. Different versions are placed in a subdirectory named by version.
│   ├───aetheremailmodule
│   │   └───0.0.1
│   ├───alltrailscenteredclustering
│   │   └───0.0.1
│   ├───aml_itp_module
│   │   └───0.0.1
│   ├───attractions_conflation_entity_type_similarity_calculation_scope_module
│   │   └───0.0.1
│   ├─── ......     
│   └───wikicenteredclustering
│       └───0.0.1
├───config                # TODO
├───doc                   # TODO, may store the reference doc of components and pipelines.
├───pipelines             # Store the pipeline code
│   ├───components        # The generate package code of assets.
│   │       _assets.py
│   │       _workspace.py
│   │       __init__.py
│   ├───get_started
│   │   │   pipeline.py   # Pipeline code.
│   │   │   __init__.py
│   │   └───subgraphs     # The subgraph code that will be called in the pipeline
│   │          train_score_eval.py
│   │          __init__.py
│   ├───large_graph
│   │   │   pipeline.py   # Pipeline code.
│   │   │   __init__.py
│   │   └───subgraphs
│   │          attractions_entity_conflation_image_similarity_sub_graph_9935.py
│   │          attractions_entity_feature_vector_generation_subgraph_5929.py
│   │          backup_file_5fc1.py
|   |          ......
│   └───utils
│          pipeline_helper.py    # TODO
│          utils.py
│          __init__.py
├───scripts
│      aml_create_win_cluster.py
│      ......
└───tests     # Unittest of pipelines and components.
```
