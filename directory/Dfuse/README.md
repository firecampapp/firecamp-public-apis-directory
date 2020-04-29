# **Dfuse**
------------------

#### **Modules-:**
- `GraphQL`
- `Rest API`
- `WebSocket`
------------------- 
>### **Preview of Dfuse GraphQL query collection in Firecamp**

![Dfuse queries list and debugging](https://raw.githubusercontent.com/shreya-gr/firecamp-public-apis-directory/add-dfuse-content/directory/Dfuse/GraphQL.gif)


#### 1)GraphQL
###### `Collections`
-  TransactionEdgeHeader --->   Details of a single transaction response.
-   TransactionEdge --->   A single transaction response
-   TransactionOutcome --->   outcome of the transaction
-   Transaction --->   Details of The transaction done
-   Pagination ---> standard way of providing cursors, and a way of telling the client when more results are available.
-   CursorSignature ---> R,V,S signature of the cursor
-   Signature ---> R,v,s signature of the transaction
-   CursorGasDetails ---> control struture of the Gas
-   Blockbynumber ---> Get a single block by its number
-   Toand FroTransaction ---> Details of Transaction done by one to a person
-   Cursors --->sequentially process the rows in your result set
-   GasDetails ---> Details of the Gas such as gas limit,gas used, etc
-   CursorPageInfo ---> cursor of the first element of the list, use it to search in the opposite direction and cursor of the last element of the list, use it to continue
-   BlockBynumberHeader ---> Header details of a single block by its number
-   Recent_Transaction --->   Details of the recent transaction done
 
------------------

>### **Preview of Dfuse HTTP in Firecamp**

![Dfuse Rest HTTP requests](https://raw.githubusercontent.com/shreya-gr/firecamp-public-apis-directory/add-dfuse-content/directory/Dfuse/HTTP.gif)


#### 2)Rest API


###### `GET Requests`
- By_time ---> The following  fetches the block ID, time and block number for the timestamp 
- key_accounts ---> Fetches the accounts controlled by the given public key, at any block height.
- transaction_id --> Fetching the transaction lifecycle associated with the provided parameter :id.
- table --> Fetches the state of any table, at any block height.
- table_accounts --->Fetches a table from a group of contract accounts, at any block height.
- table_scopes --->Fetches a list of scopes, for a given table on a contract account, at any block height.
- search_transaction-Search an EOSIO blockchain for transactions based on free-form criterias
- state_abi-Fetches the ABI for a given contract account, at any block height.
- table_scope_account --->Fetches all rows for a table in a given contract for a group of scopes, at any block height.
- table_row --->Fetches a single row from the state of any table, at any block height.
- permission_links-Fetches snapshots of any account’s linked authorizations on the blockchain, at any block height.


###### `POST Requests`
- get_account ---> Returns an object containing various details about a specific account on the blockchain.
- get_block ---> Returns an object containing various details about a specific block on the blockchain.
- get_info --->Returns an object containing various details about the blockchain.
- push_transaction --->This method expects a transaction in JSON format and will attempt to apply it to the blockchain.
- send_transaction --->This method expects a transaction in JSON format and will attempt to apply it to the blockchain.
- push_transactions --->This method expects a transaction in JSON format and will attempt to apply it to the blockchain.
- get_block_header_state --->Retrieves the glock header state
- get_abi --->Retrieves the ABI for a contract based on its account name
- get_currency_balance --->Retrieves the current balance
- get_currency_stats --->Retrieves currency stats
- get_required_keys --->Returns the required keys needed to sign a transaction.
- get_producers ---> Retrieves producers list
- get_raw_code_and_abi --->Retrieves raw code and ABI for a contract based on account name
- get_scheduled_transaction --->Retrieves the scheduled transaction
- get_table_by_scope --->Retrieves table scope
- get_table_rows --->Returns an object containing rows from the specified table.
- abi_json_to_bin --->Returns an object containing rows from the specified table.
- abi_bin_to_json --->Returns an object containing rows from the specified table.
- get_code --->Returns an object containing rows from the specified table.
- get_raw_abi --->Returns an object containing rows from the specified table
-get_activated_protocol_features --->Retreives the activated protocol features for producer node

------------------

>### **Preview of Dfuse WebSocket in Firecamp**

![Dfuse Websockets demo](https://raw.githubusercontent.com/shreya-gr/firecamp-public-apis-directory/add-dfuse-content/directory/Dfuse/WebSocket.gif)


#### 3) WebSocket
- get_action_traces --->Retrieve a stream of executed actions, filtered by receiver and account
- get_head_info --->Retrieve a stream of informations about the chain as it moves forward
- get_table_rows --->Retrieve a stream of changes to the tables, the side effects of transactions/actions being executed
- get_transaction_lifecycle --->Retrieve a “transaction_lifecycle” (when “fetch” is true) and follow its life-cycle (when “listen” is true)
- unlisten --->Allows to interrupt a stream.

------------------
