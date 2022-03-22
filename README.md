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

You can see an example of variable overrides in the themes directory.

```plantuml
@startmindmap "mymindmap"

!include https://raw.githubusercontent.com/eimajtrebor/plantuml-mindmap-skins/master/themes/basic-theme.puml
!include https://raw.githubusercontent.com/eimajtrebor/plantuml-mindmap-skins/master/starter-skin.puml

* Idea

    ** Node 1
    ** Node 2
    
      *** Sub-node 1
      ***_ No box node

@endmindmap

```
