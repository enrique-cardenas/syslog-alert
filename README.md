# syslog_alert

A Spark streaming application that uses Kafka as a streaming platform. The program reads input from a topic of syslog messages, determines if the message exceeds a threshold, and if so creates and produces a record to an output topic of alerts

