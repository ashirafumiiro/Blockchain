# Blockchain
Custom Blockchain Creation

### Running the example
Navigate to the folder containing the compiled assemblies  
```bash
dotnet Tutorial.dll 6001 Henry
```
A second terminal can be used to start a second node
```bash
dotnet Tutorial.dll 6001 Mesh
```
The nodes can then be able to communicate with each other using websockets

Adapted from https://www.c-sharpcorner.com/article/blockchain-basics-building-a-blockchain-in-net-core/