Instructions to generate GFM compatible mermaid diagrams:

* Always start with a graph directive followed by a semicolon (e.g., `flowchart TD;`)
* Use plain unquoted IDs (e.g., `NodeA`) and quote only the labels (e.g., `NodeA["Label text"]`)—do not quote IDs themselves
* Escape special characters inside labels (`#`, `"`, `<`, `>`, `%`) using HTML entities
* Avoid or capitalize reserved IDs and keywords like `end`, `default`, `o`, `x`
* Keep each `style`, `classDef`, and `linkStyle` command on its own line without trailing semicolons
* Use only diagram types GitHub supports: flowchart, sequence, class, state, gantt, ER
* Keep node labels short to prevent rendering issues
