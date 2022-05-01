# Docker-Orgamax v21


Es sollten die Ports 5143 TCP/UDP und 5144 TCP/UDP freigegeben werden bestenfalls noch der Port 80 es läuft ein Webserver mit Basic Auth darauf die Zugangsdaten ändern sich bei jedem start das Pawwort bekommt man über die Docker logs oder über Portainer.

Über die Weboberfläche kann man die Datenbanken hochladen die angepasste ini sowie die Datenbanken auch wieder downloaden. Es ist weiterhin ebenfalls möglich via curl ein Backup zu laden "curl -u orgamax:J0Jm5 http://192.168.70.45/backup.php --output Backup.zip".



es sollten alle Dateien im DB Ordner kopiert werden :

DB6.FDB
DB4.FDB
DB5.FDB
DB3.FDB
DB8.FDB
DB0.FDB
DB1.FDB
DB2.FDB
DB7.FDB
DB9.FDB
CENTRALDB.FDB



Es sind keinerlei weitere anpassung in den dll's nötig.

https://hub.docker.com/r/chrishdx/orgamaxserver

Ich übernehme keinerlei Haftung und oder Gewährleistung für den reibungsosen Betrieb dieses Images.
