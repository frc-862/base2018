# base2018
Base code for 2018

* Command Based
* Drive Subsystem
* JUnit (or similar) test bodies
* Nexus Camera integration direct from GRIP
* Logging
* Motion Profiling (tune with OBot, Sirius, and Flash)
* Isolate teleop input methods in custom Joystick Objects

New ideas/growth
* Live data publishing in development mode?
* Maintain robotstate for adaptive path following/improved auton/etc

# Build setup

You can use gradle to quickly setup an environment to build and deploy the robot.

Just run `gradlew build deploy` or `gradlew.bat build deploy` and the code will be deployed.

To setup integration with your IDE, just run `gradlew idea` or `gradlew eclipse` depending on whether you use IntelliJ or Eclipse.
After that, you should be able to open the project in your IDE.

## Other useful gradle tasks

Some other useful gradle tasks are `robotBuilder`, `restart_rio_code`, and `determine_rio_address`.
To run without an internet connection, append `--offline` to your gradle command.