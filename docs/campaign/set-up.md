# Aufsetzen von CiviCampaign

Dieses Kapitel wird Dir helfen, CiviCampaign so aufzusetzen, dass Du Aktivitäten (zu denen Zuwendungen, Umfragen und Mailings gehören), die einer bestimmten Kampagne oder einem Projekt zugeordnet werden können, verfolgen kannst. 

## Aktiviere CiviCampaign 

Zuerst musst Du die CiviCampaign-Komponente aktivieren.

1.  Gehe zu **Administer > System Settings > Components**.
2.  Wähle **CiviCampaign** aus und drücke# **Enable** und dann **Save** 

Sobald CiviCampaign aktiviert ist, wird ein neues Menüfeld **Campaigns** zu sehen sein, welches am oberen Rand des CiviCRM-Bildschirms zu sehen ist.

## Setze einen neuen Kampagnen-Typ auf.

CiviCampaign bietet von sich aus drei Standard-Kampagnen-Typen an:

-   Direkte Mail
-   Empfehlungs-Programm
-   Aktiven-Engagement

Du kannst jeglichen Kampagnen-Typ hinzufügen, der für Deine Arbeit passt (und die, die nicht passen, deaktivieren).

Um einen neuen Kampagnen-Typ hinzuzufügen:

1.  Gehe zu **Administer > CiviCampaign > Campaign Types**. 
2.  Dies wird Dir alle existierenden Kampagnen-Typen auflisten: 
     
    ![column headers are: label, value (unique number), description, order, reserved, enabled (yes or no)](/img/campaign_configuration_typeoptions_1.png)
3.  Klicke auf **Add Campaign Type**, und gib dem neuen Typ einen Namen und eine (optionale) Beschreibung.
4.  Zusätzlich kannst Du die Standard-Gewichtung ändern: Dieses ändert die Abfolge in der neue Veranstaltungstypen im Drop-Down-Menü erscheinen (die kleinste Nummer erscheint zuerst).
5.  Klicke **Save**.

Beim nächsten Mal, wenn Du eine neue Kampagne erstellst, wird dieser Kampagnent auch zur Verfügung stehen.

## Kampagnenstatus

Der Kampagne einen Status zu vergeben erlaubt Dir, die Phase zu tracken in der die Kampagne sich gerade befindet.

1.  Gehe zu **Administer > CiviCampaign > Campaign Status**. Die Standard-Stati sind "Planned" (Geplant / In Vorbereitung), "In Progress" (Laufend), "Completed" (Beendet) und "Cancelled" (ausgesetzt).
2.  Klicke **Add Campaign Status**, vergib einen Namen und, wenn Du magst, eine Beschreibung.
3.  Die Gewichtung zu ändern ist nicht notwendig, wird aber die Reihenfolge der Anzeige in den Drop-Down-Menüs beeinflussen.
4.  Klicke **Save** und der neue Status wird verfügbar sein, um ihn bei Kampagnen zu benutzen.

![overview of campaign statuses. Column headers are: label, value, description, order, reserved (yes or no), enabled (yes or no)](/img/campaign_configuration_statuses.png)

## Engagement-index 

CiviCampaign erlaubt dir, das Interesse und Engagement von einzelnen Personen in einer bestimmten Aktivität aufzuzeichnen. Der Engagement-Index kann für generelle Aktivitäten oder Aktionen aufgenommen werden (wie zB das Versenden von Emails, Besprechungen, Telefongespräche) und auch jede andere zusätzlcihe Aktivität die Du erstellst. Um mehr über das Zuweisen von Aktivitäten zu einer Person zu erfahren, schaue Dir das Kapitel "Kontakte" in der "Organisiere Deine Daten"-Sektion an. 

Um den Engagement Index zu konfigurieren:

1.  Gehe zu **Administer > CiviCampaign > Engagement Index**.
2.  Konfiguriere den Engagement-Index als eine Nummer, zum Beispiel kann 1 ein hohes Level an Engagement sein, während 5 ein niedriges Level darstellt.

Diese Information kann Dich bei der Einschätzung der Angestellten- oder Organisatoren am Mitgliederengagement bzw. Interesse an Deiner Organsation unterstützen.

![overview of engagement index options. Columns headers are: label, value, description, order, reserved (yes or no), enabled (yes or no). Each option can be edited, disabled, or deleted.](/img/campaign_configuration_engageoptions.png)
