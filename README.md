# esrow.sol

Contract compilied using [Openzepplion ](https://docs.openzeppelin.com/contracts/4.x/api/utils#escrow)

This financial aid escrow contract, holds funds designated for a payee until they withdraw them.
// # Escrow Contract #
// Involves three 'actors' -- 'sender', 'recipient', 'arbitrator'
// Holds Ether from 'sender' to be transferred to 'recipient'.
// Ether in contract is transferred to 'recipient' when two of the three 'actors' `confirm`.
// Contract can be `void`ed by 'sender' after `block.timestamp` is past 'timestampExpired'
// Ether is transferred to 'sender' upon successful `void`.

