------------------------------------MultiLabelBirdVer2.ipynb------------------------------------------

######Cosa è stato aggiunto?#########

E' stata modificata la visualizzzione dei dizionari (print(dictionary)) in modo da non prendere troppo
spazio







------------------------------------MultiLabelBird.ipynb---------------------------------------------


#######Come modificare il codice######

Creare un altro notebook chiamandolo MultiLabelBird_Nome_Cognome

NON MODIFICARE QUESTO NOTEBOOK!!!


#######Errori/perplessità######

Ogni volta che faccio learn.lr_find() ho il valid_loss con #NA#, perche? Se riuscite sistemate…

Mi viene creata un label  ('') con la maggior probabilità per tutte le immagini. Vedere ultima riga di codice: learn.data.classes[:10].  

Come detto per  tutte le immagini ho maggior probabilità per questa classe, vedere penultima e terz’ultima linea di codice:
Preds e preds_tta.
