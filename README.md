# Easytrieve-Extension

Technology Extension for Easytrieve
Changes needs to be done in console configuration files.

Code-scanner-config.xml

        <discoverer extensionId="com.castsoftware.uc.asmzos" dmtId="asmzosfilediscoverer"
                    fileExtensions=".asm;.ASM;.mlc;.MLC;.asmacro;.ASMACRO;" label="Assembler"/>
        <discoverer extensionId="com.castsoftware.uc.easytrieve" dmtId="esyzosfilediscoverer"
                    fileExtensions=".ESY;.MAC;.esy;.mac" label="Easytrieve"/>
        <discoverer extensionId="com.castsoftware.labs.ctl.link" dmtId="ctlzosfilediscoverer"
                    fileExtensions=".CTL;.ctl;.ndm;.NDM;" label="CTL"/>


dependencies-matrix.xml

   <technology symbol="Assembler" type="language">
        <allow symbol="SQL"/>
    </technology>

<technology symbol="CTL" type="language">
        <allow symbol="SQL"/>
    </technology>

<technology symbol="Easytrieve" type="language">
        <allow symbol="SQL"/>
    </technology>
