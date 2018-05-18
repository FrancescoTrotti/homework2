# homework2

# Corso ciberfisico univr

- Autore: Francesco trotti

- Data: 17/05/2018

# Esecuzione:

Per eseguire il progetto clonare questa repository da gitHub con il comando "git clone ". Spostarsi nella cartella 'homework2' e avviare lo script presente nel file "setup.sh" con il comando ./setup.sh.
Per avviare la guida autonoma del turtlebot nel modello della delta lanciare il nodo "roslaunch turtlebot3_gazebo turtlebot3_homework2.launch" in un terminale, il nodo "roslaunch turtlebot3_navigation turtlebot3_navigation.launch map_file:=$HOME/map.yaml" in un secondo terminale e il nodo "rosrun rviz rviz -d `rospack find turtlebot3_navigation`/rviz/turtlebot3_nav.rviz".
Una volta eseguito rviz selezionare il bottone "2D pose estimate" per stabilire il punto di partenza del turtlebot e il bottone "2D nav goal" per stabilirne l'arrivo. 

# Progettazione:

Ho deciso di ricreare come modello del monodo l'aula Delta dell'università. E' stato fatto girare il tunderbolt3 all'interno del monodo per averne una ricostruzione su rviz riconoscendo le collizioni varie del ambiente.   

# Video dimostrativo

Il link rimanda al video dimostrativo del progetto concluso.
https://drive.google.com/file/d/1L_wjNkf6vI_3nzm3c_3re_eMagCq0O6n/view?usp=sharing
