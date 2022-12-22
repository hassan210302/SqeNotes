# Modular Architecture 
# Important points about Three Tier Architecture
 - Three layers 
   - Presentation Layer
   - Buisness Layer
   - Data Layer

## Benefits
  - Independent Modules

## Web Development Usage
 - Front End Layer
  - It consists of front end server having static content and some dynamic content using cache. 
 - Middle Layer
  - It consists of processing layer. For example Spring, Asp.net, Rails
 - Data Layer 
  - It consists of data processing layer and Database such as MySql
  
## Difference Between layers and Tiers
- Tiers Depends on physical distribution
- Layers Depends on logical distribution
 - For Example, Our middle tier which consists of our buisness layer consists of different classes. We can call these classes layers. All these Layers are on the middle Tier.


# Cloud Native Enviroinment

- Building Flexible, Scaleable applications in cloud computing environment

## Benefits 

- Increase Efficiency (Support Devops and Continous Delivery)
- Reduced Cost (Dont have to invest on infrastructure in long term so operational cost saving)
- Ensure Availability (No downtime during future updates)

## Tradiontional Vs Cloud Native
- Traditional are not scalable 
- Traditional took longer to deploy than cloud native

## What is cloud-native application architecture?

- Combines software components to run scalable applications
 1. Immutable infrastructure (If the application requires more computing resources, the old server is discarded, and the app is moved to a new high-performance server. Its means no manual update to server)
 2. Microservices
 3. API (Between Microservices to share Data)
 4. Service mesh
