# Spazzoli-ReinforcementLearning-Experiments
## Obiettivi
Questa repository è stata creata per raccogliere il materiale elaborato da Mattia Spazzoli per il conseguimento dell'attività progettuale in Data Mining M presente all'interno del piano di studi di Ingegneria Informatica Magistrale di Bologna.

L'obiettivo del progetto è realizzare uno studio con tema Reinforcement Learning, una modalità di apprendimento automatico, compreso all'interno del maxi tema del Machine Learning. Siccome nel RL lo scopo principale è la realizzazione di un agente in grado di prendere decisioni, attraverso l'interzione con l'ambiente in cui opera e con l'obiettivo di massimizzarne l'efficacia. Lo studio ha posto l'attensione anche su di uno delle tipologie di agenti più utilizzate in questo ambito come il Deep Q-Learning.

Dopo una prima fase di studio si sono scelte due piattaforme, tra le più utilizzate per la realizzazione di progetti di RL, con il fine di studiarne le principali caratteristiche, metterle a confronto e realizzare con ogniuna un esperimento con i dati di esempio contenuti al loro interno.
Tra le possibili piattaforme di RL proposte dal professore presenti al link https://analyticsindiamag.com/top-10-reinforcement-learning-platforms-developers-must-know/ sono state scelte le due seguenti:
1) OpenAI Gym (https://gym.openai.com/)
2) Dopamine (https://opensource.google/projects/dopamine)

Per entrambe lo scopo era quello di realizzare un progetto che comprenda l'utilizzo di un'agente di tipo Deep Q-Learning e l'ambiente di esempio CartPole-v0, uno dei più noti per i progetti in Reinforcement Learning.

## Risultati
I risultati dell'attività progettuale sono ottunuti attraverso una presentazione PowerPoint presente all'interno di questa cartella e dalla realizzazione di due notebook presenti all'interno della sotto cartella Experiments, che contengono al loro interno le due applicazioni che ci si era prefisso di realizzare. In particolare all'interno del notebook di Open Ai Gym è stato realizzato, addestrato e testato un agente DQN mentre in quello di Dopamine il focus è stato spostato sulla scrittura del file gin-config per configurare a meglio l'utilizzo di un agente DQN già disponibile all'interno della libreria. In entrambi i casi, gli agenti sono stati eseguiti per 400 epoche con ottimi valori di riconpensa, come si può vedere all'interno dei progetti oppure all'interno della presentazione PowerPoint.
