# foundry-pipelines

One folder per Foundry pipeline, each with its `PipelineManifest.yaml` (and the `PipelineManifest.layout.json` Foundry Studio keeps node positions in).

| Pipeline | |
|---|---|
| [`PacketPipeline/`](PacketPipeline) | `EnrichmentPipeline`: XML packets -> JSON -> decoded -> ISP-enriched |

Profiles and schemas the manifests refer to are in [foundry-common/configs](https://gitlab.com/foundry-common/configs); check a manifest with `manifest.py validate` from [foundry-common/scripts](https://gitlab.com/foundry-common/scripts).
