---
title: XML flight plan generation
source: https://chat.openai.com/c/c04d57af-cc09-4ef2-83a6-cdd4e84af2cc
date: 2023-11-03-2023-11-03T12-49-51
model: -{model_name}
---

# XML flight plan generation

#### You:
Write Javascript code to transform this string: OMDB DB464 IVURO KUSEN LALDO GIDIL IMLOT 2500N/05700E KATUS PEDEX KINOX EGPIC EGRON LAKIV OPKC

Into this file:
<?xml version="1.0" encoding="utf-8"?>
<flight-plan xmlns="http://www8.garmin.com/xmlschemas/FlightPlan/v1">
  <created>2023-01-28T10:08:49Z</created>
  <waypoint-table>
    <waypoint>
      <identifier>OMDB</identifier>
      <type>AIRPORT</type>
      <country-code>OM</country-code>
      <lat>25.252778</lat>
      <lon>55.364444</lon>
      <comment />
    </waypoint>
    <waypoint>
      <identifier>DB464</identifier>
      <type>INT</type>
      <country-code>OM</country-code>
      <lat>25.355028</lat>
      <lon>55.761861</lon>
      <comment />
    </waypoint>
    <waypoint>
      <identifier>IVURO</identifier>
      <type>INT</type>
      <country-code>OM</country-code>
      <lat>25.327778</lat>
      <lon>56.154167</lon>
      <comment />
    </waypoint>
    <waypoint>
      <identifier>KUSEN</identifier>
      <type>INT</type>
      <country-code>OM</country-code>
      <lat>25.307778</lat>
      <lon>56.394444</lon>
      <comment />
    </waypoint>
    <waypoint>
      <identifier>LALDO</identifier>
      <type>INT</type>
      <country-code>OO</country-code>
      <lat>25.301667</lat>
      <lon>56.600000</lon>
      <comment />
    </waypoint>
    <waypoint>
      <identifier>GIDIL</identifier>
      <type>INT</type>
      <country-code>OO</country-code>
      <lat>25.295047</lat>
      <lon>56.822917</lon>
      <comment />
    </waypoint>
    <waypoint>
      <identifier>IMLOT</identifier>
      <type>INT</type>
      <country-code>OO</country-code>
      <lat>25.285556</lat>
      <lon>57.134444</lon>
      <comment />
    </waypoint>
    <waypoint>
      <identifier>2557E</identifier>
      <type>INT</type>
      <country-code>XX</country-code>
      <lat>25.000000</lat>
      <lon>57.000000</lon>
      <comment />
    </waypoint>
    <waypoint>
      <identifier>KATUS</identifier>
      <type>INT</type>
      <country-code>OI</country-code>
      <lat>25.266667</lat>
      <lon>57.783333</lon>
      <comment />
    </waypoint>
    <waypoint>
      <identifier>PEDEX</identifier>
      <type>INT</type>
      <country-code>OI</country-code>
      <lat>25.203056</lat>
      <lon>59.358611</lon>
      <comment />
    </waypoint>
    <waypoint>
      <identifier>KINOX</identifier>
      <type>INT</type>
      <country-code>OI</country-code>
      <lat>25.162500</lat>
      <lon>60.161667</lon>
      <comment />
    </waypoint>
    <waypoint>
      <identifier>EGPIC</identifier>
      <type>INT</type>
      <country-code>OI</country-code>
      <lat>25.136389</lat>
      <lon>60.625000</lon>
      <comment />
    </waypoint>
    <waypoint>
      <identifier>EGRON</identifier>
      <type>INT</type>
      <country-code>OP</country-code>
      <lat>25.078889</lat>
      <lon>61.545833</lon>
      <comment />
    </waypoint>
    <waypoint>
      <identifier>LAKIV</identifier>
      <type>INT</type>
      <country-code>OP</country-code>
      <lat>24.528889</lat>
      <lon>64.828889</lon>
      <comment />
    </waypoint>
    <waypoint>
      <identifier>OPKC</identifier>
      <type>AIRPORT</type>
      <country-code>OP</country-code>
      <lat>24.908558</lat>
      <lon>67.162761</lon>
      <comment />
    </waypoint>
  </waypoint-table>
  <route>
    <route-name>OMDB OPKC</route-name>
    <flight-plan-index>1</flight-plan-index>
    <route-point>
      <waypoint-identifier>OMDB</waypoint-identifier>
      <waypoint-type>AIRPORT</waypoint-type>
      <waypoint-country-code>OM</waypoint-country-code>
    </route-point>
    <route-point>
      <waypoint-identifier>DB464</waypoint-identifier>
      <waypoint-type>INT</waypoint-type>
      <waypoint-country-code>OM</waypoint-country-code>
    </route-point>
    <route-point>
      <waypoint-identifier>IVURO</waypoint-identifier>
      <waypoint-type>INT</waypoint-type>
      <waypoint-country-code>OM</waypoint-country-code>
    </route-point>
    <route-point>
      <waypoint-identifier>KUSEN</waypoint-identifier>
      <waypoint-type>INT</waypoint-type>
      <waypoint-country-code>OM</waypoint-country-code>
    </route-point>
    <route-point>
      <waypoint-identifier>LALDO</waypoint-identifier>
      <waypoint-type>INT</waypoint-type>
      <waypoint-country-code>OO</waypoint-country-code>
    </route-point>
    <route-point>
      <waypoint-identifier>GIDIL</waypoint-identifier>
      <waypoint-type>INT</waypoint-type>
      <waypoint-country-code>OO</waypoint-country-code>
    </route-point>
    <route-point>
      <waypoint-identifier>IMLOT</waypoint-identifier>
      <waypoint-type>INT</waypoint-type>
      <waypoint-country-code>OO</waypoint-country-code>
    </route-point>
    <route-point>
      <waypoint-identifier>2557E</waypoint-identifier>
      <waypoint-type>INT</waypoint-type>
      <waypoint-country-code>XX</waypoint-country-code>
    </route-point>
    <route-point>
      <waypoint-identifier>KATUS</waypoint-identifier>
      <waypoint-type>INT</waypoint-type>
      <waypoint-country-code>OI</waypoint-country-code>
    </route-point>
    <route-point>
      <waypoint-identifier>PEDEX</waypoint-identifier>
      <waypoint-type>INT</waypoint-type>
      <waypoint-country-code>OI</waypoint-country-code>
    </route-point>
    <route-point>
      <waypoint-identifier>KINOX</waypoint-identifier>
      <waypoint-type>INT</waypoint-type>
      <waypoint-country-code>OI</waypoint-country-code>
    </route-point>
    <route-point>
      <waypoint-identifier>EGPIC</waypoint-identifier>
      <waypoint-type>INT</waypoint-type>
      <waypoint-country-code>OI</waypoint-country-code>
    </route-point>
    <route-point>
      <waypoint-identifier>EGRON</waypoint-identifier>
      <waypoint-type>INT</waypoint-type>
      <waypoint-country-code>OP</waypoint-country-code>
    </route-point>
    <route-point>
      <waypoint-identifier>LAKIV</waypoint-identifier>
      <waypoint-type>INT</waypoint-type>
      <waypoint-country-code>OP</waypoint-country-code>
    </route-point>
    <route-point>
      <waypoint-identifier>OPKC</waypoint-identifier>
      <waypoint-type>AIRPORT</waypoint-type>
      <waypoint-country-code>OP</waypoint-country-code>
    </route-point>
  </route>
</flight-plan>

#### ChatGPT:
Here is one possible solution:

```javascript
var inputString = "OMDB DB464 IVURO KUSEN LALDO GIDIL IMLOT 2500N/05700E KATUS PEDEX KINOX EGPIC EGRON LAKIV OPKC";
var waypoints = inputString.split(" ");

var xml = '<?xml version="1.0" encoding="utf-8"?>\n' +
    '<flight-plan xmlns="http://www8.garmin.com/xmlschemas/FlightPlan/v1">\n' +
    '  <created>' + new Date().toISOString() + '</created>\n' +
    '  <waypoint-table>\n';

for (var i = 0; i < waypoints.length; i++) {
  var waypoint = waypoints[i];
  var countryCode = "XX";
  if (waypoint.endsWith("N")) {
    countryCode = "OO";
  } else if (waypoint.endsWith("E")) {
    countryCode = "OI";
  } else if (waypoint.endsWith("C")) {
    countryCode = "OP";
  }

  var identifier = waypoint.replace(/[0-9]/g, '').replace("/",'');
  var lat = parseFloat(waypoint.substring(waypoint.indexOf("N") - 4, waypoint.indexOf("N")))/100;
  var lon = parseFloat(waypoint.substring(waypoint.indexOf("E") - 4, waypoint.indexOf("E")))/100;
  var type = "INT";
  if (i === 0) {
    type = "AIRPORT";
    countryCode = "OM";
  }
  xml += '    <waypoint>\n' +
      '      <identifier>' + identifier + '</identifier>\n' +
      '      <type>' + type + '</type>\n' +
      '      <country-code>' + countryCode + '</country-code>\n' +
      '      <lat>' + lat + '</lat>\n' +
      '      <lon>' + lon + '</lon>\n' +
      '      <comment />\n' +
      '    </waypoint>\n';
}

xml += '  </waypoint-table>\n' +
    '</flight-plan>';
console.log(xml);
```

Please note that this is an example and it's not guaranteed to work for all cases and it does not handle the case where the input string is not well formatted.
