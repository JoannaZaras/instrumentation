#ByteBuddy Instrumentation example

Project shows example of using ByteBuddy Agent to intercept of calling method doSomething from class User.
This method writes User's name to the console.

Sample command line to call the agent:
java -javaagent:./agent/build/libs/kodilla-agent.jar -jar ./build/libs/instrumentation-1.0-SNAPSHOT.jar
