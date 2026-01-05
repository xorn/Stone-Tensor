# Stone-Tensor
Stone Tensor LLC

graph TD
    %% Node Definitions
    SC((Stoney Coin<br/>1000 Coins @ $0.01<br/>3% Staking Bonus))
    
    AB[Andy Boyd: CEO<br/>Visionary, Economics, Charisma<br/>799 SC]
    
    RB[Russle Baldridge: CTO<br/>Technical, Hardware, Software<br/>150 SC]
    
    W[Weston: Technical Advisor<br/>Software, Server Setup<br/>50 SC]
    
    SP[Spencer Post: Consultant<br/>Psychology, Econ, Cluster Computing<br/>1 SC]
    
    TBD1[TBD: Software Tech]
    TBD2[TBD: Server Maintenance]

    %% Connections
    SC --- AB
    AB --- RB
    AB --- W
    AB -.-> SP
    
    RB --- TBD1
    W --- TBD2

    %% Styling
    style SC fill:#f9f,stroke:#333,stroke-width:2px
    style AB fill:#d4edda,stroke:#28a745,stroke-weight:2px
    style SP stroke-dasharray: 5 5
