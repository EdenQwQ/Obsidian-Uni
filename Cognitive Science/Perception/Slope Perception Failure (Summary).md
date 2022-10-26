#psychology/cognitive-science/perception #summary #psychology/cognitive-science/technology/VR

# Introduction

## Research Inspiration

That the orientation of a down-sloping hill is always overestimated was observed by the authors, which intrigued their curiosity.

## Comparison to Earlier Researches
Earlier researches focused mainly on viewing distance and the comparison of "top" and "down" viewing, while this stresses more on the direction of gaze.

## Highlights

The three experiments uses both real and **virtual** environment. In the latter one, Virtual Reality is used to render a immersive experience while being able to record important data such as optical orientation. Yet real-life experiments are conducted to prevent bias in virtual environment.

# Experiments

## Experiment 1

> Visual matches of small wooden slopes

### Methods

 - Participants are asked to observe a wooden slope placed in front of them, and adjust the wooden piece with a string to match the slant.
 - There are 6 conditions: combination of 3 reference angles and 2 viewing distances.
 - <u>The matching slope is irregularly curved on the side to discourage linear perspective.</u>

### Results

The match slope is raised higher when the reference slope is further away, which indicates the basic failure of downhill slope constancy. Yet the effect is reliable for the two steeper slopes, but not for the least steep one.

### Limitations

The viewed object is simply a small wooden slope, which can't stand for larger real-life objects such as a hill.

## Experiment 2 A

>Verbal estimates of virtual slopes

### Methods

 - Use Virtual Reality system to render a virtual environment. A large slope is presented behind a wall and is visible through a wide aperture. Participants are to observe the slope through the aperture.
 - A white ball is placed on the slope as a reference mark during judgments.
 - Each participants are asked to make 30 judgments of slope across three conditions:
	1. Main condition: The ball is located 2 m down the surface and the viewer is simulated as being either at the edge (Near) or 1 m back from the edge (Far).
	2. Control for viewing distance: The ball was located 1 m down the surface. The viewer is simulated as being 1 m back from the edge (Far-control).

 - The six possible condition orders are distributed equally across the participants.
 - Participants are encouraged to make the precisest judgments.
 - Head orientation information is also recorded.

### Results

 - The main comparison between Far and Near shows that slopes appear shallower when viewed from the edge.
 - The comparison between Far and Far-control indicated that viewing distance is not a main factor.
 - Low slopes are estimated less exaggeratedly than real hills as reported, which reflects a limitation of virtual representations. Yet the comparison between different viewing positions is consistent with real-life observations.

### Limitations

Head orientation is not emphasized during the analysis. The virtual environment is shown not consistent with real environment.

## Experiment 2 B

>Proprioception of head orientation

### Purpose

Misperception of head orientation could help account for the misperception of downhill surface orientation. But the proprioceptive misperception of head orientation has not been documented.

### Methods

Participants are **blindfolded** and asked to position their head at a specific degree. The head pitch data were recorded. Control groups are used to eradicate the effect of the weight of the device.

### Results

The produced head declination shows a gain of 0.5, suggesting that the perceived head orientation increases with a gain of 2 relative to actual changes in head orientation.

## Modelling

>A geometrical model of changes in downhill slope perception with point of view

 - The perceived geometrical slant ($\alpha_p$) equals to the difference between the perceived gaze declination ($\gamma_p$)and the perceived optical slant ($\beta_p$).

$$ \alpha_p = \gamma_p - \beta_p $$

 - The perceived gaze declination is a linear function of the actual gaze orientation ($\gamma$).

$$ \gamma_p = k\cdot\gamma $$

 - The perceived optical slant is a continuous function of the actual optical slant ($\beta$).

$$ \beta_p = f(\beta) $$

Thus we can get the final model:

$$ \alpha_p = k\cdot\gamma - f(\beta) $$

The gain factor $k$ fits the best when set to $2$,  which is also consistent with the data in [[Slope Perception Failure (Summary)#Experiment 2 A|Experiment 2 A]].

## Retrospect

> Methodological considerations in studying failures of constancy

Former experiments where people are asked to judge the slope and walk towards different positions in real world proved to be inconsistent and was discontinued. As adults do not usually notice failures of constancy, they maybe able to predict the perceptual consequences of their actions as they move.

## Experiment 3 A

> Failures of geographical slant constancy with visual estimates of real surfaces

### Purpose

 - To address the concern that cognitive strategies may mask the researched perceptual phenomenon.
 - Use real surfaces to create a [[Between-subject Design & Within-subject Design|within-subject]] data set.

### Methods 

 - The main design includes three different slope orientations and two different viewing positions. Retinal size is controlled by two different surface side for each cell in the main design.
 - The 12 experiment trials are randomly intermixed with 12 filler trials, which are used to overload memory for each variable.
 - A questionnaire is used to assess participants' belief about the experiment and its design. <u>To avoid the vagaries of verbal responses, the estimate is given by orienting a line on a screen.</u>
 - The stand where the surfaces are mounted is specially-designed to avoid horizontal and vertical reference.

### Results 

 - Survey data shows that special strategies and predictions based on the thought of the hypothesis is not dominant.
 - There is a reliable effect of viewing distance.
 - There is also a reliable effect of board size. Larger boards are commonly judged steeper. This shows that retinal size is not a reliable factor as farther boards would project a smaller retinal size while judged steeper.
 - A best fitting gain factor of gaze orientation is derived for each board size. The overall gain factor is $1.5$.
 - Record of head movement suggests that participants may try to stabilize their head orientation to maintain a fixed frame of reference.
 - When the head orientation factor ($2$) is considered with an unknown eye-in-head declination factor, the best fitting model ascribes an overall gain of 1.46 to the eye-in-head component of gaze.

### Retrospect 

Participants may stabilize their head to maintain the reference, which is highly due to the difference of virtual environment and the real-world environment. In the former one, eye-in-head declination is limited because of the device so that head orientation is directly regarded as gaze declination, making the gain factor smaller when gaze declination is applied.

## Experiment 3 B

### Purpose 

As in unrestricted viewing conditions, gaze can be declined by a combination of head orientation and eye-in-head declination, the experiment sought to measure the perceived gaze declination in a natural environment.

### Methods 

 - Participants are asked to view some specified viewing target from different windows and to adjust the line on the screen to match their orientation of line of sight to the target. The five viewing targets are ordered randomly for each participant.
 - Later the participants are again lead to the five windows with a different order and make a verbal estimate.

### Results 

The measured gain is 1.31 for the visual matches and 1.51 for verbal matches.

### Discussion

The gain factor provides a good approximate to the best fitting gain estimated in [[Slope Perception Failure (Summary)#Experiment 3 A|Experiment 3 A]]. The gain factor of perceived gaze orientation maybe affected by multiple factors including head orientation and eye-in-head declination, but they are not sought to be isolated. Such perceptual error need not to be translated into action errors as the latter one may reflect more about calibrated action rather than perceptual experience.

# Conclusion

Hills look steeper when standing back from the edge and looking along them than when standing near the edge and looking down on their surface. Perception of gaze orientation itself and proprioception of the pitch of the head in particular are both overestimated. Simple geometric models of the data that take into account the misperception of gaze direction provide excellent fits to the data when the only free parameters in the model are measured empirically. <u>In both sets of data, the perception of optical slant is exaggerated in ways that are predicted by theories of coding efficiency.</u> <u>The misperception of gaze direction and the misestimation of optical slant may approximately offset each other in most visual contexts and normally provide coding advantages for detecting departures from the horizontal.</u> 

# [[Thoughts on the Study]]
