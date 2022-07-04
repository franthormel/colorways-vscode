# Colorways VS Code
A Visual Studio Code Theme inspired by Firefox Colorways.

## Screenshots

![Cheers (Balanced)](images/preview/cheers-balanced.png)


## Availability
| Theme name (style) | Status                                                                                 |
| ------------------ | -------------------------------------------------------------------------------------- |
| Cheers (Balanced)  | [Available](https://marketplace.visualstudio.com/items?itemName=Franthormel.colorways) |
| Cheers (Bold)      | Under construction                                                                     |
| Cheers (Soft)      | Future work                                                                            |

## Packaging and publishing
1. Install vsce.
```
npm install -g vsce
```

2. Package files.
```
vsce package -o extensions/
```

3. Publish changes
```
vsce publish.
```

See [this guide](https://code.visualstudio.com/api/working-with-extensions/publishing-extension) for more.