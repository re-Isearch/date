# Date Formats (especially ISO-8601:2019) 
This contains a version of the date parser from re-Isearch designed/intended for use in other projects. Among the changes it uses std:string instead of the re-Isearch's own STRING class.

Our motivation for publishing the parser is to support the paradigm defined within ISO-8601:2019 and EDTF (the Extended Date Time Format) through a number of common date expresssions including national expressions and those frequently found in emails and other electronic documents. So alongside ISO-8601 dates it support RFC-2822, RFC-3339 as well as national date expressions including a number of extensions (not covered in any of these formats).

It contains also a generic version of our slide presentation on the ISO-8601:2019 Date and Time Format Standard. 

This repro (especially the documentation) has been partially supported by a fellowship from

[<IMG HEIGHT="60" SRC="https://2020.standict.eu/sites/all/themes/dotte/logo.png" ALT="StandICT">](http://standict.eu/)

 and is provided under the  “Attribution 4.0 International (CC BY 4.0) License”. This means that you are free to share (copy and redistribute the material in any medium or format) and/or adapt (remix, transform, and build upon the material for any purpose, even commercially) this handbook under the terms that you give fair attribution.  You must give appropriate credit, provide a link to the  license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use. 
