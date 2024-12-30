LEPTON SCRIPTS
==============

Scripts for working with Lepton EDA.

## Help

lepton-h

    Usage: wds_lepton ...
    
    Lepton EDA project management program. Use this program for accessing
    and printing Lepton EDA projects.
    
      show     Show configuration variables.
      new-prj  Create new project.
    
      open [FILE]             Open schematics and symbols.
      attrib [FILE]           Open schematics to edit attributes.
      new-sch NAME TITLE      Create "sch/NAME_pag01.sch" schematic.
      new-sym NAME TEMPLATE   Create "sym/NAME.sym" symbol.
    
      update    Update symbols and page numbers.
      ls-sch    List schematics.
      out-pdf   Create pdf file from schematics.
      out-bom   Create BOM from schematics.
      out-drc   Create DRC from schematics.
    
    Schematic attributes: page, pages, author, title
    Variables: EDITOR, COMPANY_NAME, EMPLOYEE_NAME, PROJECT_REVISION
    Configuration files: pkg/CONFIG

## Collaborating

For making bug reports, feature requests and donations visit
one of the following links:

1. [gemini://harkadev.com/oss/](gemini://harkadev.com/oss/)
2. [https://harkadev.com/oss/](https://harkadev.com/oss/)
