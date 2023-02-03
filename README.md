## vscode-sshfs-patch

This is a patch for an [as-of-now abandoned issue #341][3] that's affecting some users of the [VSCode SSHFS extension][1]. Hopefully the project will be revived, but until then this should fix the issue.

This is provided as-is, YMMV, use at your own risk etc. It's simply a copy of the diff'ed files that were previously made available by the developer in a [one-off CI build][2] (that run is no longer available on GitHub).

## How to use

```
1. quit VSCode
2. clone this repo
3. open a terminal in the cloned dir and run
```shell
bash vscode-sshfs-patch.bash
```
4. confirm the overwrites


[1]: https://marketplace.visualstudio.com/items?itemName=Kelvin.vscode-sshfs
[2]: https://github.com/SchoofsKelvin/vscode-sshfs/actions/runs/2429991070
[3]: https://github.com/SchoofsKelvin/vscode-sshfs/issues/341
