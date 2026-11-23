# gta6-meme-x-01

Entry for the make.fun bounty "Post a GTA 6 meme on X".

## What this is

A GTA 6 meme posted on X. `POST.json` names the post; `main.ts`
copies it to the output directory where the gate reads it, and the
house reads the post from X (its first picture and its text) and hands
that to the judge.

## Run

```sh
mkdir -p out && MAKEFUN_BOT_DIR=. MAKEFUN_OUTPUT_DIR=out node main.ts
```

Node 22, standard library only. No network, no wall clock, no files
outside the repo. Deterministic: two runs write identical bytes.

## License

MIT
