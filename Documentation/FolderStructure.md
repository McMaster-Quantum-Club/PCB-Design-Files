# Folder Structure
Please follow the folder structure outlined below.

```
  <Repository Name>
  └─── Block Diagram
  └─── BOM
  └─── Documentation
  └─── Draftsman
  └─── Library
  |   └─── <part_folder>
  |   └─── ...
  |   └    *.SchLib
  |   └    *.PcbLib
  |   └    *.LibPkg
  |   └    *.DbPkg
  └─── Mfn Package
  |   └─── CCP-NEU-YYY-NNN-FABPKG-P<REV>
  |   |   └─── BOM
  |   |   |   └    CCP-NEU-YYY-NNN-ML-P-.xlsx
  |   |   |   └    CCP-NEU-YYY-NNN-ML-P-.pdf (Draftsman output)
  |   |   └─── Manufacturing Files (Gerbers, NC Drill, PCB Stack)
  |   |   |   └─── Gerbers
  |   |   |   |    └    <Alitum Output Gerber Files>
  |   |   |   └─── NC Drill
  |   |   |   |    └    <Alitum Output NC Drill Files>
  |   |   |   └─── Pick and Place
  |   |   |   |    └    <Alitum Output Pack and Place Files>
  |   |   |   └─── Report Board Stack
  |   |   |   |    └    Board_Stackup.xls
  |   |   |   |    └    Board_Stackup.pdf (Draftsman output)
  |   |   └─── PDFs
  |   |   |   └    CCP-NEU-YYY-NNN-AD-P-.pdf (Assembly Drawing, Draftsman output)
  |   |   |   └    CCP-NEU-YYY-NNN-SC-P-.pdf (Fabrication Drawing, Draftsman output)
  |   |   |   └    CCP-NEU-YYY-NNN-SD-P-.pdf (Schematic, Altium output)
  |   |   |   └    CCP-NEU-YYY-NNN-PC-P-.pdf (PCB Layers, Draftsman output)
  |   |   |   └    CCP-NEU-YYY-NNN-QC-P-.pdf (Quality Control Standard, Draftsman output)
  |   |   └    README.md
  |   └    ...
  └─── PCB
  └─── Schematic
  └─── StepFiles
  └─── Templates
  └    .gitignore
  └    README.md
  └    <project_name>.PrjPcb
  └    <project_name>.PrjPcbStructure
  └    <project_name>.PrjPcbVariants
  └    <project_name>.OutJob
```

### Folder Definitions:

**Block_Diagram:** foldering containing the designs block diagram  
**BOM:** altium .BomDoc location and exported BOM location  
**Documentation:** any and all documentation files (pdfs, markdown, text files, etc.)  
**Draftsman:** altium draftsman file (.PCBDwf) file location  
**Gerbers:** exported gerber location  
**Library:** projects part library  
**Mfn Package:** the manufacturing packages for each revision of the board  
**PCB:** home of the altium .PcbDoc file  
**PDFs:** exported PDF files  
**Schematic:** home of the altium .SchDoc and .Harness files  
**StepFiles:** exported .step files  
**Templates:** home of the altium templates for .SchDoc and .PCBDwf files  

