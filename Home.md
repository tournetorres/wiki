# Concepts to review 
(Or at least lightly familiarize yourself with...)

## Core technologies

### JavaScript
* [[pros and cons of JavaScript]]
* [[vs. other languages]]
* [[event loop]]
* [[scope|scope in JavaScript]] / [[closures|closures in JavaScript]]
* [[loops]]
* [[hoisting]]
* [[instantiation patterns]]
* [[truthy and falsy]]
* [[type coercion]]
* [[objects|objects in JavaScript]]
	* [[prototypes|prototypes in JavaScript]]
* [[this]]
* [[bind]] / [[currying]]
* [[Best practices]]
    * [[Short-circuiting]]
    * [[Switch / case]]
    * [[Ternary operator]]
    * [[Variables in for loops]]
    * [[Recursion call stacks]]
    * [[Namespacing]]
* [[ES6]]
    * [[let vs const vs var]]
    * [[arrow functions]]
    * [[promises]]
    * [[generators]]
    * [[iterators]]
    * [[for-of vs. for-in loop|loops]]
    * [[classes]]
    * [[destructuring]]
    * [[string interpolation]]
    * [[modules]]
    * [[transpiling]]
    * [[Lesser-known]]
		* [[Maps / Sets]]
		* [[Proxies]]
		* [[Reflections]]
    * [[Augmented methods]]
		* [[Math]]
		* [[Number]]
		* [[Array]]
		* [[Object]] (especially Object.assign)
		* [[Strings and Unicode]]

### [[HTTP]]
* [[HTTP requests and responses]]
* [[HTTP headers]]
* [[HTTP response codes]]
* [[HTTP basic auth]]
* [[What is a cookie?]]
* [[AJAX]] / [[JSONP]]
* [[ReST]] (and how it compares to SOAP, Graph, etc.)
* [[Asynchronous ReST]]

### [[Databases]]
* [[What does "ACID compliant" mean?]]
* [[Database transactions]]
* [[Migrations]]
* [[ORMs]]

#### SQL databases
* [[Popular SQL databases and their differences]]
    * [[mySQL]]
    * [[PostgreSQL]]
    * [[Oracle]]
    * [[SQLite]]

* [[what is a "relational" database|what is a relational database]]
* [[what's a B-Tree, and why does it matter for a database?|b-trees in databases]]
* [[Primary key vs foreign key]]
* [[Schema design]]
    * [[normalization]]
    * [[denormalization]]
* [[Basic select statements]]
* [[Joins]]
* [[Sub-selects]]
* [[Grouping]]

#### [[NoSQL databases]]
* MongoDB
	* [[why is Mongo useful, why it might suck]]
	* [[what's a "document database"? how does it work?]]
	* [[aggregation pipeline]]
	* [[Mongo indexing]]
	* [[BSON]]
* [[Memcache]]
* Redis
	* [[Serialized / Queued / Atomic transactions]]
	* [[why is Redis useful, why it might suck]]
	* [[the most-useful Redis data types|Redis data types]]
	* [[the most-useful Redis operations|Redis operations]]
* CouchDB
	* [[MapReduce]]
* [[LevelDB]]
* [[Cassandra]]
* [[Riak]]
* [[Neo4j]]
* [[HDFS / HBase with Hadoop]]

### Browsers
* [[What is the DOM]]?
* [[How would you design the DOM, if you had to make it from scratch?|How would you design the DOM?]]
* [[Outline how browsers keep your data secure]]
* [[What is a virtual DOM?]]
* [[What happens when you load a page?]]
	* [[Async vs. Defer]]
	* [[Pagination and eager loading]]
* [[Event handling and bubbling]]
	* [[Event delegation]]

### [[Regular expressions]]

### Automation
* [[Grunt]] / [[Gulp]]

### HTML
* [[semantic markup]]
* [[Responsive & Adaptive design]]
* [[block vs inline]]
* [[Client-side vs. server-side rendering]]
* [[templating]]
	* [[popular JS template engines]]
	* [[interpolation|interpolation in templates]]
	* [[control flow|control flow in templates]]
* [[how is HTML rendered by the browser?]]
* [[what is "reflow"?]]
* [[accessibility]]

### CSS
* [[what does "cascading" mean?]]
* [[how do you organize your stylesheets, and why?]]
* [[selectors]]
	* [[native JS selectors]]
	* [[jQuery selectors]]
* [[computing specificity]]
* [[pseudo-classes]]
* [[box model]]
* [[how does CSS help to make a responsive web app?]]
* [[CSS libraries]]
	* [[Bootstrap]]
	* [[Material-UI]]
	* [[Normalize.css and ResetCSS]]

## Tools and Frameworks

### [[Server]]
* Node
	* [[what is a server?]]
	* [[what is Node?]]
	* [[Streams]]
	* [[How does Node compare to other server-side technologies]]
	* [[why Node is useful, why it might suck]]
	* Useful packages
		* Node-inspector
		* Nodemon
* Express
	* [[vs. HAPI, Koa, and others]]
	* [[Middleware]]
	* [[Router]]

### [[Client]]
* jQuery
* D3
* React
	* [[what is React?|what is React]]
	* [[compare React vs Angular]]
	* [[Flux]] / [[Redux]]
	* [[React Native]]
	* [[JSX]]
* Angular
	* [[What Is Angular?|What Is Angular]]
	* [[Ionic]]
	* [[compare React vs Angular]]
	* [[Angular 1.x vs Angular 2]]
	* [[Typescript]]
* Backbone
	* [[what is Backbone?]]
	* [[why Backbone is useful, why it might suck]]
* Ember
	* [[what is Ember?]]
	* [[why Ember is useful, why it might suck]]

### Code management
* git
	* [[git basics]]
	* [[git gotchas]]
	* [[why do people refer to "the SHA-1"?]]
	* [[merge vs rebase debate]]. where do you stand?
* [[GitHub]]

### Package management
* [[apt-get]]
* [[brew]]
* [[npm]]

### Dependency management
* [[Webpack]]
* [[Browserify]]
* [[nvm]]

### Deployment
* [[AWS]]
* [[Digital Ocean]]
* [[Heroku]]

## Concepts

### Problem-solving
* [[problem decomposition]]
* [[Case-based reasoning]]
* [[Back-of-the-envelope]]
* "[[examplify]]"
* [[pattern-matching]]
* [[simplify then generalize]]
* [[Base case]], then [[inductive reasoning]]
* [[How to apply scientific method to programming?]]

### Programming paradigms
* [[imperative vs. declarative]]
* [[object-oriented]]
* [[functional programming]]
	* [[functors]] / [[monads]]
	* [[higher-order functions]]
	* [[lambda expressions]]
	* [[Reactive programming]]
* [[recursion]]
	* [[dynamic programming]] / [[memoization]]
	* [[Limiting the call stack]]

### System design
* [[Client-server]]
* [[Workers]]
* [[Service-oriented architecture]]
* [[Multi-tier architecture]]
* [[MVC]]
	* [[MV*]] (pronounced "MV-star")
* [[asynchronous programming]]
	* [[callback hell]]
	* [[multi-threading]]
	* [[race condition]]
* [[Pub/sub|Publish subscribe]]
* [[Middleware]]
* [[ReST]]
	* [[HTTP "verbs"]]
	* [[CRUD]]
* [[what should you consider when you design an API?]]
* [[DRY]] (related to "single source of truth")
* [[single-responsibility principle]]
* [[idempotency]]
* [[loose coupling]] / [[separation of concerns]]
	* [[cohesion versus coupling]]
	* [[statelessness]]
		* "[[shared-nothing]]" architecture
* [[abstraction]]
* [[contracts (interfaces)|interfaces]] between components
	* [[modules]]
	* [[classes]]
	* [[duck typing]]
	* [[data-hiding]]
	* [[interface versus implementation]]

### Networking
* [[TCP/IP]]
* [[TCP vs. UDP]]
* [[ports]]
* [[socket]]
* [[WebRTC]]
* [[DNS]]
* [[HTTP]]
* [[HTTPS]]
* [[hostnames]]
* [[domains and subdomains]]
* [[how email works]]
* [[proxy]]
* [[reverse proxy]]
* [[load balancer]]
* [[MIME types]]
* [[URI]]
* [[CDN]]
* [[DDOS]]
* [[standards/RFC's]]
* [[what really happens when you upload a file?]]

### Operationalizing / Productionizing your system
* Scaling
	* [[vertical scaling]]
	* [[horizontal scaling]]
	* [[sharding]]
	* [[caching]]
	* [[Database replication]]
* [[Monitoring]]
* [[Configuration management]]
* [[Branch management]]
* [[Release management]]

### Project management
* [[Agile vs waterfall]]
* [[MVP]]

### Testing and writing testable code
* [[Try / Catch]]
* [[Debugging with Chrome Dev Tools]]
* [[Black-box vs white-box]]
* [[Regression testing]]
* [[Unit testing vs integration testing]]
* [[Smoke-testing vs end-to-end testing]]
* Testing libraries
	* [[selenium]]
	* [[mocha, chai, etc]]
		* [[can you use these on the fly]]? no harness or setup provided...
* [[Continuous integration]]
	* [[online CI services]]
	* [[Jenkins]]
* [[Mocking & Stubbing]]
* [[How testing improves system design]]

### Security
* [[Hashing vs encryption]]
* [[Authentication vs authorization]]
* [[Common encryption ciphers]]
* [[Public-Private Key Encryption]]
* [[oAuth]]
* [[Same-origin policy]]
* [[XSS]]
* [[CORS]]

### Data structures
* [[Linked lists]]
* [[Strings]]
* [[Arrays]]
* [[Trees]]
	* [[Binary search tree]]
	* [[Trie]]
	* [[Heap]]
* [[Stacks]]
* [[Queues]]
	* [[FIFO vs LIFO]]
	* [[Dequeue]]
* [[Graphs]]
* [[Hash tables]]

### Algorithms
* [[Big-O]]
* [[Search]]
* Sort
	* [[Bubble sort]]
	* [[Merge sort]]
	* [[Insertion sort]]
	* [[Quick sort]]
	* [[Radix sort]]
* [[Time and Space Complexity (Big O notation)]]

### How computers work
* [[Memory]]
	* [[Speed of different data storage options]]
	* [[What does the OS really do when your program instantiates an object?]]
	* [[Memory management]]
		* [[What does "swapping to disk" mean? Why would you care?]]
		* [[Garbage collecting]]
	* [[Index / Search]]
* Binary stuff
	* [[Bit-twiddling]]
	* [[What are "floating point errors"?]]
* [[Code interpretation and compilation]]
* [[Call stacks]]
	* [[What is a stack overflow?]]
* [[common unix command line utilities]]
* [[How does the internet work]]
* [[What is the 'full stack'?]]