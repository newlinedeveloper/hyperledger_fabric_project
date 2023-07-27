# hyperledger_fabric_project
E2E Private blockchain setup using hyperledger fabric

1. Introduction
2. kubernetes cluster setup
3. Fabric CA Server
4. Generating Certificates and Artifacts
5. Starting Ordering services
6. Starting Peers service
7. channel operation
8. Chaincode operation
9. API server
10. Frontend application
11. Hyperledger explorer integration
12. Setting up monitoring service
13. Setting up Ingress controller


#### Introduction
- Roadmap
- Repository download
- Folder structure understanding

#### Kubernetes cluster setup
- Installing tools like kubectl and lens IDE
- Creating Kubernetes cluster
- Creating NFS server
- Persistance volume and persistance volumn claim
- sample application

#### Fabric CA server
- Creating Fabric CA deployment for all the orgs i.e ca-org1, ca-org2, ca-org3 and ca-orderer
- Starting up CA servers

#### Generating Certificates and Artifacts
- Generating certificates for peers and orderer
- Creating genesis block and channel tx

#### starting ordering service
- Creating deployment and services - RAFT cluster
- Starting up ordering nodes

#### Starting peers services
- Creating deployment and services - 3 orgs
- Creating deployment for cli
- Starting up peer nodes

#### Channel operation 
- Creating application channel - mychannel
- Join channel
- updating Anchor peers

#### Chaincode operation
- Understanding external chaincode builder
- packaging and installing chaincode
- Creating chaincode deployment
- Approving and commiting chaincode
- Invoking transactions

#### API server
- Creating API server for registering user and invoking transactions
- Connection profile
- overriding default fabric CA configuration
- Starting API server




