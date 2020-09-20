<h1 align="center">floopware</h1>
<div align="center">
  <strong>a hummingbird fork by okk.</strong>
</div>
<br/>
Pull requests are welcome. (please do prs)
# TODO:
refactor

# How to setup
Clone the workspace
```
https://github.com/itsokk/floopware.git
```
Go into folder and open up a command prompt and do

**Eclipse** -
gradlew setupDevWorkspace eclipse build

**Intelij** -
gradlew setupDevWorkspace idea genIntellijRuns build

# Open in IDE
**Eclipse**
```Right click -> New -> Java Project -> Browse location -> Select floopware folder -> Finish```

**Intelij**
```Open -> Select floopware folder -> Import gradle project```

# Run

Add ```-Dfml.coreMods.load=me.okk.floopware.mixin.launch.FlopLoader``` to VM options.
