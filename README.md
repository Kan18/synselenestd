#[Selene](https://github.com/Kampfkarren/selene) standard library for the [Synapse X](https://x.synapse.to) dynamic Lua extension loading tool
(Requires the Roblox standard library)

How to use:

- Create project which will use Selene
- Copy over `synapse.toml` file to project folder
- Create a `selene.toml` file in project folder with `std = "lua51+roblox+synapse"`
- Create Roblox standard lib with `selene generate-roblox-std`
- You can either manually use Selene through compiling it with Cargo, or install the VSC extension available [here](https://marketplace.visualstudio.com/items?itemName=Kampfkarren.selene-vscode)

Contributing:

If you find any missing functions, or want to help with adding more libraries, please make a pull request or issue!