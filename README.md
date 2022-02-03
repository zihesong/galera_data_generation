# galera_data_generation
1. Use [galera-db.py](./galera-db.py) to initialize the galera database;
2. Use [galera-data.py](./galera-data.py) to generate transaction data. For each run, the results will be stored in folder "result", and data of each client will be collected in separate txt file;
3. Use [group_data.py](./group_data.py) to normalize the collected data in to one file result.txt;
4. Run [oopsla_txn_graph.py](./oopsla_txn_graph.py) to check the violation.
