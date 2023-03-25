# currency-conversion-spring-boot
to run this microservice please use following url:- this service basically return the currency exchange value based on passed parameter from and to and quantity

e.g:- localhost:8100/currency-conversion/from/USD/to/INR/quantity/10

sample response returned for this above url will be:-

{ "id" : 111, "from": "USD", "to": "INR", "conversionMultiple": 65, "totalCalculatedAmount": 650, "environment": "8000" }
