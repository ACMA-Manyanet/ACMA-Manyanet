<div align="center">
  <img src="Banner ACMA.png"/>
</div>

<h2> ¡Bienvenidos a nuestro Github! 👋 </h2>

<table border="0">
  <tr>
    <td width="60%" style="vertical-align: top;">
      <p align="justify">
        Somos <b>ACMA</b> (Agencia de Contenido Manyanet Alcobendas). Nos dedicamos a <b>facilitar</b> la vida a los profesores.
      </p>
      <p align="justify">
        Realizamos todo tipo de trabajos informáticos, ya sean de creación de software como de creación de contenido (páginas web, pósters, vídeos...) enfocado en el nivel de los estudiantes para los cuales va dirigido.
      </p>
      <p align="justify">
        Por último, nos dedicamos a formar a nuestros integrantes en una gran variedad de herramientas (<b>Photoshop</b>, <b>Python</b>, <b>Adobe Illustrator</b>...) para conseguir que realicen los encargos solicitados de forma excepcional.
      </p>
    </td>
    <td width="40%" style="vertical-align: top; text-align: center;">
      <img src="https://media.giphy.com/media/MC6eSuC3yypCU/giphy.gif" width="100%" style="border-radius: 10px;" />
    </td>
  </tr>
</table>

<h2>Herramientasa 🛠️ </h2>
<div>
	<p style="display: inline-block;">
	<p>
		<kbd>
			<kbd>Programming Languages</kbd>
			<br>
			<br>
			<img alt="Python" src="https://img.shields.io/badge/Python-05122A?style=flat&logo=python">
		</kbd>
    <kbd>
			<kbd>Databases</kbd>
			<br>
			<br>
			<img alt="Github Pages" src="https://img.shields.io/badge/Github%20Pages-05122A?style=flat&logo=Github">
		</kbd>
	</p>
  <p>
    <kbd>
			<kbd>Software and Tools</kbd>
			<br>
			<br>
			<img alt="Git" src="https://img.shields.io/badge/Git-05122A?style=flat&logo=Git">
      <img alt="Github Desktop" src="https://img.shields.io/badge/Github%20Desktop-05122A?style=flat&logo=Github">
      <img alt="Blogger" src="https://img.shields.io/badge/Blogger-05122A?style=flat&logo=blogger">
      <img alt="Tinkercad" src="https://img.shields.io/badge/Tinkercad-05122A?style=flat&logo=tinkercad">
      <img alt="" src="https://img.shields.io/badge/Google%20Drive-05122A?style=flat&logo=googledrive">
      <img alt="" src="https://img.shields.io/badge/adobe%20illustrator-05122A?style=flat&logo=adobe%20illustrator">
      <img alt="" src="https://img.shields.io/badge/adobe%20photoshop-05122A?style=flat&logo=adobe%20photoshop">
      <img alt="" src="https://img.shields.io/badge/figma-05122A?style=flat&logo=figma">
      <img alt="" src="https://img.shields.io/badge/Inkscape-05122A?style=flat&logo=inkscape">
      <img alt="" src="">
      <img alt="" src="">
      <img alt="" src="">
			<img alt="Visual Studio Code" src="https://img.shields.io/badge/Visual%20Studio%20Code-05122A?style=flat&logo=Visual%20Studio%20Code">
			<img alt="Canva" src="https://img.shields.io/badge/Canva-05122A?style=flat&logo=Canva">
		</kbd>
  </p>
</div> <!--Añadir más categorías-->

<h2>Estatus</h2>
<!--START_SECTION:waka-->
name: Waka Readme

on:
  schedule:
    # Runs at 12am IST
    - cron: '30 18 * * *'
  workflow_dispatch:
jobs:
  update-readme:
    name: Update Readme with Metrics
    runs-on: ubuntu-latest
    steps:
      - uses: ACMA-Manyanet/waka-readme-stats@master
        with:
          WAKATIME_API_KEY: ${{ secrets.WAKATIME_API_KEY }}
          GH_TOKEN: ${{ secrets.GH_TOKEN }}
	- uses: anmol098/waka-readme-stats@master
	  with:
	      WAKATIME_API_KEY: ${{ secrets.WAKATIME_API_KEY }}
	      GH_TOKEN: ${{ secrets.GH_TOKEN }}
	      SHOW_OS: "False"
	      SHOW_PROJECTS: "True"
<!--END_SECTION:waka-->
