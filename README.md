# William Husum Home Assistant config files

## My devices

<!-- start-table -->

<table>
    <thead>
        <tr>
            <th>Switches 🎚</th>
            <th>Units (#)</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>TP-Link HS100</td>
            <td>2</td>
        </tr>
        <tr>
            <td>Smart Plug EU</td>
            <td>1</td>
        </tr>
        <tr>
            <td>Sonoff Smart Zigbee Switch MINI</td>
            <td>1</td>
        </tr>
        <tr>
            <td>Sonoff Basic 3 WiFi</td>
            <td>1</td>
        </tr>
        <tr>
            <td>Xiaomi Aqara Single Button</td>
            <td>1</td>
        </tr>
        <tr>
            <td>Philips Hue Dimmer switch</td>
            <td>3</td>
        </tr>
        <tr>
            <td>&nbsp;</td>
            <td>&nbsp;</td>
        </tr>
    </tbody>
    <thead>
        <tr>
            <th>Sensors 🌡️</th>
            <th>Units (#)</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Xiaomi Aqara Motion Sensor</td>
            <td>5</td>
        </tr>
        <tr>
            <td>Xiaomi Aqara Temperature Sensor</td>
            <td>2</td>
        </tr>
        <tr>
            <td>Xiaomi Aqara FP1 mmWave sensor</td>
            <td>1</td>
        </tr>
        <tr>
            <td>Netatmo Healthy Home Coach</td>
            <td>1</td>
        </tr>
        <tr>
            <td>Xiaomi Aqara Vibration Sensor</td>
            <td>1</td>
        </tr>
        <tr>
            <td>Xiaomi Aqara Window/Door Sensor</td>
            <td>2</td>
        </tr>
        <tr>
            <td>Xiaomi Mi Flora Plant Sensor </td>
            <td>1</td>
        </tr>
        <tr>
            <td>&nbsp;</td>
            <td>&nbsp;</td>
        </tr>
    </tbody>
    <thead>
        <tr>
            <th>Lights 💡</th>
            <th>Units (#)</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Phillips Hue White B22 E27</td>
            <td>1</td>
        </tr>
        <tr>
            <td>Phillips Hue Lux Extension 9W Dimmable A19 White Bulb</td>
            <td>1</td>
        </tr>
        <tr>
            <td>Philips Hue LightStrip Plus V4 2m Base Kit</td>
            <td>2</td>
        </tr>
        <tr>
            <td>Philips Hue Adore Bathroom Mirror Lamp</td>
            <td>1</td>
        </tr>
        <tr>
            <td>Phillips Hue White Ambiance Candle E14</td>
            <td>1</td>
        </tr>
        <tr>
            <td>Phillips Hue White Filament Globe G125 E27</td>
            <td>2</td>
        </tr>
        <tr>
            <td>IKEA TRADFRI Bulb E14</td>
            <td>2</td>
        </tr>
        <tr>
            <td>&nbsp;</td>
            <td>&nbsp;</td>
        </tr>
    </tbody>
    <thead>
        <tr>
            <th>Media Players 📻</th>
            <th>Units (#)</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Google Nest Mini</td>
            <td>3</td>
        </tr>
        <tr>
            <td>Google Nest Hub</td>
            <td>1</td>
        </tr>
        <tr>
            <td>Google Chromecast Audio</td>
            <td>1</td>
        </tr>
        <tr>
            <td>Google Chromecast With Android TV</td>
            <td>1</td>
        </tr>
        <tr>
            <td>&nbsp;</td>
            <td>&nbsp;</td>
        </tr>
   </tbody>
    <thead>
        <tr>
            <th>Hubs</th>
            <th>Units (#)</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Conbee II</td>
            <td>1</td>
        </tr>
        <tr>
            <td>&nbsp;</td>
            <td>&nbsp;</td>
        </tr>
    </tbody>
       </tbody>
    <thead>
        <tr>
            <th>Device Tracker 📲</th>
            <th>Units (#)</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>iPhone 12 Mini</td>
            <td>1</td>
        <tr>
        <tr>
            <td>iPhone 13 Pro</td>
            <td>1</td>
        <tr>
        <tr>
            <td>Samsung Galaxy Note20 Ultra</td>
            <td>1</td>
        <tr>
        <tr>
            <td>Samsung Galaxy Tab S8+</td>
            <td>1</td>
        <tr>
            <td>&nbsp;</td>
            <td>&nbsp;</td>
        </tr>
    </tbody>
    <thead>
        <tr>
            <th>Vacuum 🧹</th>
            <th>Units (#)</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Xiaomi Roborock S5 Max</td>
            <td>1</td>
        <tr>
            <td>&nbsp;</td>
            <td>&nbsp;</td>
        </tr>
    </tbody>
    <thead>
        <tr>
            <th>Server/Network 🌐</th>
            <th>Units (#)</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Raspberry Pi 4</td>
            <td>1</td>
        <tr>
        <tr>
            <td>Synology Disk Station DS918+</td>
            <td>1</td>
        <tr>
        <tr>
            <td>Unifi Dream Router</td>
            <td>1</td>
        </tr>
        <tr>
            <td>Unifi UAP-AC-PRO</td>
            <td>1</td>
        </tr>
    </tbody>
</table>
<!-- end-table -->

# Supervisor add-ons
- [Home Assistant Google Drive Backup](https://github.com/sabeechen/hassio-google-drive-backup) version 0.109.1 by @sabeechen

# HACS plugins

# Automations - Table of Content


## [Lower thermostat temperature, when window is opened](https://github.com/WilliamHusum/config/blob/master/automations.yaml#:~:text=%2D%20id%3A%20%271673257664798%27)
When we open the window in the bedroom: 
 - Save the current temperature the thermostat is set to
 - Set the thermostat temperature to low (turn it off)
When the window is closed again:
 - Retrieve the saved temperature
 - Set the thermostat temperature to the saved value

