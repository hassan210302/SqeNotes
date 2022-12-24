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
 3. API (Cloud-native systems use APIs to bring the loosely coupled microservices together.)
 4. Service mesh (Service mesh is a software layer in the cloud infrastructure that manages the communication between multiple microservices.)
 5. Containers (Smallest Unit, They are software components that pack the microservice code and other required files in cloud-native systems.)

## What is cloud-native application development?
- Continuous integration (Continuous integration (CI) is a software practice in which developers integrate changes into a shared code base frequently and without errors.)
- CD (With CD, development teams ensure that the microservices are always ready to be deployed to the cloud.)
- Devops 
- ServerLess

## What are the benefits of cloud-native application development? 

- Faster development (Not depending upon any one, Always ready to deploy with devops practices)
- Plateform Independence (Cloud take cares of the consistency and reliability of the operating environment)
- Cost Effectiveness (You pay on resources you used)

## Cloud Native Stack  
Cloud-native stack describes the layers of cloud-native technologies that developers use to build, manage, and run cloud-native applications.
- Infrastructure Layer (It consists of operating systems, storage, network)
- Provisioning layer (Services to configure Cloud environment)
- Runtime layer (This comprises cloud data storage, networking capability, and a container runtime such as containerd)
- Orchestration and management layer (Responsible for integrating the various cloud components so that they function as a single unit)
- Observability and analysis tools ( Observability and analysis tools monitor, evaluate, and improve the system health of cloud applications. )

# Aws Services
### Cloud Front 
- Have edge locations
- If data is already available at the edge location serve data quickly 
- Else save data in the edge location 
- Copies of data are available at different edge locations around the world

### S3 Bucket 
- Static web hosting 
- store files of data 
- scalable 
- Version Controlling 

## Extensibility 
These are some ideal characteristics of Extensibility 
1. Flexible
2. Configurable 
3. Customizable 
4. Upgradeable 
5. Integrated

Following are types of extensibility 
- Data model 
- Processes
- User Interface
- Well Integration 

## Client Side vs Server Side vs Pre Rendering 

### Client Side 
- Browser Returns an Html Page of javascript
- Every thing is compiled at the Client side using client browser
- Initial Loading slow but then fast 
- Useful in dynamic data
### Server Side
With old server-side rendering solutions, you built a web page—with PHP for example—the server compiled everything, included the data, and delivered a fully populated HTML page to the client. It was fast and effective.
Initial loading is fast than slow
Better seo 
### Pre Rendering 
- Starting page with static content then loads dynamic slowly

## Service Worker

Service Worker is a script that works on browser background without user interaction independently. Also, It resembles a proxy that works on the user side. With this script, you can track network traffic of the page, manage push notifications and develop “offline first” web applications with Cache API.

- Push Notification 
- Cache
- Network Traffic
- Basis for PWA
