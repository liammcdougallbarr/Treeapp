# Treeapp

Learning C# and .NET through modular projects and simple scripts.

## Modules

- **WriteLineModule**: prints messages to the console
- **PingModule**: sends a ping to a URL and returns status
- **OpenSiteModule**: opens a given URL in the default browser

## How to run

1. Open in Visual Studio or VS Code
2. Run `Program.cs` which calls all modules

## Learning goals

- Practice modular coding
- Understand function calls
- Build reusable scripts

## Terminal Git Update Notes

### Git Setup
- Installed Git for Windows and configured Git Bash.
- Verified Git works via Git Bash terminal.
- Initialized local Git repository for Treeapp project.
- Connected to GitHub repository: `https://github.com/liammcdougallbarr/Treeapp.git`.
- First commit and push via terminal.
- Added `.gitignore` to exclude `bin/`, `obj/`, and `.vs/` folders.

### Program.cs
- Updated `Program.cs` to call `Treeapp.Modules.WriteLine.Print()`.
- Fixed build issues:
    - Original `Program.cs` would not compile because `WriteLine` could not be found.
    - Conflicts resolved when rebasing with remote repository.

### WriteLine.cs
- Renamed WriteLine file to `WriteLine.cs` and placed it in `Modules.cs` folder.
- Added `WriteLine` module class:
    - `public static void Print()` outputs a simple message to the console.
- Ensured `Program.cs` successfully calls the module without build errors.

### PingSite.cs
- Added `PingSite.cs` module in `Modules.cs` folder.
- Currently bare-bones, no functions implemented yet.
- Placeholder for future module to ping a URL and return status.
