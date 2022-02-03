# Checking Transactional Consistency Consistency for Galera
1. Use [galera_db.py](./galera_db.py) to initialize the galera database;
2. Use [galera_data.py](./galera_data.py) to generate transaction workloads. For each run, the collected traces will be stored in folder "result" where the trace for each client will be stored in a separate txt file;
3. Use [group_data.py](./group_data.py) to normalize the collected data into one file result.txt;
4. Run [oopsla_txn_graph.py](./oopsla_txn_graph.py) to check if the execution run violates transactional consistency consistency.
