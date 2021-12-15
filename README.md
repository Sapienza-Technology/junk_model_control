# junk_model_control
This repository contains the model of the prototype junk ready to be imported into Gazebo and controllers to actuate the joints.

Cosa va installato (sudo apt install):

 ros-noetic-ros-control
 ros-noetic-ros-controllers
 ros-noetic-gazebo-ros-pkgs
 ros-noetic-gazebo-ros-control


Come si usa:

Con roslaunch avviare gazebo.launch per lanciare il modello
Se si usa un plugin di gazebo per il movimento:
    
   rimuovere commenti dal plugin che si vuole usare in nomeRobot.gazebo
   
   avviare teleop_twist_keyboard o qualcosa che invia velocità sul topic/cmd_vel
   
Se si controllano i singoli joint:
 
   avviare controller.launch, ora i topic sono avviati e si possono inviare i messaggi lì



Documentazione che spiega un po'
https://docs.google.com/document/d/1Q-z89Nq6KxA98zwQB5gFTV8kIPjzO76WKeKSYKOiydE/edit#
