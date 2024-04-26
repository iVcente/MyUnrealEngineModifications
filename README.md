These are my personal changes to Unreal Engine source code. Inside the following directories are the proposed modifications to UE for my use cases:
* **EOS**: When adding EOS plugins to the project, this is used to be able to build Linux servers from a Windows machine;
* **MoviePlayer**: Even when `FLoadingScreenAttributes.bMoviesAreSkippable` is set to `false`, player is still able to skip movies. This really becomes a problem when you'd like, for instance, to display a loading screen and manually hide it when your game routines are completely ready. This code fixes this issue.
