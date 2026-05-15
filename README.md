# AF-MPD Thruster Open-Source Project

This repository is the public open-source archive for my ISEF engineering project: an AF-MPD thruster, or applied-field magnetoplasmadynamic rocket thruster. The goal of this repository is to make the project understandable, reusable, and improvable by students, makers, and researchers who are interested in electric propulsion, plasma devices, vacuum testing, and experimental aerospace hardware.

The project is not presented as a finished or perfect commercial system. It is an iterative research and engineering project. Some designs worked better than others, some files represent older versions, and several parts of the system still need improvement. I am sharing the files so that other people can learn from the design process, review the mechanical choices, and use the models as references for future improvements.

## Project Purpose

The purpose of this project is to design, build, and document an experimental AF-MPD rocket thruster system. In an MPD thruster, electrical current and magnetic fields interact with plasma to accelerate propellant and generate thrust. In an applied-field MPD design, an external magnetic field is added to influence plasma behavior and potentially improve performance.

This repository is intended to provide:

- Open access to the 3D design files used during the project.
- Project images and documentation that explain the hardware and design process.
- A clear record of older design iterations and newer versions.
- Reference material that interested researchers can inspect, redesign, and improve.
- Notes about limitations, unresolved problems, and possible future work.

## Repository Status

This repository is currently being organized for open-source release. The CAD and 3D-printing files that have already been uploaded are part of the project design history and include older or intermediate iterations. Future organization will separate the repository into clearer folders for historical files, latest files, images, documentation, software, electronics, and simulation notes.

The current uploaded hardware files include STEP, STL, 3MF, and PDF design files for thruster-related parts such as anode/nozzle components, cathode components, plates, holders, clamps, and draft assemblies.

## Current Uploaded CAD and 3D Files

The files currently uploaded include earlier or intermediate design files such as:

- `mpd-v1.step`
- `mpd-thruster draft 1.stl`
- `Drawing 3.pdf`
- `Anode nozzle 2.step`
- `rocket nozzle (1).step`
- `hollow cathode.step`
- `hollow cathode (1).step`
- `anode plate.step`
- `anode conducting plate.step`
- `cathode clamp.step`
- `w70cu clamp.step`
- `right plate.step`
- `right plate (1).step`
- `Magnet holder (2).step`
- `Magnet holder (2).3mf`
- `seperator.step`

These files should be understood as part of the project's iteration history unless they are later moved into a clearly marked latest-design folder. Some file names still reflect the original export names from the design process, including spaces, parentheses, and draft naming. They may be renamed or reorganized later for clarity.

## Planned Repository Organization

To make the project easier to understand and reuse, the repository is intended to be organized into a structure similar to this:

```text
AF-mpdt/
├── README.md
├── LICENSE
├── SAFETY.md
├── hardware/
│   ├── latest/
│   │   ├── thruster-assembly/
│   │   ├── vacuum-chamber/
│   │   ├── test-platform/
│   │   ├── control-panel/
│   │   └── frame/
│   ├── iterations/
│   │   └── legacy-uploaded-files/
│   └── drawings/
├── images/
│   ├── cad-renders/
│   ├── testing/
│   └── project-overview/
├── docs/
│   ├── project-description.md
│   ├── design-iteration-history.md
│   └── limitations-and-future-work.md
├── simulation/
├── electronics/
└── software/
```

The goal of this structure is to separate historical iteration files from the latest reference design. The latest-design section is expected to include files for the vacuum chamber, full test platform, control panel, frame, and thruster assembly.

## Latest Design Files to Be Added

The latest project files are expected to be organized by subsystem. These are the major areas that should be represented in the open-source archive:

### Thruster Assembly

The thruster assembly section should include the newest AF-MPD thruster geometry, including the anode, cathode, nozzle, insulators or separators, clamps, conducting plates, magnet holders, and any required mounting hardware.

### Vacuum Chamber

The vacuum chamber section should include CAD models, drawings, or reference images for the vacuum chamber used to test the thruster. If possible, it should also describe the chamber interfaces, mounting points, feedthroughs, and any limitations of the vacuum test environment.

### Test Platform

The test platform section should document the complete test setup used to support the thruster, chamber, frame, electronics, measurement devices, and related hardware. This section should help other researchers understand how the system was assembled and tested.

### Control Panel

The control panel section should describe the hardware interface used for operating or monitoring the system. If Arduino-based control code is included later, it should be linked from this section.

### Frame

The frame section should include the mechanical support structure for the testing system. This can include CAD files, assembly images, material notes, and design decisions related to stability, alignment, and safety.

## Project Documentation and Images

This repository is intended to include project images and written documentation so that people can understand the project without needing to open every CAD file first. Useful documentation may include:

- Project overview diagrams.
- CAD renders of the thruster and test setup.
- Photos of fabricated or assembled parts.
- Photos of the vacuum chamber and test platform.
- Control panel images.
- Explanations of how the design changed between iterations.
- Notes about what worked, what did not work, and what should be improved.

The purpose of these images and descriptions is to make the project easier to understand for ISEF judges, students, open-source contributors, and researchers who want to reference or improve the design.

## Software and Tools Used

The project used the following tools:

- **Fusion 360** for CAD modeling, mechanical design, assemblies, and exported 3D files.
- **VS Code** for programming, text editing, documentation, and repository organization.
- **Arduino IDE** for Arduino-related programming and hardware control work.
- **Console-based simulation** for simulation, calculation, or command-line experiment support.
- **ChatGPT** for explanation, writing assistance, organization, and project planning.
- **Codex** for repository organization, file cleanup, and documentation assistance.

AI tools were used to help organize and describe the project files. The engineering design decisions, testing context, and project goals remain part of the original research and development process.

## Known Limitations

This project is still a developing experimental system. Important limitations include:

- Some uploaded CAD files are older iterations and may not represent the latest or best version.
- Some part names and file names are not yet standardized.
- The current repository does not yet include all latest subsystem files, images, or documentation.
- The mechanical design may need further improvement for durability, alignment, cooling, mounting, or manufacturability.
- The thruster design may need more testing and optimization before performance claims can be made.
- Vacuum testing hardware, electrical interfaces, and measurement systems may require additional validation.
- Simulation results and physical test results may not match perfectly and should be compared carefully.
- Safety systems and control electronics should be reviewed before any replication attempt.

These limitations are included intentionally because the purpose of open-sourcing this project is not only to show the successful parts, but also to make the engineering process transparent and useful for future improvement.

## Possible Future Improvements

Potential future improvements include:

- Organizing all historical CAD files into clearly labeled iteration folders.
- Adding the latest Fusion 360 exports for the vacuum chamber, test platform, control panel, frame, and complete thruster assembly.
- Adding images and diagrams to explain the system architecture.
- Adding more detailed manufacturing notes for each part.
- Adding Arduino code and wiring documentation if applicable.
- Adding simulation inputs, console outputs, assumptions, and equations.
- Improving the magnetic field layout and documenting magnet placement.
- Improving cathode, anode, and nozzle geometry.
- Improving electrical insulation and thermal protection.
- Improving the test stand, measurement system, and repeatability of experiments.
- Adding a clearer license for hardware files, documentation, images, and code.

## Safety Notice

This project involves concepts and hardware that may include high current, high voltage, hot surfaces, vacuum systems, plasma, magnets, and mechanical structures. These can be dangerous. The files in this repository are provided for educational and research reference only. Do not attempt to reproduce or operate similar hardware without proper supervision, safety equipment, laboratory procedures, and expert review.

## For Researchers and Contributors

Researchers or interested builders can use this repository to:

- Review the mechanical design and iteration history.
- Compare different thruster component geometries.
- Use STEP/STL/3MF files as references for redesign.
- Identify weaknesses in the current system.
- Suggest improved materials, geometry, cooling, mounting, electronics, testing, or simulation methods.

If you use or improve this project, please document what changed and why. The long-term goal is to make the project more understandable, safer, and more useful for future AF-MPD thruster research.

## License

A formal open-source license should be added before the project is considered fully released. Because this repository contains hardware design files, documentation, images, and possibly code, the licensing may need to distinguish between:

- Hardware/CAD files.
- Documentation and images.
- Arduino or other software code.

Until a license is added, reuse rights may be unclear. A future update should add an appropriate open hardware and/or open-source software license.
