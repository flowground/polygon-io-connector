# ![LOGO](logo.png) Polygon **flow**ground Connector

## Description

A generated **flow**ground connector for the Polygon API (version 1.0.0).

Generated from: https://api.apis.guru/v2/specs/polygon.io/1.0.0/swagger.json<br/>
Generated at: 2019-05-07T17:43:44+03:00

## API Description

The future of fintech.

## Authorization

Supported authorization schemes:
- API Key
## Actions

### Available Companies

> Get a list of the traded companies that polygon.io streams. Company includes some details about the company which we hope to add more to soon.

*Tags:* `Stocks`

#### Input Parameters
* `sort` - _optional_ - Which field to sort by. For desc place a `-` in front of the field name. eg `?sort=-marketcap`
* `perpage` - _optional_ - How many items to be on each page during pagination
* `page` - _optional_ - Which page of results to return

### Available Currencies

> Get a list of the currencies that polygon.io streams.

*Tags:* `Currencies`

### Historic Aggregates

> Get historic aggregations for a symbol.

*Tags:* `Stocks`

#### Input Parameters
* `size` - _required_ - Size of the aggregation. `second` or `minute`
    Possible values: second, minute.
* `symbol` - _required_ - Symbol of the company to retrieve
* `date` - _required_ - Date/Day of the historic ticks to retreive
* `offset` - _optional_ - Timestamp offset, used for pagination
* `limit` - _optional_ - Limit the size of response, max: 10000

### Historic Forex Ticks

> Get historic ticks for a currency pair. Example for **USD/JPY** the from would be **USD** and to would be **JPY**. The date formatted like **2017-6-22**

*Tags:* `Currencies`

#### Input Parameters
* `from` - _required_ - From Symbol of the currency pair
* `to` - _required_ - To Symbol of the currency pair
* `date` - _required_ - Date/Day of the historic ticks to retreive
* `offset` - _optional_ - Timestamp offset, used for pagination
* `limit` - _optional_ - Limit the size of response, max: 10000

### Historic Quotes

> Get historic quotes for a symbol.

*Tags:* `Stocks`

#### Input Parameters
* `symbol` - _required_ - Symbol of the company to retrieve
* `date` - _required_ - Date/Day of the historic ticks to retreive
* `offset` - _optional_ - Timestamp offset, used for pagination
* `limit` - _optional_ - Limit the size of response, max: 10000

### Historic Trades

> Get historic trades for a symbol.

*Tags:* `Stocks`

#### Input Parameters
* `symbol` - _required_ - Symbol of the company to retrieve
* `date` - _required_ - Date/Day of the historic ticks to retreive
* `offset` - _optional_ - Timestamp offset, used for pagination
* `limit` - _optional_ - Limit the size of response, max: 10000

### Last Trade for a Currency Pair

> Get Last Trade Tick for a Currency Pair.

*Tags:* `Currencies`

#### Input Parameters
* `from` - _required_ - From Symbol of the pair
* `to` - _required_ - To Symbol of the pair

### Last Trade for a Symbol

> Get the last trade for a given stock.

*Tags:* `Stocks`

#### Input Parameters
* `symbol` - _required_ - Symbol of the stock to get

### Last Quote for a Currency Pair

> Get Last Quote Tick for a Currency Pair.

*Tags:* `Currencies`

#### Input Parameters
* `from` - _required_ - From Symbol of the pair
* `to` - _required_ - To Symbol of the pair

### Last Quote for a Symbol

> Get the last quote tick for a given stock.

*Tags:* `Stocks`

#### Input Parameters
* `symbol` - _required_ - Symbol of the stock to get

## License

**flow**ground :- Telekom iPaaS / polygon-io-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
