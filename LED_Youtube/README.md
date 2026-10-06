# Tutorial LED Board

A tutorial-based LED board with two indicator branches, assembly drawings, schematic PDF, BOM, STEP model, Gerbers, drill files, and pick-and-place data.

![Board preview](Images/LED_Youtube-board.png)

*Preview generated from the supplied Gerber layers.*

## Files

- [Complete project archive](Archives/LED_Youtube.zip)
- [Saved design-rule report](Reports/LED_Youtube-DRC.txt)
- Editable source files are also available in the project source folder.

## Design status

The saved DRC report records **0 violations and 0 waived violations**. This is an existing report, not a fresh check of the source.

## Learning reference

This is a tutorial-based practice project. The reference files supplied alongside the local work identify **Altium Designer 22 Tutorial - Quick & Easy | Step by Step**: https://youtu.be/PqFtSpAXB9Q. This project is presented as learning work, with credit to the original tutorial.

## Use and validation

Open editable project files in their original CAD application. The archives preserve project subfolders; extract an archive before opening its project. External libraries or 3D-model paths may need to be remapped on another computer.

These are portfolio design files. Existing reports are snapshots from their recorded dates; fabrication exports are not evidence of manufactured or bench-tested hardware. Review the design and rerun the checks before fabrication.

No blanket license is assigned. Third-party components, libraries, and tutorial material retain their original rights and terms.

## Browse this project

Open [LED_Youtube.PrjPcb](Altium_Project/LED_Youtube.PrjPcb) in Altium Designer. Download or clone the whole repository to keep related files together.

| Folder | Contents |
| :--- | :--- |
| [Altium_Project/](Altium_Project/) | Editable project, schematic, PCB and supporting native libraries/BOM documents kept together for relative references |
| [Archives/](Archives/) | Unchanged original complete project ZIP |
| [BOM/](BOM/) | Supplied bill of materials exports |
| [Documentation/](Documentation/) | Supporting documentation and preserved source-reference snapshots |
| [Images/](Images/) | Existing schematic and board previews |
| [Manufacturing/](Manufacturing/) | Existing fabrication, drill and assembly outputs |
| [Models/](Models/) | Supplied mechanical/3D exports |
| [Reports/](Reports/) | Saved design-check reports |

Native libraries and `.BomDoc` files stay next to the `.PrjPcb` to retain source references. Existing output `DocumentPath` entries are adjusted to the grouped folders where those files were supplied. Original project files and archives are retained. Some pre-existing HTML check-report references and absolute output-job/model paths have no portable supplied equivalent; regenerate/remap these in Altium if needed. No new design-rule check was run during this reorganization.
