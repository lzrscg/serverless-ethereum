# Serverless Ethereum
This is a serverless Ethereum RPC endpoint build on AWS. It follows the [Ethereum JSON-RPC Specification](https://playground.open-rpc.org/?schemaUrl=https://raw.githubusercontent.com/ethereum/eth1.0-apis/assembled-spec/openrpc.json&uiSchema%5BappBar%5D%5Bui:splitView%5D=true&uiSchema%5BappBar%5D%5Bui:input%5D=false&uiSchema%5BappBar%5D%5Bui:examplesDropdown%5D=false). 

## RPC Methods
This is the status of the Ethereum RPC methods implemented in a cloud-optimized manner. Not all methods may be implemented in the future.
- [ ] **eth_getBlockByHash** - Returns information about a block by hash.
- [ ] **eth_getBlockByNumber** - Returns information about a block by number.
- [ ] **eth_getBlockTransactionCountByHash** - Returns the number of transactions in a block from a block matching the given block hash.
- [ ] **eth_getBlockTransactionCountByNumber** - Return the number of transactions in a block matching the given block number.
- [ ] **eth_getUncleCountByBlockHash** - Returns the number of uncles in a block from a block matching the given block hash.
- [ ] **eth_getUncleCountByBlockNumber** - Returns the number of uncles in a block from a block matching the given block number.
- [ ] **eth_protocolVersion** - Returns the current Ethereum protocol version.
- [ ] **eth_chainId** - Returns the chain ID of the current network.
- [ ] **eth_accounts** - Returns a list of addresses owned by client.
- [ ] **eth_blockNumber** - Returns the number of most recent block.
- [ ] **eth_call** - Executres a new message call immediately without creating a transaction on the block chain.
- [ ] **eth_estimateGas** - Generates and returns an estimate of how much gas is necessary to allow the transaction to complete.
- [ ] **eth_gasPrice** - Returns the current price per gas in wei.
- [ ] **eth_feeHistory**
- [ ] **eth_newFilter** - Creates a filter object, based on filter options, to notify when the state changes (logs).
- [ ] **eth_newBlockFilter** - Creates a filter in the node, to nodify when a new block arrives.
- [ ] **eth_newPendingTransactionFilter** - Creates a filter in the node, to notify when new pending transactions arrive.
- [ ] **eth_uninstallFilter** - Uninstalls a filter with a given id.
- [ ] **eth_getFilterChanges** - Polling method for a filter, which returns an array of logs which occured since last poll.
- [ ] **eth_getFilterLogs** - Returns an array of all logs matching filter with given id.
- [ ] **eth_getLogs** - Returns an array of all logs matching filter with given id.
- [ ] **eth_mining** - Returns whether the client is actively mining new blocks.
- [ ] **eth_hashrate** - Returns the number of hashes per second that the node is mining with.
- [ ] **eth_getWork** - Returns the hash of the current block, the seedHash, and the boundary condition to be met ("target").
- [ ] **eth_submitWork** - Used for submitting a proof-of-work solution.
- [ ] **eth_submitHashrate** - Used for submitting mining hashrate.
- [ ] **eth_sign** - Returns an EIP-191 signature over the provided data.
- [ ] **eth_signTransaction** - Return an RLP encoded transaction signed by the specified account.
- [ ] **eth_sendRawTransaction** - Submits a raw transaction.
- [ ] **eth_getTransactionByHash** - Returns the information about a transaction requested by transaction hash.
- [ ] **eth_getTransactionByBlockHashAndIndex** - Returns information about a transaction by block hash and transaction index position.
- [ ] **eth_getTransactionByBlockNumberAndIndex** Returns information about a transaction by block number and transaction index position.
- [ ] **eth_getTransactionReceipt** - Returns the receipt of a transaction by transaction hash.

0 / 32 (0%) Complete
