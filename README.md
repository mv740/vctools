
# vctools

Visual C++ Build Tools 2017 based on Windows Server Core LTSC 2019.

Mostly same as [the official sample](https://docs.microsoft.com/en-us/visualstudio/install/advanced-build-tools-container?view=vs-2017)
but limited to C++ tools.

## Tags

### minimum-latest

```
--add Microsoft.VisualStudio.Workload.VCTools
```

### recommended-latest, latest

```
--add Microsoft.VisualStudio.Workload.VCTools
--includeRecommended
```

### atl-mfc-cli-latest

Why not 😎

```
--add Microsoft.VisualStudio.Workload.VCTools
--includeRecommended
--add Microsoft.VisualStudio.Component.VC.ATL
--add Microsoft.VisualStudio.Component.VC.ATLMFC
--add Microsoft.VisualStudio.Component.VC.CLI.Support
```

## See also

* [Advanced example for containers](https://docs.microsoft.com/en-us/visualstudio/install/advanced-build-tools-container?view=vs-2017)
