<p align="center">
  <img src="https://raw.githubusercontent.com/Coccinella-Labs/stillness/main/.github/assets/thumbnail.png" alt="stillness" width="100%">
</p>

# stillness

A minimal, single-file page theme. A static `index.html` with a soft gradient background, animated blobs, and a centered content area — no build step, no dependencies.

## Usage

Serve the directory with any static file server:

```bash
# Python
python3 -m http.server

# npx
npx serve .
```

Then open `http://localhost:8000`.

## Customize

- Title and heading text live in `index.html` (`<title>` and `<h1>`).
- Colors come from the CSS `radial-gradient` background and the `blob-N` classes.
- The interactive gradient tracks the mouse (`mousemove`), overridable by removing the `<script>` block.

## License

MIT — see [LICENSE](LICENSE) for details.