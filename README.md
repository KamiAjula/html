<html>
  <head>
    <meta charset="utf-8">
    <title>erste versuche mit html</title>
    <style>
      body {
         line-height:15pt;
         background-color: #D1FFFD;
	     margin:15px 20px 15px 20px;
      }
      h1 {
        text-align:center;
        font-size:70px;
        color:darkblue;
      }
      #h1 {
        color:blue;
        font-style:italic;
        line-height:40pt;
        text-align:left;
        position:relative;
        z-index:2;
        }
      #zwei {
        font-size:30px;
        text-decoration:underline;
        color:blue;
        }
      .s1 {
        color: rgb(102, 178,255);
        }
      #d1 {
        background: rgb(102, 178,255);
        width: 730px;
	margin:10px;
        border:2px solid rgb(255, 0, 0);
        }
      #d2 {
        Background: rgb(102, 178,255);
        width:60%;
	height:200px;
	overflow:auto;
        }
      .eldenring {
	margin:25px 0px 25px 250px;
        font-size:50px;
        }
      #artorias {
      	position:absolute;
        top:20px;
        left:200px;
        z-index:1;
        } 
      #megaman {
        position:absolute;
        top:150px;
        right:30px;
        z-index:1;
        }
    </style>
  </head>
  <body>
    <h1><font size="8"> erste lernversuche mit html und css </font></h1>
    
    <h1 id="h1">erst mal einen text schreiben <br> den man dann bissl bearbeiten kann <br> </h1>

	<image id="artorias" src="https://i.ibb.co/hfvj6ng/Artorias-1.png" width="300" height="300"></image>
        
    <p id="eins"> als naechstes kommen <strong>listen</strong> dran<br><br> ich nehme dafuer einfach mal ein paar spieletitel<br><br> erstmal unsortiert </p>
    
    <image id="megaman" src="https://i.ibb.co/T0TBfbZ/Megaman-1.png" width="300" height="300"></image>
    
    <p id="zwei"> Spiele </p>
    <ul>
       <li id="destiny"><a href="https://de.m.wikipedia.org/wiki/Destiny_2"> destiny </a></li>
       <li id="elden_ring"> elden ring </li>
       <li id="gta5"> GTA 5 </li>
    </ul>
    <p class="eins"> und etz sortiert </p>
    <ol>
       <li><a href="#table"> Elden Ring</a> </li>
       <li><a href="#table"> Destiny 2</a> </li>
       <li><a href="#table"> GTA 5</a> </li>
    </ol>
    <p><span class="s1"> jetzt erst einmal was schoenes zum sehen und hoeren</span></p>

    <iframe width="560" height="315" src="https://www.youtube.com/embed/VIwC9_VCZCY?si=V5ij0RW41UXHFuwp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

    <br> <br>

    <p>sooooo wollen wir weiter machen? <br> <br> </p>

    <iframe src="https://giphy.com/embed/vyTnNTrs3wqQ0UIvwE" width="480" height="400" frameBorder="0" class="giphy-embed" allowFullScreen></iframe>

     <br> <br>

    <p> Ok dann halt noch ein gute laune lied </p>

    <iframe width="560" height="315" src="https://www.youtube.com/embed/0HJXBNaRfW0?si=ZOB_kF1Tz-sSMkJY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

    <br> <br>

    <p> so weiter gehts mit dem sinnlosen muell <br> es soll ja <strong>langweilig</strong> bleiben </p>

    <table id="table">
    	<tr>
        	<th>Spielname</th>
        	<th>Genre</th>
        	<th>release</th>
        	<th>entwickler</th>
        </tr>
        <tr>
        	<td>Elden Ring</td>
            <td>Action-Rollenspiel</td>
            <td>25.02.2022</td>
            <td>FromSoftware</td>
        </tr>
        <tr>
        	<td>Destiny 2</td>
            <td>MMO-Shooter</td>
            <td>28.08.2017</td>
            <td>Bungie</td>
        </tr>
        <tr>
        	<td>GTA V</td>
            <td>Open-World, Action</td>
            <td>17.09.2013</td>
            <td>Rockstar North</td>
        </tr>
    </table>

    <p class="eldenring"><strong>Elden ring</strong></p>
    
    <div id="d1"><p>Elden Ring ist ein 2022 veröffentlichtes Open-World-Action-Rollenspiel des japanischen Studios FromSoftware.<br>
Das Computerspiel entstand aus dem Wunsch des leitenden Entwicklers Hidetaka Miyazaki, mit dem durch die<br> Fantasy-Saga Das Lied von Eis und Feuer bekannt gewordenen George R. R. Martin ein Videospiel zu entwerfen,<br> bei dem der Schriftsteller für die Hintergrundgeschichte und Mythologie verantwortlich zeichnet.[2]<br> Der Titel wurde überaus positiv von der Computerspielpresse aufgenommen und verkaufte sich innerhalb eines<br> Jahres über 20 Millionen Mal.</p></div>

	<p>Destiny 2</p>
    
    <div id="d2"><p>Destiny 2 ist ein Mehrspieler-Computerspiel, entwickelt von Bungie und veröffentlicht von Activision. Bungie und Activision wurden im Jahre 2019 unabhängig voneinander. Der Ego-Shooter ist ein reines Onlinespiel und wurde für die PlayStation 4 und die Xbox One am 6. September 2017 veröffentlicht. Die Version für Microsoft Windows wurde am 24. Oktober 2017 veröffentlicht.[2][3] Außerdem erschien das Spiel für Google Stadia,[4][5] Xbox Series X und S sowie die PlayStation 5.[6] Destiny 2 ist der Nachfolger des 2014 erschienenen Destiny.<br>

Die Spielewelt ist eingebettet in ein Science-Fiction-Szenario. Jeder Spieler schlüpft in die Rolle eines sogenannten Hüters, Beschützer der letzten verbliebenen sicheren Stadt auf der Erde. Die Hüter nutzen eine als „Licht“ bezeichnete Macht, um die Stadt vor verschiedenen außerirdischen Rassen zu verteidigen. Eine dieser Rassen, die sogenannten Kabale und angeführt von „Dominus Ghaul“, greifen zu Beginn des Spiels die Stadt an und berauben die Hüter ihrer Macht. Der Spieler startet mit der Reise, diese Macht zurückzugewinnen und Ghaul samt seiner „Rotlegion“ zu besiegen und die letzte Stadt zurückzuerobern.<br>

Wie schon im ersten Teil des Spiels sind die Handlungen von Destiny 2 in Spieler-gegen-Spieler- (PvP) und Spieler-gegen-Umgebung-Aktivitäten (PvE) aufgeteilt. Zusätzlich zu den klassischen Story-Missionen, in denen die Handlung des Spiels verfolgt wird, enthält Destiny 2 im PvE-Modus sogenannte „Strikes“ für Gruppen aus drei Spielern und „Raids“ für sechs Spieler. Hierbei werden willkürlich gewählte Story-Missionen in verschiedenen Schwierigkeits-Graden gespielt. Weiterhin gibt es auf den verschiedenen Planeten unterschiedliche Events und Aktivitäten mit Nicht-Spieler-Charakteren (NPC). Sogenannte Kompetitiv-Modi, die dem PvP-Prinzip nachempfunden sind, enthalten sowohl zielbasierte Typen als auch klassisches Deathmatch.</p></div>

    <p><a href="#top">zum anfang</a></p>
    
  </body>
</html>
