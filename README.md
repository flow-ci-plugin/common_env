
# env Step
Config Variables

### INPUTS
* `FLOW_ENV_HASH` - 

## EXAMPLE 

```yml
steps:
  - name: env
    enable: true
    failure: true
    plugin:
      name: env
      inputs:
        - FLOW_ENV_HASH=$FLOW_ENV_HASH
```
