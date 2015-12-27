# Bionics - notes

## Terms
See glossary.md

## Labs
Various labs working in this field, and any specialities of the labs

* MIT Media Lab working on AFOs
* UMich under Cain, Kao, Ferris use almost exclusively pneumatic muscles. Built a KAFO with thigh/hamstring muscles
* ASU Phoenix used regenerative braking at ankle of AFO to power the onboard computer
* Case Western Reserve working on RGOs

## Devices
Current devices released in the field

* InMotion Anklebot: MIT Media Lab AFO
* Stride Management Assist system by Honda can be used by the able bodied as well as disabled
* Raytheon XOS exoskeleton
* Honda HAL (hybrid assisted limb) can be single-joint or full exoskeleton. Most versatile, but can't do a running pace
* ReWalk at Tel Aviv U, Israel: similar to Ekso
* BLEEX (Berkeley Lower Extremity Exoskeleton system) at Cal
* HULC (Human Universal Load Carrier) military
* Ekso/eLEGS: toned down HULC reduces lower limb loading even at running pace. Can help with sit/stand transition. Reduced to rehabilitation centers in 2010
* REX by REX Bionics (New Zealand) - more like a walking robot, can work without anyone in it
* Parker Hannifin Indego exoskeleton from Vanderbilt in Nashville, TN hip/knee (but not foot/ankle) exoskeleton, uses FES
* MyoPro by Myomo (2013) upper limb exoskeleton
* LOPES: treadmill based gait training
* Lokomat: treadmill based gait training (Hocoma AG, Switzerland)

## Notes
In no particular order, to be restructured later

* Average energy cost of walking with a powered orthosis is less than that of walking in an RGO or HKAFO, which means the person can walk farther in a pLEO [Sherk][1]
* FES is used to reduce electrical demand of motors [Sherk][1]
* Types of actuators: linear, rotary, pneumatic. Linear must cross the joint to be moved, can push or pull. Usually done with screw gears. Rotary motors pretty self explanatory, usually on or near the joint. Pneumatic are most similar to skeletal muscles, can only expand/contract. Made of an elastic cylinder surrounded by loose braided material (usu. carbon fiber). Fill the balloon, length contracts as diameter expands. Need abductors/adductors. [Sherk][1]
* AFOs one of the most researched powered orthotics [Sherk][1]
* "ankle rockers", "extra" energy from plantarflexion [Sherk][1]
* Foot switch 30x faster than myoelectric input for learning step timing [Sherk][1]
* Hip might be a good source of stability & power generation. Medically important (leading cause of falls) so might be covered by insurance sooner [Sherk][1]
* Passive devices are simple & cheap but don't adapt to different needs & can't give sensory feedback [Tucker][2]
* Powered orthorics can improve ADL, reduce energy needs, not hurt the unaffected muscles & joints, increase gait symmetry [Tucker][2]
* Gait symmetry is important so the wearer doesn't throw off previously uninjured parts of the body to compensate for the injured piece [Tucker][2]
* Work on this stuff is increasingly important because the population is becoming older, and older people suffer a lot of gait-related issues: pathological gait from stroke or spinal cord injuries, Parkinson's, lower limb amputations [Tucker][2]
* Helpful fields of improvement that grow this one: actuation, energy storage, miniaturized sensing, automated pattern recognition, embedded computing [Tucker][2]
* Open questions prior to mass adoption: How can we improve physical and cognitive interactions? How can we generalize control methods & mechanisms across different parts of the body? How do humans normally move, and how can we use this? What is different between lab environments and real world challenges? [Tucker][2]
* High level control: device detects locomotive intent, recognizes task at hand (standing descending stairs) [Tucker][2]
* Direct volitional control: directly manipulating joint motion, torque, angles, etc. [Tucker][2]
* Mid-level control: user uses volitional control to communicate desired state (e.g. walking); device determines current status & next steps [Tucker][2]
* Spend more time with Fig.1 in [Tucker][2]
* "The human and the robot must work together in an intuitive and synergistic way: the device recognizes the user's motion intentions and acts to assist with that movement *with minimal congnitive disruption* and required compensatory motion, and rich sensory feedback is provided to the user. Thus, a well-designed and interactive P/O controller must begin with an understanding of the human controller." [Tucker][2] (emphasis added)
* Human locomotion depends on larger patterns generated in the spine (through a network of spinal interneurons - CPG) and on volitional and reflex-dependent fine control at different levels [Tucker][2]
* Volitional motor control originates at the supraspinal (cortical/brain) level. This is e.g. major changes in locomotor patterns. Specifically: premotor and motor cortex, cerebellum, brain stem. Brain stem regulates CPG and reflexes. These systems also aggregate & process vestibular & visual systems, which are used in balance, orientation, and precision movement control [Tucker][2]
* Locomotor patterns are modulated by feedback from muscle spindles, Golgi tendon organs, mechanoreceptors on joint capsules, tactile mechanoreceptors, free nerve endings on the skin (sense of touch). This is used to increase gait efficiency and stabilize posture during perturbations [Tucker][2] 


## References
Full citations later; these papers can be found in the `papers` folder

[1]: Sherk, The Evolution of Powered Orthotic Technology
[2]: Tucker, Control strategies for active lower extremity
prosthetics and orthotics: a review
