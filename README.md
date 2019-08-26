# Documentatie DSMRloggerWS (laatste Versie 1.0.2)

<p>Voor de project beschrijving ga naar <a href="https://willem.aandewiel.nl/index.php/2018/08/28/slimme-meter-uitlezer/">www.aandewiel.nl</a>.</p>
<br>
<table>
<tr><th>Versie</th><th>Opmerking</th></tr>
<tr>
   <td valign="top">1.0.2</td>
   <td>Eerste Officiële Release
      <br>Debug efficiënter gemaakt
      <br>Display status OLED scherm is nu onafhankelijk van binnenkomend Telegram
      <br>Firmware Update voortgang zichtbaar in telnet
      <br>Diverse cosmetische verbeteringen.
      <br>Het is verstandig om de <b>.html</b> en <b>.js</b> files uit de data map via de FSexplorer
	  te uploaden (kan ook met de Update Server maar dan verlies je de historische
          gegevens)
   </td>
</tr>
<tr>
   <td valign="top">0.4.7</td>
   <td>Splitsen settings.ini file in DSMRsettings.ini en DSMRchartColors.ini
      <br><b>P - No Parsing (show RAW data from Smart Meter)</b> maakt nu de DTR pin hoog
          zodat de Slimme Meter de Telegrammen ook daadwerkelijk verstuurd!!
      <br>Diverse cosmetische verbeteringen.
   </td>
</tr>
<tr>
   <td valign="top">0.4.6</td>
   <td>Intergratie MQTT (#define USE_MQTT)
      <br>Via FSexplorer -> [Edit instellingen] -> [Settings]
      <br>Kunnen de volgende gegevens worden ingevuld:
      <br> &nbsp; &nbsp; &nbsp; MQTT server (URL of IP)
      <br> &nbsp; &nbsp; &nbsp; MQTT username
      <br> &nbsp; &nbsp; &nbsp; MQTT password
      <br> &nbsp; &nbsp; &nbsp; MQTT send interval
      <br> &nbsp; &nbsp; &nbsp; MQTT top Topic
      <br>Diverse cosmetische verbeteringen.
   </td>
</tr>
<tr>
   <td valign="top">0.4.5</td>
   <td>Mogelijkheid om pré DSMR 4.0 Slimme Meters uit te lezen
          #define&nbsp;USE_PRE40_PROTOCOL
      <br>Diverse cosmetische verbeteringen.
      <br><hr>
          Als de Slimme Meter geef fase informatie geeft kan
          de PowerDeliverd gebruikt worden om PowerDelivered_l1
          te gebruiken (#define&nbsp;SM_HAS_NO_FASE_INFO)
   </td>
</tr>
<tr>
   <td valign="top">0.4.4</td>
   <td>Mogelijkheid om de Timestamp niet uit de Slimme Meter te halen
      <br>maar uit een NTP server (#define&nbsp;USE_NTP_TIME).
      <br>Betere meldingen op het Oled-scherm (o.a. start AP mode).
      <br>Directe reactie als op de Wake-Up knop (FLASH) wordt gedrukt.
      <br>Diverse cosmetische verbeteringen.
   </td>
</tr>
<tr><td valign="top">0.4.3</td><td>Update meterstanden voor tab [per Uur], [per Dag] en [per Maand]</td></tr>
<tr><td valign="top">0.4.0</td><td>Eerste publieke versie</td></tr>
</table>
<br>
<h2 id="inhoudsopgave">Inhoudsopgave</h2>
<ul>
<li><a href="https://mrwheel.github.io/DSMRloggerWS/introductie/">Introductie</a></li>
<li>Voorbereiding<ul>
<li><a href="https://mrwheel.github.io/DSMRloggerWS/installatieArduinoIDE/">ArduinoIDE</a></li>
<li><a href="https://mrwheel.github.io/DSMRloggerWS/installatieESP8266core/">ESP8266 core</a></li>
<li><a href="https://mrwheel.github.io/DSMRloggerWS/installatieDataUploadTool/">Data Upload Tool</a></li>
</ul>
</li>
<li>Firmware<ul>
<li><a href="https://mrwheel.github.io/DSMRloggerWS/benodigdeBibliotheken/">Benodigd Bibliotheken</a></li>
<li><a href="https://mrwheel.github.io/DSMRloggerWS/installatieBibliotheken/">Installeren Bibliotheken</a></li>
<li><a href="https://mrwheel.github.io/DSMRloggerWS/clonenFirmware/">DSMR Firmware van Github</a></li>
<li><a href="https://mrwheel.github.io/DSMRloggerWS/uploadFirmware_V4/">Firmware Flashen DSMR-logger V4 board</a></li>
<li><a href="https://mrwheel.github.io/DSMRloggerWS/uploadDataMap_V4/">Data Flashen naar DSMR-logger V4 board</a></li>
</ul>
</li>
<li>Hardware<ul>
<li><a href="https://mrwheel.github.io/DSMRloggerWS/hardware_V4/">DSMR-logger Versie 4</a></li>
<li><a href="https://mrwheel.github.io/DSMRloggerWS/hardware_V4_Programmer/">Programmer voor de DSMR-logger</a></li>
</ul>
</li>
</ul>

<center><img src="mkdocs/docs/img/DSMR_V4_d.JPG"></center>
