#### A proposed deep tracker

- This file provides results of the proposed deep tracker tested on this <a href='http://cvlab.hanyang.ac.kr/tracker_benchmark/index.html'>benchmark</a>.

###### General results

|   CVPR13   | <img src='./imgs/cvpr13_OPE_overlap.svg'> | <img src='./imgs/cvpr13_OPE_locaterr.svg'> |
| :--------: | ----------------------------------------- | ------------------------------------------ |
| **OTB50**  | <img src='./imgs/otb50_OPE_overlap.svg'>  | <img src='./imgs/otb50_OPE_locaterr.svg'>  |
| **OTB100** | <img src='./imgs/otb100_OPE_overlap.svg'> | <img src='./imgs/otb100_OPE_locaterr.svg'> |

###### Results of all challenges

  - Because of too many images, all challenge results have been arranged in the form of table.
  - Red => First
  - Orange => Second
  - Green => Third
  - Blue => Fourth
  - Black => After the first four

|   CVPR13   | <img src='./imgs/cvpr13_overlap_challenges.PNG'> | <img src='./imgs/cvpr13_location_challenges.PNG'> |
| :--------: | ------------------------------------------------ | ------------------------------------------------- |
| **OTB50**  | <img src='./imgs/otb50_overlap_challenges.PNG'>  | <img src='./imgs/otb50_location_challenges.PNG'>  |
| **OTB100** | <img src='./imgs/otb100_overlap_challenges.PNG'> | <img src='./imgs/otb100_location_challenges.PNG'> |

###### All videos views

- all results in the perspective of  videos
- green: ground-truth
- red: tracked result

| <img src='./gifs/Basketball.gif'> | <img src='./gifs/Biker.gif'>        | <img src='./gifs/Bird1.gif'>        | <img src='./gifs/Bird2.gif'>      | <img src='./gifs/BlurBody.gif'> | <img src='./gifs/BlurCar1.gif'>  | <img src='./gifs/BlurCar2.gif'> | <img src='./gifs/BlurCar3.gif'> | <img src='./gifs/BlurCar4.gif'>   | <img src='./gifs/BlurFace.gif'>  |
| --------------------------------- | ----------------------------------- | ----------------------------------- | --------------------------------- | ------------------------------- | -------------------------------- | ------------------------------- | ------------------------------- | --------------------------------- | -------------------------------- |
| <img src='./gifs/BlurOwl.gif'>    | <img src='./gifs/Board.gif'>        | <img src='./gifs/Bolt.gif'>         | <img src='./gifs/Bolt2.gif'>      | <img src='./gifs/Box.gif'>      | <img src='./gifs/Boy.gif'>       | <img src='./gifs/Car1.gif'>     | <img src='./gifs/Car2.gif'>     | <img src='./gifs/Car24.gif'>      | <img src='./gifs/Car4.gif'>      |
| <img src='./gifs/CarDark.gif'>    | <img src='./gifs/CarScale.gif'>     | <img src='./gifs/ClifBar.gif'>      | <img src='./gifs/Coke.gif'>       | <img src='./gifs/Couple.gif'>   | <img src='./gifs/Coupon.gif'>    | <img src='./gifs/Crossing.gif'> | <img src='./gifs/Crowds.gif'>   | <img src='./gifs/Dancer.gif'>     | <img src='./gifs/Dancer2.gif'>   |
| <img src='./gifs/David.gif'>      | <img src='./gifs/David2.gif'>       | <img src='./gifs/David3.gif'>       | <img src='./gifs/Deer.gif'>       | <img src='./gifs/Diving.gif'>   | <img src='./gifs/Dog.gif'>       | <img src='./gifs/Dog1.gif'>     | <img src='./gifs/Doll.gif'>     | <img src='./gifs/DragonBaby.gif'> | <img src='./gifs/Dudek.gif'>     |
| <img src='./gifs/FaceOcc1.gif'>   | <img src='./gifs/FaceOcc2.gif'>     | <img src='./gifs/Fish.gif'>         | <img src='./gifs/FleetFace.gif'>  | <img src='./gifs/Football.gif'> | <img src='./gifs/Football1.gif'> | <img src='./gifs/Freeman1.gif'> | <img src='./gifs/Freeman3.gif'> | <img src='./gifs/Freeman4.gif'>   | <img src='./gifs/Girl.gif'>      |
| <img src='./gifs/Girl2.gif'>      | <img src='./gifs/Gym.gif'>          | <img src='./gifs/Human2.gif'>       | <img src='./gifs/Human3.gif'>     | <img src='./gifs/Human4-2.gif'> | <img src='./gifs/Human5.gif'>    | <img src='./gifs/Human6.gif'>   | <img src='./gifs/Human7.gif'>   | <img src='./gifs/Human8.gif'>     | <img src='./gifs/Human9.gif'>    |
| <img src='./gifs/Ironman.gif'>    | <img src='./gifs/Jogging-1.gif'>    | <img src='./gifs/Jogging-2.gif'>    | <img src='./gifs/Jump.gif'>       | <img src='./gifs/Jumping.gif'>  | <img src='./gifs/KiteSurf.gif'>  | <img src='./gifs/Lemming.gif'>  | <img src='./gifs/Liquor.gif'>   | <img src='./gifs/Man.gif'>        | <img src='./gifs/Matrix.gif'>    |
| <img src='./gifs/Mhyang.gif'>     | <img src='./gifs/MotorRolling.gif'> | <img src='./gifs/MountainBike.gif'> | <img src='./gifs/Panda.gif'>      | <img src='./gifs/RedTeam.gif'>  | <img src='./gifs/Rubik.gif'>     | <img src='./gifs/Shaking.gif'>  | <img src='./gifs/Singer1.gif'>  | <img src='./gifs/Singer2.gif'>    | <img src='./gifs/Skater.gif'>    |
| <img src='./gifs/Skater2.gif'>    | <img src='./gifs/Skating1.gif'>     | <img src='./gifs/Skating2-1.gif'>   | <img src='./gifs/Skating2-2.gif'> | <img src='./gifs/Skiing.gif'>   | <img src='./gifs/Soccer.gif'>    | <img src='./gifs/Subway.gif'>   | <img src='./gifs/Surfer.gif'>   | <img src='./gifs/Suv.gif'>        | <img src='./gifs/Sylvester.gif'> |
| <img src='./gifs/Tiger1.gif'>     | <img src='./gifs/Tiger2.gif'>       | <img src='./gifs/Toy.gif'>          | <img src='./gifs/Trans.gif'>      | <img src='./gifs/Trellis.gif'>  | <img src='./gifs/Twinnings.gif'> | <img src='./gifs/Vase.gif'>     | <img src='./gifs/Walking.gif'>  | <img src='./gifs/Walking2.gif'>   | <img src='./gifs/Woman.gif'>     |

