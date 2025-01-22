# elmer-sif-vscode

VS Code extension for Elmer Multiphysics SIF.

Just drop this directory inside your `.vscode` directory, it should work.

If you have problems, assuming your user is called `admin` under Windows, add the following snipped to the `.vscode/extensions.json`.

```json
{
    "identifier": {
        "id": "elmer-sif-vscode",
        "uuid": "1ac0881a-fd8e-64cf-9141-f5d1ce3f5ff7"
    },
    "version": "0.1.0",
    "location": {
        "$mid": 1,
        "fsPath": "c:\\Users\\admin\\.vscode\\extensions\\elmer-sif-vscode",
        "_sep": 1,
        "external": "file:///c%3A/Users/admin/.vscode/extensions/elmer-sif-vscode",
        "path": "/c:/Users/admin/.vscode/extensions/elmer-sif-vscode",
        "scheme": "file"
    },
    "relativeLocation": "elmer-sif-vscode",
    "metadata": {
        "installedTimestamp": 1736852017255,
        "pinned": false,
        "source": "gallery",
        "id": "1ac0881a-fd8e-64cf-9141-f5d1ce3f5ff7",
        "publisherId": "1ac0881a-fd8e-64cf-9141-f5d1ce3f5ff7",
        "publisherDisplayName": "Walter Dal'Maz Silva",
        "targetPlatform": "undefined",
        "updated": false,
        "isPreReleaseVersion": false,
        "hasPreReleaseVersion": false
    }
}
```
