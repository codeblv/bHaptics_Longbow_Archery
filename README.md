# Bhaptics_Archery

## Summary
Archery game for Tactosy demo - in Bhaptics.co

## Developer's Note
### 17.03.29 WED
The first day of project. Spent too much time on VR setting issues...
* Project started.
* CRLF&LF Problem solved
: http://handam.tistory.com/127
* "sampleVRTK.unity" constructed with a lecture clip
: https://www.youtube.com/watch?v=yMYomOO9G4k
* Problem occured: A bow disappears when game starts
: Fixed - collider didn't set yet -> Colider set
* Objects can not be grabbed
: They don't be child of controller -> Solved (Mappping Problem)
* Oculus frame problem
: Only appears in usage of Oculus not HTC Vive. Looks VRTK and tracking Problem.
	- Need to set VR area again, check whether it is VRTK problem or not.
	- It was a tracking problem. After reset oculus sensor, the problem solved.
* Main graphic scene construction started - "mainScene.unity"
	- Finding for proper assets
* Tried to make able to grab an arrow but failed.
	- Have to find difference compare to sample file
	- Copied VRTK into my own scene, but problem doesn't solved yet.
* The first issue should be solved: "Grab an arrow"
### 17.03.31 FRI
SteamVR and VRTK seems based on HTC Vive. Therefore, it is not very-fit to Oculus. However, Unity supports Oculus based developments in its environment. Have to learn more to optimize the game.
* By compare&contrast, tried to solve an issue(grab an arrow).
* Because of a device problem(GPU) computer changed.
* Unity and git settsing
* Issue: Grab an arrow
	- Grab is able, however blue arrow(in eg code) appears and is grabbed.
	- Looks a script problem. Analysis started.
* Oculus account lost... Wait for help.
* Oculus doesn't work in SteamVR environment.
* Another error -> Playing VR makes Unity to shut down.
	- Seems project should be reset.

### 17.04.02 SUN
This is a Suday afternoon~ 
* git made again, bdecause of authorization problem...
* too much problems with setting...
* Git authorization problem solved: via GitHubDesktop
* Problem of Crash: VRTK prefab
* How can I do it differently?
	- Have to study Unity VR deeply....

### 17.04.10 MON
End of vacations
* Made a new git repository.
* Changed into Oculus only dev (do not use openVR, steam, VRTK.etc)
* Studying....
* Seems not too hard

### 17.04.12 WED
Hard working WED!
* Grab problem was solved!
* Need to calibrate the bow to stick to hand properly
* How about shooting an arrow?
* Start to copy : https://www.youtube.com/watch?v=WGBg4fy2Fdc
* Made a new git...
* Copied Youtube lec (~1:12:22)
