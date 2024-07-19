# tf-create-m0-cluster


export MONGODB_ATLAS_PUBLIC_KEY="xxxx"
export MONGODB_ATLAS_PRIVATE_KEY="32313b49-8057-4d12-ade5-111111111"

## known issue
```bash
Error: error creating MongoDB Cluster: POST https://cloud.mongodb.com/api/atlas/v1.0/groups/669a22680f73721cc7f0de9e/clusters: 400 (request "INVALID_ENUM_VALUE") An invalid enumeration value M0 was specified.
```