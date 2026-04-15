<!DOCTYPE html>
<html>
<head>
  <title>Graph Editor</title>
  <script src="https://unpkg.com/vis-network/standalone/umd/vis-network.min.js"></script>
  <style>
    body { font-family: Arial; }
    #mynetwork {
      width: 100%;
      height: 500px;
      border: 1px solid gray;
      margin-top: 10px;
    }
    textarea {
      width: 300px;
      height: 120px;
    }
  </style>
</head>
<body>

<h2>Graph Editor (tự chỉnh vị trí)</h2>

<p>Nhập đỉnh (id x y):</p>
<textarea id="nodesInput">
1 0 0
2 200 0
3 100 150
</textarea>

<p>Nhập cạnh (u v):</p>
<textarea id="edgesInput">
1 2
2 3
1 3
</textarea>

<br><br>
<button onclick="drawGraph()">Vẽ đồ thị</button>
<button onclick="savePositions()">Lưu vị trí</button>

<div id="mynetwork"></div>

<script>
let network;

function drawGraph() {
    let nodeLines = document.getElementById("nodesInput").value.trim().split("\n");
    let edgeLines = document.getElementById("edgesInput").value.trim().split("\n");

    let nodes = [];
    let edges = [];

    // parse nodes
    nodeLines.forEach(line => {
        let [id, x, y] = line.split(" ").map(Number);
        nodes.push({
            id: id,
            label: id.toString(),
            x: x,
            y: y,
            fixed: false
        });
    });

    // parse edges
    edgeLines.forEach(line => {
        let [u, v] = line.split(" ").map(Number);
        edges.push({ from: u, to: v });
    });

    let container = document.getElementById("mynetwork");

    let data = {
        nodes: new vis.DataSet(nodes),
        edges: new vis.DataSet(edges)
    };

    let options = {
        physics: false // 🔥 giữ nguyên vị trí
    };

    network = new vis.Network(container, data, options);
}

// lưu vị trí sau khi kéo
function savePositions() {
    let positions = network.getPositions();
    let result = "";

    for (let id in positions) {
        let pos = positions[id];
        result += id + " " + Math.round(pos.x) + " " + Math.round(pos.y) + "\n";
    }

    alert("Copy vị trí:\n\n" + result);
}
</script>

</body>
</html>
