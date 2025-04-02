# Numbered-Access-Control-List
This file consists of Numbered Access Control List configuration with 3 routers acting a as a pc and a R1 as a router

(config)# access-list (1-99) permit/deny (source ip address) (wildcard mask)

(config)# interface (interface name/number)

(config-if)# ip access - group (ACL-num) (in/out)

Important note:- At the end of every ACL there is an implicit deny statement, so to permit the rest of the traffic we have to configure a permit any statement.
