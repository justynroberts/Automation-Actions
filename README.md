# Automation-Actions

A curated sample of scripts to speed up diagnostics and remediation for PagerDuty's Automation Actions

# PDCLI.


| # |Name  |Description  |Prerequisites  |
|--|--|--|--|--| --
| 1| inventory.sh | Basic Information regarding a local server |None  |
| 2| systemealth.sh | CPU,Memory,Swap Space,Disk Space |  |
| 3|filehogs.sh  |List top x files for size  |  |
| 4|cleantempdir.sh  |Housekeeping  |  |
| 5|logparse.sh  |Parse a log and add markers  |  |
| 6|enpointcheck.sh  |Check endpoint availability and return a marker|  |
| 7|kubernetespods.sh  |Check pod status for namespace and mark  |  |
| 8|loginremote.sh  |Sample login to remote server  |  |
| 9|rebootremote.sh  |Sample login and remote reboot  |  |
| 10|containerlogs.sh  |Parse container logs for errors|  |



## UML diagrams

You can render UML diagrams using [Mermaid](https://mermaidjs.github.io/). For example, this will produce a sequence diagram:

```mermaid
sequenceDiagram
Alice ->> Bob: Hello Bob, how are you?
Bob-->>John: How about you John?
Bob--x Alice: I am good thanks!
Bob-x John: I am good thanks!
Note right of John: Bob thinks a long<br/>long time, so long<br/>that the text does<br/>not fit on a row.

Bob-->Alice: Checking with John...
Alice->John: Yes... John, how are you?
```

And this will produce a flow chart:

```mermaid
graph LR
A[Square Rect] -- Link text --> B((Circle))
A --> C(Round Rect)
B --> D{Rhombus}
C --> D**