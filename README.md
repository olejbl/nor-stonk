# nor-stonk

Post: https://www.nordnet.no/api/2/login/anonymous
GET: https://www.nordnet.no/api/2/instrument_search/query/stocklist?apply_filters=instrument_id%253D17418478

Returns:
{
    "rows": 1,
    "total_hits": 1,
    "results": [
        {
            "instrument_info": {
                "instrument_id": 17418478,
                "name": "GameStop Corporation",
                "long_name": "GameStop Corporation",
                "symbol": "GS2C",
                "instrument_group_type": "EQ",
                "instrument_type_hierarchy": "EQ/ESHMTF",
                "instrument_type": "ESHMTF",
                "isin": "US36467W1099",
                "currency": "EUR",
                "clearing_place": "PERS_DE",
                "is_tradable": true,
                "is_shortable": false
            },
            "status_info": {
                "trading_status": "UNKNOWN",
                "translated_trading_status": "UNKNOWN",
                "tick_timestamp": 1622185613000
            },
            "market_info": {
                "market_id": 4,
                "market_sub_id": 50,
                "identifier": "GS2C",
                "tick_size_id": 34830987
            },
            "price_info": {
                "last": {
                    "price": 214.3000,
                    "decimals": 1
                },
                "open": {
                    "price": 206.9000,
                    "decimals": 1
                },
                "close": {
                    "price": 191.9000,
                    "decimals": 2
                },
                "turnover": 980768.50,
                "turnover_normalized": 9915667.61,
                "turnover_volume": 4703,
                "bid": {
                    "price": 213.7000,
                    "decimals": 1
                },
                "ask": {
                    "price": 214.3000,
                    "decimals": 1
                },
                "bid_volume": 162,
                "ask_volume": 119,
                "high": {
                    "price": 216.4000,
                    "decimals": 1
                },
                "low": {
                    "price": 204.7000,
                    "decimals": 1
                },
                "diff": {
                    "diff": 22.4000,
                    "decimals": 2
                },
                "diff_pct": 11.67,
                "spread": {
                    "price": 0.6000,
                    "decimals": 4
                },
                "spread_pct": 0.28,
                "tick_timestamp": 1622195631000,
                "realtime": false
            },
            "exchange_info": {
                "exchange_country": "DE"
            },
            "key_ratios_info": {
                "ps": 2.99,
                "eps": -3.31,
                "pb": 37.88
            },
            "historical_returns_info": {
                "yield_1d": 11.67,
                "yield_1w": 52.64,
                "yield_1m": 43.25,
                "yield_3m": 123.23,
                "realtime": false
            },
            "company_info": {
                "general_meeting_date": 1623189600000,
                "report_date": 1623189600000,
                "report_type": "FIRST_QUARTER_EARNINGS_RESULTS",
                "report_description": "Kvartalsrapport (1. kvartal)"
            },
            "statistical_info": {
                "statistics_timestamp": 1622160005881,
                "number_of_owners": 1178
            }
        }
    ]
}
