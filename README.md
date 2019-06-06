# hello-world
First Repository

Hello! My name is Samuel Park

CHANGES?!?!
package myfirstrobot;
import robocode.*;


public class MyFirstRobot extends Robot
{
public void run(){
    while(true){
        ahead(100);
        turnGunRight(360);
        back(100);
        turnGunRight(360);        
    }
}
public void onScannedRobot(ScannedRobotEvent e){
    fire(1);
}
    
}
