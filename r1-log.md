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


### TODO
- setup Kubernetes
- [setup MySQL for quick tests](https://kubernetes.io/docs/tasks/run-application/run-single-instance-stateful-application/)
- airflow - create a new workflow with 2 steps:
    1. script to gather the info
    2. script to filter/sort the info
- exercises git
- [kafka setup](https://kafka.apache.org/quickstart)
- ccm setup
