# cse422-lab-1-solved
**TO GET THIS SOLUTION VISIT:** [CSE422 Lab 1 Solved](https://mantutor.com/product/cse422-solved-3/)


---

**For Custom/Order Solutions:** **Email:** mantutorcodes@gmail.com  

*We deliver quick, professional, and affordable assignment help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;115268&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE422 Lab 1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
PROBLEM SCENARIO CO1

On holiday, a flight currently wants to travel to Bucharest from Arad. But there is no direct way to Bucharest from Arad. However, the cities are connected with each other like a graph. The distance between the connected cities are given. The flight wants to travel through the most optimal way. To find the optimal path to travel, another information is provided: the straight line distance between any city and the final destination (Bucharest).

Now apply A* search to determine the most optimal value for the route Arad to Bucharest and help the flight. You have to use the straight line distance as the heuristic value for the cities.

City Heuristic value City Heuristic value

Arad 366 Mehadia 241

Bucharest 0 Neamt 234

Craiova 160 Oradea 380

Eforie 161 Pitesti 100

Fagaras 176 Rimnicu Vilcea 193

Dobreta 242 Timisoara 329

Hirsova 151 Urziceni 80

lasi 226 Vaslui 199

Lugoj 244 Zerind 374

For simplicity assume these notations

Arad A Neamt F

Bucharest Z Oradea B

Craiova S Pitesti P

Eforie T Rimnicu Vilcea R

Fagaras O Timisoara C

Dobreta V Urziceni D

Hirsova N Vaslui H

lasi Q Zerind E

Lugoj G

Mehadia L

INPUTS

Your txt file should take each node followed by each destination it can reach and their corresponding distance and heuristics. You are to read the file then ask the user to input the starting and the destination point.

OUTPUTS

The output will contain the total distance from the starting point to the destination followed by printing the nodes it followed to calculate the distance.

SAMPLE INPUT

In the text file:

Arad 366 Zerind 75 Sibiu 140 Timisoara 118

Zerind 374 Arad 75 Oradea 71 Oradea 380 Zerind 71 Sibiu 151

… … … … … …

Bucharest 0 Pitesti 101 Fagaras 211 Giurgiu 90 Urziceni 85

Giurgiu 77 Bucharest 90

… … … … … …

The text file is arranged as follows:

Each line starts with a node followed by the heuristic of that node

Then the neighboring nodes and the distance from the parent node is given as a pair All neighboring city-distance pairs are listed after the heuristic.

For example, the text file starts with Arad which has a heuristic of 366. It is the parent node to Zerind, Sibiu and Timisoara which are 75, 140 and 118 km away from Arad. Notice that since Bucharest is the End node which is why it has a heuristic of 0.

In console:

Start node: Arad

Destination: Bucharest

Sample output

Path: Arad -&gt; Sibiu -&gt; Rimnicu -&gt; Pitesti -&gt; Bucharest

Total distance: 418 km

If there is no path found from the Start node to the End node, simply print “NO

PATH FOUND”
