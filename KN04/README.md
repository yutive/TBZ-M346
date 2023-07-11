## Subnetz: Screenshot und Begleittext. Zeigen Sie, dass Sie das neue Subnetz erstellt haben.

![](subnet.png)

Dies ist ein neues Subnetz welches von 172.31.100.0 - 172.31.100.255 reicht. Das Subnetz benannte ich "subnet-K04".

## Elastic IPs: Screenshot der Liste.

![](elastic-ips.png)

## Security Groups. Screenshot und Begleittext. Zeigen Sie die Inbound-Rules und die Namen der Security-Groups.

![](security-groups.png)

Ich erstellte zwei Security Groups. Eine für den Web Server namens "WebServer" und die ander für den Datenbank Server namens "DB-Server".

### Web-Server
![](web-inbound.png)
![](web-outbound.png)

### DB-Server
![](db-inbound.png)
![](db-outbound.png)

## Netzwerk-Interfaces: Screenshots und Begleittext. Zeigen Sie die private und öffentliche IP und diezugewiesene Security-Gruppe
![](network-interface.png)
![](network-interface-database.png)
![](network-interface-web.png)
## Laden Sie die aktualisierten Cloud-init Konfigurationen hoch in Git. Im Web-Konfig, sollte die IP angepasst sein.
![Cloud-init File](cloud-init-web.yaml)

## Erstellung der Instanz. Zeigen Sie die Details der beiden Instanzen, im speziellen die öffentliche undprivate IPs müssen sichtbar sein.
![](details-db.png)
![](details-web.png)

## Zeigen Sie, dass Sie nun alle drei Seiten aufrufen können (index.html, info.php und db.php).
![](index-html.png)
![](db-php.png)
![](info-php.png)