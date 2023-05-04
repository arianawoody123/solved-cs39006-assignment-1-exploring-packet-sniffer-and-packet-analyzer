Download Link: https://assignmentchef.com/product/solved-cs39006-assignment-1-exploring-packet-sniffer-and-packet-analyzer
<br>
Execute the following steps.

<ul>

 <li>Ensure that no browsing activity is going on in your machine. Close all the browser tabs.</li>

 <li>Download and run Wireshark.</li>

 <li>Start capturing packets over your default (active) network interface. 4) Open a browser tab and open the website <a href="http://iitkgp.ac.in/">http://iitkgp.ac.in</a><u>​           </u><a href="http://iitkgp.ac.in/">/</a>.​  5) Wait for 2 minutes.</li>

</ul>

6) Now on the same browser tab, open the website <a href="https://www.cornell.edu/">https://www.cornell.edu</a>​      <a href="https://www.cornell.edu/">/</a>.​  7) Close the browser tabs.

<ul>

 <li>Stop packet capture.</li>

 <li>Save the pcap file from Wireshark.</li>

</ul>

Now answer the following questions by analyzing the packet traces.

<ol>

 <li>What are the different protocols you observe at the following layers of the protocol stack?

  <ol>

   <li>Application layer</li>

   <li>Transport layer</li>

   <li>Network layer</li>

  </ol></li>

 <li>What is the total amount of data being received for the following two cases?

  <ol>

   <li>When you access <a href="http://iitkgp.ac.in/">http://iitkgp.ac.i</a>​ <a href="http://iitkgp.ac.in/">n</a></li>

   <li>When you access <a href="https://www.cornell.edu/">https://www.cornell.ed</a>​ <a href="https://www.cornell.edu/">u</a></li>

  </ol></li>

 <li>How many DNS packets have you observed in total?

  <ol>

   <li>Create a &lt;Domain Name, IP&gt; table by exploring the queries and the answers in those DNS packets. The Domain Name will be the domain for which you see a query, and the IP address will be the address that is being returned against the corresponding query.</li>

   <li>Can you find out the IP of the DNS servers by exploring the DNS packets?</li>

  </ol></li>

 <li>Answer the following when you access the site <a href="http://iitkgp.ac.in/">http://iitkgp.ac.i</a><u>​ </u><a href="http://iitkgp.ac.in/">n</a>.​

  <ol>

   <li>How many HTTP GET requests do you observe? List down the GET requests.</li>

   <li>For each of the HTTP GET requests as you see above, find out (ii) the total number of TCP segments being received, and (ii) the total amount of data being received in the corresponding HTTP Response message.</li>

  </ol></li>

</ol>

=====================================

Assignment 1 Submission

Name: &lt;Your_Name&gt;

Roll number: &lt;Your_Roll_Number&gt;

Link of the pcap file: &lt;Google_Drive_Link_of_the_pcap_File&gt;

=====================================

You should put the header at the beginning, and then type the answers to the above questions. Submit the doc file through Moodle by the deadline.