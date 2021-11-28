# AS code for controlling kawasaki fs020n manipulator

The protocol description and comments in the code are in russian, sorry.

FILES:

- kawasaki_fs020n_protocol.md

    Описание протокола взаимодействия с роботом через TCP. В файле содержится описание доступных команд, с помощью которых можно реализовывать желаемое движение робота.

    Description of the TCP communication protocol. Look through this file to understand what commands are available to send to the robot.

- kawasaki_fs020n_protocol.pdf

    PDF версия описания протокола.

    PDF version of the description of the TCP communication protocol.

- kawasaki_fs020n_ros_control_code.as

    Код на языке AS, который зашит в робот. Этот код представляет собой реализацию вышеупомянутого протокола.

    Code on the AS language that has been programmed in the robot. This code is a realization of the the above protocol.