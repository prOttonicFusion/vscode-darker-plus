# Darker+
A darker version of the default dark theme for VS Code

## Installation
Clone the repository to `~/.vscode/extensions/` and (re-)launch VS Code.

## Editing
The theme can be easily tweaked by changing the colors listed in `themes/darker_plus.json`. To try out settings without having to restart VS Code, the setting can be copied over to the `workbench.colorCustomizations` setting in `.vscode/settings.json`. E.g.
```
{
    ...
    
    "workbench.colorCustomizations": {
        "sideBarTitle.foreground": "#D60000",
    }

    ...
}
```