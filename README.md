# Booster
This project is implemented as a distributed group based shopping system that involves TCP & UDP protocols in Java Language. The sender process takes user-entered "TCP-Group Server" IP and port from using keyboard. Next, it sends login credentials along with current member point to the TCP-Group server. The TCP-group server displays the message and verifies the credentials. If it is correct then the member's point is updated and a success message is sent back to the client. The TCP-group server is a concurrent server. Upon successful login, the Group server communicates with dedicated Silver/Gold/Platinum server to conduct the shopping process.
