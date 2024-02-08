load balancer using iptables nth and static module
checks servers if the port is open ro not, then reblances active servers

chmod 755 load-balance

nohup ./load-balance > load-balancer.log &
