[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/YFgwt0yY)
# MiniTorch Module 2

<img src="https://minitorch.github.io/minitorch.svg" width="50%">


* Docs: https://minitorch.github.io/

* Overview: https://minitorch.github.io/module2/module2/

This assignment requires the following files from the previous assignments. You can get these by running

```bash
python sync_previous_module.py previous-module-dir current-module-dir
```

The files that will be synced are:

        minitorch/operators.py minitorch/module.py minitorch/autodiff.py minitorch/scalar.py minitorch/scalar_functions.py minitorch/module.py project/run_manual.py project/run_scalar.py project/datasets.py



Simple:
<img src="images/simple1.png">
<img src="images/simple2.png">
<img src="images/simple3.png">
number of points: 50
number of hidden layers: 2
learning rate: 0.1
number of epochs: 500
Epoch: 0/500, loss: 0, correct: 0
Epoch: 10/500, loss: 37.04466787477349, correct: 24
Epoch: 20/500, loss: 35.14459019157752, correct: 24
Epoch: 30/500, loss: 34.687611309836505, correct: 25
Epoch: 40/500, loss: 34.58507841713337, correct: 26
Epoch: 50/500, loss: 34.55997740244538, correct: 26
Epoch: 60/500, loss: 34.5505753609364, correct: 26
Epoch: 70/500, loss: 34.543969834061365, correct: 26
Epoch: 80/500, loss: 34.53752223375938, correct: 26
Epoch: 90/500, loss: 34.52792319981603, correct: 26
Epoch: 100/500, loss: 34.51312732863864, correct: 26
Epoch: 110/500, loss: 34.4963566743471, correct: 26
Epoch: 120/500, loss: 34.47177296595259, correct: 26
Epoch: 130/500, loss: 34.43753297159141, correct: 26
Epoch: 140/500, loss: 34.39805355272544, correct: 26
Epoch: 150/500, loss: 34.35536478380102, correct: 26
Epoch: 160/500, loss: 34.3069082866675, correct: 26
Epoch: 170/500, loss: 34.23991170122101, correct: 26
Epoch: 180/500, loss: 34.13915271497539, correct: 26
Epoch: 190/500, loss: 34.011946018430976, correct: 26
Epoch: 200/500, loss: 33.75942873072348, correct: 26
Epoch: 210/500, loss: 33.3693993331866, correct: 26
Epoch: 220/500, loss: 32.81715865642421, correct: 36
Epoch: 230/500, loss: 32.03979098599239, correct: 39
Epoch: 240/500, loss: 30.944146917433223, correct: 39
Epoch: 250/500, loss: 29.697042191461687, correct: 41
Epoch: 260/500, loss: 28.268224307479596, correct: 41
Epoch: 270/500, loss: 26.556880230635915, correct: 45
Epoch: 280/500, loss: 24.56933028870782, correct: 45
Epoch: 290/500, loss: 22.375666060892375, correct: 47
Epoch: 300/500, loss: 20.07192184312115, correct: 49
Epoch: 310/500, loss: 17.75654768608744, correct: 50
Epoch: 320/500, loss: 15.596091200388765, correct: 50
Epoch: 330/500, loss: 13.658573053419559, correct: 50
Epoch: 340/500, loss: 12.018727860055156, correct: 50
Epoch: 350/500, loss: 10.65923689919784, correct: 50
Epoch: 360/500, loss: 9.547233976677381, correct: 50
Epoch: 370/500, loss: 8.636493208490133, correct: 50
Epoch: 380/500, loss: 7.87690751974497, correct: 50
Epoch: 390/500, loss: 7.237830573598318, correct: 50
Epoch: 400/500, loss: 6.6947081201604455, correct: 50
Epoch: 410/500, loss: 6.228818102494084, correct: 50
Epoch: 420/500, loss: 5.827223354642109, correct: 50
Epoch: 430/500, loss: 5.481520103756643, correct: 50
Epoch: 440/500, loss: 5.178966689130644, correct: 50
Epoch: 450/500, loss: 4.913884793688938, correct: 50
Epoch: 460/500, loss: 4.677485437226647, correct: 50
Epoch: 470/500, loss: 4.465321530792759, correct: 50
Epoch: 480/500, loss: 4.2738888122930945, correct: 50
Epoch: 490/500, loss: 4.10032298548282, correct: 50
Epoch: 500/500, loss: 3.9422513563658073, correct: 50
Diag:
<img src="images/diag1.png">
<img src="images/diag2.png">
<img src="images/diag3.png">
number of points: 50
number of hidden layers: 3
learning rate: 0.1
number of epochs: 600
Epoch: 0/500, loss: 0, correct: 0
Epoch: 10/500, loss: 37.04466787477349, correct: 24
Epoch: 20/500, loss: 35.14459019157752, correct: 24
Epoch: 30/500, loss: 34.687611309836505, correct: 25
Epoch: 40/500, loss: 34.58507841713337, correct: 26
Epoch: 50/500, loss: 34.55997740244538, correct: 26
Epoch: 60/500, loss: 34.5505753609364, correct: 26
Epoch: 70/500, loss: 34.543969834061365, correct: 26
Epoch: 80/500, loss: 34.53752223375938, correct: 26
Epoch: 90/500, loss: 34.52792319981603, correct: 26
Epoch: 100/500, loss: 34.51312732863864, correct: 26
Epoch: 110/500, loss: 34.4963566743471, correct: 26
Epoch: 120/500, loss: 34.47177296595259, correct: 26
Epoch: 130/500, loss: 34.43753297159141, correct: 26
Epoch: 140/500, loss: 34.39805355272544, correct: 26
Epoch: 150/500, loss: 34.35536478380102, correct: 26
Epoch: 160/500, loss: 34.3069082866675, correct: 26
Epoch: 170/500, loss: 34.23991170122101, correct: 26
Epoch: 180/500, loss: 34.13915271497539, correct: 26
Epoch: 190/500, loss: 34.011946018430976, correct: 26
Epoch: 200/500, loss: 33.75942873072348, correct: 26
Epoch: 210/500, loss: 33.3693993331866, correct: 26
Epoch: 220/500, loss: 32.81715865642421, correct: 36
Epoch: 230/500, loss: 32.03979098599239, correct: 39
Epoch: 240/500, loss: 30.944146917433223, correct: 39
Epoch: 250/500, loss: 29.697042191461687, correct: 41
Epoch: 260/500, loss: 28.268224307479596, correct: 41
Epoch: 270/500, loss: 26.556880230635915, correct: 45
Epoch: 280/500, loss: 24.56933028870782, correct: 45
Epoch: 290/500, loss: 22.375666060892375, correct: 47
Epoch: 300/500, loss: 20.07192184312115, correct: 49
Epoch: 310/500, loss: 17.75654768608744, correct: 50
Epoch: 320/500, loss: 15.596091200388765, correct: 50
Epoch: 330/500, loss: 13.658573053419559, correct: 50
Epoch: 340/500, loss: 12.018727860055156, correct: 50
Epoch: 350/500, loss: 10.65923689919784, correct: 50
Epoch: 360/500, loss: 9.547233976677381, correct: 50
Epoch: 370/500, loss: 8.636493208490133, correct: 50
Epoch: 380/500, loss: 7.87690751974497, correct: 50
Epoch: 390/500, loss: 7.237830573598318, correct: 50
Epoch: 400/500, loss: 6.6947081201604455, correct: 50
Epoch: 410/500, loss: 6.228818102494084, correct: 50
Epoch: 420/500, loss: 5.827223354642109, correct: 50
Epoch: 430/500, loss: 5.481520103756643, correct: 50
Epoch: 440/500, loss: 5.178966689130644, correct: 50
Epoch: 450/500, loss: 4.913884793688938, correct: 50
Epoch: 460/500, loss: 4.677485437226647, correct: 50
Epoch: 470/500, loss: 4.465321530792759, correct: 50
Epoch: 480/500, loss: 4.2738888122930945, correct: 50
Epoch: 490/500, loss: 4.10032298548282, correct: 50
Epoch: 500/500, loss: 3.9422513563658073, correct: 50

Split:
<img src="images/split1.png">
<img src="images/split2.png">
<img src="images/split3.png">
number of points: 50
number of hidden layers: 4
learning rate: 0.5
number of epochs: 600
Epoch: 0/600, loss: 0, correct: 0
Epoch: 10/600, loss: 33.43380276489284, correct: 29
Epoch: 20/600, loss: 33.08084585289608, correct: 29
Epoch: 30/600, loss: 32.64092684920051, correct: 31
Epoch: 40/600, loss: 32.058824809784795, correct: 34
Epoch: 50/600, loss: 31.3013043910546, correct: 35
Epoch: 60/600, loss: 30.334378548902098, correct: 35
Epoch: 70/600, loss: 29.193529220688028, correct: 36
Epoch: 80/600, loss: 27.769210432924098, correct: 36
Epoch: 90/600, loss: 25.991109222107653, correct: 36
Epoch: 100/600, loss: 23.917926972165695, correct: 36
Epoch: 110/600, loss: 27.871064161451667, correct: 41
Epoch: 120/600, loss: 21.800214641024255, correct: 44
Epoch: 130/600, loss: 22.130739013439285, correct: 46
Epoch: 140/600, loss: 22.271105236298858, correct: 43
Epoch: 150/600, loss: 17.914384492789072, correct: 46
Epoch: 160/600, loss: 20.040648156670823, correct: 42
Epoch: 170/600, loss: 17.243521567915806, correct: 44
Epoch: 180/600, loss: 13.46816754145052, correct: 48
Epoch: 190/600, loss: 23.84987276784036, correct: 40
Epoch: 200/600, loss: 11.59113601947298, correct: 48
Epoch: 210/600, loss: 11.197192061693023, correct: 47
Epoch: 220/600, loss: 18.27439267858757, correct: 45
Epoch: 230/600, loss: 7.363980529311964, correct: 49
Epoch: 240/600, loss: 5.807355048975812, correct: 50
Epoch: 250/600, loss: 5.186755071831155, correct: 50
Epoch: 260/600, loss: 4.75231166905393, correct: 50
Epoch: 270/600, loss: 34.89566662671975, correct: 37
Epoch: 280/600, loss: 8.297333978861845, correct: 46
Epoch: 290/600, loss: 8.431189298056593, correct: 46
Epoch: 300/600, loss: 6.340044541698974, correct: 46
Epoch: 310/600, loss: 5.325097296740664, correct: 47
Epoch: 320/600, loss: 3.7276342569599983, correct: 50
Epoch: 330/600, loss: 3.3640386221476293, correct: 50
Epoch: 340/600, loss: 3.1028064895061243, correct: 50
Epoch: 350/600, loss: 3.161525857671269, correct: 50
Epoch: 360/600, loss: 25.659691812228267, correct: 41
Epoch: 370/600, loss: 7.23442379291523, correct: 48
Epoch: 380/600, loss: 3.4232256589782963, correct: 50
Epoch: 390/600, loss: 2.9294959050107945, correct: 50
Epoch: 400/600, loss: 2.6930304421971165, correct: 50
Epoch: 410/600, loss: 2.573867935002711, correct: 50
Epoch: 420/600, loss: 5.619366382176739, correct: 46
Epoch: 430/600, loss: 6.0596133893788515, correct: 46
Epoch: 440/600, loss: 3.7934927942427685, correct: 49
Epoch: 450/600, loss: 3.473999905788972, correct: 49
Epoch: 460/600, loss: 3.3868545815737567, correct: 49
Epoch: 470/600, loss: 3.296011741389204, correct: 49
Epoch: 480/600, loss: 3.235915931511249, correct: 49
Epoch: 490/600, loss: 3.072482666131603, correct: 49
Epoch: 500/600, loss: 2.604102662912909, correct: 49
Epoch: 510/600, loss: 2.136768679365593, correct: 50
Epoch: 520/600, loss: 1.7672014550226238, correct: 50
Epoch: 530/600, loss: 1.498563381319219, correct: 50
Epoch: 540/600, loss: 1.4141607424111753, correct: 50
Epoch: 550/600, loss: 1.3504360921898795, correct: 50
Epoch: 560/600, loss: 1.289940350302834, correct: 50
Epoch: 570/600, loss: 1.2336701558315768, correct: 50
Epoch: 580/600, loss: 1.181503171468792, correct: 50
Epoch: 590/600, loss: 1.1330872811261046, correct: 50
Epoch: 600/600, loss: 1.0838638791949138, correct: 50


XOR:
<img src="images/xor1.png">
<img src="images/xor2.png">
<img src="images/xor3.png">
number of points: 50
number of hidden layers: 5
learning rate: 0.5
number of epochs: 625
Epoch: 0/625, loss: 0, correct: 0
Epoch: 10/625, loss: 33.29272586804448, correct: 38
Epoch: 20/625, loss: 31.933702207732644, correct: 36
Epoch: 30/625, loss: 30.109269778649782, correct: 38
Epoch: 40/625, loss: 27.618849692521255, correct: 37
Epoch: 50/625, loss: 27.600088039888945, correct: 35
Epoch: 60/625, loss: 22.971380709555554, correct: 40
Epoch: 70/625, loss: 23.90159528447079, correct: 41
Epoch: 80/625, loss: 28.641603471303384, correct: 32
Epoch: 90/625, loss: 23.80217434954302, correct: 39
Epoch: 100/625, loss: 21.540300447311974, correct: 39
Epoch: 110/625, loss: 19.26747789392672, correct: 39
Epoch: 120/625, loss: 17.29722261456297, correct: 42
Epoch: 130/625, loss: 14.354835892500658, correct: 44
Epoch: 140/625, loss: 17.61091915596096, correct: 39
Epoch: 150/625, loss: 18.489674345574496, correct: 40
Epoch: 160/625, loss: 14.024029663485432, correct: 43
Epoch: 170/625, loss: 16.176075764706802, correct: 40
Epoch: 180/625, loss: 9.935001410669026, correct: 47
Epoch: 190/625, loss: 18.225077423910612, correct: 40
Epoch: 200/625, loss: 7.752251507223811, correct: 48
Epoch: 210/625, loss: 6.087600153720627, correct: 50
Epoch: 220/625, loss: 9.965653856484872, correct: 46
Epoch: 230/625, loss: 5.493442155927169, correct: 50
Epoch: 240/625, loss: 4.458534363716128, correct: 50
Epoch: 250/625, loss: 5.145526010696036, correct: 49
Epoch: 260/625, loss: 7.6413717108057995, correct: 49
Epoch: 270/625, loss: 3.7281974681857215, correct: 50
Epoch: 280/625, loss: 3.21679382219898, correct: 50
Epoch: 290/625, loss: 2.8440415090214786, correct: 50
Epoch: 300/625, loss: 3.310352223363277, correct: 48
Epoch: 310/625, loss: 15.015108663012548, correct: 42
Epoch: 320/625, loss: 2.5535535026013974, correct: 50
Epoch: 330/625, loss: 2.251787850161779, correct: 50
Epoch: 340/625, loss: 2.0198775152925865, correct: 50
Epoch: 350/625, loss: 1.8351611392433755, correct: 50
Epoch: 360/625, loss: 1.7026991438119554, correct: 50
Epoch: 370/625, loss: 1.7030707988171871, correct: 50
Epoch: 380/625, loss: 2.876306926205687, correct: 48
Epoch: 390/625, loss: 26.907729943515964, correct: 36
Epoch: 400/625, loss: 14.278166102487999, correct: 40
Epoch: 410/625, loss: 9.752632414157242, correct: 47
Epoch: 420/625, loss: 9.936635737290251, correct: 45
Epoch: 430/625, loss: 3.3323094464783423, correct: 48
Epoch: 440/625, loss: 1.6944235373134986, correct: 50
Epoch: 450/625, loss: 1.4796260085036277, correct: 50
Epoch: 460/625, loss: 1.324353593790295, correct: 50
Epoch: 470/625, loss: 1.207386828312068, correct: 50
Epoch: 480/625, loss: 1.1173151662342389, correct: 50
Epoch: 490/625, loss: 1.0414237164194735, correct: 50
Epoch: 500/625, loss: 0.9762341869540034, correct: 50
Epoch: 510/625, loss: 0.9191514078593899, correct: 50
Epoch: 520/625, loss: 0.8686466053044345, correct: 50
Epoch: 530/625, loss: 0.8235730995606907, correct: 50
Epoch: 540/625, loss: 0.783048784542987, correct: 50
Epoch: 550/625, loss: 0.7464176364765499, correct: 50
Epoch: 560/625, loss: 0.7131088243947851, correct: 50
Epoch: 570/625, loss: 0.6829475140183808, correct: 50
Epoch: 580/625, loss: 0.6552029307512985, correct: 50
Epoch: 590/625, loss: 0.629613451275519, correct: 50
Epoch: 600/625, loss: 0.6060674198266995, correct: 50
Epoch: 610/625, loss: 0.5838827674946643, correct: 50
Epoch: 620/625, loss: 0.5633334513524354, correct: 50
Epoch: 625/625, loss: 0.553648244030371, correct: 50
