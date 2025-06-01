`Transactions` represent events that alter the values of `assets` and `liabilities`. All `transactions` have a date, currency and a value in said currency. More information can apply depending on the type of `transaction`.

## Types of Transactions 
### Monetary Assets and Liabilities Transactions:
- Inbound Transfer: When a value is being added to an `monetary asset` or `liability` coming from another `monetary asset`. This means that `inbound tranfers` always generate an `outbound transfer` somewhere else. `Inbound transfers'` currency is set by the `asset` where its `outbound transfer` pair was created. If it doesn't match with the `inbound transfer` `asset` or `liability` currency, a conversion ratio is used to calculate the transaction value. This is done by multiplying the ratio to the `outbound transfer` value.
- Outbound Transfer: When a value is being removed from an `monetary asset` and being sent to an `monetary asset` or `liability`. An `outbound transfer` always generate an `inbound transfer` somewhere else. The value of the `outbound transfer` is defined by the currency of its related `monetary asset`.
- Buy Transaction: Can only be done in `monetary assets` and represents the use of cash to add an `realizable asset` to the portfolio. The value of the buy transaction is set into the `realizable asset` initial value. 
### Realizable Assets Transactions:
- Sell Transaction:
- Appreciation: Can only be created in `realizable assets` and represent an percentual increase in its value.  
- Depreciation: Can only be created in `realizable assets` and represent an percentual decrease in its value.
- Capital Gain:
