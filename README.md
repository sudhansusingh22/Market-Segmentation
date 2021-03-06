# Community Detection( Market Segmentation)
Find market segments in social network data of Facebook users.

## Objective:
* Data consisted of users as nodes and their relationship between friends as their edges. 
* The algorithm detected communities in attributed graph data based on the structural, demographic (age, sex, ethnicity, education) and attribute similarities using Python's iGraph module. 
* The found segments were evaluated via influence propagation. 
* In influence propagation an entity in the segment is influenced and how fast the influence propagates over the entire network is evaluated. 
* The faster the influence propagates, the better is the segment.

## Data sets:
http://masonporter.blogspot.in/2011/02/facebook100-data-set.html

## Requirements:
* igraph : http://igraph.org/
* scipy

## Steps to Run:
* Load Facebook data and find market segments:
```python
python marketSegment.py
```
* Evaluate the results:
```R
evaluation.R
```
## Results:
Node Ids grouped together:
 ```
 4,29,5,67,6,24,10,47,12,108
8,18,9,51,91
20,79,34,244
7,210,13,96,15,19,37,16,98,21,135,22,161,35,66,75,103,94,181,107,178,119,136,193,182,184
50,145,113,125,162,254
11,117,38,42,90,52,57,86,298,93,191,112,203,118,241,163,185,165,189,199,218
74,128,155,206,235,231,290
54
242
71,78,84,238,101,138,123,253,126,153,134,177,169,221,292,217,277,293,257,320
17,168,25,70,32,269,36,110,65,176,77,133,150,234,95,106,237,124,140,141,187,146,166,208,256,317,252,266,267
1,73,28,44,33,68,43,152,59,62,61,64,76,160,89,211,100,154,105,281,120,147,158,130,207,139,183,173,236,202,229,274,308,310,280,300
41,296,48,179,49,248,72,157,97,129,225,121,261,306,151,200,196,313,198,276,215,224,222,243,263,275,272,304,278,312,314,283,318,321
2,180,14,197,26,63,31,60,39,56,40,83,46,109,58,137,111,170,114,131,149,240,156,295,172,294,305,174,307,311,186,227,259,232,303,273,319
27,88,30,55,45,205,80,171,271,81,247,99,175,104,115,122,142,164,245,192,230,194,315,323,219,285,220,239,264,223,284,228,255,291,251,301,309,270,287,297,316
0,167,3,23,53,250,268,69,159,82,85,262,87,204,209,92,216,102,116,127,144,132,143,249,148,265,188,212,190,213,195,226,258,201,279,214,282,289,233,260,246,288,286,299,302,322
```
