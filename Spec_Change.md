For example:
```
#showtooltip Priest(Holy/Shadow)
/run SetSpecialization(GetSpecialization()==2 and 3 or 2)
```

So change: `YOURCLASS` and `(SPEC1NAME/SPEC2NAME)`
```
#showtooltip YOURCLASS(SPEC1NAME/SPEC2NAME)
/run SetSpecialization(GetSpecialization()==2 and 3 or 2)
```
