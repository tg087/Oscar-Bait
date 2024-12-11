---
title: "Codebuch Oscar Bait"
author: "Tom Geyer"
date: "2024-06-25"
output: github_document
---

# Codebuch Datenerhebung *Oscar Bait*

## Hintergrund zur Datenerhebung

Der Begriff "Oscar Bait" wurde in Filmkreisen vermutlich schon seit Anfang der 1940er Jahre genutzt.
Die erste öffentliche Erwähnung lässt sich auf das Jahr 1948 zurückführen. In diesem Jahr nutzte das
Magazin "The New Republic" den Begriff in einer Kritik des Filmes "Fort Apache". Regisseur John Ford
wurde vorgeworfen, der Film sei gezielt auf die Vorlieben der Oscar Jury abgestimmt.\
Unter "Oscar Bait" versteht man also eine spezielle Art von Filmen, die mit der Intension produziert werden,
Auszeichnungen bei den Academy Awards zu erhalten. Der Stereotypische "Oscar Bait" behandelt dabei
historische Themen und Ereignisse, beinhaltet einen Krieg, erzählt eine biografische Geschichte während
die Handlung bestenfalls auch noch auf wahren Ereignissen basieren.\
Bei dieser Datenerhebung wurden alle Oscarnominierten und -ausgezeichneten Filme in der Kategorie "Best Picture"
von 1990 bis 2024 (63.-96. Oscarverleihung) auf diese Eigenschaften untersucht. Anhand dieser Erhebung soll untersucht werden, ob
das Klischee des "Oscar Baits" von den nominierten und gewinnenden Filmen erfüllt wird.

## Attribute

**name_film**\
Englischer Titel des Filmes.


**oscar**\
Ausgabe der Academy Awards bei welchen der Film nominiert für die Kategorie "Best Picture" nominiert wurde.

**release**\
Monat der Veröffentlichung in den amerikanischen Kinos. Da die Academy Awards im März stattfinden, können Filme in den US Kinos auch erst im Januar und Februar des Jahres der Oscarverleihung selbst erscheinen. Wenn dies der Fall war, wurde der Zusatz AS (Academy Season) hinzugefügt.

**length**\
Länge des Filmes in Minuten.

**genre**\
Das (Haupt-)Genre des Filmes.

**historic**\
Hat die Handlung einen historischen Hintergrund oder spielt in einem bestimmten vergangenen Zeitalter?

1 = Ja\
2 = Nein

**war**\
Spielt die Handlung während eines Krieges bzw. ist ein Krieg ein wichtiger Bestandteil des Filmes?

1 = Ja\
2 = Nein

**true_story**\
Basiert die Handlung auf wahren Begebenheiten?

1 = Ja\
2 = Nein

**biographical**\
Handelt es sich um eine biografische Erzählung?

1 = Ja\
2 = Nein

**bait_score**\
Der Wert ergibt sich aus der Summe der vorangegangenen Kategorien, welche mit 1, also mit "Ja" beantwortet wurde.

**winner**\
Hat der Film den Oscar in der Kategorie "Best Picture" gewonnen?
