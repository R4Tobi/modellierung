Übungsaufgabe 21 - CDN
▪ Modellieren Sie eine Anfrage an ein Content Delivery Network
(CDN) in BPMN. Gruppieren Sie dafür die beschriebenen
Vorgänge im CDN (Ereignisse, die nicht direkt im CDN liegen,
sind rot hervorgehoben)
o Zunächst wird eine Anfrage gestellt.
o Diese Anfrage wird dann in eine Queue eingereiht und im
Anschluss die voraussichtliche Antwortzeit berechnet.
o Wird diese Antwortzeit nicht eingehalten, bricht das CDN ab und
muss mehr Ressourcen (z.B. Server) bereitstellen.
o Andernfalls bestehen 2 Möglichkeiten:
− Ist die Queue leer, kann eine Antwort erstellt werden.
− Sofern die Queue nicht leer ist, kann eine Antwort erst dann erstellt
werden, sobald die Anfrage an der ersten stelle in der Queue ist.
o Nachdem die Antwort erstellt wurde, sind im CDN keine weiteren
Schritte notwendig und die Antwort kann ausgeliefert werden.
