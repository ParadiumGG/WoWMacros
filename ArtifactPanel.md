Dont know what this is or does? Maybe you've missed out on some Legion Content or took a break and didnt know what you've missed.
Read up about this here on [WoWhead](https://www.wowhead.com/guide/starting-legion-questing-broken-shore-dalaran-artifacts-professions-4620#artifact-acquisition)

```
#showtooltip 16
/run if ArtifactFrame:IsVisible() then HideUIPanel(ArtifactFrame) else SocketInventoryItem(16)end
```

or 

```
#showtooltip 16
/run if ArtifactFrame:IsShown() then ArtifactFrame:Hide() else SocketInventoryItem(16) end
```
