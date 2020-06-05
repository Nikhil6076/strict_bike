# strict_bike
This projects main aim is to make the helmet mandatory while driving a two wheeler.

In order to make the rider’s ride safe and happy we  can use this smart bike . Almost three-quarters of fatal crashes (74%) involved a head injury. Nearly all riders who died (97%) were not wearing a helmet . In India alone an average of around 98 riders die per day because of not wearing helmet . Hence by this analysis we can consider that most of the riders die because of not wearing helmet . Based on this point we would like to pair the helmet with bike. 

By using this smart bike the rider can have a safe journey as the rider can only ride the bike till the time he wears his helmet .Once the helmet is removed then the bike stops  moving gradually and comes to rest position.

For a bike to move forward successfully it should  undergo these 3 stages . If any  of the one is failed(because of rider not wearing helmet) the bike doesn’t move forward.

COMMUNICATION : It is  a way of connection between both bike and helmet .Till the time there is a communication between both bike and helmet the bike can be controlled by the rider but once the communication is lost(i.e only when the rider doesn’t wear a helmet) the bikes slows down and comes to rest state . This communication is achieved  by placing an IR(Infrared)emitter on the helmet and IR(Infrared)receiver on bike. When the emitter on the helmet  sends IR rays this will be received by the IR receiver on the bike which leads to successful communication between between  both helmet and bike.

SIGNAL GENERATION :After  the communication is successful then by using arduino and relay connected on breadboard we send  signals in order to supply the continuous  power to sparkplug .If the communication is not successful which means the rider is not wearing the helmet so the signal will not be generated  and there will be no power supplied  to  sparkplug.

IGNITION :When the signal is generated which means power will be supplied to sparkplug and thus the ignition will be done . But when there is no signal generated which means failure in communication  and thus ignition cannot be done and bike comes to rest automatically.




