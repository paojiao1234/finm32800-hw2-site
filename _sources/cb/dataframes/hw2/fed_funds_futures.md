# Dataframe: `hw2:fed_funds_futures` - Fed Funds Futures

futures data with date, symbol, ohlc, and volume


## DataFrame Glimpse

```
Rows: 11653
Columns: 7
$ date   <datetime[ns]> 2026-10-25 00:00:00
$ symbol          <str> 'ZQG7-ZQJ7'
$ open            <f64> 15.5
$ high            <f64> 16.0
$ low             <f64> 15.5
$ close           <f64> 16.0
$ volume          <u64> 333


```

## Dataframe Manifest

| Dataframe Name                 | Fed Funds Futures                                                          |
|--------------------------------|--------------------------------------------------------------------------------------|
| Dataframe ID                   | [fed_funds_futures](../dataframes/hw2/fed_funds_futures.md)                                       |
| Sources                        | CME Globex                                          |
| Providers                      | Databento                                        |
| Provider Links                 | https://databento.com/                                   |
| Tags                           | Futures, Fedwatch                                             |
| Access Types                   |                                       |
| How is data pulled?            | Databento API                                                   |
| Data available up to (min)     | 2026-10-25 00:00:00                                                             |
| Data available up to (max)     | 2026-10-25 00:00:00                                                             |
| Dataframe Path                 | D:\桌面\芝加哥大学\第一学期\FINM32800\hw2-paojiao1234\_data\fed_funds_futures.parquet                                             |


**Linked Charts:**


- [hw2:fedwatch_latest_forecast](../../charts/hw2.fedwatch_latest_forecast.md)



## Pipeline Manifest

| Pipeline Name                   | HW 2: The Yield Curve and the Policy Path                       |
|---------------------------------|--------------------------------------------------------|
| Pipeline ID                     | [hw2](../../../index.md)              |
| Maintainer                      | Jeremiah Bejarano               |
| Contributors                    | Jeremiah Bejarano |
| Repository                     | https://github.com/hw-finm-32800/hw2                  |
| Pipeline Web Page               | <a href="file://D:/桌面/芝加哥大学/第一学期/FINM32800/hw2-paojiao1234/docs/index.html">Pipeline Web Page      |
| Date of Last Code Update        | 2026-10-27 01:17:46           |
| OS Compatibility                | Windows, Linux, macOS |
| Linked Dataframes               |  [hw2:crsp_treasury_consolidated](../../dataframes/hw2/crsp_treasury_consolidated.md)<br>  [hw2:fed_yield_curve](../../dataframes/hw2/fed_yield_curve.md)<br>  [hw2:fed_funds_futures](../../dataframes/hw2/fed_funds_futures.md)<br>  |


**Build Commands:**
```
doit

```

