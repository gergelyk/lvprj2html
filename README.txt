Building
========

- Go to Build Specifications
- Right click lvprj2html, Properties
- Setup destination directory
- Right click lvprj2html, Build
- Got to destination directory
- open lvprj2html.llb
- Right click lvprj2html.vi, Top Level


Installing
==========

- Shut down LabVIEW
- Copy lvprj2html.llb to <LabVIEW installation directory>\project\
- Open LabVIEW
- "lvprj2html..." should be accessible from Tools menu


Usage
=====

- Open your project
- From Tools menu select "lvprj2html..."
- Optionally select "Inspect Dependencies"
- Click Generate, and wait
- When the process is finished, you can find your documentation in <Your project>\doc directory

Notes: 

- All the old files in <Your project>\doc directory will be lost
- Your project must not have broken dependencies
- If any problem occured, check the log to see which item of the project was the source of the issue




