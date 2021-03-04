# SQL Logs

## SELECT Opdrachten

### Female Selection

Query:
``` SELECT * FROM `user_details` WHERE `gender` = 'Female' ```

Uitkomst:
Selecteert in table user_details alle users van het vrouwelijke geslacht.

### first_name Morgan Selection

Query:
``` SELECT `first_name`, `last_name` FROM `user_details` WHERE `first_name` = 'Morgan' ```

Uitkomst:
Selecteert in table user_details de voor- en achternamen van de personen waarvan de voornaam Morgan is.

### user_id Selection

Query:
``` SELECT * FROM `user_details` WHERE `user_id` = '1' OR `user_id` = '2' ```

Uitkomst:
Selecteert in table user_details alle gegevens van de users met user_id's 1 en 2

## UPDATE Opdracht

Query:
``` UPDATE `user_details` SET `first_name` = 'jelani', `last_name` = 'alexis' WHERE `username` = 'rogers63' ```

Uitkomst:
Updatet in table user_details de first_name en last_name van de persoon met username rogers63. De naam verandert van David John naar Jelani Alexis.

## DELETE Opdracht

Query:
``` DELETE FROM `user_details` WHERE `last_name` = 'david' ```

Uitkomst:
Verwijdert in table user_details alle gebruikers met de achternaam David.
