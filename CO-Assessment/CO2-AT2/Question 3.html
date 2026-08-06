## Routing Protocol Visualization and Analysis

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Routing Protocol Visualization</title>

<style>
body{
    font-family:Arial,sans-serif;
    background:#f4f6f9;
    text-align:center;
    margin:0;
}

header{
    background:#1976d2;
    color:white;
    padding:20px;
}

.container{
    width:90%;
    margin:auto;
}

.buttons{
    margin:20px;
}

button{
    padding:12px 20px;
    margin:10px;
    font-size:16px;
    cursor:pointer;
    border:none;
    border-radius:5px;
    background:#1976d2;
    color:white;
}

button:hover{
    background:#0d47a1;
}

.network{
    display:flex;
    justify-content:center;
    align-items:center;
    margin-top:40px;
}

.node{
    width:60px;
    height:60px;
    border-radius:50%;
    background:#2196f3;
    color:white;
    font-weight:bold;
    line-height:60px;
}

.line{
    width:100px;
    height:5px;
    background:#555;
}

.active{
    background:#4CAF50 !important;
}

.packet{
    width:20px;
    height:20px;
    background:red;
    border-radius:50%;
    position:absolute;
    display:none;
    transition:all 1s linear;
}

#status{
    margin-top:30px;
    font-size:20px;
    font-weight:bold;
    color:#d32f2f;
}

table{
    width:80%;
    margin:40px auto;
    border-collapse:collapse;
}

table,th,td{
    border:1px solid black;
}

th{
    background:#1976d2;
    color:white;
}

th,td{
    padding:12px;
}
</style>

</head>
<body>

<header>
<h1>Routing Protocol Visualization</h1>
<h3>Proactive (OLSR) vs Reactive (AODV)</h3>
</header>

<div class="container">

<div class="buttons">
<button onclick="runOLSR()">Run OLSR</button>
<button onclick="runAODV()">Run AODV</button>
<button onclick="showComparison()">Compare</button>
</div>

<div class="network">

<div class="node" id="n1">A</div>
<div class="line"></div>

<div class="node" id="n2">B</div>
<div class="line"></div>

<div class="node" id="n3">C</div>
<div class="line"></div>

<div class="node" id="n4">D</div>

</div>

<p id="status">Click any protocol to start visualization.</p>

<div id="comparison"></div>

</div>

<script>

function resetNodes(){

document.querySelectorAll(".node").forEach(n=>{
n.classList.remove("active");
});

document.getElementById("comparison").innerHTML="";
}

function highlight(nodes,index,text){

if(index>=nodes.length){
return;
}

document.getElementById(nodes[index]).classList.add("active");

document.getElementById("status").innerHTML=text+" : "+nodes[index].toUpperCase();

setTimeout(function(){

highlight(nodes,index+1,text);

},900);

}

function runOLSR(){

resetNodes();

document.getElementById("status").innerHTML="OLSR : Periodic HELLO Messages";

highlight(["n1","n2","n3","n4"],0,"HELLO");

setTimeout(function(){

document.getElementById("status").innerHTML="Route already available";

},4500);

setTimeout(function(){

document.getElementById("status").innerHTML="Packet sent instantly from A to D";

},6500);

}

function runAODV(){

resetNodes();

document.getElementById("status").innerHTML="Broadcasting Route Request (RREQ)";

highlight(["n1","n2","n3","n4"],0,"RREQ");

setTimeout(function(){

resetNodes();

document.getElementById("status").innerHTML="Returning Route Reply (RREP)";

highlight(["n4","n3","n2","n1"],0,"RREP");

},5000);

setTimeout(function(){

document.getElementById("status").innerHTML="Route established. Data transmission begins.";

},10000);

}

function showComparison(){

document.getElementById("comparison").innerHTML=`

<h2>Protocol Comparison</h2>

<table>

<tr>
<th>Feature</th>
<th>OLSR (Proactive)</th>
<th>AODV (Reactive)</th>
</tr>

<tr>
<td>Route Discovery</td>
<td>Routes maintained continuously</td>
<td>Created only when needed</td>
</tr>

<tr>
<td>Route Maintenance</td>
<td>Periodic HELLO updates</td>
<td>Route Error (RERR) and rediscovery</td>
</tr>

<tr>
<td>Routing Overhead</td>
<td>High</td>
<td>Low</td>
</tr>

<tr>
<td>Communication Delay</td>
<td>Very Low</td>
<td>High during first transmission</td>
</tr>

<tr>
<td>Performance in High Mobility</td>
<td>Moderate</td>
<td>Better</td>
</tr>

<tr>
<td>Best Use Case</td>
<td>Stable Networks</td>
<td>Highly Mobile Networks</td>
</tr>

</table>

`;

}

</script>

</body>
</html>
