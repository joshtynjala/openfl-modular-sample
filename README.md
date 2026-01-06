# Compile OpenFL with haxe-modular Sample

Compiles an [OpenFL](https://openfl.org/) project using the [haxe-modular](https://lib.haxe.org/p/modular) library. When a button is clicked, a new module is loaded from the server at runtime.

haxe-modular modifies the behavior of the Haxe compiler to split the generated JavaScript into separate modules when the `Bundle.load()` method is used.

## Usage

Add the [modular](https://lib.haxe.org/p/modular) Haxelib to your _project.xml_ file:

```xml
<haxelib name="modular"/>
```

Run the following commands in your project directory:

```sh
npm init -y
npm install haxe-modular --save-dev
```

That's it! You don't need to do anything special to build and run.

```sh
lime test html5 -debug
```

## Requirements

- haxe-modular 0.14.0 or newer
- Lime 8.0.0 or newer
- OpenFL 9.2.0 or newer

## Credits

Sample created by [Josh Tynjala](https://github.com/sponsors/joshtynjala), the author of [Feathers UI](https://feathersui.com/) and a member of the [OpenFL](https://openfl.org/) leadership team.