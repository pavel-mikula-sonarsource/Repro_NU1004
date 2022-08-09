# Repro_NU1004

## Structure

`Net6Root` project targets `net6` and reference `Net46Reference` SDK-style project targeting `net46`.

## Restore

```
nuget restore Repro_NU1004.sln -LockedMode
```

Produces

>NU1004: The project Net46Reference has no compatible target framework. The packages lock file is inconsistent with the project dependencies so restore can't be run in locked mode. Disable the RestoreLockedMode MSBuild property or pass an explicit --force-evaluate option to run restore to update the lock file.
