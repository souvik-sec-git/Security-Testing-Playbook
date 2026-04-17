# Security-Testing-Playbook

ML Algorithms are the mathematical methods used to learn patterns from data.  
ML Models are the trained outputs derived from these algorithms.

#### 3 key components:

   ###### a. Decision process:  
             which makes predictions or classifications based on input data.  
   ###### b. Error function:  
             which evaluates performance and provides feedback.  
   ###### c. Model optimisation process:  
             which fine-tunes the algorithm to minimise errors and improve accuracy.  

This iterative process continues until the model reaches a satisfactory performance level.  

#### 4 Categories of ML algorithms:  

   ###### a. Supervised learning: 
             relies on labeled data to train models for classification or regression tasks.  
             Ex: such as predicting house prices or identifying spam emails.  

  ###### b. Unsupervised learning: 
            works with unlabeled data to discover hidden patterns, often using clustering, association, or dimensionality reduction techniques.  
   
  ###### c. Semi-supervised learning:  
            combines elements of both, using a small portion of labeled data to guide the learning process.  
   
   ###### d. Reinforcement learning :  
             mimics human learning by rewarding correct decisions and penalizing mistakes, allowing an agent to refine its actions over time to achieve                                   the best outcome. 


#### AI (behave like humans) :  

  ###### Artificial Neural Network
           [(neurons: cells responsible for communicating between body and brain).  
           This communication is done by synapses(Electrical/chemical signals)].  
 
  ###### Deep Learning(DL):  

          Where there is 3 layer. Doesn’ require labelling/human interaction. Thus its scalable ML as it is self-learning.
          Input Layer [Raw Data, with nodes depending on data type, 4x4 image = 16 nodes (each node represents neuron & connection between them acts as synapses)] → Hidden            Layer(Process and refine the input, bringing the network closer to a prediction) → Output Layer(Final Prediction)




<!--

### Important in security:
 - Preventing lateral movement 

#### Q1. What is IANA (Internet Assigned Numbers Authority)?
        Responsible for Global internet identifiers such as IP address blocks [192.168.1.0/24(ipv4),
        8.8.8.0(organization ip-ISP style)], Port numbers (http/80,https/443,
        ftp/21, ssh/22), protocol parameters (TCP/6, UDP/17, ICMP/1).
        
<p align="center">
  <img
    src="https://github.com/script-kiddie-005/Security-Testing-Playbook/blob/main/images/3.png?raw=true" width=8000 height=400>
</p>
        
            	
              IANA [(controlled by ICAAN (multi stake-holder model)] -> Regional Internet Registries -> ISPs -> us
              
                - IANA matters because:
                
                1.	Port to service assumption
                2.	Protocol consistency
                3.	DNS hierarchy[translate human-friendly domain names into IP addresses.
                    {Root level(.) -> TLD(.com,.org,.in) -> Authoratative name server(A/AAAA, CNAME, MX record)-> Recursive resolver(ISP, cloudflare)}]

                 - DNS hierarchy matters:

                1.Subdomain enumeration abuses hierarchy
                2.Zone transfers leak authoritative data
                3.Cache poisoning targets resolvers
                4.Misconfigured DNS exposes internal assets
<p align="center">
  <img
    src="https://github.com/script-kiddie-005/Security-Testing-Playbook/blob/main/images/2.jpg?raw=true" width=8000 height=400>
</p>
                
        Well-known ports (0–1023)
        Registered ports (1024–49151)


-->

 

    
