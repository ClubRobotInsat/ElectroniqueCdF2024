# Feedback

This file contains feedback, ideas, and things to do next year for the electronics team, gathered after the 2024 french robotics cup ,  
its purpose is to help the club to improve and guide newcomers with experience-driven suggestions and tips.

- Properly use git, i.e. hosting entire projects on github and pulling/pushing instead of just uploading/downloading zipped project files. [Potential inspiration](https://www.youtube.com/playlist?list=PLn6004q9oeqEwmWBugy04WfmDpkLn4PIn)
- Update club KiCad library
- Establish routines/procedures/checklist(s) for signing off on/ordering PCBs, possibly including use of github actions. [Potential checklist](https://github.com/azonenberg/pcb-checklist)
- Rounded corners on PCBs
- [Use KiCad plugins](https://www.youtube.com/watch?v=eMdX3R9ni7g)
- If reusing/iterating on cards from 2024, everything in the anomaly file must be addressed
- Print PCBs on paper at 1:1 scale to verify footprints and check mechanical compliance.  
- Write down the new golden rules to follow to avoid ruining components (such as moving components about while the board is powered, etc)  
- Be more cautious during pcb design, add protective circuitry for sensitive and vital components such as MCP2551  
- Establish a procedure to check a board's functions after having finished assembly (check solder connections, etc )  
- Modify the architecture so that one can switch the robot off without switching the main processing board off. (raspberry pi)
- Add fans to create airflow and prevent overheating
- Pay more attention to raspberry pi's optimal power supply conditions and thermal dissipation
- Potentially offload calculations to a GPU or FPGA
- Schottky diodes to protect power supply reverse current surges
- Buy some new, improved, esthetically pleasing conformal coating for the boards
- Maintain changelogs of PCBs - textfile in project repo
- Clean/Re-organize electronics/PCB repo.
