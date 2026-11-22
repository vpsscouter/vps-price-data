# VPS Scouter price data

Compare VPS hosting plans by price, specs, and server location. See renewal rates and find a plan that fits your budget.

This repository mirrors the [official VPS Scouter dataset](https://vpsscouter.com/data). [VPS Scouter](https://vpsscouter.com) compares advertised virtual private server plans from provider pricing pages. A [Hugging Face snapshot](https://huggingface.co/datasets/vpsscouter/vps-prices) is also available.

- [CSV export](vps-prices.csv)
- [JSON export](vps-prices.json)
- [Mirror changelog](CHANGELOG.md)

## Methodology

The publisher collects advertised prices and specifications from each provider’s own pages. The exports use monthly list prices in US dollars before affiliate discounts. Check the advertised billing term, renewal price when available, per-plan check date, and source URL before comparing or buying. If a source page is temporarily unreadable, the last confirmed data can remain for up to 60 days. The canonical dataset includes all tracked plans. VPS Scouter’s rankings and price index use plans with at least 1 GB of RAM.

See the [field dictionary and methodology](https://vpsscouter.com/data) for details. The mirror fetches both canonical exports on Mondays at 08:37 UTC and records changed downloads in the changelog. The source may update more frequently during major sales. The UTC mirror timestamp and the source’s per-plan check dates describe different events.

## Charts and price changes

- [VPS price index](https://vpsscouter.com/vps-price-index) shows price trends over time.
- [VPS price changes](https://vpsscouter.com/vps-price-changes) tracks changes in advertised plans and prices.

## License and attribution

The dataset is available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Credit **VPS Scouter, [Open VPS price data](https://vpsscouter.com/data), CC BY 4.0** and indicate any changes you make.
