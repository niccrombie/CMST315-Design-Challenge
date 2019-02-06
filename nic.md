# CMST315-Lab 1
Class: CMST 315<br>
1/31/2019<br>
<b>Names:</b> Matthew Denhom, Nic Crombie, Caroline Reed<br>
<b>Objective:</b><br> The objective of the lab was to create and design a network for a regional Internet Service Provider (ISP) using Variable Length Subnet Masking (VLSM) to meet the needs of 4 clients, and allow for room to grow and expand as an ISP. Given a network address prefix to work with we were to design the optimal network addressing scheme.

<b>Equipment Used:</b><br><br>

Blender (for the diagram) (Matt D.)<br>
Powerpoint <br>
Pencil and Paper <br>

<b>Notes and Observations:</b><br> Given a IP address with a /17 prefix of 206.12.0.0/17 we were left with 15 bits to work with in a network schema. Four companies requested a number of nodes or unique addresses they would need to start their business network.<br>
Total of unique addresses: 32,768.<br><br>
Large Company (Local ISP): 5000 addresses requested.<br>
Medium-Large Company (University): 1500.<br>
Medium Company (Department Store): 200.<br>
Small (real estate office): 50.<br><br>

We started off with disagreements on how far we could stretch the network and how VLSM worked to begin with so we had to do a little research and discovery before we came to a final agreement on how to create a "balanced" network the didn't overcomplicate things. We started off subnetting 3 bits creating 8 /20 addresses. We would further devide these up to meet the needs of the companies. However this would have lead to some companies have little room for growth to expand, and in the case of the large company 2 network addresses.
<br><br>
To simplify our network we eventually landed on subnetting 2 bits, followed by subetting those 4 networks by 2 more bits, and on down till we had a /25 prefix. giving Company A a /19 prefix, B a /21 prefix, C a /23 prefix, D a /25 prefix. compared to the original /20, /21, /24, 26.
<br><br>
<b>Diagrams:</b><br> Diagram was created by Matt. D. using blender. To represent the VLSM scheme visually.
<br><br>
<b>Conclusion:</b><br> We learned more about how we could have done it to be more efficient without giving more then a company requested. That we could have aimed for meeting just over the customers needs and in the future if they needed more we could have assigned them additional addresses in the future to meet their future needs. 
