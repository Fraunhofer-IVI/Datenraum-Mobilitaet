# Datenraum Mobilität

Dieses Repository dient zur Dokumentation des Datenraum Mobilität. 
Über die [Discussions](https://github.com/Fraunhofer-IVI/Datenraum-Mobilitaet/discussions)
Funktion von Github können Sie Fragen, Kommentare usw. teilen und über die [Issues](https://github.com/Fraunhofer-IVI/Datenraum-Mobilitaet/issues)
Probleme melden.
Außerdem werden wir den Bereich [Announcements](https://github.com/Fraunhofer-IVI/Datenraum-Mobilitaet/discussions/categories/announcements)
für Ankündigungen, wie z.B. Downtimes oder Komponentenupdates, nutzen.

## Zugang zum Datenraum Mobilität

Um mit ihrem Connector Zugang zum Datenraum zu erhalten, benötigen Sie zuerst ein gültiges DAPS Token. 
Dieses Token können Sie beantragen unter [Requested & Issued Demo certificates](https://industrialdataspace.jiveon.com/docs/DOC-2002)
oder direkt bei [Gerd Brost](https://www.dataspaces.fraunhofer.de/de/software/identity_provider.html).

Wenn Sie den [Dataspace Connector](https://github.com/International-Data-Spaces-Association/DataspaceConnector) nutzen, können Sie Ihren Connector mit Token wie unter [Dataspace Connector-Configuration](https://international-data-spaces-association.github.io/DataspaceConnector/Deployment/Configuration)
beschrieben konfigurieren. Nun können Sie Ihren Connector z.B. mit einem einem der Broker verbinden um eigene Resourcen zu veröffentlichen oder Resourcen von anderen Connectoren im Datenraum anfragen.

## Stages
Es existieren zwei voneinander getrennte Stages oder Umgebungen des Datenraum Mobilität. Eine Testumgebung und eine Demoumgebung. Wie der Name schon sagt wird die Testumgebung zum Testen neuer Connectoren und Resourcen verwendet.
Haben Sie einen neuen Connector sollten Sie ihn zuerst in der Testumgebung testen.

### Testumgebung
Eine Übersicht über die Testumgebung gibt es hier: https://logging.test.mobilitydataspace.io/

#### Broker
Das User Interface des Brokers ist zu erreichen unter https://broker.test.mobilitydataspace.io/resources
Die IDS Schnittstelle zum Publizieren einer Resource ist zu erreichen unter https://ids.broker.test.mobilitydataspace.io/infrastructure

### Demoumgebung
Eine Übersicht über die Testumgebung gibt es hier: https://logging.mobilitydataspace.io/

#### Broker
Das User Interface des Brokers ist zu erreichen unter https://broker.mobilitydataspace.io/resources
Die IDS Schnittstelle zum Publizieren einer Resource ist zu erreichen unter https://ids.broker.mobilitydataspace.io/infrastructure

## Ontologie
Der Datenraum Mobilität verwendet die [MobiDS Ontologie](../main/ontology/MobiDS-Ontology.ttl)