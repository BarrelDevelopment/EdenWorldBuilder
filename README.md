# Eden: World Builder 2.1.1
Development build from Eden: World Builder 2.1 running in  Xcode version 16.1 (16B40).

## Description
In this development build, some changes have been made to make it run in Xcode 16. 
The world download function has also been modified to download the latest worlds.
> [!IMPORTANT]  
> The latest version on the AppStore is Eden: World Builder 2.2.7. These worlds have a higher build limit and are not fully supported in Eden: World Builder 2.1 (and this build).
> With this developmet build, you can download and open worlds form 2.2.7, but the blocks will be cut off at the old height limit. 

### Fly mode
By cloning this repo, the fly mode is activated by default. You can use the fire and pickaxe buttons to change the height of the player. 
In the player class you will find three bools. Set them to `false` to disable it:
```
bool FLY_MODE=true;
bool FLY_UP=true;
bool FLY_DOWN=true;
```

## Getting Started
### Installing
Open Xcode and create a new project from this git repository `https://github.com/BarrelDevelopment/EdenWorldBuilder.git` or manage it manually with `git clone https://github.com/BarrelDevelopment/EdenWorldBuilder.git`.

### Executing program
Within Xcode, select the Eden target an build the project on the simulator. 

## Acknowledgments
* [Discord](http://discord.gg/rjYXwBC)
* [EdenWorldBuilder GitHub](https://github.com/ryanjkontos/EdenWorldBuilder)
