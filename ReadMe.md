# SNS ASSIGNMENT2
* Multithread Server is created
* When Client Sends the Message first it's CRC is calculated then that CRC and message respective matrix is sent via message object ,for sending the messages pickle library is used. 
* Server receives the message object now the server extracts and the matrix and decodes it into the string and calculates the CRC of the received string,if the CRC is equal to the Received CRC than the message received is succesul otherwise there is error in the message and this status is send back to client.