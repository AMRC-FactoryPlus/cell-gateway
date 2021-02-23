# Factory+ Cell Gateway Stack
This is a stack containing all required services for the cell gateways. Once deployed with `docker stack deploy -c docker-compose.yml cell-gateway`, it will push all containers out to nodes with the `fplus-role=cell-gateway` label.

The Cell Gateway Stack is automatically deployed to all Cell Gateways in the Factory+ architecture using the `cell-gateway` role and provides the required functionality for the gateway to capture, process and forward data from devices to the wider Factory+ network. For more information on how data capture and translation works in the Factory+ architecture, see the Edge Translation section of the Factory+ specification.
