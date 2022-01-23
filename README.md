# fllowr (Twitter Clone)

## Architecture

- Amazon EventBridge as the main event bus
- AWS Step Functions Express Workflows as the target for the events that are routed by EventBridge based on the rules
