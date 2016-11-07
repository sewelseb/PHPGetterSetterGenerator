<html>
	<head>
		<title>Generateur de getter et setters</title>
		<script type="text/javascript">
			function creer()
				{
					var tableauAttribut= document.getElementById("attribut").value.split(" ");
					var getter="";
					var setter="";
					var attributComplet="";
					var hydrate="public function hydrate(";
					var setterHydrate="";

					for (var key=0; key <tableauAttribut.length; key++)
					{
						attribut = tableauAttribut[key];
						attributComplet+='private $_'+attribut+';<br/>';
						document.getElementById("attributComplet").innerHTML=attributComplet;

						getter+= "public function set"+attribut.substr(0,1).toUpperCase()+attribut.substr(1,attribut.length)+"($arg) <br/>";
						getter+=" {<br/>";
						getter+="   $this->_"+attribut+"=$arg;<br/>";
						getter+=" }<br/>";

						document.getElementById("getter").innerHTML=getter;

						setter+= "public function get"+attribut.substr(0,1).toUpperCase()+attribut.substr(1,attribut.length)+"() <br/>";
						setter+=" {<br/>";
						setter+="    return $this->_"+attribut+";<br/>";
						setter+=" }<br/>";
						setterHydrate+="$this->set"+attribut.substr(0,1).toUpperCase()+attribut.substr(1,attribut.length)+"($"+attribut+"); <br/>";
						if(key==0)
						{
							hydrate+="$"+attribut;
						}
						else
						{
							hydrate+=", $"+attribut;
						}
						
					}
					hydrate+=") <br/>";
					hydrate+="{<br/>";
					hydrate+=setterHydrate;
					hydrate+="<br/>";
					hydrate+="}";
					
					document.getElementById("getter").innerHTML=getter;
					document.getElementById("setter").innerHTML=setter;
					document.getElementById("hydrate").innerHTML=hydrate;
				}

		</script>
	</head>

	<body>
		PHP:<br>
		nom de l'attribut (si plusieur, les séparer par un espace): <input type="texte" id="attribut"/>
		<button onclick="creer()">Creer</button><br/>
		<div id="attributComplet">
		</div>
		
		<br/>

		<div id="setter">
		</div>
		<br/>
		<div id="getter">
		</div>
		<br/>
		<div id="hydrate">
		</div>
	</body>
</html>