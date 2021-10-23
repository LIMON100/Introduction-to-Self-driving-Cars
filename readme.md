# Introduction to Self Driving Car

## Taxonomy of Driving

### Driving Task:

Lateral Control - Steering

Longitudinal Control - braking, acceleration

Object and Event detection and response(OEDR) - detection, reaction

Planning - long-term, short-term


## Requirements for Perception:

### Perception:

we want to be able to make sense of the environment around us and the way we're moving within it.

#### Goals fro perception:

#### Static objects:
	road and lane marking
	curbing(off-road)
	traffic lights
	road-sign
	construction sign, obstruction & more(on-road)

#### Dynamic Objects:
	vehicles-4 wheelers
		 2 wheelers
	pedastrians

#### Ego localization
	position
	velocity, acceleration
	orientation, angular motion
	
	

#### Sensor

Detect the measures or detect a property of the environment, or changes to a property

#### category:
	exteroceptive: surroundings
				(camera, stereo, 
				lidar(number_of_beams, points_per_second, rotation_rate, field_of_view)solid state lidar
				Radar(robust object detection and relative speed estimation, comparison(range, field-of-view, position-speed accuracy))
				ultrasonic-short range all weather distance measure, low cost(range, cost, field of view)
				
	proprioceptive: internal
				Gnss/IMU-global positioning management system()	
				wheel odometry- Tracks wheel velocities and orientation(speed accuracy, position drift)



#### Hardware Configuration:

	aggresive deceleration = 5 m/s^2
	comfortable deceleration = 2 m/s^2
	
	

#### Software Architecture:

Environment Perception

Environment Mapping

Moting Planning

Controller

System Supervisor


#### Software architecture

#### Environment Perception

#### Environment Mapping

#### Moting Planning

#### Controller

#### System Supervisor

