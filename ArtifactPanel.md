Dont know what this is or does? Maybe you've missed out on some Legion Content or took a break and didnt know what you've missed.
Read up about this here on [WoWhead 1](https://www.wowhead.com/guide/starting-legion-questing-broken-shore-dalaran-artifacts-professions-4620#artifact-acquisition) and [WoWhead 2]([https://www.wowhead.com/guide/starting-legion-questing-broken-shore-dalaran-artifacts-professions-4620#artifact-acquisition](https://www.wowhead.com/news/new-artifact-calculator-appearances-tab-all-artifact-colors-in-modelviewer-relic-250431)) 

```
#showtooltip 16
/run if ArtifactFrame:IsVisible() then HideUIPanel(ArtifactFrame) else SocketInventoryItem(16)end
```

or 

```
#showtooltip 16
/run if ArtifactFrame:IsShown() then ArtifactFrame:Hide() else SocketInventoryItem(16) end
```

or 

```
#showtooltip 16
/run SocketInventoryItem(16);
```
