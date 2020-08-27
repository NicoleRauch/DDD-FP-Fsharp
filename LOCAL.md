# Jupyter Notebook lokal mit F# zum Laufen bekommen:

### Einmalig:

 - jupyter notebook installieren: 
    * Via conda or pip: https://jupyter.org/install
    * Via MacPorts: sudo port install py38-jupyter (und einen Symlink auf `jupyter` anlegen!)
 - .NET-Kernel zu Jupyter hinzufügen:
    * .NET 3.1 installieren
    * dotnet-interactive installieren: https://github.com/dotnet/interactive/blob/main/docs/NotebooksLocalExperience.md
        * `dotnet tool install -g --add-source "https://dotnet.myget.org/F/dotnet-try/api/v3/index.json" Microsoft.dotnet-interactive`
    * `dotnet interactive jupyter install`    
 - `jupyter kernelspec list` sollte .NET Kernels anzeigen (.net-csharp, .net-fsharp und .net-powershell)
 
 ### Hier bereits eingecheckt:
 
 - Binder Kompatibilität herstellen: [https://github.com/dotnet/interactive/blob/master/docs/CreateBinder.md]
 
 
### Jedes Mal:

- `jupyter notebook` startet aktuelles Verzeichnis als Jupyter-Application
 
 
 
 
