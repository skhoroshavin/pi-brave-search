# pi-brave-search

A `web_search` tool for [pi](https://github.com/earendil-works/pi-coding-agent), backed by the
[Brave Search API](https://brave.com/search/api/). Returns titles, URLs and snippets for a query.

## Install

```bash
pi install npm:pi-brave-search
```

## Setup

Export your Brave Search API subscription token:

```bash
export BRAVE_SEARCH_API_KEY=<your-token>
```

Without it the tool errors with a hint instead of searching.

## License

MIT. See [LICENSE](./LICENSE).
