<h1>Plastic Waste</h1>

<h2>Background</h2> 

<p>
    The widespread usage of plastics began only 70 years ago; yet, in that short period, the production of plastic—and plastic waste—has grown at an extraordinary rate. Rather than allowing plastic waste to accumulate in landfills, we can extract valuable products from plastic waste by using a resource-recovery plastic waste management method.
</p>

<p>
    In this case study, we will go over an example plastic waste supply chain for polyethylene terephthalate (PET), a material used in plastic bottles. A p-graph of the supply chain is shown in the image below. First, the PET pellet suppliers send PET pellets to a bottle production technology, which produces empty plastic bottles. The empty bottles are then filled with a beverage at a bottle filling technology. Next, the bottled beverage is purchased and consumed by a customer; the empty bottles are discarded. The discarded bottles go through a Materials Recovery Facility (MRF), which sorts the plastics. Afterwards, the plastics are sent to one of three plastic processing technologies: landfills, WTE, and reclaimer technologies. Landfills are where the plastics are discarded and turned into garbage, Waste to Energy (WTE) technologies convert the plastic into electricity by using heat, and reclaimer technologies recycle the plastic and recover the rPET (recycled PET) pellets. When PET pellets get recycled, the quality of the pellets degrade, and it cannot be used again for plastic bottle production. Instead, rPET pellets are used in clothing application. 
</p>

<img src="Pictures\plastic_waste\p_graph.png" width="1200">

<p>
    We would like to encourage the system to process waste into electricity or to recycle it into PET pellets rather than dumping it into a landfill. In order to do this, we must apply incentives. In this case study, we will try to encourage the recycling of plastic waste by applying rPET incentives at low, market, and high price points. If we increase the price of rPET, we will expect more plastic to be processed into rPET. 
</p>

<p>
    Since the nodes in the model are located at various locations across the USA, it is difficult to visually analyze the results using the full expanded map. Instead, we will be focusing on the southeastern corner of Wisconsin, which is where the bulk of the nodes are concentrated. 
</p>

<img src="Pictures\plastic_waste\expanded_map.png">

<h2>Low rPET Price</h2>

<p>
    In the low rPET price scenario, the price of rPET is lower than normal market price. It is not high enough to overcome the operating costs of the equipment, thus, none of the plastic bottles are recycled into rPET.  
</p>

<img src="Pictures\plastic_waste\low_price.png">

<p>
    The map below emphasizes the locations of the two reclaimer technology sites present in the system. Reclaimer technologies take in sorted, discard bottles (labeled as "Bottle, compated, sorted" in the legend) and produce rPET and residue. Since reclaimers are the only technology in this system which produces rPET, our analysis will mainly be focusing on the pathways coming to and from these technology nodes. In addition to being reclaimer sites, these two nodes are also beverage consumption technology sites, and they demand consumed beverage, electricity, and rPET products. 
</p>

<img src="Pictures\plastic_waste\low_price_1.png">

<p>
    In this scenario, the reclaimer technology nodes are simply acting as beverage consumers: they take in bottled beverages and output empty bottles ("Bottle, compacted"). No rPET pellets are made since there are no sorted bottles ("Bottles, compacted, sorted") going into the reclaimer technology sites.
</p>

<img src="Pictures\plastic_waste\low_price_2.png">

<p>
    The discarded bottles from the reclaimer technologies are sent to Materials Recovery Faciliies (MRF) sites. Afterwards, the bottles can either be landfilled, transformed into energy, or recycled as rPET. As shown by the presence of electricity product flow lines, at a low rPET price, the optimal result is processing the bottles into electricity. 
</p>

<img src="Pictures\plastic_waste\low_price_3.png">

<h2>Market rPET Price</h2>

<p>
    The results of the market price scenario is identical to the low price scnario. This indicates that the price of rPET is still not high enough to overcome the operating costs of the equipment, and the system continues to avoid processing the plastic bottles into rPET in favor of electricity. 
</p>

<img src="Pictures\plastic_waste\market_price.png">

<h2>High rPET Price</h2>

<p>
    In the high rPET price scenario, the price of rPET is set to a value above market price. The results of the model are displayed below. Unlike the low and market price scenarios, the high price scenario does not have any electricity transportation arrows. The products in the system are redirected from making electricity to go towards making rPET, but since the reclaimer technology site is also a demand node for rPET, the rPET product flows are not visible on the map. 
</p>

<img src="Pictures\plastic_waste\high_price.png">

<p> 
    The reclaimer technology sites are also receiving sorted, compacted bottles in addition to the bottled beverages. This indicates that the reclaimer technologies are acting as beverage consumers and as a technology site for processing bottles into rPET. 
</p>

<img src="Pictures\plastic_waste\high_price_1.png">


<h2>Conclusion</h2>

<p>
    Plastic pollution is a decades-old problem that has only been getting worse due to the increased demand for single-use plastics during the COVID-19 pandemic. Besides landfilling the plastic waste, we can also recycle it and recover energy from it. 
</p>

<p>
    In this case study, we applied PET incentives on the system in order to encourage the recycling of plastics. As the price of PET plastics increase, recycling plastic bottles into PET plastics becomes more profitable. Low and market prices are not high enough to overcome the operating cost barriers of the reclaimer technologies. It is only when high incentives are applied that the system begins to utilize the rPET pathway. 
</p>