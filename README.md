# about me
Il mio nome è Giuseppe.<br> Questa è una calcolatrice.
<head>
    <script>
	    
		function somma(){
			
			var a = parseInt (document.getElementById("a").value);
			var b = parseInt(document.getElementById("b").value);
			
	    a=a+b;
			alert("Somma= " + a );	
		}
		
		function differenza(){
			
			var a = parseInt (document.getElementById("a").value);
			var b = parseInt(document.getElementById("b").value);
			
	    a=a-b;
			alert("Differenza= " + a );	
		}
		
		function moltiplicazione(){
			
			var a = parseInt (document.getElementById("a").value);
			var b = parseInt(document.getElementById("b").value);
			
	    a=a*b;
			alert("Moltiplicazione= " + a );	
		}
		
		function divisione(){
			
			var a = parseInt (document.getElementById("a").value);
			var b = parseInt(document.getElementById("b").value);
			
			if(b == 0){
			
			alert("la divisione è impossibile");}
			
			else{
	    a=a/b;
			alert("Divisione= " + a );	
		}}
		
		function potenza(){
			
			var a = parseInt (document.getElementById("a").value);
			var b = parseInt(document.getElementById("b").value);
			d=a;
		if(a==0){
            alert("MATH ERROR");
			}
       
	   else{
		if(b==0){
		alert("La potenza e'= 1");
		}
		else{
	    for(c=1;c<b;c++){
		a=a*d;
		}
			alert("La potenza è= " + a );	
		}}}
		
		
	</script>
</head>

    <body>
 	
	        <p>Calcolatrice</p>
	            <br/><br/>
	                <input type="text" placeholder="              primo numero"; id="a" style=" width:200px; height:50px";>
	                <input type="text" placeholder="             secondo numero";id="b"style=" width:200px; height:50px";> <br/>
	            <br/><br/>
	        <button onclick="somma()"style=" width:100px; height:50px";>+</button >         
			<button onclick="differenza()"style=" width:100px; height:50px";>-</button>
			<button onclick="moltiplicazione()"style=" width:100px; height:50px";>*</button><br>        
			<button onclick="divisione()"style=" width:100px; height:50px";>/</button>
			<button onclick="potenza()"style=" width:100px; height:50px";>^</button>
	    <br/><br/>
    </body>
</html>

