# dev

Workspace of the [progressive-web-office](https://github.com/progressive-web-office)
organisation: every repository of the organisation, as a git submodule.

```sh
git clone --recurse-submodules https://github.com/progressive-web-office/dev.git
```

| Folder | Repository |
| --- | --- |
| `progressive-web-office.github.io` | The app, its documentation and the brand files |
| `dot-github` | [`.github`](https://github.com/progressive-web-office/.github): profile of the organisation |

Bring every submodule to the latest commit of its default branch:

```sh
git submodule update --remote
```
