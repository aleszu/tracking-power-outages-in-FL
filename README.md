# Tracking power outages in Florida via FPL

Power outages tracker in Florida Power &amp; Light Company using Github Actions triggered every 20 minutes.

This tracker uses the JSON feed (https://www.fplmaps.com/customer/outage/CountyOutages.json) intercepted from [this website](https://www.fplmaps.com/index.html).

|	COUNTY 	|	OUT	|	RESTORED	|	AFFECTED	|	TOTAL SERVED	|
|	---	|	---	|	---	|	---	|	---	|
|	Alachua	|	0	|		|		|	1,267	|
|	Baker	|	1	|		|		|	5,651	|
|	Bradford	|	0	|		|		|	4,200	|
|	Brevard	|	670	|	370	|	1,040	|	330,380	|
|	Broward	|	5,250	|	36,240	|	41,490	|	963,570	|
|	Charlotte	|	3,560	|	620	|	4,180	|	126,690	|
|	Clay	|	0	|		|		|	955	|
|	Collier	|	8,090	|	7,630	|	15,720	|	228,540	|
|	Columbia	|	1	|		|		|	14,674	|
|	De Soto	|	130	|	20	|	150	|	17,710	|
|	Duval	|	0	|		|		|	10	|
|	Flagler	|	2	|		|		|	67,703	|
|	Glades	|	0	|	350	|	350	|	3,640	|
|	Hardee	|	0	|	0	|	0	|	30	|
|	Hendry	|	0	|	3,140	|	3,140	|	11,020	|
|	Highlands	|	0	|	0	|	0	|	550	|
|	Indian River	|	220	|	1,410	|	1,630	|	99,250	|
|	Lee	|	1,960	|	5,120	|	7,080	|	288,630	|
|	Manatee	|	540	|	2,640	|	3,180	|	198,710	|
|	Martin	|	360	|	940	|	1,300	|	94,710	|
|	Miami-Dade	|	18,560	|	43,080	|	61,640	|	1,180,070	|
|	Monroe	|	0	|		|		|	96	|
|	Nassau	|	0	|		|		|	27,135	|
|	Okeechobee	|	0	|	120	|	120	|	20,480	|
|	Orange	|	0	|		|		|	3	|
|	Osceola	|	0	|		|		|	3	|
|	Palm Beach	|	9,250	|	19,900	|	29,150	|	766,020	|
|	Putnam	|	12	|		|		|	20,705	|
|	Sarasota	|	13,000	|	380	|	13,380	|	287,120	|
|	Seminole	|	0	|		|		|	60,171	|
|	St Johns	|	13	|		|		|	108,681	|
|	St Lucie	|	170	|	540	|	710	|	145,010	|
|	Suwannee	|	0	|		|		|	5,176	|
|	Union	|	0	|		|		|	1,681	|
|	Volusia	|	9	|		|		|	192,286	|
|	Total	|	61,798	|	122,500	|	184,260	|	5,272,527	|![image](https://user-images.githubusercontent.com/6544861/192832014-2e360e33-d8b1-4e78-b306-9cbef2002988.png)
