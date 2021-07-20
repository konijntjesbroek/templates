## Project Plan Template
_created by_: Arlo Gittings  
_created on_: 2021-07-19  
_last modified_: 2021-07-19  
### Description
A collection of templates for programming and projects. The basis is that solid
planning and identification of a problem reduces the work needed.
### Layout
- project:
    - LICENSE - a clean copy of the GPL.
    - README.md - bones for README file
        - header
            - Name
            - creation
            - last modification
        - description
            - plain english
            - end user focus
        - installation
            - basic installation
            - detail of installation variables and scripts
        - usage
            - typical usage
            - description of available options
    - change.log
        - blank file for tracking puroses
        - format 
            - first entry for a date: %Y-%m-%d %H%M <entry>
            - subsequent entries for the same date <11 spaces>%H%M <entry>
    - plan.md
        - header
            - Name
            - creation
            - last modification
        - Description
            - functional concepts
            - technical
            - developer focus
        - Layout
            - unordered list that provides the current state of the project
            - ignores management files (plan, README, changelog, LICENSE)
        - Success Factors
            - milestones for project
            - change over time
            - divided into phases with due times if needed
    - the separator
        - allows for quick alignment with tabstops to 80 characters
        - loaded into init.vim
            - inoremap <leader>tsep <esc>10=== --- <esc>A
            - ;tsep generates a fullwidth separator
            - for each tabstop, delete one layer off the end.
            - by alternating === --- it allows to quickly center tabular data
### Success Factors:
- Phase One
    - quickly automate project generation
    - create a template for each type of program or documentation project
- Phase Two
    - review templates monthly
    - identify fields that are used frequently
