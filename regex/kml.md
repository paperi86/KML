<\?xml version="1.0" encoding="UTF-8"\?>
<kml xmlns="http://www.opengis.net/kml/2.2" xmlns:gx="http://www.google.com/kml/ext/2.2">
[ ]*<Document id="Parade_Salamanca_[A-Za-z]*">
[ ]*<open>1</open>
[ ]*<name>[^<]*</name>
[ ]*<description>[<![\w \.Á-Úá-úü>:\(\),ñ\]]*</description>

[ ]*((<Style id="Style_Parade_Salamanca_[A-Za-z]*_Marker_[0-9]{1,2}">
[ ]*)(<IconStyle>
[ ]*)(<scale>1</scale>
[ ]*)(<Icon>
[ ]*)(<href>https://raw.githubusercontent.com/paperi86/KML/main/MapMarkers/Parade_Salamanca_[A-Za-z]*/marker-[0-9]{1,2}.png</href>
[ ]*)(</Icon>
[ ]*)(</IconStyle>)
[ ]*</Style>
[ ]*)+
[ ]*<Style id="Style_Parade_Salamanca_[A-Za-z]*_Line_Normal">
[ ]*<LineStyle>
[ ]*<color>ff[0-f]{6}</color>
[ ]*<width>8</width>
[ ]*<gx:outerColor>ff[0-f]{6}</gx:outerColor>
[ ]*<gx:outerWidth>0.25</gx:outerWidth>
[ ]*</LineStyle>
[ ]*</Style>

[ ]*<Placemark>
[ ]*<name>[^<]*</name>
[ ]*<styleUrl>#Style_Parade_Salamanca_[A-Za-z]*_Line_Normal</styleUrl>
[ ]*<LineString>
[ ]*<tessellate>1</tessellate>
[ ]*<coordinates>(
[ ]*(([\-0-9\.]+),){2}0)+
[ ]*</coordinates>
[ ]*</LineString>
[ ]*</Placemark>

[ ]*<Folder>
[ ]*<name>[^<]*</name>(
[ ]*<Placemark>(
[ ]*<name>[^<]*</name>|
[ ]*<address>[^<]*</address>|
[ ]*<description>[^<]*</description>|
[ ]*<styleUrl>#Style_Parade_Salamanca_[A-Za-z]*_Marker_[0-9]{1,2}</styleUrl>){1,4}
[ ]*<Point>
[ ]*<coordinates>
[ ]*[0-9,\.\-]*
[ ]*</coordinates>
[ ]*</Point>
[ ]*</Placemark>)+
[ ]*</Folder>
[ ]*</Document>
</kml>