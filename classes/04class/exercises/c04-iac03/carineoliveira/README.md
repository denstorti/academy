# C04-IAC03

## Command Execution Output
- [output.txt](output.txt)

## Questions:
- Describe below why some changes just updated the resource being changed and the other required a full replacement of the resource.
    - It will depend on the type of the resource:
    Example 1: the VPC CIDR impacts on the network structure, so if changed, the other resources linked to the VPC will also require an update. 
    Example 2: the subnet name won't impact other resources, so when updated will not require the replacement of the subnet or any other resource.

***
Answer for exercise [c04-iac03](https://github.com/devopsacademyau/academy/blob/c41e824fb2a2c55e3a30b2371a87e3a7551b6741/classes/04class/exercises/c04-iac03/README.md)
