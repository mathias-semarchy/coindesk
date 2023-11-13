API
https://api.coindesk.com/v1/bpi/currentprice.json

JSON
{
    "bpi": {
        "EUR": {
            "code": "EUR",
            "description": "Euro",
            "rate": "36,061.6376",
            "rate_float": 36061.6376,
            "symbol": "&euro;"
        },
        "GBP": {
            "code": "GBP",
            "description": "British Pound Sterling",
            "rate": "30,932.5459",
            "rate_float": 30932.5459,
            "symbol": "&pound;"
        },
        "USD": {
            "code": "USD",
            "description": "United States Dollar",
            "rate": "37,018.7195",
            "rate_float": 37018.7195,
            "symbol": "&#36;"
        }
    },
    "chartName": "Bitcoin",
    "disclaimer": "This data was produced from the CoinDesk Bitcoin Price Index (USD). Non-USD currency data converted using hourly conversion rate from openexchangerates.org",
    "time": {
        "updated": "Nov 13, 2023 09:30:00 UTC",
        "updatedISO": "2023-11-13T09:30:00+00:00",
        "updateduk": "Nov 13, 2023 at 09:30 GMT"
    }
}


CREATE TABLE bpi (
	bpi_id SERIAL,
	updated varchar(25) NULL,
	updatedISO varchar(25) NULL,
	updateduk varchar(25) NULL,
	eur_rate varchar(25) NULL,
	eur_rate_float varchar(25) NULL,
	gbp_rate varchar(25) NULL,
	gbp_rate_float varchar(25) NULL,
	usd_rate varchar(25) NULL,
	usd_rate_float varchar(25) NULL,
	curr_date timestamp default CURRENT_TIMESTAMP,
	CONSTRAINT pk_bpi PRIMARY KEY (bpi_id)
);