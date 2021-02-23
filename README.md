# Cell Gateway Stack
This is a stack containing all required services for the cell gateways. Once deployed with `docker stack deploy -c docker-compose.yml cell-gateway`, it will push all containers out to nodes with the `fplus-role=cell-gateway` label.
