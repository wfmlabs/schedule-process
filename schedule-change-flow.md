# Schedule Change Request Process Flow

<div class="mermaid">
flowchart LR
    %% First Row
    Start(["Start"]) --> Step1["Step 1<br/>Agent Submits<br/>Change Request"]
    Step1 --> Step2["Step 2<br/>Validate<br/>Request"]
    Step2 --> Step3{"Step 3<br/>Coverage<br/>Adequate?"}
    Step3 -->|No| Step4["Step 4<br/>Request<br/>Denied"]
    Step3 -->|Yes| Step5["Step 5<br/>Update<br/>Schedule"]
    Step5 --> Step6["Step 6<br/>Notify<br/>Agent"]
    Step4 --> Step6
    Step6 --> A((A))
    
    %% Second Row
    A --> Step7["Step 7<br/>Document<br/>Change"]
    Step7 --> Step8["Step 8<br/>Update<br/>Reports"]
    Step8 --> End(["End"])
    
    %% Styling
    classDef process fill:#f9f9f9,stroke:#333,stroke-width:1px
    classDef decision fill:#fffdf6,stroke:#333,stroke-width:1px
    classDef endpoint fill:#ffffff,stroke:#333,stroke-width:1px,stroke-dasharray: 5 5
    
    class Step1,Step2,Step4,Step5,Step6,Step7,Step8 process
    class Step3 decision
    class Start,End,A endpoint
</div>