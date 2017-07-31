# Kinesis-agent

This Kinesis agent can be run as non-root user

Installing AmazonKinesis Agent

Download Code from Github  :
https://github.com/kiranclarivate/Kinesis-agent.git

You should have full access on below directories.You can ask server root user to create these folders and give you full ownership of it.Root user can achieve this by running chown <username> <folder> command.
  1./var/log/aws-kinesis-agent
  2./etc/aws-kinesis/
 Navigate to Kinesis-agent.
Open Kinesis.sh
Set JAVA_HOME and KINESIS_HOME as per your system .Save the file.
Java version must be 1.7+
Run .kinesis.sh build to build the project
Make necessary changes in /etc/aws-kinesis/agent.json file.

Run . kinesis.sh start to start the agent.
Run . kinesis.sh stop to stop the agent.


