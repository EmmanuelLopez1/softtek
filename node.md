## Node js interview

### What is node js?
    Node js is a execution enviroment for javascript in server side.
    It allow us work with files, buffers and other used features in server side.

### Why people should use node js?
    Node js is asynchronous, and allow us work with several connections at same time due to its non-blocking input/output (I/O) model.
    Node js counts with npm, its a management package system, and help the developers to share and reuse modules, npm is one of the most biggest collection of code in the world.
    Node support communication in two channels, and is very popular by that reason, we can make online games, chats and other applications for work in real time.

### What is the difference between frontend and backend.
    Frontend is what the user can see and interact, its builded in technologies like Html, css, JavaScript, React js, next js. On the other hand, the backend is what allow proccess the user actions in the server side, here the data is validated, saved and secured. Here are technologies like node js, nest js,  mongodb, express js, and so on. In the Javascript enviroment.

### What are stubs?
    In software development, a "stub" refers to a piece of code or a function that serves as a temporary substitute for a module or component. Stubs are used in various testing and development scenarios to simulate the behavior of real components that are not yet available or are difficult to incorporate into a testing environment.

### What are callback hells?
    The term callback hell is refered when several callbacks are nested in a specific place, this makes dificult to read and mantain the code.
    To avoid this we must to use the new syntax async/await when we work with promises.

### What are events?
    Events is way to communication between different parts in a application, Node js is asynchronous, and we dont know when an action will be finished, the events allow us to know when an action have been finished and act in consecuence.

### What is Event-drive programing?
    Is a way programing focused and based in events. The program doesnt run sequentially, listen events and reacts to events in the app.

### Why node js works with a subproccess?
    Allow to node realize async proccess, it allow proccess work fast and without issues

### Can more processes be created in node js?
    Yes we can create more processes and clusters for currency and parallelization.

### what is a cluster?
    A cluster is a collection of workers or processes. A cluster allow distribute the requests in each worker to take advantage for diferent core of the cpu.

### what is a worker?
    Is a process inside a cluster, is a process independent with its own main thread.

### what is express js?
    Is a framework for node js, make simple and agil creation of  web applications and apis.

### what is a multiplexer?
    Its a mechanism that allows to main thread of node js listen (I/O) events, its responsible to monitoring and notify to main thread when an event has happened. 

### What is REPL?
    Its means "Read-Eval-Print Loop", its a common feature of come programing language like python and node js. Help us to try easily features of the lenguaje, make proofs and explore it.
    In node js case, it help us to interact with JavaScript environment in the server.

### What is the diferent between blocking and non-blocking functions?
    Blocking funtions stop the main thread of the application, the program waits until the function has finished to continue the program execution, on the other hand, non-blocking functions are async, the main thread of the program continues executing while the subprocess are executing to solve the funtion.

### node js owns secundary processes?
    Yes, it can be used to take advantage of parlallel operations and multithread systems. child process module can be used for comunication with subprocesses

### What is event loop in node js?
    Event loop helps to node js to work with non-blocking operations, its responsible for manage the event queue, this is where the async request are stored before to be procesed by the event loop.

### What are streams in node js?
    Streams allow us work with data in async way, specially when we work with a large amount of data. You can write or read data in chunks instead of doing everything at once, this help with the spped of the application.
    There are 4 types of streams:
        Readable, writable, duplex and transform: The lastone is a type of duplex type, allow us transform the data while they are writing and reading.

### What is the diference between readFile y createReadStream?
    Readfile read all the data in an async way and store it in memory before to pass it to the user, on the other hand createReadStream read the file in chunks and the user doesnt nedd to wait until all the file is ready.

### How node js manage non-detected exceptions?
    We can detect non-detected exceptions in the appliacation at process level with an object global process listener for catch those events.

### What are benefits of a single-thread web backend versus a multithreaded one?
    -is easier for developers develop aplications.
    -applicatios are easily scalable.

### Why is good practice separte application of server?
    We can separate the api implementation of network implementation, this allow us to realize api proofs without doing network calls.

### How do you decide use express or nest js in a project?
    Its depends of the project, express its a lightweigth framework and its useful when to build small or medium project where simplicity and sped are necesary, on the other hand nest in bigger projects where a better organization and structure are crucial, nest is better.

### Explain oauth 2.0 and its benefits.
    Oauth 2.0 its an authorization framework that allow to user to  grant to their resources to a third-party application without share thier credentials.

### Compare service oriented architecture (SOA) and microservice architecture (MSA):
    They are two different popular architecture systems for creating complex system software.
    SOA is an architectural style that focuses on decomposing an application into loosely coupled services. MSA descompose an application into independent services.

### What does it mean low coupled and high cohesion?
    Its refers to design principles that have as objetive make software systems more modular, maintainable and scalable.

    Lo coupled it means, modules in systems are designed to be independet of each other.
    High cohesion means the way to group together related functionalities.

### How do you guarantee the security of backend systems?
    -Follow secure coding practices, like input validation, output coding and dont use vulnerable libraries.
    -Authentication and access control, backend systems must to implement solid authentication mechanism, like two factor authentication and role control.
    -Encryption: Backend systems must encrypt sensitive data.
    -security proofs.
    
