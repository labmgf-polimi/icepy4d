# Camera

You can easily import Icepy classes by

```python
import icepy.classes as icepy_classes
```

and directly access to the Camera class by

```python
icepy_classes.Camera
```

::: icepy.classes.camera.Camera
    options:
      members:
        - width
        - height
        - K
        - dist
        - extrinsics
        - pose
        - C
        - t
        - R
        - euler_angles
        - P
        - update_K
        - update_dist
        - update_extrinsics
        - read_calibration_from_file
        - extrinsics_to_pose
        - pose_to_extrinsics
        - project_point
        - factor_P
        - Rt_to_extrinsics
        - C_from_P
        - build_pose_matrix
        - euler_from_R