# hello-world
Trying to create a SmartThings App to use motion and Lux levels
Have ZERO programming knowledge beyond writing/editing DOS batch files (yes, I'm THAT old - who remembers autoexec.bat?)
Available apps use motion or lux (turn on if I go in a room, turn on if it gets dark)
Other apps rely on outside light levels for their trigger or to modify a dimmer setting once the light is triggered by another thing
I have a gloomy corner in my kitchen that gets dark even during the day (but not all day, and not every day)
When I walk in, I want the light in that corner to go on ONLY if it's too dark to see what I'm doing
The motion/lux sensor is located in the gloomy corner
Light levels in this spot are the result of a complicated combination of time of day, sun angle, cloudiness AND whether the main light in the kitchen is already on
Sunrise/sunset won't help
Outdoor light levels won't help
This should be so simple... If [motion] And [Lux < value] Then [turn on light for x minutes after motion stops]
The Lux values will need to fall into a relatively narrow (indoor) range (I don't need it if the main light is on), and the switching sensitivity must also be quite small
I need to find out how to tweak the Fibaro sensor using SmartThings settings so it reads every 10 mins or so (initially to find my optimum on/off points) and I need to make its amount of change before switching something less than the default (I think) 200 Lux
So that's where I'm at and what I'm hoping to do, but I don't even know if this is the right place to be!
