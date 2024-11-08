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
<head>
    <title>Key Topics for System Design Preparation</title>
</head>
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




<h1>System Design GIT Pages</h1>

<p>- https://lnkd.in/gqqBreDG</P>

<p>- https://lnkd.in/gmzbeCZe</P>

<p>- https://lnkd.in/gRvCYnga</P>

<p>- https://lnkd.in/gXdGwnaW</P>

<p>- https://lnkd.in/gv3vkRXV</P>

<p>- https://lnkd.in/gKZv_ijT</P>

<p>https://engineering.fb.com/2022/11/04/video-engineering/instagram-video-processing-encoding-reduction//<p>

<p>https://newsletter.simpleaws.dev/<p1>



<h1>Git Hub System Design Links</h1>
<p>https://github.com/InterviewReady/system-design-resources</P>
<p>https://github.com/binhnguyennus/awesome-scalability</P>
<p>https://github.com/InterviewReady/system-design-resources</p>


<h1>Spotify</h1>

<p>https://www.linkedin.com/pulse/spotify-system-architecture-omar-ismail/</p>


<h1>RocksDB:</h1>

<p>https://rockset.com/blog/rocksdb-is-eating-the-database-world/</p>


<h1>Job Scheduler Design:</h1>
<p>https://medium.com/trendyol-tech/a-distributed-job-scheduler-story-part-ii-b756ffacde63</p>

<p>https://www.linkedin.com/pulse/system-design-distributed-job-scheduler-keep-simple-stupid-ismail/</p>

<p>https://leetcode.com/discuss/general-discussion/1082786/System-Design%3A-Designing-a-distributed-Job-Scheduler-or-Many-interesting-concepts-to-learn</p>

<p>https://dropbox.tech/infrastructure/asynchronous-task-scheduling-at-dropbox</p>

<p>https://engineering.klarna.com/distributed-systems-key-concepts-patterns-d4d5236b9816</p>

<p>https://engineering.klarna.com/automate-resilience-bc0733ac88f4</p>



<p>Airbnb: https://lnkd.in/dAPjjaA3</p>

<p>Amazon: https://lnkd.in/dyp43Yqp</p>

<p>Asana: https://lnkd.in/dWqZxf6Y</p>

<p>Atlassian: https://lnkd.in/d-i34bUQ</p>

<p>BitTorrent, Inc.: https://lnkd.in/dfZPa6Ma</p>

<p>Cloudera: https://blog.cloudera.com</p>

<p>Docker, Inc: https://blog.docker.com</p>

<p>Dropbox: https://lnkd.in/dUQJTxac</p>

<p>eBay: https://lnkd.in/dnmca2uT</p>

<p>Meta: https://lnkd.in/dbwkUDjN</p>

<p>GitHub: https://lnkd.in/dSC9StzD</p>

<p>Google: https://lnkd.in/ddPVy6Zj</p>

<p>Groupon: https://lnkd.in/dsyGvUWF</p>

<p>Highscalability: http://highscalability.com</p>

<p>Instacart: https://tech.instacart.com</p>

<p>Instagram: https://lnkd.in/dEs6FyGn</p>

<p>LinkedIn: https://lnkd.in/d_yQe9g6</p>

<p>Mixpanel: https://mixpanel.com/blog</p>

<p>Netflix: https://lnkd.in/dKhbQqxd</p>

<p>Nextdoor: https://lnkd.in/dDdGPQgR</p>

<p>PayPal: https://lnkd.in/d9YkeE_h</p>

<p>Pinterest: https://lnkd.in/duz8a8vq</p>

<p>Quora: https://lnkd.in/d-iuzYZq</p>

<p>Reddit, Inc.: https://redditblog.com</p>

<p>Salesforce: https://lnkd.in/dV9unb47</p>

<p>Shopify: https://lnkd.in/dQtK4TME</p>

<p>Slack: https://slack.engineering</p>

<p>SoundCloud: https://lnkd.in/dgWK_v4h</p>

<p>Spotify: https://labs.spotify.com</p>

<p>Stripe: https://lnkd.in/dm-WBTgr</p>

<p>System design primer: https://lnkd.in/dnUnsQE9</p>

<p>Twitter: https://lnkd.in/d9tmm5wj</p>

<p>Thumbtack: https://lnkd.in/d6QTWF_p</p>

<p>Uber: http://eng.uber.com</p>

<p>Yahoo: https://lnkd.in/dKgyhbNE</p>

<p>Yelp: https://lnkd.in/d_6hhMS4</p>

<p>Zoom: https://lnkd.in/dquH3cKY</p>

<h1>Meta Engineering Blog</h1>
<p>https://lnkd.in/gUfytp6i</p>

 <h1>Instagram Engineering Blog</h1>
<p>https://lnkd.in/gauqdrcp</p>

 <h1>Uber Engineering Blog</h1>
<p>https://lnkd.in/gvptWmQT</p>

 <h1>AirBnb Engineering Blog</h1>
<p>https://airbnb.io/</p>

 <h1>Netflix Engineering Blog</h1>
<p>https://lnkd.in/gRb2hkWa</p>

 <h1>Linkedin Engineering Blog</h1>
<p>https://lnkd.in/g5tPjCSC</p>

 <h1>Spotify Engineering Blog</h1>
<p>https://lnkd.in/gh4-PwFa</p>

 <h1>Stripe Engineering Blog</h1>
<p>https://lnkd.in/gzir7EM9</p>

 <h1>Snap Engineering Blog</h1>
<p>https://eng.snap.com/blog</p>

 <h1>Instcart Engineering Blog</h1>
<p>https://lnkd.in/gGykVadC</p>

 <h1>Etsy Engineering Blog</h1>
<p>https://lnkd.in/g6bYuXSd</p>

 <h1>Canva Engineering Blog</h1>
<p>https://canvatechblog.com/</p>

 <h1>Miro Engineering Blog</h1>
<p>https://lnkd.in/gdrCyTrQ</p>

 <h1>Lyft Engineering Blog</h1>
<p>https://eng.lyft.com/</p>

 <h1>Twitter Engineering Blog</h1>
<p>https://lnkd.in/gRNDHNcH</p>

 <h1>Myntra Engineering Blog</h1>
<p>https://tech.myntra.com/</p>

 <h1>Flipkart Engineering Blog</h1>
<p>https://lnkd.in/gukdB3Tz</p>

 <h1>Tinder Engineering Blog</h1>
<p>https://medium.com/tinder</p>

 <h1>Pinterest Engineering Blog</h1>
<p>https://lnkd.in/g7DWBCqn</p>

 <h1>Slack Engineering Blog</h1>
<p>https://slack.engineering/</p>

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


<h1>Important papers</h1>

<h1>Dynamo: Amazon's Highly Available Key-value Store</h1>
<p>https://lnkd.in/</p>

<h1>🔹BigTable</h1>
<p>https://lnkd.in/g7MEFuiY</p>

<h1>🔹Cassandra</h1>
<p>https://lnkd.in/dQ2sFfXT</p>

<h1>🔹Hadoop Distributed File System</h1>
<p>https://lnkd.in/dxRUaNfa</p>

<h1>🔹Google File System</h1>
<p>https://lnkd.in/gvk8eXtm</p>

<h1>🔹Kafka</h1>
<p>https://lnkd.in/gUe-4dn2</p>

<h1>🔹CockroachDB</h1>
<p>https://lnkd.in/gr3NJvJc</p>



<h1>1-Kafka Basics</h1>
<p>❄️ http://bit.ly/3gCdWSe</p>
<p>❄️http://bit.ly/3EWDnpV</p>

<h1>2-Kafka Producer</h1>
<p>❄️ http://bit.ly/3gxgctS</p>

<h1>3-Kafka Stream</h1>
<p>❄️http://bit.ly/3XzJB7i</p>

<h1>4-KSQL</h1>
<p>❄️http://bit.ly/3XAGegr</p>

<h1>5-Kafka Connect</h1>
<p>❄️http://bit.ly/3GKUiyb</p>

<h1>6- Python</h1>
<p>❄️ http://bit.ly/3CoFlhp</p>

<h1>7- Java Basic</h1>
<p>❄️http://bit.ly/3UbVDkl</p>

<h1>8-Docker</h1>
<p>❄️ https://bit.ly/3VlE2rg</p>

<h1>9-ProjectgTadx7kn</h1>
<p>❄️ http://bit.ly/3iezjcR</p>


<p>https://github.com/karanpratapsingh/system-design#next-steps</p>

<p>https://kps.hashnode.dev/system-design-the-complete-course</p>

<p>Airbnb: https://lnkd.in/dC-aHMy2</p>

<p>Atlassian: https://lnkd.in/dgiama9Q</p>

<p>Dropbox: https://dropbox.tech/</p>

<p>Meta: https://lnkd.in/dUpizyy7</p>

<p>GitHub: https://lnkd.in/db3AxDg8</p>

<p>Google: https://lnkd.in/dPhZdkFe</p>

<p>Instagram: https://lnkd.in/dwXUeZg6</p>

<p>Linkedin: https://lnkd.in/djxTkz7v</p>

<p>Netflix: https://lnkd.in/dW9fcqxD</p>

<p>PayPal: https://lnkd.in/dx4w6682</p>

<p>Pinterest: https://lnkd.in/djQzgKRZ</p>

<p>Quora: https://lnkd.in/djUjDjTV</p>

<p>Reddit: https://lnkd.in/d_9zeUtA</p>

<p>Shopify: https://lnkd.in/d2NhrVK3</p>

<p>Slack: https://slack.engineering</p>

<p>Twitter: https://lnkd.in/dFxdurgr</p>

<p>Uber: https://lnkd.in/ds6bpCtj</p>

<p>Yelp: https://lnkd.in/d_kH_tpG</p>

<p>Zoom: https://lnkd.in/d8MRCE43</p>


<h1>Dynamo: Amazon’s Highly Available Key-value Store</h1>
<p>https://lnkd.in/gTadx7kn</p>

<h1>BigTable</h1>
<p>https://lnkd.in/g7MEFuiY</p>

<h1>CockroachDB</h1>
<p>https://lnkd.in/gr3NJvJc</p>

<h1>Kafka</h1>
<p>https://lnkd.in/gUe-4dn2</p>

<h1>Google File System</h1>
<p>https://lnkd.in/gvk8eXtm</p>

<h1>[Bonus] The Log: What every software engineer should know about real-time data's unifying abstraction</h1>
<p>https://lnkd.in/grgZ8yZY</p>

<p>https://khalilstemmler.com/articles/software-design-architecture/full-stack-software-design/</p>

<p>https://khalilstemmler.com/letters/3-steps-to-solve-most-design-problems/</p>


<p>https://github.com/stemmlerjs</p>

<h1>"How we store and process millions of orders daily at #grab"</h1>
<p>Grab : https://engineering.grab.com/how-we-store-millions-orders</p>


<p>https://github.com/resumejob/system-design-algorithms</p>

<p>https://sre.google/</p>

<p>https://netflixtechblog.com/</p>

<p>https://medium.com/airbnb-engineering</p>

<p>https://slack.engineering/</p>

<p>https://www.uber.com/en-IN/blog/bangalore/engineering/</p>

<p>https://blog.twitter.com/engineering/en_us</p>




<p>https://github.com/jwasham/coding-interview-university</p>

<p>https://github.com/yangshun/tech-interview-handbook</p>

<p>https://github.com/donnemartin/system-design-primer</p>

<p>https://github.com/vasanthk/how-web-works</p>

<p>https://github.com/DopplerHQ/awesome-interview-questions</p>


<p>https://github.com/dennyzhang/cheatsheet.dennyzhang.com</p>




<p>https://get.interviewready.io/blog/interviewready-20-system-design</p>

<p>https://github.com/InterviewReady/system-design-resources</p>

<p>https://github.com/prasadgujar/low-level-design-primer</p>


<p>https://github.com/InterviewReady/system-design-resources</p>

<p>https://levelup.gitconnected.com/100-essential-systems-design-concepts-that-every-developer-must-know-part-1-1318c2c402ca</p>

<h1>100 Essential Systems Design Concepts That Every Developer Must Know (Part 1: 1–10) :</h1>

<p>https://levelup.gitconnected.com/100-essential-systems-design-concepts-that-every-developer-must-know-part-1-1318c2c402ca</p>

<h1>Top 30 System Design Interview Questions and Problems for Programmers and Software Engineers :</h1>

<p>https://faun.pub/top-30-system-design-interview-questions-and-problems-for-programmers-417e89eadd67</p>

<p>https://github.com/Amanhacker/system-design-resources
https://cheatsheet.dennyzhang.com/cheatsheet-systemdesign-A4</p>


<h1>What are some resources (books, blogs, people, etc) you’ve learned from? Who are your role models in the field?</h1>

<p>General People:</p>

<p>Martin Fowler - A legend in this industry. So much of my early career was influenced by his thinking.</p>
<p>danah boyd - such great insights into the (not always great) impact of technology on people.</p>
<p>Brett Victor - I sometimes feel like he has been given a gift from the future and we are just finding out about it now.</p>
<p>Randall Monroe - He has such a gift for making the (highly technical) absurdities of our world so easy to laugh at.</p>
<p>Neal Ford (from thoughtworks) - Truly excellent communicator. He inspired me to learn how to give a better tech talk.</p>
<p>Venkat Subramaniam (from Agile Developer) - Similar to Neal, Venkat has such energy and a passion for his craft.
Books:</p>

<p>The Design of Everyday Things</p>
<p>Clean Code</p>
<p>Growing Object Oriented Software Guided by Tests</p>
<p>The Pragmatic Programmer</p>
<p>Working Effectively with Legacy Code</p>
<p>Refactoring</p>
<p>Object Thinking</p>
<p>Godel, Escher, Bach - This one can be controversial, but it really got me to stretch the way I think about computing and that in itself is worth a lot.</p>
<p>Blogs/Podcasts:</p>

<p>High Scalability</p>
<p>InfoQ (used to have a ton of great videos from so many conferences)</p>
<p>infrequently.org</p>
<p>Stratechery</p>
<p>apenwarr.ca</p>
<p>Thoughtworks Podcast
<p>Googlers who've inspired me:</p>

<p>Robert Konigsberg - Who helped me truly find my voice.</p>
<p>Titus Winters - Who has given me so much support and opportunity over the years.</p>
<p>George Fairbanks - Whose deep thoughts on the craft of software development have caused me to think much more deeply about the work I do.</p>
<p>Michelle Levesque - Who probably doesn’t remember me, but she showed me what authentic and inspired technical leadership can look like.</p>
<

<h1>5 papers that every senior backend engineer should read.</h1>

<h1>Harvest, Yield and Scalable Tolerant Systems - </h1>
<p>https://lnkd.in/gX_Up2p4</p>

<h1>On Designing and Deploying Internet Scale Services - </h1>
<p>https://lnkd.in/gA5mgzXv</p>

<h1>Data on the Outside versus Data on the Inside - </h1>
<p>https://lnkd.in/g5HU9cAC</p>

<h1>Building on Quicksand - </h1>
<p>https://lnkd.in/gmWnJBVX</p>

<h1>A Note on Distributed Computing - </h1>
<p>https://lnkd.in/gxEkVgDC</p>

</body>
</html>
