# DayZ_Always_SUN_Master_XML
A " .XML " File that adds SUN... Alot of it... W/ day and night multipliers set to 3 and 8... The cfgweather.xml is located in the DayZ_offline.enoch Folder, when you open this Folder just scroll down untill you see cfgweather.xml, open the File and Copy/Paste my code over it and you'll have SUN... ALOT OF SUN...

<?xml version="1.0" encoding="UTF-8" standalone="yes" ?>

<!-- 'reset' and 'enable' are a bool, and therefore supports: 0/1, true/false, yes/no -->

<!-- 'reset' controls whether you want to load in the weather from storage or not (false by default) -->

<!-- 'enable' controls whether this file is enabled or not (true by default) -->

<weather reset="1" enable="1">

    <overcast>

        <current actual="0.2" time="120" duration="240" />

        <limits min="0.2" max="0.3" />

        <timelimits min="900" max="1800" />

        <changelimits min="0.0" max="0.1" />

    </overcast>

    <fog>

        <current actual="0.0" time="120" duration="240" />

        <limits min="0" max="0.1" />

        <timelimits min="900" max="1800" />

        <changelimits min="0" max="0.1" />

    </fog>

	<rain>

        <current actual="0.0" time="120" duration="240" />

        <limit min="0.0" max="0.1" />

        <timelimits min="900" max="1800" />

        <changelimits min="0.0" max="0.1" />

        <thresholds min="0" max="0.1" end="1" />

    </rain>

    <wind>

        <maxspeed>10</maxspeed>

        <params min="0" max="0.5" frequency="30" />

    </wind>

    <storm density="0.5" threshold="0.7" timeout="25"/>

</weather>
