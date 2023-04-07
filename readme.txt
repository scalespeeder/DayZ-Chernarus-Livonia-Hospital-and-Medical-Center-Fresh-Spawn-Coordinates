DayZ Chernarus & Livonia Hospital & Medical Center New Player Fresh Spawn Locations & Coordinates XML Mod For Consoles & PC XML Snippets Instructions & Terms Of Use

These snippets will spawn in new players around Hospitals & Medical Centres (Chernarus) & Medical Centres (Livonia), depending on which file or code snippets you use.

PLEASE NOTE FRESH SPAWNS MAY APPEAR IN GAS LOCATIONS OR AT OTHER UNSUITABLE LOCATIONS, I HAVEN'T TESTED THEM ALL!

Limited Testing on PC Chernarus & Livonia Local Server DAYZ Version 1.20 APRIL 2023.

XML Snippets Created by @scalespeeder. Please report bugs & errors to scalespeeder@gmail.com with screenshots.

TERMS OF USE
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS
OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN
AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH
THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

Using these modded xml / json files and instructions could break the functioning of your DAYZ server, requiring a reinstall that would wipe
all player progress.

Using these modded files neccessitates increased regular restarts to prevent server crashing.

It is suggested you thoroughly test your server after applying these files to ensure proper
functioning of your server.

I always recomend you validate your files at: https://www.xmlvalidation.com/ and https://jsonformatter.curiousconcept.com/

Instructions:

To download all of the files from the Github, click on the green "Code" button then "download zip" and extract / unzip that file onto your local PC hard-drive.

I have included 1.20 Update Compatible cfgplayerspawnpoints files, you just need to rename them as such and upload the correct one to your CHERNARUS or LIVONIA (Enoch) Mission Directory and restart your server.
HOWEVER if you are using this mod beyond update 1.20 it is preferable to overwrite the vanilla player spawn points inside your cfgplayerspawnpoints.xml file with the approriate xml snipet
you can see below, as there may be other changes to the file:
	
<!-- Chernarus Spawns-->

<generator_posbubbles>

	<!--Chernarus Hospital Spawn Points-->
    <pos x="2165.044922" z="3357.664795" />
    <pos x="6474.122070" z="2719.580078" />
    <pos x="8017.260742" z="12752.350586" />
    <pos x="10283.892578" z="2285.150635" />
    <pos x="11413.849609" z="14597.907227" />
    <pos x="11928.188477" z="9070.382813" />
	
	<!-- Chernarus Medical Center Spawn Points-->	
	<pos x="1271.748535" z="11408.562500" />
    <pos x="2739.142090" z="5181.487793" />
    <pos x="3454.529785" z="13163.477539" />
    <pos x="3647.120850" z="14861.591797" />
    <pos x="3757.443848" z="9011.004883" />
    <pos x="5990.664063" z="7680.112305" />
    <pos x="7051.179199" z="4305.796387" />
    <pos x="7278.656738" z="7067.685547" />
    <pos x="8121.413086" z="11022.764648" />
    <pos x="8572.504883" z="13969.001953" />
    <pos x="9472.970703" z="8838.847656" />
    <pos x="10116.269531" z="5511.441895" />
    <pos x="10347.991211" z="3450.491943" />
    <pos x="11266.918945" z="12144.144531" />
    <pos x="12776.978516" z="10064.617188" />
    <pos x="13386.528320" z="6314.850586" />
    <pos x="13876.155273" z="13117.765625" />
	
</generator_posbubbles>

<!--Livonia Spawns-->
	
	
<!-- Livonia Medical Center Spawn Points -->

<generator_posbubbles>
    <pos x="819.941345" z="5575.764160" />
    <pos x="1924.757202" z="7365.787109" />
    <pos x="3778.416260" z="11776.202148" />
    <pos x="5047.897949" z="9765.221680" />
    <pos x="6051.901367" z="4189.495117" />
    <pos x="6696.117676" z="11143.583984" />
    <pos x="9534.388672" z="10279.279297" />
    <pos x="10875.620117" z="11011.625000" />
    <pos x="11295.464844" z="9585.522461" />
    <pos x="11489.015625" z="2923.876953" />
    <pos x="11500.687500" z="4657.147949" />
    <pos x="11622.706055" z="372.221130" />
</generator_posbubbles>



Save and re-upload if necessary and re-start your server for the changes to take effect.

Thanks, Rob.