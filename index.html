<!DOCTYPE html>

<html>

<head>

 <style>

   body { margin:0; background:#fff8f0; font-family:sans-serif; padding:10px; }

   .comic { display:grid; grid-template-columns:1fr 1fr; gap:8px; }

   .panel {

     background:white; border:3px solid black; border-radius:8px;

     padding:15px; font-size:13px; font-weight:bold;

     min-height:100px; display:flex; align-items:center;

     justify-content:center; text-align:center;

     position:relative;

   }

   .panel-num {

     position:absolute; top:5px; left:8px;

     font-size:10px; color:#aaa;

   }

   h3 { text-align:center; color:#e07; }

   #status { text-align:center; color:#999; font-size:13px; }

 </style>

</head>

<body>

 <p id="status">⏳ Writing your comic story...</p>

 <h3 id="title"></h3>

 <div class="comic" id="comic" style="display:none">

   <div class="panel"><span class="panel-num">1</span><span id="p1"></span></div>

   <div class="panel"><span class="panel-num">2</span><span id="p2"></span></div>

   <div class="panel"><span class="panel-num">3</span><span id="p3"></span></div>

   <div class="panel"><span class="panel-num">4</span><span id="p4"></span></div>

 </div>



 <script>

   fetch("https://api.cohere.ai/v1/chat", {

     method: "POST",

     headers: {

       "Authorization": "Bearer IqxOkTqSjoZc0jkeViZEvFaPg8crJEyqrdvS0r7Q",

       "Content-Type": "application/json"

     },

     body: JSON.stringify({

       model: "command-r-plus-08-2024",

       message: "Write a 4-panel comic strip for children aged 7-16 about friendship, family or school. Include a conflict and a kind resolution. Use human character names only (no animals). Reply in EXACTLY this format, nothing else:\\nTITLE: [title]\\nP1: [one short sentence]\\nP2: [one short sentence]\\nP3: [one short sentence]\\nP4: [one short sentence]"

     })

   })

   .then(r => r.json())

   .then(data => {

     const lines = data.text.split("\\n");

     document.getElementById("title").textContent = lines[0].replace("TITLE:","").trim();

     document.getElementById("p1").textContent = lines[1].replace("P1:","").trim();

     document.getElementById("p2").textContent = lines[2].replace("P2:","").trim();

     document.getElementById("p3").textContent = lines[3].replace("P3:","").trim();

     document.getElementById("p4").textContent = lines[4].replace("P4:","").trim();

     document.getElementById("comic").style.display = "grid";

     document.getElementById("status").textContent = "";

   })

   .catch(err => {

     document.getElementById("status").textContent = "❌ " + err;

   });

 </script>

</body>

</html>


