BlockAura Token Smart Contract V3.1
This repository contains token contract, BlockAura-ETH.sol with contracts PauserRole, Context, Ownable, MinterRole, Pausable, ERC20, ERC20Detailed and BlockauraToken.
Smart Contract Solutions

BlockAura-ETH V3.1 Dapp have seven basic contracts:

BlockauraToken.sol: This is the Token smart contract on solidity. It has been inherited with features of PauserRole, Context, Ownable, MinterRole, Pausable, ERC20, ERC20Detailed. The tokenomics of BlockAura-Token-3.0 can be referred here.

PauserRole.sol: This is the contract which holds the BlockAura token minting, transfers, burning operations to pause and is being completely controlled by the minters only.

Ownable.sol: Contract module which provides a basic access control mechanism, where there is an account (an owner) that can be granted exclusive access to specific functions. By default, the owner account will be the one that deploys the contract. This can later be changed with {transferOwnership}.

Pausable.sol: Base contract which allows children to implement an emergency stop mechanism.

Context.sol: Provides information about the current execution context, including the sender of the transaction and its data. While these are generally available via msg.sender and msg.data, they should not be accessed in such a direct manner, since when dealing with GSN meta-transactions the account sending and paying for execution may not be the actual sender (as far as an application is concerned).

ERC20.sol: This implementation emits additional Approval events, allowing applications to reconstruct the allowance status for all accounts just by listening to said events. Note that this isn't required by the specification, and other compliant implementations may not do it.

ERC20Detailed.sol: All the operations are done using the smallest and indivisible token unit, just as on Ethereum all the operations are done in wei.
