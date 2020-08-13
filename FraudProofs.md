## Double Spend
- if 2 tx use the same UTXO as input

## Invalid Input
- 'block-height-mismatch'
- 'input-root-index-overflow'
- 'input-transaction-index-overflow'
- 'empty-transaction'
- 'transaction-index-mismatch'
- 'input-output-index-overflow'
- 'input-withdraw'
- 'input-return'
- HTLC
  - 'input-utxo-type'
  - 'input-htlc-type'
  - 'htlc-preimage'

## Invalid Sum
- reverts if sum(inputs) < sum(outputs)

## Invalid Transactions
- 'metadata-size-underflow'
- 'metadata-size-overflow'
- 'witnesses-size-underflow'
- 'witnesses-size-overflow'
- 'inputs-size-underflow'
- 'inputs-size-overflow'
- 'transaction-length'
- 'inputs-type-overflow'
- 'inputs-witness-reference-overflow'
- 'inputs-index-overflow'
- 'inputs-size'
- 'outputs-token-length-underflow'
- 'outputs-token-length-overflow'
- 'outputs-token-id-overflow'
- 'outputs-amount-underflow'
- 'outputs-amount-overflow'
- 'outputs-amount-overflow'
- 'outputs-owner-underflow'
- 'outputs-owner-overflow'
- 'outputs-owner-id-overflow'
- 'outputs-data-underflow'
- 'outputs-data-overflow'
- 'outputs-return-owner-underflow'
- 'outputs-return-owner-overflow'
- 'outputs-return-owner-id-overflow'
- 'outputs-type'
- 'witness-caller-empty'
- 'witness-type'
- 'witnesses-size-overflow'
- 'witnesses-index-overflow'
- 'metadata-deposit-height-underflow'
- 'metadata-deposit-height-overflow'
- 'metadata-deposit-token-overflow'
- 'metadata-height-underflow'
- 'metadata-height-overflow'
- 'metadata-height-overflow'
- 'metadata-index-overflow'
- 'metadata-index-overflow'
- 'metadata-output-overflow'

## Invalid Witness
- 'output-id'
- 'deposit-token'
- 'deposit-block-number'
- 'deposit-data'
- 'utxo-witness'
- 'root-witness'
- 'htlc-owner-return'

## Malformed Block
- 'transaction-length-overflow'
- 'net-length-overflow'