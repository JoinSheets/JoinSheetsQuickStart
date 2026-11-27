+++
title = "Quick Start"
weight = 1
description = "Where to start: open the app, pick data sources and fields, build a table, and export the result."
+++

JoinSheets is a browser-based table builder: it joins flat tables on a key and
assembles them into the view you need.

The short path from launching the app to your first result fits into just
three screens, which you can switch between using the buttons in the app's
main menu.

{{< mermaid >}}
%%{init: {'block': {'padding': 40}}}%%
block-beta
columns 3
D("Data") F("Fields") T("Table")
X("Excel or CSV"):3
D --> F
F --> D
F --> T
T --> F
T --> X
X --> D
classDef stage fill:#f2f5f7,stroke:#141010,stroke-width:2px,color:#141010
classDef io fill:#6e6e73,stroke:#141010,stroke-width:2px,color:#ffffff
class D,F,T stage
class X io
{{< /mermaid >}}

<div style="height:2rem"></div>

1. [Launch the App](01-open-the-app/)
2. [The Data Screen](02-data-screen/)
3. [The Fields Screen](03-fields-screen/)
4. [The Table Screen and Working with Data](04-table-screen/)
5. [Save Your Result](05-save-preset/)
