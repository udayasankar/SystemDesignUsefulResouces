<!DOCTYPE html>
<html>
<body>

<h2>A System Design Interview usually lasts for 45-60 minutes. The following template will guide you on how to manage time duration in a System Design Interview:</h2>

<table border="1">
    <tr>
        <th>Step</th>
        <th>Duration</th>
        <th>Details</th>
    </tr>
    <tr>
        <td>Requirement Clarifications</td>
        <td>3-5 min</td>
        <td>
            <b>Ask clarifying questions to understand the problem and expectations of the interviewer:</b>
            <ul>
                <li><b>Functional Requirements</b>
                    <ul>
                        <li>Focussed use cases to cover (MVP)</li>
                        <li>Use cases that will not be covered</li>
                        <li>Who/How will use the system</li>
                        <li>Total/Daily active users</li>
                    </ul>
                </li>
                <li><b>Non Functional Requirements</b>
                    <ul>
                        <li>Is the system Highly Available or Highly Consistent? CAP theorem?</li>
                        <li>Does the system require low latency?</li>
                        <li>Does the system need to be reliable?</li>
                    </ul>
                </li>
            </ul>
        </td>
    </tr>
    <tr>
        <td>Estimations</td>
        <td>3-5 min</td>
        <td>
            <ul>
                <li>Latency/Throughput expectations</li>
                <li>QPS (Queries Per Second) Read/Write ratio</li>
                <li>Traffic estimates</li>
                <li>Storage estimates</li>
                <li>Memory estimates</li>
            </ul>
        </td>
    </tr>
    <tr>
        <td>API Design</td>
        <td>3-5 min</td>
        <td>Outline the different APIs for required scenarios</td>
    </tr>
    <tr>
        <td>Database Schema Design</td>
        <td>3-5 min</td>
        <td>
            <ul>
                <li>Identify the type of database (SQL or NoSQL)</li>
                <li>Design schema like tables/columns and relationships with other tables (SQL)</li>
            </ul>
        </td>
    </tr>
    <tr>
        <td>System's Detailed Design</td>
        <td>20-25 min</td>
        <td>
            <p><b>Draw/Explain high-level components of the system, covering components if needed:</b></p>
            <ul>
                <li>Client (Mobile, Browser)</li>
                <li>DNS</li>
                <li>CDN</li>
                <li>Load Balancers</li>
                <li>Web / Application Servers</li>
                <li>Microservices</li>
                <li>Blob/Object Storage</li>
                <li>Proxy/Reverse Proxy</li>
                <li>Database (SQL or NoSQL)</li>
                <li>Cache (Client side, CDN, Server side, Database side, Application level caching)</li>
                <li>Messaging Queues for asynchronous communication</li>
            </ul>
            <p><b>Additional Considerations:</b></p>
            <ul>
                <li>Algorithm/Data structure selection and scalability</li>
                <li>Scaling individual components - Horizontal & Vertical Scaling</li>
                <li>Database Partitioning
                    <ul>
                        <li>Methods
                            <ul>
                                <li>Horizontal Partitioning</li>
                                <li>Vertical Partitioning</li>
                                <li>Directory-Based Partitioning</li>
                            </ul>
                        </li>
                        <li>Criteria
                            <ul>
                                <li>Range-Based Partitioning</li>
                                <li>Hash-Based Partitioning (Consistent Hashing)</li>
                                <li>Round Robin</li>
                            </ul>
                        </li>
                    </ul>
                </li>
                <li>Replication & Redundancy
                    <ul>
                        <li>Primary & Secondary Server Redundancy</li>
                        <li>Data replication from active to mirrored database</li>
                    </ul>
                </li>
                <li>Database Types and Strategies
                    <ul>
                        <li>SQL - Sharding, Indexes, Master-Slave, Master-Master, Denormalization</li>
                        <li>NoSQL - Key-Value, Document, Wide-Column, Graph</li>
                    </ul>
                </li>
                <li>Communication Protocols (IP, TCP, UDP, HTTP/S, RPC, REST, Web Sockets)</li>
            </ul>
        </td>
    </tr>
    <tr>
        <td>Resolve Bottlenecks and Follow-up Questions</td>
        <td>2-3 min</td>
        <td></td>
    </tr>
</table>

</body>
</html>

<table border="1">
  <tbody>
    <tr>
        <td>Requirements</td>
        <td>Functional Requirements</td>
        <td></td>  
    </tr>    
    <tr>
      <td></td>  
      <td>Non-Functional Requirements</td>  
      <td></td>    
    </tr>
    <tr>
      <td></td>  
      <td>Daily Active Users</td>
      <td></td>    
    </tr>    
    <tr>
       <td></td>    
      <td>Read-to-Write Ratio</td>
       <td></td>    
    </tr>   
    <tr>
       <td></td>    
      <td>Usage Patterns</td>
       <td></td>    
    </tr>    
    <tr>
       <td></td>    
      <td>Peak and Seasonal Events</td>    
       <td></td>    
    </tr>      
    <tr>
      <td>Database</td>
      <td>Data Model</td>
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td>Entity Relationship Diagram</td>
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td>SQL</td>
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td>Type of Database</td>
      <td></td>
    </tr>
    <tr>
      <td>API Design</td>
      <td>HTTP Verb</td>
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td>Request-Response Headers</td>
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td>Request-Response Contract</td>
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td>Data format</td>
      <td>JSON, XML, Protocol Buffer</td>
    </tr>
    <tr>
      <td>Capacity Planning</td>
      <td>Query Per Second (Read-Write)</td>
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td>Bandwidth (Read-Write)</td>
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td>Storage</td>
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td>Memory</td>
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td>Cache (80-20 Rule)</td>
      <td></td>
    </tr>
    <tr>
      <td>High Level Design</td>
      <td>Basic Algorithm</td>
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td>Data Flow</td>
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td>Read-Write Scenario</td>
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td>Tradeoffs</td>
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td>Alternatives</td>
      <td></td>
    </tr>
    <tr>
      <td>Network Protocols</td>
      <td>TCP, UDP</td>
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td>REST</td>
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td>RPC</td>
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td>WebSocket</td>
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td>SSE</td>
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td>Long Polling</td>
      <td></td>
    </tr>
    <tr>
      <td>Cloud Patterns</td>
      <td>CQRS</td>
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td>Publish-Subscribe</td>
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td>Serverless Functions</td>
      <td></td>
    </tr>
    <tr>
      <td>Data Structures</td>
      <td>CRDT</td>
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td>Trie</td>
      <td></td>
    </tr>
    <tr>
      <td>Design Deep Dive</td>
      <td>Single Point of Failures</td>
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td>Bottlenecks (Hot spots)</td>
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td>Concurrency</td>
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td>Distributed Transactions</td>
      <td>Two-Phase Commit, Sagas</td>
    </tr>
    <tr>
      <td>Probabilistic Data Structures</td>
      <td>Bloom Filter, HyperLogLog, Count-Min Sketch</td>
      <td></td>
    </tr>
    <tr>
      <td>Coordination Service</td>
      <td>Zookeeper</td>
      <td></td>
    </tr>
    <tr>
      <td>Logging</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Monitoring</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Alerting</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Tracing</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Deployment</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Security</td>
      <td>Authorization, Authentication</td>
      <td></td>
    </tr>
    <tr>
      <td>Consensus Algorithms</td>
      <td>Raft, Paxos</td>
      <td></td>
    </tr>
    <tr>
      <td>Components</td>
      <td>DNS</td>
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td>CDN</td>
      <td>Push-Pull</td>
    </tr>
    <tr>
      <td></td>
      <td>Load Balancer</td>
      <td>Layer 4-7, Active-Active, Active-Passive</td>
    </tr>
    <tr>
      <td></td>
      <td>Reverse Proxy</td>
      <td></td>
    </tr>
    <tr>
      <td>Application Layer</td>
      <td>Microservice-Monolith</td>
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td>Service Discovery</td>
      <td></td>
    </tr>
    <tr>
      <td>SQL Data Store</td>
      <td>Leader-Follower, Leader-Leader</td>
      <td>Indexing, Federation, Sharding, Denormalization, SQL Tuning</td>
    </tr>
    <tr>
      <td>NoSQL Data Store</td>
      <td>Graph, Document, Key-Value, Wide-Column</td>
      <td></td>
    </tr>
    <tr>
      <td>Message Queue</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Task Queue</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Cache</td>
      <td>Query-Object Level</td>
      <td>Client, CDN, Webserver, Database, Application</td>
    </tr>
    <tr>
      <td>Cache Update Pattern</td>
      <td>Cache Aside, Read Through, Write Through, Write Behind, Refresh Ahead</td>
      <td></td>
    </tr>
    <tr>
      <td>Cache Eviction Policy</td>
      <td>LRU, LFU, FIFO</td>
      <td></td>
    </tr>
    <tr>
      <td>Clocks</td>
      <td>Physical clock, Lamport clock (logical), Vector clock</td>
      <td></td>
    </tr>
  </tbody>
</table>



<html>
<body style="background-color:powderblue; font-family: Arial, sans-serif;">

<h1 id="SystemDesignUsefulResources">System Design Useful Resources</h1>

<!-- System Design Resources and Basics -->
<h2>System Design Resources and Basics</h2>
<table border="1" cellpadding="10" cellspacing="0" style="border-collapse: collapse; width: 100%;">
  <caption><strong>System Design Resources and Basics</strong></caption>
  <tr>
    <th>Resource</th>
    <th>Link</th>
  </tr>
  <tr>
    <td>Donne Martin</td>
    <td><a href="https://github.com/donnemartin/system-design-primer" target="_blank">https://github.com/donnemartin/system-design-primer</a></td>
  </tr>
  <tr>
    <td>Awesome Scalability</td>
    <td><a href="https://github.com/binhnguyennus/awesome-scalability" target="_blank">https://github.com/binhnguyennus/awesome-scalability</a></td>
  </tr>
  <tr>
    <td>Awesome System Design</td>
    <td><a href="https://github.com/ashishps1/awesome-system-design-resources" target="_blank">https://github.com/ashishps1/awesome-system-design-resources</a></td>
  </tr>
</table>

<br>

<html>
<body>
<h2>Key Topics for System Design Preparation</h2>
<p>No matter the scale, these topics come into play each time. Prepare these well.</p>

<table border="1">
    <tr>
        <th>Topic</th>
        <th>Link</th>
    </tr>
    <tr>
        <td>Checksum</td>
        <td><a href="https://lnkd.in/gJnJpnRF" target="_blank">https://lnkd.in/gJnJpnRF</a></td>
    </tr>
    <tr>
        <td>CAP Theorem</td>
        <td><a href="https://lnkd.in/gjtcJxeN" target="_blank">https://lnkd.in/gjtcJxeN</a></td>
    </tr>
    <tr>
        <td>SQL vs NoSQL</td>
        <td><a href="https://lnkd.in/gwCe58TU" target="_blank">https://lnkd.in/gwCe58TU</a></td>
    </tr>
    <tr>
        <td>Circuit Breaker</td>
        <td><a href="https://lnkd.in/gvSrR_EA" target="_blank">https://lnkd.in/gvSrR_EA</a></td>
    </tr>
    <tr>
        <td>Load Balancing</td>
        <td><a href="https://lnkd.in/gefSiXEJ" target="_blank">https://lnkd.in/gefSiXEJ</a></td>
    </tr>
    <tr>
        <td>Fault Tolerance</td>
        <td><a href="https://lnkd.in/guiDtdXT" target="_blank">https://lnkd.in/guiDtdXT</a></td>
    </tr>
    <tr>
        <td>API Design</td>
        <td><a href="https://lnkd.in/g6tHgXr7" target="_blank">https://lnkd.in/g6tHgXr7</a></td>
    </tr>
    <tr>
        <td>WebSockets</td>
        <td><a href="https://lnkd.in/gzdAdBNC" target="_blank">https://lnkd.in/gzdAdBNC</a></td>
    </tr>
    <tr>
        <td>API Gateway</td>
        <td><a href="https://lnkd.in/gWYGxs3S" target="_blank">https://lnkd.in/gWYGxs3S</a></td>
    </tr>
    <tr>
        <td>Failover</td>
        <td><a href="https://lnkd.in/g-eH-Pvf" target="_blank">https://lnkd.in/g-eH-Pvf</a></td>
    </tr>
    <tr>
        <td>Caching</td>
        <td><a href="https://lnkd.in/gAp-9udf" target="_blank">https://lnkd.in/gAp-9udf</a></td>
    </tr>
    <tr>
        <td>Scalability</td>
        <td><a href="https://lnkd.in/gHUfp8x9" target="_blank">https://lnkd.in/gHUfp8x9</a></td>
    </tr>
    <tr>
        <td>HeartBeat</td>
        <td><a href="https://lnkd.in/gzfQt74b" target="_blank">https://lnkd.in/gzfQt74b</a></td>
    </tr>
    <tr>
        <td>Proxy Server</td>
        <td><a href="https://lnkd.in/gs2ZF8_d" target="_blank">https://lnkd.in/gs2ZF8_d</a></td>
    </tr>
    <tr>
        <td>Bloom Filters</td>
        <td><a href="https://lnkd.in/gnekDkQv" target="_blank">https://lnkd.in/gnekDkQv</a></td>
    </tr>
    <tr>
        <td>REST vs RPC</td>
        <td><a href="https://lnkd.in/gVGeh3VV" target="_blank">https://lnkd.in/gVGeh3VV</a></td>
    </tr>
    <tr>
        <td>Idempotency</td>
        <td><a href="https://lnkd.in/gqGnkZHg" target="_blank">https://lnkd.in/gqGnkZHg</a></td>
    </tr>
    <tr>
        <td>Database Index</td>
        <td><a href="https://lnkd.in/gE_q5m_g" target="_blank">https://lnkd.in/gE_q5m_g</a></td>
    </tr>
    <tr>
        <td>Data Replication</td>
        <td><a href="https://lnkd.in/gPBmH5h8" target="_blank">https://lnkd.in/gPBmH5h8</a></td>
    </tr>
    <tr>
        <td>Database Scaling</td>
        <td><a href="https://lnkd.in/gX7AKQHY" target="_blank">https://lnkd.in/gX7AKQHY</a></td>
    </tr>
    <tr>
        <td>Data Redundancy</td>
        <td><a href="https://lnkd.in/gccsuSvr" target="_blank">https://lnkd.in/gccsuSvr</a></td>
    </tr>
    <tr>
        <td>Service Discovery</td>
        <td><a href="https://lnkd.in/gEjBT8ZA" target="_blank">https://lnkd.in/gEjBT8ZA</a></td>
    </tr>
    <tr>
        <td>Disaster Recovery</td>
        <td><a href="https://lnkd.in/gEYQ_74X" target="_blank">https://lnkd.in/gEYQ_74X</a></td>
    </tr>
    <tr>
        <td>ACID Transactions</td>
        <td><a href="https://lnkd.in/g-sjsMwX" target="_blank">https://lnkd.in/g-sjsMwX</a></td>
    </tr>
    <tr>
        <td>Database Sharding</td>
        <td><a href="https://lnkd.in/gnuxe5pu" target="_blank">https://lnkd.in/gnuxe5pu</a></td>
    </tr>
    <tr>
        <td>Distributed Locking</td>
        <td><a href="https://lnkd.in/gJrrrqsa" target="_blank">https://lnkd.in/gJrrrqsa</a></td>
    </tr>
    <tr>
        <td>Consistent Hashing</td>
        <td><a href="https://lnkd.in/gmrHsEzq" target="_blank">https://lnkd.in/gmrHsEzq</a></td>
    </tr>
    <tr>
        <td>Distributed Caching</td>
        <td><a href="https://lnkd.in/gUH2yV-X" target="_blank">https://lnkd.in/gUH2yV-X</a></td>
    </tr>
    <tr>
        <td>Consistency Patterns</td>
        <td><a href="https://lnkd.in/gey7tqYh" target="_blank">https://lnkd.in/gey7tqYh</a></td>
    </tr>
    <tr>
        <td>Latency vs Throughput</td>
        <td><a href="https://lnkd.in/gDAx6QQd" target="_blank">https://lnkd.in/gDAx6QQd</a></td>
    </tr>
    <tr>
        <td>Serverless Architecture</td>
        <td><a href="https://lnkd.in/gtS52Sza" target="_blank">https://lnkd.in/gtS52Sza</a></td>
    </tr>
</table>

<h2>Additional Resources</h2>
<ul>
    <li><a href="https://github.com/systemdesign42/system-design" target="_blank">https://github.com/systemdesign42/system-design</a></li>
    <li><a href="https://github.com/kamranahmedse/developer-roadmap" target="_blank">https://github.com/kamranahmedse/developer-roadmap</a></li>
    <li><a href="https://github.com/EbookFoundation/free-programming-books" target="_blank">https://github.com/EbookFoundation/free-programming-books</a></li>
    <li><a href="https://github.com/CodingChallengesFYI/SharedSolutions" target="_blank">https://github.com/CodingChallengesFYI/SharedSolutions</a></li>
</ul>

</body>
</html>


<!-- Design Lectures -->
<h2>Design Lectures</h2>
<table border="1" cellpadding="10" cellspacing="0" style="border-collapse: collapse; width: 100%;">
  <caption><strong>Design Lectures</strong></caption>
  <tr>
    <th>Lecture</th>
    <th>Link</th>
  </tr>
  <tr>
    <td>CS Lectures</td>
    <td><a href="https://www.youtube.com/playlist?list=PLhQjrBD2T3828ZVcVzEIhsHVgjANGZveu" target="_blank">https://www.youtube.com/playlist?list=PLhQjrBD2T3828ZVcVzEIhsHVgjANGZveu</a></td>
  </tr>
  <tr>
    <td>MIT Distributed Systems</td>
    <td><a href="https://www.youtube.com/@6.824/videos" target="_blank">https://www.youtube.com/@6.824/videos</a></td>
  </tr>
</table>

<br>

<!-- Additional Links -->
<h2>Additional Links</h2>
<ul>
  <li><a href="https://research.google/teams/" target="_blank">Google Research Teams</a></li>
  <li><a href="https://rclayton.silvrback.com/use-state-machines" target="_blank">Use State Machines - RClayton Blog</a></li>
</ul>

<!-- Awesome Microservices -->
<h2>Awesome Microservices</h2>
<p><a href="https://github.com/markoa/awesome-microservices" target="_blank">https://github.com/markoa/awesome-microservices</a></p>

<!-- Search Engines Design -->
<h2>Search Engines Design</h2>
<p><a href="https://www.youtube.com/@msci541-searchengines3" target="_blank">https://www.youtube.com/@msci541-searchengines3</a></p>

<!-- Awesome System Design Concepts -->
<h2>Awesome System Design Concepts</h2>
<table border="1" cellpadding="10" cellspacing="0" style="border-collapse: collapse; width: 100%;">
  <caption><strong>Awesome System Design Concepts</strong></caption>
  <tr>
    <th>No</th>
    <th>Notes</th>
    <th>Link</th>
  </tr>
  <tr>
    <td>1</td>
    <td>Awesome System Design</td>
    <td><a href="https://github.com/ashishps1/awesome-system-design-resources" target="_blank">https://github.com/ashishps1/awesome-system-design-resources</a></td>
  </tr>
  <tr>
    <td>2</td>
    <td>AWS Architecture Blog</td>
    <td><a href="https://lnkd.in/eEchKJif" target="_blank">https://lnkd.in/eEchKJif</a></td>
  </tr>
  <tr>
    <td>3</td>
    <td>System Design Newsletter</td>
    <td><a href="https://github.com/systemdesign42/system-design?tab=readme-ov-file#p-companies" target="_blank">https://github.com/systemdesign42/system-design?tab=readme-ov-file#p-companies</a></td>
  </tr>
</table>

</body>
</html>

<!DOCTYPE html>
<html>
<body style="background-color:powderblue; font-family: Arial, sans-serif;">

<!DOCTYPE html>
<html>
<body style="background-color:powderblue; font-family: Arial, sans-serif;">

<h1>Remaining Engineering Blogs:</h1>

<table border="1" cellpadding="10" cellspacing="0" style="border-collapse: collapse; width: 100%;">
  <caption><strong>Additional Engineering Blogs</strong></caption>
  <tr>
    <th>No</th>
    <th>Notes</th>
    <th>Link</th>
  </tr>
  <tr>
    <td>1</td>
    <td>Remaining 25 Blogs</td>
    <td><a href="https://lnkd.in/ekhdFT3t" target="_blank">https://lnkd.in/ekhdFT3t</a></td>
  </tr>
</table>

</body>
</html>


<h1>75 Engineering Blogs Worth Reading to Improve Your System Design:</h1>

<table border="1" cellpadding="10" cellspacing="0" style="border-collapse: collapse; width: 100%;">
  <caption><strong>Engineering Blogs</strong></caption>
  <tr>
    <th>No</th>
    <th>Blog Name</th>
    <th>Link</th>
  </tr>
  <tr><td>1</td><td>Red Hat Developers</td><td><a href="https://developers.redhat.com/" target="_blank">https://developers.redhat.com/</a></td></tr>
  <tr><td>2</td><td>High Scalability</td><td><a href="https://lnkd.in/eQ4eDw4E" target="_blank">https://lnkd.in/eQ4eDw4E</a></td></tr>
  <tr><td>3</td><td>Engineering at Meta</td><td><a href="https://lnkd.in/e8tiSkEv" target="_blank">https://lnkd.in/e8tiSkEv</a></td></tr>
  <tr><td>4</td><td>AWS Architecture Blog</td><td><a href="https://lnkd.in/eEchKJif" target="_blank">https://lnkd.in/eEchKJif</a></td></tr>
  <tr><td>5</td><td>All Things Distributed</td><td><a href="https://lnkd.in/emXaQDaS" target="_blank">https://lnkd.in/emXaQDaS</a></td></tr>
  <tr><td>6</td><td>Netflix Tech Blog</td><td><a href="https://lnkd.in/efPuR39b" target="_blank">https://lnkd.in/efPuR39b</a></td></tr>
  <tr><td>7</td><td>LinkedIn Engineering Blog</td><td><a href="https://lnkd.in/ehaePQth" target="_blank">https://lnkd.in/ehaePQth</a></td></tr>
  <tr><td>8</td><td>Uber Engineering Blog</td><td><a href="https://eng.uber.com/" target="_blank">https://eng.uber.com/</a></td></tr>
  <tr><td>9</td><td>Engineering at Quora</td><td><a href="https://lnkd.in/em-WkhJd" target="_blank">https://lnkd.in/em-WkhJd</a></td></tr>
  <tr><td>10</td><td>Pinterest Engineering</td><td><a href="https://lnkd.in/esBTntjq" target="_blank">https://lnkd.in/esBTntjq</a></td></tr>
  <tr><td>11</td><td>Lyft Engineering Blog</td><td><a href="https://eng.lyft.com/" target="_blank">https://eng.lyft.com/</a></td></tr>
  <tr><td>12</td><td>Twitter Engineering Blog</td><td><a href="https://lnkd.in/evMFNhEs" target="_blank">https://lnkd.in/evMFNhEs</a></td></tr>
  <tr><td>13</td><td>Dropbox Engineering Blog</td><td><a href="https://dropbox.tech/" target="_blank">https://dropbox.tech/</a></td></tr>
  <tr><td>14</td><td>Spotify Engineering</td><td><a href="https://lnkd.in/eJerVRQM" target="_blank">https://lnkd.in/eJerVRQM</a></td></tr>
  <tr><td>15</td><td>GitHub Engineering</td><td><a href="https://lnkd.in/eCADWt8x" target="_blank">https://lnkd.in/eCADWt8x</a></td></tr>
  <tr><td>16</td><td>Instagram Engineering</td><td><a href="https://lnkd.in/e7Gag8m5" target="_blank">https://lnkd.in/e7Gag8m5</a></td></tr>
  <tr><td>17</td><td>Canva Engineering Blog</td><td><a href="https://canvatechblog.com/" target="_blank">https://canvatechblog.com/</a></td></tr>
  <tr><td>18</td><td>Etsy Engineering</td><td><a href="https://lnkd.in/eddzzKRt" target="_blank">https://lnkd.in/eddzzKRt</a></td></tr>
  <tr><td>19</td><td>Booking.com Tech Blog</td><td><a href="https://blog.booking.com/" target="_blank">https://blog.booking.com/</a></td></tr>
  <tr><td>20</td><td>Expedia Technology</td><td><a href="https://lnkd.in/ehjuBE5J" target="_blank">https://lnkd.in/ehjuBE5J</a></td></tr>
  <tr><td>21</td><td>Airbnb Tech Blog</td><td><a href="https://lnkd.in/emGrJbGM" target="_blank">https://lnkd.in/emGrJbGM</a></td></tr>
  <tr><td>22</td><td>Stripe Engineering Blog</td><td><a href="https://lnkd.in/em6Svgyx" target="_blank">https://lnkd.in/em6Svgyx</a></td></tr>
  <tr><td>23</td><td>Ebay Tech Blog</td><td><a href="https://tech.ebayinc.com/" target="_blank">https://tech.ebayinc.com/</a></td></tr>
  <tr><td>24</td><td>Flickr's Tech Blog</td><td><a href="https://code.flickr.net/" target="_blank">https://code.flickr.net/</a></td></tr>
  <tr><td>25</td><td>Hubspot Product and Engineering Blog</td><td><a href="https://lnkd.in/eRGZkBd4" target="_blank">https://lnkd.in/eRGZkBd4</a></td></tr>
  <tr><td>26</td><td>Zynga Engineering</td><td><a href="https://lnkd.in/eex5Ddry" target="_blank">https://lnkd.in/eex5Ddry</a></td></tr>
  <tr><td>27</td><td>Yelp Engineering Blog</td><td><a href="https://lnkd.in/epgBW_4J" target="_blank">https://lnkd.in/epgBW_4J</a></td></tr>
  <tr><td>28</td><td>Heroku Engineering Blog</td><td><a href="https://lnkd.in/evgctQjh" target="_blank">https://lnkd.in/evgctQjh</a></td></tr>
  <tr><td>29</td><td>Discord Engineering and Design</td><td><a href="https://lnkd.in/evY4gpUA" target="_blank">https://lnkd.in/evY4gpUA</a></td></tr>
  <tr><td>30</td><td>Zomato</td><td><a href="https://lnkd.in/e9gf3APD" target="_blank">https://lnkd.in/e9gf3APD</a></td></tr>
  <tr><td>31</td><td>Hotstar</td><td><a href="https://blog.hotstar.com/" target="_blank">https://blog.hotstar.com/</a></td></tr>
  <tr><td>32</td><td>Swiggy</td><td><a href="https://bytes.swiggy.com/" target="_blank">https://bytes.swiggy.com/</a></td></tr>
  <tr><td>33</td><td>Acast Tech</td><td><a href="https://lnkd.in/esuCEYZb" target="_blank">https://lnkd.in/esuCEYZb</a></td></tr>
  <tr><td>34</td><td>ASOS Tech Blog</td><td><a href="https://lnkd.in/esXfdv3G" target="_blank">https://lnkd.in/esXfdv3G</a></td></tr>
  <tr><td>35</td><td>Shopify Engineering</td><td><a href="https://lnkd.in/evvnqQTj" target="_blank">https://lnkd.in/evvnqQTj</a></td></tr>
  <tr><td>36</td><td>Microsoft Tech Blogs</td><td><a href="https://lnkd.in/etw_7_bN" target="_blank">https://lnkd.in/etw_7_bN</a></td></tr>
  <tr><td>37</td><td>Engineering at Microsoft</td><td><a href="https://lnkd.in/eEKz4ECi" target="_blank">https://lnkd.in/eEKz4ECi</a></td></tr>
  <tr><td>38</td><td>MongoDB Engineering Blog</td><td><a href="https://lnkd.in/e9iaqcmZ" target="_blank">https://lnkd.in/e9iaqcmZ</a></td></tr>
  <tr><td>39</td><td>Slack Engineering</td><td><a href="https://slack.engineering/" target="_blank">https://slack.engineering/</a></td></tr>
  <tr><td>40</td><td>DoorDash Engineering</td><td><a href="https://lnkd.in/ep5raBZv" target="_blank">https://lnkd.in/ep5raBZv</a></td></tr>
  <tr><td>41</td><td>Akamai</td><td><a href="https://lnkd.in/ey_dtA7C" target="_blank">https://lnkd.in/ey_dtA7C</a></td></tr>
  <tr><td>42</td><td>Expedia Technology</td><td><a href="https://lnkd.in/ehjuBE5J" target="_blank">https://lnkd.in/ehjuBE5J</a></td></tr>
  <tr><td>43</td><td>Reddit Engineering</td><td><a href="https://lnkd.in/e4E_XzaX" target="_blank">https://lnkd.in/e4E_XzaX</a></td></tr>
  <tr><td>44</td><td>Snap Engineering</td><td><a href="https://eng.snap.com/blog" target="_blank">https://eng.snap.com/blog</a></td></tr>
  <tr><td>45</td><td>CloudFlare</td><td><a href="https://lnkd.in/exEsYAx5" target="_blank">https://lnkd.in/exEsYAx5</a></td></tr>
  <tr><td>46</td><td>Engineering at Depop</td><td><a href="https://lnkd.in/eGjRYcFd" target="_blank">https://lnkd.in/eGjRYcFd</a></td></tr>
  <tr><td>47</td><td>SourceDiving (Cookpad's Engineering Blog)</td><td><a href="https://sourcediving.com/" target="_blank">https://sourcediving.com/</a></td></tr>
  <tr><td>48</td><td>Auto Trader Engineering Blog</td><td><a href="https://lnkd.in/eGDKA_g3" target="_blank">https://lnkd.in/eGDKA_g3</a></td></tr>
  <tr><td>49</td><td>Indeed Engineering Blog</td><td><a href="https://lnkd.in/ecFS87Dt" target="_blank">https://lnkd.in/ecFS87Dt</a></td></tr>
  <tr><td>50</td><td>Gusto Engineering Blog</td><td><a href="https://lnkd.in/e7yVxDKs" target="_blank">https://lnkd.in/e7yVxDKs</a></td></tr>
  <tr><td>51</td><td>Engineering at Birdie</td><td><a href="https://lnkd.in/eUqJTpje" target="_blank">https://lnkd.in/eUqJTpje</a></td></tr>
</table>

</body>
</html>

<!DOCTYPE html>
<html>
<body>

<h1>Compilation Credits: John Crickett</h1>

<table>
    <caption>Engineering Blogs</caption>
    <tr>
        <th>No</th>
        <th>Title</th>
        <th>Link</th>
    </tr>
    <tr><td>1</td><td>AWS Architecture</td><td><a href="https://lnkd.in/eEchKJif">https://lnkd.in/eEchKJif</a></td></tr>
    <tr><td>2</td><td>All Things Distributed</td><td><a href="https://lnkd.in/emXaQDaS">https://lnkd.in/emXaQDaS</a></td></tr>
    <tr><td>3</td><td>Microsoft Tech</td><td><a href="https://lnkd.in/etw_7_bN">https://lnkd.in/etw_7_bN</a></td></tr>
    <tr><td>4</td><td>Engineering at Microsoft</td><td><a href="https://lnkd.in/eEKz4ECi">https://lnkd.in/eEKz4ECi</a></td></tr>
    <tr><td>5</td><td>Meta</td><td><a href="https://lnkd.in/e8tiSkEv">https://lnkd.in/e8tiSkEv</a></td></tr>
    <tr><td>6</td><td>Netflix Tech</td><td><a href="https://lnkd.in/efPuR39b">https://lnkd.in/efPuR39b</a></td></tr>
    <tr><td>7</td><td>LinkedIn Engineering</td><td><a href="https://lnkd.in/ehaePQth">https://lnkd.in/ehaePQth</a></td></tr>
    <tr><td>8</td><td>Uber Engineering</td><td><a href="https://eng.uber.com/">https://eng.uber.com/</a></td></tr>
    <tr><td>9</td><td>Engineering at Quora</td><td><a href="https://lnkd.in/em-WkhJd">https://lnkd.in/em-WkhJd</a></td></tr>
    <tr><td>10</td><td>Pinterest Engineering</td><td><a href="https://lnkd.in/esBTntjq">https://lnkd.in/esBTntjq</a></td></tr>
    <tr><td>11</td><td>Lyft Engineering</td><td><a href="https://eng.lyft.com/">https://eng.lyft.com/</a></td></tr>
    <tr><td>12</td><td>Twitter Engineering</td><td><a href="https://lnkd.in/evMFNhEs">https://lnkd.in/evMFNhEs</a></td></tr>
    <tr><td>13</td><td>Dropbox Engineering</td><td><a href="https://dropbox.tech/">https://dropbox.tech/</a></td></tr>
    <tr><td>14</td><td>Spotify Engineering</td><td><a href="https://lnkd.in/eJerVRQM">https://lnkd.in/eJerVRQM</a></td></tr>
    <tr><td>15</td><td>Github Engineering</td><td><a href="https://lnkd.in/eCADWt8x">https://lnkd.in/eCADWt8x</a></td></tr>
    <tr><td>16</td><td>Instagram Engineering</td><td><a href="https://lnkd.in/e7Gag8m5">https://lnkd.in/e7Gag8m5</a></td></tr>
    <tr><td>17</td><td>Canva Engineering</td><td><a href="https://canvatechblog.com/">https://canvatechblog.com/</a></td></tr>
    <tr><td>18</td><td>Etsy Engineering</td><td><a href="https://lnkd.in/eddzzKRt">https://lnkd.in/eddzzKRt</a></td></tr>
    <tr><td>19</td><td>Booking.com Tech</td><td><a href="https://blog.booking.com/">https://blog.booking.com/</a></td></tr>
    <tr><td>20</td><td>Expedia Technology</td><td><a href="https://lnkd.in/ehjuBE5J">https://lnkd.in/ehjuBE5J</a></td></tr>
    <tr><td>21</td><td>The Airbnb Tech</td><td><a href="https://lnkd.in/emGrJbGM">https://lnkd.in/emGrJbGM</a></td></tr>
    <tr><td>22</td><td>Stripe Engineering</td><td><a href="https://lnkd.in/em6Svgyx">https://lnkd.in/em6Svgyx</a></td></tr>
    <tr><td>23</td><td>Ebay Tech</td><td><a href="https://tech.ebayinc.com/">https://tech.ebayinc.com/</a></td></tr>
    <tr><td>24</td><td>Flickr's Tech</td><td><a href="https://code.flickr.net/">https://code.flickr.net/</a></td></tr>
    <tr><td>25</td><td>Hubspot Product and Engineering</td><td><a href="https://lnkd.in/eRGZkBd4">https://lnkd.in/eRGZkBd4</a></td></tr>
    <!-- Continue listing all other blogs similarly -->
</table>

<table>
    <caption>Basic Engineering Links For Design</caption>
    <tr>
        <th>No</th>
        <th>Title</th>
        <th>Link</th>
    </tr>
    <tr><td>1</td><td>Engineering at Meta</td><td><a href="https://lnkd.in/e8tiSkEv">https://lnkd.in/e8tiSkEv</a></td></tr>
    <tr><td>2</td><td>Google Research</td><td><a href="https://ai.googleblog.com/">https://ai.googleblog.com/</a></td></tr>
    <tr><td>3</td><td>Google Cloud Blog</td><td><a href="https://lnkd.in/enNviCF8">https://lnkd.in/enNviCF8</a></td></tr>
    <tr><td>4</td><td>AWS Architecture Blog</td><td><a href="https://lnkd.in/eEchKJif">https://lnkd.in/eEchKJif</a></td></tr>
    <tr><td>5</td><td>All Things Distributed</td><td><a href="https://lnkd.in/emXaQDaS">https://lnkd.in/emXaQDaS</a></td></tr>
    <!-- Continue listing all other basic engineering links similarly -->
</table>

<table>
    <caption>System Design Links</caption>
    <tr>
        <th>No</th>
        <th>Title</th>
        <th>Link</th>
    </tr>
    <tr><td>1</td><td>Uber</td><td><a href="https://lnkd.in/gASdDKdJ">https://lnkd.in/gASdDKdJ</a></td></tr>
    <tr><td>2</td><td>Airbnb</td><td><a href="https://lnkd.in/gCHCKZUA">https://lnkd.in/gCHCKZUA</a></td></tr>
    <tr><td>3</td><td>Hotstar</td><td><a href="https://blog.hotstar.com/">https://blog.hotstar.com/</a></td></tr>
    <tr><td>4</td><td>Atlassian</td><td><a href="https://lnkd.in/g6z4Mkmr">https://lnkd.in/g6z4Mkmr</a></td></tr>
    <tr><td>5</td><td>Quora</td><td><a href="https://lnkd.in/gnutuc8C">https://lnkd.in/gnutuc8C</a></td></tr>
    <!-- Continue listing all other system design links similarly -->
</table>

</body>
</html>

<!DOCTYPE html>
<html>
<body>

<table>
    <caption>Scalability Design URLs</caption>
    <tr>
        <th>No</th>
        <th>Title</th>
        <th>Link</th>
    </tr>
    <tr><td>1</td><td>Uber Time Series DB</td><td><a href="https://lnkd.in/dzpbrmAw">https://lnkd.in/dzpbrmAw</a></td></tr>
    <tr><td>2</td><td>Airbnb Idempotency</td><td><a href="https://lnkd.in/dmnevUzk">https://lnkd.in/dmnevUzk</a></td></tr>
    <tr><td>3</td><td>Facebook Cluster Management</td><td><a href="https://lnkd.in/dyB_rVRU">https://lnkd.in/dyB_rVRU</a></td></tr>
    <tr><td>4</td><td>Google Autopilot - Autoscaling</td><td><a href="https://lnkd.in/dsY3u5VM">https://lnkd.in/dsY3u5VM</a></td></tr>
    <tr><td>5</td><td>Netflix Workflow Orchestration</td><td><a href="https://lnkd.in/dZcfsTxZ">https://lnkd.in/dZcfsTxZ</a></td></tr>
    <tr><td>6</td><td>Opensource Workflow Management</td><td><a href="https://lnkd.in/d3RqkjDq">https://lnkd.in/d3RqkjDq</a></td></tr>
    <tr><td>7</td><td>Facebook Video Broadcasting</td><td><a href="https://lnkd.in/dvnXntNF">https://lnkd.in/dvnXntNF</a></td></tr>
    <tr><td>8</td><td>LinkedIn Brooklin - Real time data streaming</td><td><a href="https://lnkd.in/dfbFcB2r">https://lnkd.in/dfbFcB2r</a></td></tr>
    <tr><td>9</td><td>Amazon S3 Performance hacks</td><td><a href="https://lnkd.in/dFgxQifh">https://lnkd.in/dFgxQifh</a></td></tr>
    <tr><td>10</td><td>Amazon S3 object expiration</td><td><a href="https://lnkd.in/ddb5RPgg">https://lnkd.in/ddb5RPgg</a></td></tr>
    <tr><td>11</td><td>Circuit Breaker Algorithm</td><td><a href="https://lnkd.in/dtMAgFgN">https://lnkd.in/dtMAgFgN</a></td></tr>
    <tr><td>12</td><td>Caching strategies at Twitter</td><td><a href="https://lnkd.in/dUAque7i">https://lnkd.in/dUAque7i</a></td></tr>
    <tr><td>13</td><td>Improving Multi-CDN Delivery on Netflix</td><td><a href="https://lnkd.in/dSBVbBMz">https://lnkd.in/dSBVbBMz</a></td></tr>
    <tr><td>14</td><td>Amazon Physalia - Millions of tiny databases</td><td><a href="https://lnkd.in/dbaUXqcy">https://lnkd.in/dbaUXqcy</a></td></tr>
    <tr><td>15</td><td>Airbnb Microservice Architecture</td><td><a href="https://lnkd.in/duzNCmqw">https://lnkd.in/duzNCmqw</a></td></tr>
    <tr><td>16</td><td>Evolution of the Netflix API Architecture</td><td><a href="https://lnkd.in/dKgZnWsD">https://lnkd.in/dKgZnWsD</a></td></tr>
    <tr><td>17</td><td>How Zapier Automates Billions of Tasks</td><td><a href="https://lnkd.in/d74kktbV">https://lnkd.in/d74kktbV</a></td></tr>
    <tr><td>18</td><td>How LinkedIn Scaled to 930 Million Users</td><td><a href="https://lnkd.in/dSCZG9bx">https://lnkd.in/dSCZG9bx</a></td></tr>
    <tr><td>19</td><td>How Pinterest scaled to 11 million users with only 6 engineers</td><td><a href="https://lnkd.in/drx93zhb">https://lnkd.in/drx93zhb</a></td></tr>
    <tr><td>20</td><td>How Instagram scaled to 14 million users with only 3 engineers</td><td><a href="https://lnkd.in/dJ54KJne">https://lnkd.in/dJ54KJne</a></td></tr>
    <tr><td>21</td><td>Intro to Change Data Capture</td><td><a href="https://lnkd.in/dsk4gv5d">https://lnkd.in/dsk4gv5d</a></td></tr>
</table>

<table>
    <caption>Doordash</caption>
    <tr>
        <th>Link</th>
    </tr>
    <tr><td><a href="https://doordash.engineering/category/backend/">https://doordash.engineering/category/backend/</a></td></tr>
</table>

</body>
</html>




<h1>Distributed Compting Basics</h1>
<p>https://www.youtube.com/watch?v=UEAMfLPZZhE&list=PLeKd45zvjcDFUEv_ohr_HdUFe97RItdiB</p>
<p>https://www.cl.cam.ac.uk/teaching/2122/ConcDisSys/dist-sys-notes.pdf</p>
<p>https://www.cl.cam.ac.uk/teaching/2021/ConcDisSys/dist-sys-slides.pdf</p>





<h1>System design resources</h1>

<p>1. System Design Concepts : https://lnkd.in/gmhYfk3u</p>

<p>2. HighScalibility Website: https://lnkd.in/g-BGfKRu</p>

<p>3. Hussein Nasser Youtube: https://lnkd.in/gvJ3bjgQ</p>

<p>4. CodeKarle System Design Playlist: https://lnkd.in/g4yacWgy</p>

<p>5. Gaurav Sen's Youtube Channel : https://lnkd.in/gqnCX_bF</p>

<p>6. ByteByteGo Youtube Channel: https://lnkd.in/gtvAtCxR</p>

<p>7. Level Up System Design Survival Guide: https://lnkd.in/gDMiqHN3</p>

<p>8. Azure's Architecture Guide: https://lnkd.in/gyQvqHhc</p>

<p>9. Amazon CTO's website on all things distributed: https://lnkd.in/gz5h_ffY</p>

<p>10. Best Architecture Notes: https://lnkd.in/get4KpZ5</p>

<p>11. System Design Primer on Github: https://lnkd.in/g89Mtjea</p>

<h1>Severless</h1>
<p>https://serverlessland.com/learn</P>

<h1>𝐒𝐲𝐬𝐭𝐞𝐦 𝐃𝐞𝐬𝐢𝐠𝐧 / 𝐇𝐢𝐠𝐡-𝐋𝐞𝐯𝐞𝐥 𝐃𝐞𝐬𝐢𝐠𝐧 𝐈𝐧𝐭𝐞𝐫𝐯𝐢𝐞𝐰</h1>
<p>
<p>👉 Clement Mihailescu #SystemsExpert (https://lnkd.in/d-5mSpfw) videos to know how real-life System Design Interviews go</p>


<p>✅ 𝐀𝐏𝐈 𝐃𝐞𝐬𝐢𝐠𝐧 𝐈𝐧𝐭𝐞𝐫𝐯𝐢𝐞𝐰</p>
<p>👉 Best Practices (https://lnkd.in/d_x39xkK), Implementation (https://lnkd.in/d5fhXZJ7), and Guidelines (https://lnkd.in/dr397Hy2) of API Design</p>
<p>👉 Look for use cases like - Stripe (https://lnkd.in/dsM7PpJt) and Twitter (https://lnkd.in/dxiMu8wr) API Documentation</p>
<p>👉 #SystemsExpert also has a few case studies on API design as well</p>


<h1>Git Hub System Design Links</h1>
<p>https://github.com/InterviewReady/system-design-resources</P>
<p>https://github.com/binhnguyennus/awesome-scalability</P>

<h1>RocksDB:</h1>

<p>https://rockset.com/blog/rocksdb-is-eating-the-database-world/</p>

<h1>𝐇𝐞𝐫𝐞 𝐚𝐫𝐞 𝐚 𝐜𝐮𝐫𝐚𝐭𝐞𝐝 𝐥𝐢𝐬𝐭 𝐨𝐟 𝐆𝐢𝐭𝐇𝐮𝐛 𝐫𝐞𝐩𝐨𝐬𝐢𝐭𝐨𝐫𝐢𝐞𝐬 𝐭𝐡𝐚𝐭 𝐰𝐢𝐥𝐥 𝐫𝐞𝐚𝐥𝐥𝐲 𝐡𝐞𝐥𝐩 𝐲𝐨𝐮 𝐭𝐨 𝐚𝐝𝐯𝐚𝐧𝐜𝐞 𝐲𝐨𝐮𝐫 𝐜𝐚𝐫𝐞𝐞𝐫 𝐢𝐧 𝐒𝐨𝐟𝐭𝐰𝐚𝐫𝐞 𝐄𝐧𝐠𝐢𝐧𝐞𝐞𝐫𝐢𝐧𝐠, 𝐃𝐞𝐯𝐎𝐩𝐬, 𝐒𝐑𝐄 𝐚𝐧𝐝 𝐦𝐨𝐫𝐞! 📚</h1>

<h1>1. A list of programming tutorials in which aspiring software engineers learn how to build an application from scratch.</h1>

<p> https://lnkd.in/enxAaRv4</p>


<h1>4. Learn how to design large-scale systems</h1>

<p>📌  (https://lnkd.in/e4q_gmGK)</p>


<h1>6. A study guide for Software Engineers looking to get better at Data Structures & Algorithms</h1>

<p>📌  (https://lnkd.in/eHfVhAHA)</p>

<h1>7. A collection of (mostly) technical things every developer should aim to know</h1>

<p>📌 (https://lnkd.in/eYvUChpG)</p>


<h1>10. Curated collection of resources for frontend web developers</h1>

<p>📌 (https://lnkd.in/ekShjrRQ)</p>

<h1>11. Learn Software Architecture, Design patterns, DDD, SOLID principles and good software practices</h1>

<p>📌  (https://lnkd.in/eK4vFGf9)</p>

<h1>12. A set of guidelines for best practices, styles and methods for various programming languages.</h1>

<p>📌  (https://lnkd.in/ewc85mED)</p>


<p>https://github.com/karanpratapsingh/system-design#next-steps</p>

<p>https://kps.hashnode.dev/system-design-the-complete-course</p>

<h1>CockroachDB</h1>
<p>https://dl.acm.org/doi/pdf/10.1145/3318464.3386134</p>


<h1>[Bonus] The Log: What every software engineer should know about real-time data's unifying abstraction</h1>
<p>https://lnkd.in/grgZ8yZY</p>

<p>https://khalilstemmler.com/articles/software-design-architecture/full-stack-software-design/</p>

<p>https://khalilstemmler.com/letters/3-steps-to-solve-most-design-problems/</p>

<h1>"How we store and process millions of orders daily at #grab"</h1>
<p>Grab : https://engineering.grab.com/how-we-store-millions-orders</p>

<p>https://github.com/resumejob/system-design-algorithms</p>

<p>https://github.com/jwasham/coding-interview-university</p>

<p>https://github.com/yangshun/tech-interview-handbook</p>

<p>https://github.com/donnemartin/system-design-primer</p>

<p>https://github.com/vasanthk/how-web-works</p>

<p>https://github.com/DopplerHQ/awesome-interview-questions</p>


<p>https://github.com/dennyzhang/cheatsheet.dennyzhang.com</p>

<p>https://get.interviewready.io/blog/interviewready-20-system-design</p>

<p>https://github.com/InterviewReady/system-design-resources</p>

<p>https://github.com/prasadgujar/low-level-design-primer</p>


</body>
</html>
