# Playable Human Variant Mod

This mod brings the Human Variant sub race choice from the PHB to Baldur's Gate 3.

### Differences:

#### Selectable feat
I didn't know how to exclude the Ability Score Improvement option from the selectable
feat. So essentially that could be used (which is not how the sub race is supposed to
be used) or you could just select a feat like normal

## Installation

This mod is packaged in a way that _should_ work with Candor Mod Installer. You may also
install manually, placing the included .pak file in 
`\Documents\Larian Studios\Baldur's Gate 3\Mods` and updating your 
`\Documents\Larian Studios\Baldur's Gate 3\Profiles\[Profile Name]\modsettings.lsx` file to include
the following and set the `modsettings.lsx` to read-only:

```bash
<node id="ModOrder">
    <children>
        <node id="Module">
            <attribute id="UUID" type="FixedString" value="63160edd-4b0b-533e-9314-f3b612db5098"/>
        </node>
    </children
</node>
<node id="Mods">
    <children>
        <node id="ModuleShortDesc">
	    <attribute id="Folder" type="LSWString" value="HumanVariantMod"/>
	    ﻿<attribute id="MD5" type="LSString" value=""/>
            ﻿<attribute id="Name" type="FixedString" value="HumanVariantMod"/>
            <attribute id="UUID" type="FixedString" value="63160edd-4b0b-533e-9314-f3b612db5098"/>
            ﻿<attribute id="Version" type="int32" value="1"/>
        </node>
    </children>
</node>
````
