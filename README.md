# KiCad_Template

This is a template repo for KiCAD v6 projects with 

### Goal & Status

Goal: prototype
Status: implementation

| undefined                             | learn                                                                                            | prototype                  | 80-20-rule                                                   | polished Product |
|---------------------------------------|--------------------------------------------------------------------------------------------------|----------------------------|--------------------------------------------------------------|------------------|
| not known what the project will bring | personally learn something new (function, design, process) otherwise no usefull outcome expected | a working prototype or mvp | 80% outcome with 20% effort. Dont expect a finished product. | -                |

| idea                   | design                                                | implementation | testing | finished |
|------------------------|-------------------------------------------------------|----------------|---------|----------|
| brainstorming workflow | putting together a goal list, architecture, hig level | schematic, pcb |         |          |

## Todo

* ~add DRC, ERC as seperate WF~ 
* ~add DRC, ERC to release WF as blocking~
* ~add release checklist~
* order release checklist
* ~add workflow to automatically create new realease checklist and realease note file and reset the generic for the next release~
* ~Rename artefacts with project name and date?~
* Add diffrent PCB manufactures output via kibot
* ~Update to kicad6_auto:1.3.0~
* use version number for template

## Usage

hit "use this template" button
delet all unneded files in Doc folder
delet all Schematic stuff but not the text Placeholders <<...>>
delet all PCB stuff but not the text Placeholders <<...>> and the Board Edge (or the iBOM will fail). You can remodel it later.

### Workflow
If not working:
setting -> action -> general -> Workflow permissions -> Read and write permissions

## working

in the first workflow run the action will create a new branch "documentation" to store the newest PCBdraw pictures. 
Each action run will force push the png to this branch. So so not use the Fabrication folder in the documentation branch.

## Description. 

| Font                                                                    | Back                                                                      |
|-------------------------------------------------------------------------|---------------------------------------------------------------------------|
| ![PCB Top design](../../blob/documentation/Fabrication/PCBdraw_Top.png) | ![PCB Back design](../../blob/documentation/Fabrication/PCBdraw_Back.png) |

![Link to the current BOM](../../tree/documentation/Fabrication/BoM)
