# Book Base

Description: A CSS typesetting foundation style for fully automated multi-format book publication layout designs using the Fidus Writer and Vivliostyle pipeline.

## The purpose of creating Book Base style

A multi-format CSS book style is needed for fully automated Fidus Writer multi-format outputting that further styles can be built on top of. The Book Base style needs to cover all of the layout requirements for the following multi-format outputs: PDF screen; PDF PoD (print); archive PDF, Web Docsify, Web as Paged Media (Vivliostyle), Web paged responsive (Vivliostyle), and; eBook.

## Key issues to address are:
 
  - Covers: Multi-format issues
  - Counting of objects: Images, tables, pages, sections, lists, footnotes, citations, etc
  - Special styles and tag of objects: blockquotes, lists, tables, etc
  - Recto, Verso page designation
  - Footnote and citation interlinking
  - Note: CSS issues, but important for template: Document metadata, parts of document semantic structure tags for LOD (sections, abstract, etc); Content LOD structuring using DCMI? (Authors, funding, RoR, etc).
  - The style would be fully commented.
  - Use varaible fonts, if possible.
  - Select a CSS tooling: SASS and variables etc
  
## Compatibilty

W3C Paged Media. Version: CSS Paged Media Module Level 3 W3C Working Draft, 18 October 2018 - https://www.w3.org/TR/2018/WD-css-page-3-20181018/

The style is designed to be compatible with the following systems: Fidus Writer Book Style and accompanying Docsify Style + GitHub/Lab template, as well as Vivliostyle CLI, and Viliostyle Create Book product for previewing purposes.

