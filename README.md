# semantic_pose_sounder
Semantic location based sound trigger package for ROS.



**Dependencies**:

- semantic_pose
- pygame
- rospy



This package is designed to work with [the semantic_pose package](https://github.com/grassjelly/semantic_pose). It's written for easy configuration with the config.yaml file in the config directory.



Simply add in the correct TF frames, and specify your location boundaries, and the sound to play when the robot enters said location. Easy!



To test, remember to use the launch file! That's how you'll load the .yaml config parameters!

```bash
$ roslaunch semantic_pose_sounder semantic_pose_sounder.launch
```

