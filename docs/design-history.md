# Crabby design history

Crabby was built by FTC Team 9384, the Hydraulic Hydras, for the 2022-2023 POWERPLAY season. Work began at kickoff on September 10, 2022. The game rewarded teams for placing cones on junction poles of different heights and in designated field areas, with additional end-of-match bonuses. That challenge shaped every major mechanism on the robot.

The team produced three major robot iterations between kickoff and the State Championship. Each revision responded to a specific limitation observed during building or competition.

## Iteration 1: kickoff to Qualifier 4

### Linear slide

The first robot used a single [REV Robotics linear slide kit](https://www.revrobotics.com/rev-45-1507/) to reach the field's elevated scoring positions. The intake was attached to the bottom of the slide's final stage. The mechanism provided the needed reach, but the tall single-slide structure swayed when fully extended and the chassis moved. That motion could cause the robot to drop its cone.

### Chassis

The initial drive base used mecanum wheels for omnidirectional movement. Motors were mounted to aluminum C-channels with metal L-brackets, while the channels formed an H-shaped frame to keep the chassis square. The layout was based on the [REV Robotics Mecanum Drivetrain Kit](https://www.revrobotics.com/rev-45-1877/), with the remaining mechanisms bolted to the completed base.

### Intake

The original intake placed two compliant wheels on two servos with a narrow gap between them. A centered cone could be pulled in smoothly and held between the wheels, but the design did not reliably keep every cone upright or prevent it from falling out.

<p>
  <img src="../media/site/img_2019.jpg" width="49%" alt="First competition version of Crabby at a junction">
  <img src="../media/site/img_2020.jpg" width="49%" alt="Crabby maneuvering around cones and junctions">
</p>

## Iteration 2: Qualifier 4 to Super Qualifier

### Faster lift

The slide structure remained mostly unchanged, but its motor gearing was revised to increase lifting speed and shorten the scoring cycle.

### Claw intake

Because the compliant-wheel intake could not consistently keep cones upright, the team replaced it with a claw. The claw proved much more reliable for the robot's scoring workflow.

<img src="../media/site/gripper-v117.png" alt="CAD render of the revised cone claw">

### Direct-drive turret

The fixed lift forced the drivetrain to face a junction before scoring. To remove that alignment step, the team mounted the lift on a turret driven directly through the center of its lazy Susan bearing. The motor shaft occupied the turret's central axis, allowing the scoring assembly to rotate independently from the chassis. The team was not aware of an earlier FTC robot using this same direct-drive arrangement.

<img src="../media/site/img_0029.jpg" alt="Top view of the turret's central drive and bearing">

## Iteration 3: Super Qualifier to State Championship

### Dual slides and larger turret

A second linear slide was added to square the lift and reduce sway at maximum extension. The turret's small lazy Susan bearing was replaced with a larger one, providing enough support and surface area for both slides.

### Lower, stronger drivetrain

The chassis was substantially redesigned. Four 90-degree bevel gearboxes moved the drive motors inside the existing C-channels instead of pointing them toward the center of the robot. This placed the wheel axes through the channels' center openings and allowed a lower chassis. Additional cross-members distributed loads and kept the enlarged turret base square.

### Final intake

The claw from the second iteration was retained because it had solved the cone-retention problem.

<p>
  <img src="../media/site/20230204_192015.jpg" width="49%" alt="Team members servicing the revised robot">
  <img src="../media/site/img_1451.jpg" width="49%" alt="Front view of final Crabby configuration">
</p>

## Final configuration

The completed robot combined:

- A low, braced mecanum chassis.
- Four drive motors packaged inside the C-channels through bevel gearboxes.
- Two linear slides for reach and rigidity.
- A claw-style cone intake.
- A larger lazy Susan bearing.
- A compact, directly driven turret for chassis-independent aiming.

<img src="../media/site/final-bot-v9.png" alt="Final CAD rendering of Crabby">

[Watch Crabby in competition](../media/site/crabby-match-video.mp4).

## Sources

- [Original Crabby engineering project page](https://angelojamesny.com/crabby-2022-23)
- [FTC 2022-2023 POWERPLAY game animation](https://www.youtube.com/watch?v=HsitvZ0JaDc)
- [Original GrabCAD model listing](https://grabcad.com/library/ftc-9384-2022-2023-robot-1)

