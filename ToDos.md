ToDos
=====

Pace Car Highlighting
---------------------
Visuelle Darstellung, dass sich das Pace Car auf der Strecke befindet
Pace Car wird nicht dargestellt -> Wenn das Pace Car auf der Strecke ist sollte es im Trainingsmodus und im Rennmodus in der Übersicht mit dargestellt werden (Regler 8)

[ ] Darstellung der Steuerungselemente für das Pace Car im Home Screen  
[ ] Visualisierung des Pace Car in der Ansicht für Training  
[ ] Visualisierung des Pace Car in der Ansicht für Qualifying  
[ ] Visualisierung des Pace Car in der Ansicht für Rennen

Support für das Ghostcar
------------------------
Ghostcar wird nicht dargestellt -> Wenn das Ghostcar auf der Strecke ist sollte es im Trainingsmodus und im Rennmodus in der Übersicht mit dargestellt werden (Regler 7)

[ ] Darstellung der Steuerungselemente für das Ghostcar im Home Screen  
[ ] Visualisierung des Ghostcar in der Ansicht für Training  
[ ] Visualisierung des Ghostcar in der Ansicht für Qualifying  
[ ] Visualisierung des Ghostcar in der Ansicht für Rennen  

TTS per Kommandozeilenoption ein und ausschalten
------------------------------------------------
TTS sollte für Deutsch und Englisch funktionieren und entsprechend per Commandline Option ein- und ausschaltbar sein

[x] Implemetierung der Kommandozeilenoption "-t" bzw. "--tts" zum ein- und ausschalten von TTS  
[ ] Testing und debugging von TTS

Steuerung der CU
----------------
Steuerungsmöglichkeiten für die CU schaffen (analog zum alten RMS), so dass Start/Stopp, Speed, Brake, Fuel und Code vom PC aus gesteuert werden kann. Das sollte einfach via bridge.py realisierbar sein.

Implementierung von Abbruch und Resetfunktionen für Qualifying und Rennen
-------------------------------------------------------------------------
Bisher müssen Qualifying und Rennen fertig gefahren werden, es ist kein vorzeitiger Abbruch möglich. Außerdem merkt sich das RMS nicht die Fahrerkonfiguraion -> muss jedesmal neu eingestellt werden. Das sollte in diesem Zuge mit umgesetzt werden.
