# Legacy uploaded CAD/3D files

This directory stores the original uploaded CAD/3D files before they are renamed or de-duplicated. Files were moved here first so no duplicate or ambiguous legacy uploads are deleted during naming cleanup.

Recommended CAD/3D naming convention:

```text
subsystem_part-name_version_YYYYMMDD.format
```

Notes:

- `YYYYMMDD` is inferred from STEP `FILE_NAME` timestamps or package metadata where available.
- Keep the original filename in this directory for traceability until a maintainer confirms the canonical model and version history.
- The original misspelling `seperator.step` is preserved in the legacy record; its recommended new name uses `separator`.

| Original filename | Recommended new filename | Inferred purpose | Legacy version? | Needs manual confirmation? |
| --- | --- | --- | --- | --- |
| `Anode nozzle 2.step` | `thruster_anode-nozzle_v2_20251006.step` | Thruster anode/nozzle geometry, likely a second revision. | Yes; likely supersedes/relates to nozzle drafts. | Yes |
| `Magnet holder (2).3mf` | `mount_magnet-holder_v2_20251120.3mf` | 3MF print/project package for magnet holder. | Yes; duplicate export/package of magnet holder. | Yes |
| `Magnet holder (2).step` | `mount_magnet-holder_v1_20251002.step` | STEP model for magnet holder. | No; likely canonical CAD source for the holder. | Yes |
| `anode conducting plate.step` | `thruster_anode-conducting-plate_v2_20250728.step` | Conductive anode plate component. | Yes; likely newer variant of `anode plate.step`. | Yes |
| `anode plate.step` | `thruster_anode-plate_v1_20250708.step` | Anode plate component. | Yes; likely earlier anode plate variant. | Yes |
| `cathode clamp.step` | `thruster_cathode-clamp_v1_20250709.step` | Clamp for cathode assembly. | No | Yes |
| `hollow cathode (1).step` | `thruster_hollow-cathode_v2_20250628.step` | Hollow cathode standalone or revised component. | Yes; later timestamp than `hollow cathode.step`. | Yes |
| `hollow cathode.step` | `thruster_hollow-cathode_v1_20250628.step` | Hollow cathode component/assembly. | Yes; earlier timestamp than `hollow cathode (1).step`. | Yes |
| `mpd-thruster draft 1.stl` | `thruster_assembly-draft_v1_date-tbd.stl` | STL draft/export of MPD thruster assembly. | Yes; draft mesh export. | Yes |
| `mpd-v1.step` | `thruster_assembly_v1_20250622.step` | MPD thruster assembly, version 1. | Yes; assembly baseline. | Yes |
| `right plate (1).step` | `frame_right-plate_v2_20251108.step` | Right-side frame/plate component, later revision. | No; likely newer right plate. | Yes |
| `right plate.step` | `frame_right-plate_v1_20250714.step` | Right-side frame/plate component, earlier revision. | Yes | Yes |
| `rocket nozzle (1).step` | `thruster_rocket-nozzle_v1_20250828.step` | Rocket/nozzle component, possibly related to anode nozzle. | Yes; ambiguous nozzle naming. | Yes |
| `seperator.step` | `thruster_separator_v1_20250630.step` | Separator component; original filename is misspelled. | No | Yes; confirm spelling and subsystem. |
| `w70cu clamp.step` | `thruster_w70cu-clamp_v1_20251004.step` | W70Cu clamp component, likely electrode/cathode hardware. | No | Yes |
