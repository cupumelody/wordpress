# Advanced Demo - Web App - Single Server to Elastic Evolution

In this advanced demo lesson you are going to evolve the architecture of a popular web application wordpress
The architecture will start with a manually built single instance, running the application and database
over the stages of the demo you will evolve this until its a scalable and resilient architecture

The demo consists of 6 stages, each implementing additional components of the architecture  

- Stage 1 - Setup the environment and manually build wordpress  
- Stage 2 - Automate the build using a Launch Template  
- Stage 3 - Split out the DB into RDS and Update the LT 
- Stage 4 - Split out the WP filesystem into EFS and Update the LT
- Stage 5 - Enable elasticity via a ASG & ALB and fix wordpress (hardcoded WPHOME) 
- Stage 6 - Cleanup  

![Architecture](https://github.com/acantril/learn-cantrill-io-labs/raw/master/aws-elastic-wordpress-evolution/ArchitectureEvolutionAll.png)

## Instructions

- [Stage1](Instructions/Stage1.md)
- [Stage2](Instructions/Stage2.md)
- [Stage3](Instructions/Stage3.md)
- [Stage4](Instructions/Stage4.md)
- [Stage5](Instructions/Stage5.md)
- [Stage6](Instructions/Stage6.md)
