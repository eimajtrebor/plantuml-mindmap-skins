# PlantUML Mindmap Skins

A collection of style sheets to import into your PlantUML mindmap diagrams.

## Usage

```plantuml
@startmindmap "mymindmap"

' Theme
!$ROOT_BACKGROUND_COLOR = LightYellow
!$DEPTH1_BACKGROUND_COLOR = LightYellow
!$DEPTH2_BACKGROUND_COLOR = LightYellow
!$DEPTH3_BACKGROUND_COLOR = LightYellow
!$LINE_THICKNESS = 1

!include https://raw.githubusercontent.com/eimajtrebor/plantuml-mindmap-skins/master/starter-skin.puml

* Idea

    ** Node 1
    ** Node 2
    *** Sub-node 1
    ***_ No box node

@endmindmap
```
