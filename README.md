# madara-kit

## Run

```bash
cargo run
```

## Style

Start the TailwindCSS watcher to generate the output CSS file:

```bash
npx tailwindcss -i ./input.css -o ./public/tailwind.css --watch
```

## Publish

### Desktop

```bash
cargo bundle --release
```

Once you've ran cargo-bundle --release, your app should be accessible in: `target/release/bundle/<platform>/`.

### Web

```bash
trunk build --release
```
