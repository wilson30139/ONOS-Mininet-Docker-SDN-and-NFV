main:
	docker compose up -d
	sudo ovs-vsctl add-br ovsBridge
	sudo ovs-vsctl set-controller ovsBridge tcp:127.0.0.1:6653
	sudo ovs-vsctl set bridge ovsBridge protocols=OpenFlow14
	sudo ovs-docker add-port ovsBridge eth1 R1 --ipaddress=172.20.0.2/16
	sudo ovs-docker add-port ovsBridge eth1 R2 --ipaddress=172.20.0.3/16
	sudo ovs-docker add-port ovsBridge eth2 R3 --ipaddress=172.20.0.4/16
clean:
	docker compose down
	sudo ovs-vsctl del-br ovsBridge
