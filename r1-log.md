# #100DaysOfCode Log - Round 1 - roymontecutli

The log of my #100DaysOfCode challenge. Started on August 5th,  2022.

## Log

### R1D1 
- Initial setup in personal computer
- IDE (Eclipse) installation
- Began setup of kafka/zookeeper in containers

### R1D2
- Diagnostic quiz
   - need to work on algorithms and data structures
   - Gradient descent, Diffie-Hellman
   - greedy algorithms
- Setup airflow
	- [local setup](https://airflow.apache.org/docs/apache-airflow/stable/start/local.html)
	```bash
	airflow standalone
	airflow webserver --port 8080
	airflow scheduler
	```

### R1D3
- Setup mariadb
	- Old configuration from a previous mysqldb installation caused issues, [fix](https://stackoverflow.com/questions/65753443/how-to-fix-innodb-corrupted-data-structure), also [apparmor fix](https://serverfault.com/questions/1013128/mariadb-service-start-stuck-at-activating)
	- secure setup of the db
- Diagnostic quiz
	- need to work on headers and verbs differences for HTTP
	- network diagnostics
		- traceroute options
		- ifconfig
		- ip
		- route

### R1D4
- Designed DB schema for time tracker application
- Separate user for the application

### R1D5
- Refresher java Swing GUI
- modeling input queries

### R1D6
- Refresher query profiling in MySQL/MariaDB

### R1D7
- Setup WindowBuilder for Eclipse
- Backbone swing interface for homepage time tracker

### R1D8
- Connected Swing homepage to MariaDB
- Homepage is iterating and showing dynamically projects from the DB

### R1D9-D11
- Reading Shapira, G., Palina, T., et.al. Kafka, the definitive guide, 2nd Edition, O'Reilly

### TODO
- setup Kubernetes
- [setup MySQL for quick tests](https://kubernetes.io/docs/tasks/run-application/run-single-instance-stateful-application/)
- airflow - create a new workflow with 2 steps:
    1. script to gather the info
    2. script to filter/sort the info
- exercises git
- [kafka setup](https://kafka.apache.org/quickstart)
- ccm setup
