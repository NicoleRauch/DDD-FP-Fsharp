Jupyter Notebook mit F# zum laufen bekommen:

- Neues Repository erstellen
- jupyter Installieren: https://jupyter.org/install
- .NET-Kernel zu Jupyter hinzufuegen:
 `dotnet tool install -g dotnet-try`
 `dotnet try jupyter install`
 - `jupyter kernelspec list` sollte .NET Kernels anzeigen
 
 
 
 [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/TillRauch/f-notebook/master)