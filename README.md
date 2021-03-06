# Deno Examples 

[Deno](https://deno.land/) is a V8 based runtime which uses TypeScript as default language. This repository contains several examples of Deno use.

## Installing Deno

You can install deno using curl in Linux/Unix/osX machines or using other [tools](https://deno.land/).

```
curl -fsSL https://deno.land/x/install/install.sh | sudo DENO_INSTALL=/usr/local sh
```
You have to manually add Deno to your path in your .bash_profile.

```
export DENO_INSTALL="/Users/userName/.local"
export PATH="$DENO_INSTALL/bin:$PATH"
```

## Executing Examples

Examples are located in "examples" folder. To run examples just execute Deno binary as follows:

```
deno run examples/exampleName.ts
```
### Description

- `helloWorld.ts` Hello World in Deno.
- `modules.ts` Deno's module system.
- `nameSpace.ts` Deno's name space.
- `testing.ts` Deno's testing suite.
- `importMap.ts` Example using import map feature.
- `fsWerite.ts` Example of --allow* flags.
- `httpServer.ts` Simple http server in Deno.


## License

MIT