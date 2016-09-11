# IrRemoteFanController
/*
 * IrRemoteFanController: Any home irRemote canbe use to control fan speed 
 * An IR detector must be connected to the input RECV_PIN .
 * An Fan module must be connected to the output PWM pin 5.
 * A visible LED can be connected to iRlive to provide status.
 * Code will be shown on Serial monitor
 * Copy Two codes and  set to code1(+speed) and code2(-speed) in IrConfig.h file.
 * 
 * The logic is:
 * If the iRrecieve_code match to code1 and code2 than 
 * increase count else decrease count respectively.
 * 
 * 
 */
