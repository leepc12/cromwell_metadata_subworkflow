## cromwell_metadata_subworkflow

Use this tool if Cromwell server's built-in subworkflow embedding doesn't work due to 503 error. This happens for heavily nested workflows.

## Usage

Run it on a local Caper/cromwell server (running at localhost:8000)

```bash
$ cromwell_metadata_subworkflow/cromwell_metadata_subworkflow WORKFLOW_ID
```

