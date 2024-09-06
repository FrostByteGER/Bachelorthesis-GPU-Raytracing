# Bachelorthesis Hardware-accelerated Hit-Detection

## Übersicht
Willkommen! Dieses Dokument dient als Übersicht über alle Projektdaten und wie man selbstständig Ergebnisse erzeugen kann.
Der Ordner Projektdaten enthält einerseits den gesamten C++ Quellcode sowie die Unreal Engine 5 Projektdaten. Der Ordner Readings enthält alle Messwerte als .csv Dateien sowie die für das Erstellen der Diagramme benutzte MS-Excel Datei. Prism-HWARaytracing und UE5-HWARaytracing enthalten die .exe Dateien zum Ausführen der Testszenarien. Zum vereinfachten Ausführen dieser .exe Dateien gibt es die Launch_*.bat Dateien. Wenn ein vollständiger Messwertsatz generiert werden soll, bieten sich die Launch_Prism_All_Scenarios.bat und Launch_UE5_All_Scenarios.bat an. Zum automatisierten Zusammenfügen aller 100 .csv Dateien zu einer einzigen .csv gibt es unter Sourcecode/Python ein DataMerger.py Skript das dies tut.

Bitte bedenken Sie dass der Quellcode hauptsächlich für Windows konzipiert wurde. Unreal Engine 5 und Prism sind Linux-fähig aber wurden nie getestet.

Zwingend benötigt werden Windows 10 64-bit(!) oder neuer, eine Hardware-Raytracingfähige GPU (Nvidia RTX, AMD RDNA 2(RX6000) oder neuer, Intel Xe-HPG(Arc Alchemist) oder neuer) und Python 3.9 oder neuer. Falls nötig, bitte installieren Sie folgende MSVC++ Redistributable https://aka.ms/vs/17/release/vc_redist.x64.exe.