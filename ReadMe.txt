1.This project is create in UE4.12(actrually 4.12.5-0+UE4).And all the packages used is also 4.12 version.

2.The PlayRateTestFull is the full project.

3.If the PlayRateTestFull is too big for you,you can download the BlueprintOnly,but you'll going need some setups:
	3a.Create a SideScroller blueprint project
	3b.Add Animation Starter Pack to it
	3c.copy the Content directory in the BlueprintOnly into the newly created project and override these files

4.When press J button,the character will play a "Attack" anim(but I set the anim to Death_1 in order to see it clearly).

5.There is a attackRate in the character and anim blueprint.I set it to 1,so the anim will be palyed in 1 second no matter how long the anim is.

6.You will see the character will continue to paly several frames after the "Attack" anim is finished.