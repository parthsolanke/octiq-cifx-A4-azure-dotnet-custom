# CI detection fixture

DotNetCoreCLI@2 with `command: custom` + `custom: test`. .NET IS a recognised kind in the detector, so this works on a plain dotnet import.

Expected verdict line in the Octiq chat:

    Tests required - CI runs `dotnet test`
