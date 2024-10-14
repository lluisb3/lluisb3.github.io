---
title: "ITHER project"
excerpt: "<div style='text-align: justify'> ITHER - Home-based and data driven therapy for adolescents with hyperactivity and/or autism leveraging mixed reality. </div>"
collection: portfolio
---

 <div style='text-align: justify'> The goal of the ITHER project is to develop a room-scale multi-sensory mixed reality (MR) exercises combining context-aware visual, and 3D audio with passive haptic feedback using everyday objects available in all homes. As part of the team I was in charge of computing the 3D reconstruction of a scene recorded using the Hololens 2 headset. Afterwards, perform the 3D semantic instance segmentation of common objects that could be included in the MR game as passive haptic feedback. </div>
 
 As an example, this is a scene we want to digitally reconstruct and 3D segment common objects present on it:

 <img src='/images/scene_real.jpg'> 

<div style='text-align: justify'> In the following animation are presented the outputs from the 2 different algorithms. First the 3D reconstruction of the scene in from of a Point Cloud using the Hololens 2 headset (<a href='https://github.com/lluisb3/hl2ss'>hl2ss</a>). Second using AI (<a href='https://github.com/lluisb3/Mask3D_v2'>Mask3D</a>) from the 3D Point Cloud I compute the 3D instance segmentation of some common objects. For example you can see how the chairs as segmented as yellow objects, the bookshelves as purple, the table as light red, 2 doors as red and, the windows as light purple. </div>

 <div style='text-align: center'> <img src='/images/scene1_combined.gif'> </div> 
