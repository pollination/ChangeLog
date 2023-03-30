## Version 1.27.4 2023-03-30
- Rhino plugin: use GUID for all resource objects (Material, Modifier, Construction, Schedule, etc)
- Grasshopper plugin: fix an issue with loading the local job with `CheckStudyStatus` component.
- Grasshopper plugin: `CheckStudyStatus` component now only loads succeeded study.
- Rhino plugin: Fix SHWManager doesn't apply to the model
- Rhino plugin: prevent assigning a DetailedHVAC to a room. Use the new command `PO_ApplyDetailedHVAC`.
- Pollination: support job status for local jobs.

## Version 1.27.0 2023-03-24
- Rhino plugin: Support multiple documents in PO_HVACEditor.
- Rhino plugin: Add a new command `PO_ApplyDetailedHVAC` for assigning a DetailedHVAC to associated rooms.
