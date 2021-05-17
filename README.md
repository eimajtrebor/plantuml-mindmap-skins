# PlantUML Mindmap Skin

This repo contains a default skin for use with the PlantUML mindmap diagram. To use the skin, simply include the URL in your mindmap document.

## Basic usage

```plantuml
@startmindmap "mymindmap"

!include https://raw.githubusercontent.com/eimajtrebor/plantuml-mindmap-skins/master/starter-skin.puml

* Idea

    ** Node 1
    ** Node 2
    *** Sub-node 1
    ***_ No box node

@endmindmap
```

## Variable overrides

You can change the look of the skin by overriding some of the variables that are included in the skin. Place these overrides at the top of your mindmap file.

```plantuml
@startmindmap "mymindmap"

!$LEVELS = 5
!$FONT_SIZE = 14
!$FONT_SCALE = 2
!$ROOT_BACKGROUND_COLOR = LightYellow
!$DEPTH1_BACKGROUND_COLOR = LightYellow
!$DEPTH2_BACKGROUND_COLOR = LightYellow
!$DEPTH3_BACKGROUND_COLOR = LightYellow
!$DEPTH4_BACKGROUND_COLOR = LightYellow
!$LINE_THICKNESS = 1
!$LINE_COLOR = #333333
!$SHADOWING = 1

!include https://raw.githubusercontent.com/eimajtrebor/plantuml-mindmap-skins/master/starter-skin.puml

* Idea

    ** Node 1
    ** Node 2
    *** Sub-node 1
    ***_ No box node

@endmindmap
```

## Themes

For an even simpler way of working, include the variables in a separate file and include the file above the starter skin include.
