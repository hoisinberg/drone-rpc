# Drone-RPC
API for creating distributed  worker-orchestrator systems using gRPC bidirectional streams as the
underlying communication mechanism between orchestrator and worker jobs. It is expected that worker
startup includes establishing a bidi stream connection with an orchestrator instance, which is then
used to send RPC requests from orchestrator to worker.
