<h1>FERC Order No. 2222</h1>

<h2>Background</h2>

<p>
    On September 17, 2020, the Federal Energy Regulatory Commision (FERC) issued order No. 2222. This policy removed the cost barriers that were limiting distributed energy resources (DERs), allowing them to compete alongside traditional electricity resources. 
</p>

<p>
    DERs are small-scale power generation or energy storage technologies used locally. Some examples of DERs are rooftop solar panels, biomass generators, fuel cells, and electric vehicles. With Order No. 2222, these technologies will be more easily obtainable by the average citizen; this allows the power grid becomes more flexible and resiliant since there is less reliance on centralized power generation sites. 
</p>

<p>
    This case study demonstrates the impacts of FERC Order No. 2222 through two scenarios, one representing the system before Order No. 2222 was issued and the other representing the system after. For both cases, we used a biogas supply chain (shown below) that uses raw cattle manure to generate electricity. The power generation technology represents the DERs, and the Electricity Cost Increase technology is a pseudo technology that simulates the presence of the DER cost barrier by increasing operating costs. 
</p>

<img src="Pictures\biogas_case_study\biogas_p_graph.png">

<p>
    In our system, the supply nodes are CAFOs which supply manure to the technology sites. The technology sites then process the manure into digestate and electricity. In order to simplify the system, we only used data from a small subarea of Wisconsin, and we consolidated the electricity demand into a single point located at Milwaukee, WI; this allows us to greatly reduce the number of nodes, and the solver will then be able to find a solution quickly. 
</p>

<h2>Old Policy</h2>

<p>
    Before FERC Order No. 2222 was issued, DERs faced an extra cost barrier compared to traditional energy resources. This cost barrier is represented in the model as a pseudo technology which increased the operating cost of the system by $0.10/KWh of Electricity. 
</p>

<p>
    The figure below shows the results of the system as solved by ADAM. All of the manure from the supply nodes are processed into electricity. The electricity goes through the pseudo technology, representing a price increase, and then it is consumed by the Milwaukee demand node. 
</p>

<img src="Pictures\biogas_case_study\results_and_key.png">

<h2>New Policy</h2>

<p>
    For the new policy case, the pseudo technology was removed in order to simulate the cost barrier reduction. On the surface, the product flow results of the new policy appears to be the same as the old policy. However, the quantitative results show that the new policy has lower costs than the old policy.
</p> 

<img src="Pictures\biogas_case_study\chart.png">

<p>
    Both policy scenarios have the same revenue and transportation costs since the Milwaukee demand node remained constant in both systems. However, the Old Policy (blue) has a negative social welfare which can be attributed to the high operating costs of the system. The operating cost alone for the old policy was able to surpass the revenue generated from selling the electricity. This indicates that the cost barriers for installing DERs are too high to be profitable. As a result, many customers are barred from entering the market. On the other hand, the new policy has much lower operating costs, and as a result, generating electricity is profitable (social welfare is positive). Under the new policy, more customers will be willing to install DERs in their homes. 
</p>

<h2>Conclusion</h2>

<p>
    Before FERC Order No. 2222 was issued, the costs of DERs were too high in order to be profitable. As a result, very few people had DERs installed in their homes despite their many benefits. In order to encourage citizens to install DERs, the FERC established Order No. 2222 which removed some of the cost barriers of DERs. 
</p>

<p>
    This case study demonstrated the effects of Order No. 2222 in a small region of Wisconsin. Based on the case study, the impact of Order No. 2222 seems very promising. With a lower cost barrier, more DERs will be installed, and that will contribute to a more distributed and flexible electricity grid. Additionally, a larger proportion of the electricity market will come from sustainable and locally generated energy sources. 
</p>

<p>
    Although these results provides a good start to understanding the impacts of Order No. 2222, there is still much to improve on. The models run in this case study contain many simplifications and assuptions, and thus they do not capture many of the complicated relationship of the real world. In this case study, we only looked at technology sites that were already installed. A possible improvement on this model is adding technology candidates to the system and observe whether Order No. 2222 lowers the cost barrer enough such that the investment cost and the operating cost of the equipment can be overcome. 
</p>