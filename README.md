## Official docs

https://github.com/microsoft/winget-cli-restsource
https://learn.microsoft.com/pl-pl/windows/package-manager/winget/source

but this requires creating CosmosDB on Azure to even start rest source

## But ...
actually it's easier to create this:
https://github.com/cloudflightio/winget-pkgs

Which, after CI, creates Github Page on branch:
https://github.com/cloudflightio/winget-pkgs/tree/gh-pages

which has:
source.msix (zip)
manifests in proper folders
readme.md

Process is complicated:
https://github.com/cloudflightio/winget-pkgs/blob/main/build.ps1
+ rest in github CI

But it works

## Jantari tries to make alternative

https://github.com/jantari/rewinged

Didn't try it because it's audience is different - local repositories instead of
publicly hosted ones. It's nice to know this exists as it seems it's not that hard
to make one.