# Learn software development the fun way: Build a communcations app from scratch 

Want to learn a new language in a fun way? Want to become a better developer doing that? Let's build a communications app starting with the description provided. 

By the time we finish building this, we'll be able to understand in depth the implementation the following concepts and technologies:

- Backend Communcation Protocols
- GUIs/CLIs
- File Storage
- Databases
- Data Strctures
- Video/Audio Processing
- String processing
- File handling
- Image Processing
- DevOps: Build, Deploy and Diagnostics
and much more...


Google, ChatGPT or do whatever you want to search whenever stuck. Just make sure to properly understand if copying any code, using library, tools etc. happy coding!


#### User Requirements: 

- Send chat to A chatgroup ( 1 or more people ).
- Persist chat (for a specific chatroom and visible to subscribed user)
- Chat format: text, file(preview options for image), URL
- Audio/Video Calling, WIth screen sharing
- Browse the chat history, groups, call history etc.
- with GUI
- Settings, Call History etc.
- Chat backup and Migration Options

#### Technical Requirements:

- Languages (Make one version in each language): JS,Go, Python, C, Java, Rust, Zig etc.
- Files, chats can be compressed
- Identify how each tool’s (language, library, Framework) used across the industry.
- A small tip here: try to convert small parts of your code to assembly/obj/bytecode. Search the internet if anything seems foreign and keep on going.
- Try to be less dependent on third party libraries, only use when absolutely required. If you really use something, try to understand the internals, explore code etc,
- <b> Setup Benchmark, Testcases, Dockerize, Build and Deployment Scripts, Diagnostics (Logging, Metrics, Audit etc.) </b>
- Try to improve the application to squeeze out every last bit of performance.
- Once the initial prototype is complete, try deploying it over some free tier linux server, or any cheap linux service provider. Automate deployment by installing tools like jenkins(or use github workflows) on your local machine.
- Research on the best security practices used across the industry and try applying those relevant to the application.
- Go over webrtc: [https://webrtc.github.io/webrtc-org/architecture](https://webrtc.github.io/webrtc-org/architecture/#), understand architecture and try building a rough one of your own using udp/tcp
- 

#### Rough Guidelines For Benchmarks:
- <b>Idea Here is to squeeze out the best performance with available resources. Keep going on until resource usage hits bottleneck</b>
- 1. Notice the Spike in resource usage. 2. Identify The component/function/process taking the most amount of time for this.
- Send and Store the following no of text messages: 10K, 100K, 1 million, 10 million and so on. (spread across multiple groups and users)
- Send files worth: 1 MB, 10 MB, 100 MB and so on
- The following number of calls at a time across the application space: 1000, 10k, 100k and so on etc. 


## UI SCREENS:

***Login:***

![image](https://github.com/adarshjhaa100/communications-app-architecture/assets/31096082/f5823003-a0cb-4b47-a09b-e7849138e9d5)


***Chat:***

![image](https://github.com/adarshjhaa100/communications-app-architecture/assets/31096082/2a6903fe-39d1-4115-bf44-1ca3e097b52b)


***Search:***

![image](https://github.com/adarshjhaa100/communications-app-architecture/assets/31096082/962ddea6-23e1-40b9-8e78-75d19512b6ce)


***Call:***

![image](https://github.com/adarshjhaa100/communications-app-architecture/assets/31096082/53acaa4c-c490-45ac-bf4d-46c5aa88fdf8)


## ARCHITECTURE

**High Level Frontend Arch**

![image](https://github.com/adarshjhaa100/communications-app-architecture/assets/31096082/8ce6ac8d-0869-470a-8706-fab13aee3fb3)


**High level Backend API**

![image](https://github.com/adarshjhaa100/communications-app-architecture/assets/31096082/3a4f9abf-f2cf-426d-9af4-ebf345b8793b)


Do reach out or raise a PR for any suggestions.

