# Q-Learning in CartPoleBox Environment

Dieses Projekt implementiert einen Q-Learning-Agenten zur Lösung des CartPoleBox-v0-Umfelds. Ziel ist es, einen Pol mit einer Box auf einem Wagen im Gleichgewicht zu halten, indem geeignete Kräfte auf den Wagen ausgeübt werden.

## Überblick
### Umgebung

Das CartPoleBox-v0-Umfeld erweitert das klassische CartPole-Umfeld von OpenAI Gym durch das Hinzufügen einer Box auf der Spitze des Pols, was die Aufgabe anspruchsvoller macht.

### Q-Learning

Q-Learning ist ein modellfreier Reinforcement-Learning-Algorithmus, der darauf abzielt, die optimale Strategie für die Auswahl von Aktionen in einem Markov-Entscheidungsprozess zu erlernen.


## Implementierung
### Setup

    Registrierung der Umgebung:
    Die Umgebung wird in OpenAI Gym registriert und kann danach als CartPoleBox-v0 verwendet werden.

    Installation der Abhängigkeiten:
    Alle erforderlichen Pakete werden durch den Befehl pip install -r requirements.txt installiert.

### Training des Agenten

Der Agent wird über 1000 Episoden trainiert, wobei jede Episode maximal 200 Schritte umfasst. Der Zustandsraum wird diskretisiert, um den Lernprozess zu vereinfachen.


## Ergebnisse
### Gesamtreward pro Episode

Der Gesamtreward pro Episode zeigt, dass die anfängliche Performance des Agenten niedrig ist, sich jedoch mit zunehmendem Training verbessert. Die Schwankungen in den Gesamtrewards bleiben hoch, was auf gelegentliche Instabilitäten hinweist.

### Durchschnittlicher Reward über die letzten 100 Episoden

Der kontinuierliche Anstieg des durchschnittlichen Rewards zeigt die Lernfortschritte des Agenten. Nach etwa 600 Episoden erreicht der Durchschnittsreward seinen Höhepunkt und zeigt danach leichte Schwankungen.