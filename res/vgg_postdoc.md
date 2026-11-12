# Demo videos — Rongzhen Zhao
 
Two short clips supporting the preliminary results in my Research Statement (Vacancy 188987).
 
## 1. Real-robot pick-up with a fine-tuned VLA (Franka Panda)

<video src="real_robot.mp4" controls muted playsinline width="720"></video>

SmolVLA (LeRobot) fine-tuned on demonstrations I collected on a Franka Panda; the task is to pick up a cup. The clip shows that I have run the full real-robot loop myself: data collection, fine-tuning, deployment.
 
## 2. Video object-centric learning on LIBERO (SmoothSA + SAM pseudo-masks)

<video src="video_ocl-03.mp4" controls muted playsinline width="720"></video>

My SmoothSA fine-tuned on LIBERO with SAM pseudo-segmentation as the only supervision. Objects are discovered without manual labels, and slot identities stay consistent across frames, including during gripper contact. This is the perception module behind Result 2 in the Research Statement.
