Antworten zur Übung 1:

- Es werden je nach URL verschiedene Ergebnisse angezeigt: Die Kommandozeile führt das API aus und im Browser wird der Playground von GraphQL angezeigt
- Vorteil: Der Browser speichert die GET-Requests im Cache und kann diese in Form von Requests von dort aus auch wieder zurücksenden. Nachteil: Es kann vorkommen, dass aufgrund von Browsertyp und -version ein anderes Ergebnis angezeigt wird. GET-Anfragen übermitteln Parameter im Gegensatz zu POST-Anfragen via URL, was ein höheres Sicherheitrisiko darstellt. Browser cachen keine Ergebnisse von POST. Bei Bildern oder grossen Ergebnissen z.B. ist GET die einzige Option, wenn man es nicht selber lokal cachen will via POST.
