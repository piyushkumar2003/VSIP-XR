# Visualizing-Sustainable-Industrial-Processes-using-XR (VSIP-XR) 🥽
* Professor: [Dr Kalpana Shankhwar (IIITD)](mailto:kalpana@iiitd.ac.in)
* Made by: [Tushar Chandra](mailto:cout.destiny@gmail.com), [Piyush Kumar](mailto:piyushkumar20033@gmail.com)

## 1. ***Introduction 📒:***
We propose the development of an Augmented Reality (AR) system to aid in the process of soldering small components onto printed circuit boards (PCBs). This system will enhance accuracy and efficiency by providing real-time guidance and monitoring during the soldering process. By overlaying AR elements onto a live camera feed, users will be able to precisely identify soldering points and monitor progress.

## 2. ***Project Goals 🎯:***
- Create an AR system that accurately detects soldering points on PCBs and overlays red dots for visual guidance.
- Provide a zoomed-in real-time feed for close monitoring of the soldering points during the process.
- Ensure low latency in displaying the camera feed and AR elements for a seamless user experience.
- Implement real-time feedback mechanisms to inform users about the status of each soldering point.
- Deliver a reliable and user-friendly system that enhances soldering precision and efficiency.

## 3. ***Detailed Timeline 📅:***

### Milestone 1: Project Setup and Planning

1. Define project scope, objectives, and deliverables.
2. Identify and procure required hardware (camera, computing equipment).
3. Research and choose the appropriate software and development tools.
4. Develop a detailed project plan with tasks, dependencies, and deadlines.

### Milestone 2: Image Processing and Detection Algorithms

1. Set up the camera and capture sample PCB images.
2. Develop image processing algorithms to detect soldering points.
3. Implement calibration techniques to correct for camera distortion and perspective.
4. Test and refine the detection algorithms for accuracy and reliability.

### Milestone 3: AR Overlay and User Interface

1. Design the AR overlay for displaying red dots on the PCB image.
2. Develop the user interface for switching between views and adjusting settings.
3. Integrate the AR overlay with the live camera feed.
4. Test the user interface for usability and user experience.

### Milestone 4: Realtime Feedback and Monitoring

1. Implement mechanisms for providing real-time feedback on soldering point status.
2. Develop the zoomed-in real-time feed display.
3. Integrate real-time feedback and monitoring features with the existing system.
4. Test the system's performance, latency, and accuracy.

### Milestone 5: Testing and Optimization

1. Conduct comprehensive testing with different PCB layouts and scenarios.
2. Gather user feedback and make necessary improvements based on testing results.
3. Optimize the system for performance, stability, and responsiveness.

### Milestone 6: Documentation and Finalization

1. Create user documentation and guides for system setup and usage.
2. Finalize the software and hardware components for deployment.
3. Prepare for system deployment and support.

## 4. ***Deliverables 📦:***
Upon successful completion of the project, the following deliverables will be provided:
- Fully functional Augmented Reality-assisted soldering system.
- Source code and project documentation.

## 5. ***Conclusion 📝:***
This project aims to revolutionize the soldering process by leveraging Augmented Reality technology to enhance accuracy, efficiency, and user experience. By following the outlined timeline and milestones, we are confident in our ability to deliver a reliable and effective AR-assisted soldering system that meets the needs of our users.


---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;


## ***Objectives/Challenges***
* [X] Detect holes in pcb using openCV.



&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


# __Weekly Report (Log)__
## ***Week 1 (Aug 7 - Aug 11):***
> 1. We discussed the project scope and objectives with the professor and finalized the deliverables. 
> 2. We identified the problems faced by the insurance companies where they have to send a third part agent to verify and attest the damage of any vehicle. We further discussed on how to automate this process using AR and AI.
> 3. We discussed the project timeline and milestones with the professor and finalized the project plan.
>
> **Deliverables:** Project plan, project scope, and objectives.

## ***Week 2 (Aug 14 - Aug 18):***
> 1. As we did literature survey on the same finalized topic, we found out that the same [project](https://www.warse.org/IJATCSE/static/pdf/file/ijatcse031052021.pdf) is already done. So, we decided to change the project topic.
> 2. On further iterations we decided to work on the project of Augmented Reality assisted soldering system.
> 3. We identified the problems faced by the soldering workers where they have to solder the small components on the PCBs. 
> 4. I designed a rough layout of how the project will look.
>

<dev style = "text-align:centre">
  <img src="./Assets/1.jpeg" alt="Image" width="50%">
</dev>

## ***Week 3 (Aug 21 - Aug 25):***
> 1. I started working on the project and started learning about the openCV and how to detect the holes in the PCB.
> 2. I stated by uploading a reference image and then detecting holes of specific size in the image.
> 3. Unfortunately, there's too much noise in detecting the holes in the image. 

<div style="display: flex; justify-content: center;">
    <div style="flex: 1;">
        <img src="Assets/Detecting-holes-1.png" alt="Image 1" width="400"/>
    </div>
    <div style="flex: 1;">
        <img src="Assets/Detecting-holes-2.png" alt="Image 2" width="400"/>
    </div>
</div>

> 4. I tried to remove the noise by applying the Gaussian Blur and then applying the threshold. But, still the noise is not removed.
> 5. Finally, I decided to manually click on the two points to add the AR elements and proceed further.









<!-- Other Project Ideas -->
### Other good project ideas:
- [ ] AR Notes Writing app.
