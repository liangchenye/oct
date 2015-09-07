The tools for open container test will be maintained here.

### [octest](octest/README.md) - specs/(bundle, config)
The `octest` is a `rolling release` tool which keeps updating with OCI specs.

### [specValidator](specsValidator/README.md) - specs/(runtime, config)
The `specValidator` verifies all the specs configurations, so it is a much bigger project
and we will only validate the `stable` spec release.
So far the tool is compliance with `45ae53d4dba8e550942f7384914206103f6d2216` commit.

## Make OCT better
We will also list other container testing tools here.
Please tell us and update this file by using the following format:

```
###[tool name](tool url) - tool function
tool description

```