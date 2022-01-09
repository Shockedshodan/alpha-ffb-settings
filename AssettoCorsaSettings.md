# Assetto Corsa Settings

## Default In-Game Settings

### Alpha Base

| CM > AC > Controls > Force Feedback | Value |
| - | - |
| Gain | 70% |

| CM > CSP > FFB Tweaks | Value |
| - | - |
| Output real steering forces | ON |
| Wheel peak torque | 15 Nm |

### Alpha Mini Base

NOTE: the value is prediction, haven't tested on mini

| CM > AC > Controls > Force Feedback | Value |
| - | - |
| Gain | 100% |

| CM > CSP > FFB Tweaks | Value |
| - | - |
| Output real steering forces | ON |
| Wheel peak torque | 10 Nm |

## Alpha Base Vendor's settings 

File: [`AC.ini`](AC.ini)

<details>
  <summary>INI content</summary>

  ```
  [MachineSetUp]
TotalForce=100
SmoothLevel=1
WheelInertia=0
WheelSpring=0
WheelDamper=23
WheelFriction=20

[GameEffect]
GameSpring=100
GameDamper=100
GameInertia=100
GameFriction=100

[CarSetting]
WheelSpeed=100
Suspension=6
LimitHardness=1

[StreeingAngle]
WheelAngle=900
LimitAngle=900
Synchronous=1

[Softward]
Software=A2.2

[Language]
Languages=2
  ```
</details>

## Custom Alpha Base Settings For Cars
### TCR

File: [`AC_TCR_Honda.ini`](AC_TCR_Honda.ini)

Note: May work for all TCR cars.

- [X] Default in-game settings

| Alpha Manager | Value |
| -- | -- |
| TotalForce | 85 |
| Limit Angle | 390 |
| SmoothLevel | 2 |

