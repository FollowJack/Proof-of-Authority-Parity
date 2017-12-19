    Source for tutorial:
    https://github.com/paritytech/parity/wiki/Demo-PoA-tutorial
    
    
    Get enode:
    curl --data '{"jsonrpc":"2.0","method":"parity_addReservedPeer","params":["enode://859876a42c9d4a8da7618050f9482b09becfdc64b28852845b3f921d288d4a369d49224a78eb919748e91e20a6f4cc270baa01754f0e912e40b7885c879157a8@172.16.51.61:30300"],"id":0}' -H "Content-Type: application/json" -X POST localhost:8541