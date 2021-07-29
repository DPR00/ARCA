Para probar a arca moviéndose ejecutar los siguientes comandos:

$ roslaunch arca3_description arca3_joint_control.launch

Luego debes abrir Gazebo y Rviz. Se podrá visualizar en ambos.

Para desplazar a arca (como con el turtlebot), correr el siguiente comando:

$ rosrun teleop_twist_keyboard teleop_twist_keyboard.py

He estado probando creando un archivo para hacer el SLAM (arca_slam_mapping.launch), pero opr alguna razón el urd no se muestra bien con ello. aún no he podido ver porqué pasa eso.