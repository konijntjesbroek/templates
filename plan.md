## Project Plan Template
_created by_: Arlo Gittings  
_created on_: 2021-07-19  
_last modified_: 2021-07-19  
### Description
A collection of templates for programming and projects. The basis is that solid
planning and identification of a problem reduces the work needed. Make sure to 
document any new templates that are added in the Layout section. List the file,
its format, and the reasoning and contents for each section.
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
            - inoremap \<leader\>sep <esc>10=== --- <esc>A
            - ;sep generates a fullwidth separator
            - for each tabstop, delete one layer off the end.
            - by alternating === --- it allows to quickly center tabular data
- document
    - LICENSE - clean copy of the GPL.
    - README.
        - header
            - Title
            - Author
            - Work started
            - Latest revision
        - description
            - summation of the contents of this directory,
            - cross between a foreward and a book jacket blurb
    - latex\_guide
        - latex elements and uses
        - style guide for documents
    - md\_guide
        - markdown elements and uses
        - style guide for documents
    - outline
        - header
            - Title
            - Author
            - Start date
            - Last Revision
        - summary
            - purpose
            - thesis
        - outline
            - hierarchical list of topics and support materials
            - dates completed as progress is made
    - resources
        - blank file for documenting support data
        - format
            - separator
=== --- === --- === --- === --- === --- === --- === --- === --- === --- === --- 
            - resource id
                - unique id for use only in your document
                - numeric starting at 0
            - author(s)
            - title
            - location (URL, ISBN, etc)
=== --- === --- === --- === --- === --- === --- === --- === --- === --- === --- 
    - revisions
        - blank file for tracking 
        - format
            - first entry for a date %Y-%m-%d %H%M \<item\>
            - subsequent entries for existind date \<11 spaces\>%H%M \<item\>
    - documents - directory
        - drafts - directory
            - 1 directory for each version (maybe package in git, instead)
            - 1 file per major subheading 
        -notes - directory
            - 1 directory for each subject
            - note filename: subtopic-resourceid-datetimestamp
            - note format:
                - resource id
                - location within resource (if needed)
                - summation of information
                    - gist of information
                    - context
                - quotes
                    - verbatim transcript
                    - attribution
                    - context
### Success Factors:
- Phase One
    - quickly automate project generation
    - create a template for each type of program or documentation project
- Phase Two
    - review templates monthly
    - identify fields that are used frequently
