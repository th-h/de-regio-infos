# Additional information for the DE-regio project

This repository contains additional information on German (language) (regional) Usenet hierarchies that will be incorpated into the list of those hierarchies at <https://de-regio.de/>.

It is present at [VirtComm Code](https://code.virtcomm.de/thh/de-regio-infos) and [Github](https://github.com/th-h/de-regio-infos).

## Conventions

### File names

Files have to be named `$hierarchy.$lang.md` where `$hierarchy` is the name of the hierarchy and `$lang` has to be `de` or `en`for German or English, respectively; e.g. `backbone.de.md`.

### File contents

Files start with *YAML* front matter containing metadata, currently

* `created` for the creation date
* `lastmod` for the date of last modification

The rest of the file is in [*Markdown*](https://daringfireball.net/projects/markdown/) syntax, [*Markdown Extra*](https://michelf.ca/projects/php-markdown/extra/) flavoured.

Example:

    ---
    created: 2024-06-20
    lastmod: 2024-06-22
    ---
    # `example.*`
    
    `example.*` is an example hierarchy.

Content should start with an `H1` containing the hierarchy name; everything else is optional.

Hierarchy names should be marked as `code`.

## Help needed

If you know anything about any of those hierarchies present at <https://de-regio.de/>, don't hesitate to add your knowledge! We'll take pull requests, patches and all other usable forms of information. 
