:arrow_left: [Open an existing scenario](../HT_Open_a_scenario/HT_Open_a_scenario.md)

# How to run a SCANeR simulation: the good practices

You are using SCANeR everyday to manage your experimentation but do you use it in the proper way ? 🤔

This guide explains how to manage the execution of your simulation
- Step 1. Run modules
- Step 2. Run the simulation
- Step 3. Stop the simulation
- Step 4. Stop modules 

## Step 1. Run modules

1. Click on the `Start Simulator` button (double blue triangles) to launch all the previously selected modules
![](./assets/LaunchModules.png)  

2. Verify the status of the modules thanks to symbol in the green circle next to the modules.  
![](./assets/ModuleStates.png)  
The correct status of the module should be `Loaded`  

>All selected modules will automatically start (some of these have GUI, as ACQUISITION, VISUAL, etc.)
>Would you like to create your own module, and learn more about their states? [How to? API creation]()

## Step 2. Run the simulation
Click on the `Play Scenario` button (black triangle in a green circle) to launch the simulation  
![](./assets/LaunchSimu.png)  
The correct status of the module should be `Running`  

>When you run a scenario for the first time SCANeR creates information into cache memory to accelarate the futur runs. The first it'll take a bit more time, thank you for your patience 
>If you have set parameters in your scenario you can set the value of these parameters at the start of the simulation. Click on the grey triangle next to the `Play Scenario` button and choose `Play Scenario with Parameters`. Would you like to design parametric simulation? [How to? Design scenario for SCANeR Explore]()

The execution of this scenario looks like this:

<video src="https://user-images.githubusercontent.com/22998298/133973267-9e959c8e-1b0e-4c2b-8668-5a05809cc749.mp4" controls="controls" style="max-width: 730px;"></video>

>In this video you see that you are able to switch views between different actors of the scenario by selecting them.
>You can also switch the camera angle on the top right corner, as well as choose to be focused on the selected actor or not.
>Keep in mind that this is the `SUPERVIOR` view. In order to see the `VISUAL` view, you need to configure and start the module (check out our tutorial about this: [How to? Configure the visual rendering](../HT_configure_visual/HT_configure_visual.md)).
>On the bottom right corner of SCANeR, you have some informations about the vehicule you have currently selected.

## Step 3. Stop the simulation
Click on the `Stop Simulation` button (black square in a red circle)  
![](./assets/StopSimu.png)

⚠ This is the right way to stop the simulation, any others button should not be used to stop the simulation. ⚠  
Pause the simulation is also possible, click on the `Pause Simulation` button while while the simulation is running 😊

## Step 4. Stop modules
Click on the `Stop Simulator` button (white cross in a red circle)  
![](./assets/StopModules.png)

This button close, and kill the SCANeR modules in a clean way. If you stop the simulation with this button inconsistencies can appear (e.g. at the reload of the next simulation).  
  
We rely on you to run your simulation as it should be 😉

:arrow_right: [Replay a simulation](../HT_Replay_Simulation/HT_Replay_Simulation.md)
