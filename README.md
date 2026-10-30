# Stock Exchange Metadata

> Indian stock exchanges (BSE, NSE) with indices and segment info

**Category:** finance · **Data:** BSE/NSE public · **License:** CC-BY-4.0 · **Updates:** manual

## API Endpoints

All endpoints are served as static JSON from GitHub Pages.

| Endpoint | Format |
|----------|--------|
| `/data/exchanges.json` | JSON |

## Usage

```bash
curl https://chirag127.github.io/stock-exchanges/data.json
```

```javascript
const res = await fetch('https://chirag127.github.io/stock-exchanges/data.json');
const data = await res.json();
```

## Data

- Source: BSE/NSE public
- License: CC-BY-4.0
- Last updated: `2026-08-25T03:10:22.231Z`

See `data/` for raw JSON and `data/schema.json` for the schema.

## Documentation

Visit the [interactive docs](https://chirag127.github.io/stock-exchanges/) for the browsable API reference.

## Contributing

Issues and PRs welcome. Ensure `data/schema.json` validates all data files.

## License

CC-BY-4.0
