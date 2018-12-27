<!-- TITLE: Descripcio del projecte -->
<!-- SUBTITLE: Explicació general del projecte -->

# Descripcio del projecte
<p>Visual Studio Code és un editor, lleuger però potent, de codi open-source desenvolupat per Microsoft. S'adapta als següents sistemes operatius:</p>
<br/>
<table style="text-align:center; margin:auto;">
  <thead>
    <tr>
      <th style="background-color:#263238; border: 1px solid #37474f; " scope="col">#</th>
      <th style="background-color:#263238; border: 1px solid #37474f; "  scope="col">Primer</th>
			<th style="background-color:#263238; border: 1px solid #37474f; "  scope="col">Segon</th>
			<th style="background-color:#263238; border: 1px solid #37474f; "  scope="col">Tercer</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th style="background-color:#263238; border: 1px solid #37474f; " scope="row">Sistema Operatiu</th>
      <td>Windows</td>
      <td>Linux</td>
      <td>macOS</td>
    </tr>
    <tr>
      <th style="background-color:#263238; border: 1px solid #37474f; vertical-align:middle" scope="row">Logo</th>
      <td style="vertical-align:middle;"><img style="width:8em;" src="http://assets.stickpng.com/thumbs/5a01b63d7ca233f48ba6278f.png"/></td>
      <td style="vertical-align:middle;"><img style="width:8em;" src="http://pngimg.com/uploads/linux/linux_PNG29.png"/></td>
      <td style="vertical-align:middle;"><img style="width:7em; " src="https://www.logolynx.com/images/logolynx/13/137fbbc45babc1c2df798ebbac18eca5.png"/></td>
    </tr>
  </tbody>
</table>
<br/>
<p> Aquest editor disposa de moltes opcions/funcionalitats, entre les quals inclou aquestes: </p>
<br/>
<table style="text-align:center; margin:auto;">
  <thead>
    <tr>
			<th style="background-color:#263238; border: 1px solid #37474f; " scope="col">#</th>
      <th style="background-color:#263238; border: 1px solid #37474f; " scope="col">Opcions/Funcionalitats</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th style="background-color:#263238; border: 1px solid #37474f; " scope="row">1</th>
      <td>Suport per a debugging</td>
    </tr>
    <tr>
      <th style="background-color:#263238; border: 1px solid #37474f; vertical-align:middle" scope="row">2</th>
      <td>Sistema de control de versions de Git</td>
    </tr>
		 <tr>
      <th style="background-color:#263238; border: 1px solid #37474f; vertical-align:middle" scope="row">3</th>
      <td>Ressaltat de la sintaxi del codi (syntax highlighting)</td>
    </tr>
		 <tr>
      <th style="background-color:#263238; border: 1px solid #37474f; vertical-align:middle" scope="row">4</th>
      <td>Possibilitat de autocompletar el codi de forma intel·ligent</td>
    </tr>
		<tr>
      <th style="background-color:#263238; border: 1px solid #37474f; vertical-align:middle" scope="row">5</th>
      <td>Possibilitat de refactoritzar el codi</td>
    </tr>
  </tbody>
</table>
<br/>
<p>VS Code s'actualitza mensualment amb noves funcions i correccions d'errors. Cal esmentar que es poden dur a terme les actualitzacions a l'última versió des del mateix IDE, aquest et notificarà cada cop que l'obris (sinó ho desactives) que hi ha una nova versió i que hauries d'actualitzar-lo per tal d'obtenir les últimes característiques i correccions d'errors introduïdes.</p>

<p> A part de tot el que s'ha especificat anteriorment, visual studio code, ens permet afegir-hi una gran quantitat d'extensions per tal adaptar-se millor al llenguatge que estem fent servir, té extensions per a C, C#, Java, Go, Python i PHP entre d'altres.
Tot i això, sinó tenim cap plugin instal·lat, per defecte, suporta molts llenguatges, entre les quals hi ha Javascript, Node.js i Typescript.

Per altra banda, hem de tenir en compte que avui en dia, es fan servir frameworks per a facilitar la feina als desenvolupadors. Quan dic frameworks estic parlant d'Angular 2 o superior (TS), Angular 1 o AngularJS, ReactJS, ExpressJS, Vue.js.</p>


### Lloc Web

[Pàgina web de Visual Studio Code](https://code.visualstudio.com/)

### Requeriments Funcionals

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{font-family:Arial, sans-serif;font-size:14px;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:black;}
.tg th{font-family:Arial, sans-serif;font-size:14px;font-weight:normal;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:black;}
.tg .tg-0cjc{background-color:#67fd9a;border-color:inherit;text-align:left;vertical-align:top}
.tg .tg-c3ow{border-color:inherit;text-align:center;vertical-align:top}
.tg .tg-7od5{background-color:#9aff99;border-color:inherit;text-align:left;vertical-align:top}
.tg .tg-k799{background-color:#263238;border-color:#37474f;text-align:center}
.tg .tg-4rwv{background-color:#263238;color:#ffffff;border-color:inherit;text-align:center;vertical-align:top}
.tg .tg-0pky{border-color:inherit;text-align:left;vertical-align:top}
.tg .tg-elvq{background-color:#fffc9e;border-color:inherit;text-align:left;vertical-align:top}
.tg .tg-smvl{background-color:#fd6864;border-color:inherit;text-align:left;vertical-align:top}
.tg .tg-vh87{background-color:#9aff99;border-color:#9aff99;text-align:left;vertical-align:top}
</style>
<table class="tg">
  <tr>
    <th class="tg-k799" colspan="6"><span style="color:rgb(255, 255, 255)">Requisits Funcionals</span></th>
  </tr>
  <tr>
    <td class="tg-c3ow">Interficie de linia de comandes</td>
    <td class="tg-c3ow" colspan="5">Visual Studio Code ofereix una interfície de linea de comandes integrada dins del editor per facilitar al màxim el desenvolupament en qualsevol Sistema Operatiu <br></td>
  </tr>
  <tr>
    <td class="tg-c3ow">Enllaç de tecles rapides</td>
    <td class="tg-c3ow" colspan="5"><br>El editor de text disposa d'un seguit de combinacions de tecles per dur a terme tasques comunes. A més a més, ofereix la possibilitat de crear-ne nous per extendre la  nostra eficiència.</td>
  </tr>
  <tr>
    <td class="tg-c3ow">Motor de plugins</td>
    <td class="tg-c3ow" colspan="5"><br>El propi editor esta obert a la integració de plugins. Aquesta és la forma més ràpida de mantenir activa la comunitat. Els plugins donen lloc a la creativitat<br></td>
  </tr>
  <tr>
    <td class="tg-c3ow" rowspan="42">Suport de llenguatges de progrmació</td>
    <td class="tg-4rwv">Llenguatge</td>
    <td class="tg-4rwv">Snippets</td>
    <td class="tg-4rwv">Sintax Highlight</td>
    <td class="tg-4rwv">Brace Matching</td>
    <td class="tg-4rwv">Code Folding</td>
  </tr>
  <tr>
    <td class="tg-0pky">C and C++</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-elvq">Partial</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-7od5">Yes</td>
  </tr>
  <tr>
    <td class="tg-0pky">C#</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-7od5">Yes</td>
  </tr>
  <tr>
    <td class="tg-0pky">Clojure</td>
    <td class="tg-smvl">No</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-smvl">No</td>
  </tr>
  <tr>
    <td class="tg-0pky">Coffe Script</td>
    <td class="tg-vh87">Yes</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-7od5">Yes</td>
  </tr>
  <tr>
    <td class="tg-0pky">CSS</td>
    <td class="tg-smvl">No</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-smvl">No</td>
  </tr>
  <tr>
    <td class="tg-0pky">Dockerfile</td>
    <td class="tg-smvl">No</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-smvl">No</td>
  </tr>
  <tr>
    <td class="tg-0pky">F#</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-7od5">Yes</td>
  </tr>
  <tr>
    <td class="tg-0pky">Go</td>
    <td class="tg-smvl">No</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-7od5">Yes</td>
  </tr>
  <tr>
    <td class="tg-0pky">Groovy</td>
    <td class="tg-smvl">No</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-smvl">No</td>
  </tr>
  <tr>
    <td class="tg-0pky">Handlebars</td>
    <td class="tg-smvl">No</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-smvl">No</td>
  </tr>
  <tr>
    <td class="tg-0pky">HLSL</td>
    <td class="tg-smvl">No</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-smvl">No</td>
  </tr>
  <tr>
    <td class="tg-0pky">HTML</td>
    <td class="tg-smvl">No</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-smvl">No</td>
  </tr>
  <tr>
    <td class="tg-0pky">INI file</td>
    <td class="tg-smvl">No</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-smvl">No</td>
  </tr>
  <tr>
    <td class="tg-0pky">Java</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-7od5">Yes</td>
  </tr>
  <tr>
    <td class="tg-0pky">JavaScript</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-7od5">Yes</td>
  </tr>
  <tr>
    <td class="tg-0pky">JSON</td>
    <td class="tg-smvl">No</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-7od5">Yes</td>
  </tr>
  <tr>
    <td class="tg-0pky">LESS</td>
    <td class="tg-smvl">No</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-7od5">Yes</td>
  </tr>
  <tr>
    <td class="tg-0pky">Log file</td>
    <td class="tg-smvl">No</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-smvl">No</td>
    <td class="tg-smvl">No</td>
  </tr>
  <tr>
    <td class="tg-0pky">Lua</td>
    <td class="tg-smvl">No</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-smvl">No</td>
  </tr>
  <tr>
    <td class="tg-0pky">Makefile</td>
    <td class="tg-smvl">No</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-smvl">No<br></td>
  </tr>
  <tr>
    <td class="tg-0pky">Markdown</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-smvl">No</td>
    <td class="tg-smvl">No</td>
  </tr>
  <tr>
    <td class="tg-0pky">Objective-C</td>
    <td class="tg-smvl">No</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-smvl">No</td>
  </tr>
  <tr>
    <td class="tg-0pky">Perl</td>
    <td class="tg-smvl">No</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-smvl">No</td>
  </tr>
  <tr>
    <td class="tg-0pky">PHP</td>
    <td class="tg-smvl">No</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-smvl">No</td>
  </tr>
  <tr>
    <td class="tg-0pky">PowerShell</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-7od5">Yes</td>
  </tr>
  <tr>
    <td class="tg-0pky">Pug JS</td>
    <td class="tg-smvl">No</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-smvl">No</td>
  </tr>
  <tr>
    <td class="tg-0pky">Python</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-7od5">Yes</td>
  </tr>
  <tr>
    <td class="tg-0pky">R</td>
    <td class="tg-smvl">No</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-smvl">No</td>
  </tr>
  <tr>
    <td class="tg-0pky">Razor</td>
    <td class="tg-smvl">No</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-7od5">Yes</td>
  </tr>
  <tr>
    <td class="tg-0pky">Ruby</td>
    <td class="tg-smvl">No</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-7od5">Yes</td>
  </tr>
  <tr>
    <td class="tg-0pky">Rust</td>
    <td class="tg-smvl">No</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-smvl">No</td>
  </tr>
  <tr>
    <td class="tg-0pky">SCSS</td>
    <td class="tg-smvl">No</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-7od5">Yes</td>
  </tr>
  <tr>
    <td class="tg-0pky">Shaderlab</td>
    <td class="tg-smvl">No</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-smvl">No</td>
  </tr>
  <tr>
    <td class="tg-0pky">Shell script</td>
    <td class="tg-smvl">No</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-smvl">No</td>
  </tr>
  <tr>
    <td class="tg-0pky">SQL</td>
    <td class="tg-smvl">No</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-smvl">No</td>
  </tr>
  <tr>
    <td class="tg-0pky">Swift</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-smvl">No</td>
  </tr>
  <tr>
    <td class="tg-0pky">Typescript</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-7od5">Yes</td>
  </tr>
  <tr>
    <td class="tg-0pky">Visual Basic</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-0cjc">Yes</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-7od5">Yes</td>
  </tr>
  <tr>
    <td class="tg-0pky">Windows batch fIle</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-0cjc">Yes</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-7od5">Yes</td>
  </tr>
  <tr>
    <td class="tg-0pky">XML</td>
    <td class="tg-smvl">No</td>
    <td class="tg-0cjc">Yes</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-7od5">Yes</td>
  </tr>
  <tr>
    <td class="tg-0pky">YAML</td>
    <td class="tg-smvl">No</td>
    <td class="tg-0cjc">Yes</td>
    <td class="tg-7od5">Yes</td>
    <td class="tg-7od5">Yes</td>
  </tr>
</table>