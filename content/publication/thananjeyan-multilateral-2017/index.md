---
title: Multilateral surgical pattern cutting in 2D orthotropic gauze with deep reinforcement
  learning policies for tensioning
authors:
- Brijen Thananjeyan
- Animesh Garg
- Sanjay Krishnan
- Carolyn Chen
- Lauren Miller
- Ken Goldberg
date: '2017-05-01'
publishDate: '2024-11-15T17:07:01.636886Z'
publication_types:
- paper-conference
publication: '*2017 IEEE International Conference on Robotics and Automation (ICRA)*'
doi: 10.1109/ICRA.2017.7989275
abstract: In the Fundamentals of Laparoscopic Surgery (FLS) standard medical training
  regimen, the Pattern Cutting task requires residents to demonstrate proﬁciency by
  maneuvering two tools, surgical scissors and tissue gripper, to accurately cut a
  circular pattern on surgical gauze suspended at the corners. Accuracy of cutting
  depends on tensioning, wherein the gripper pinches a point on the gauze in R3 and
  pulls to induce and maintain tension in the material as cutting proceeds. An automated
  tensioning policy maps the current state of the gauze to output a direction of pulling
  as an action. The optimal tensioning policy depends on both the choice of pinch
  point and cutting trajectory. We explore the problem of learning a tensioning policy
  conditioned on speciﬁc cutting trajectories. Every timestep, we allow the gripper
  to react to the deformation of the gauze and progress of the cutting trajectory
  with a translation unit vector along an allowable set of directions. As deformation
  is difﬁcult to analytically model and explicitly observe, we leverage deep reinforcement
  learning with direct policy search methods to learn tensioning policies using a
  ﬁniteelement simulator and then transfer them to a physical system. We compare the
  Deep RL tensioning policies with ﬁxed and analytic (opposing the error vector with
  a ﬁxed pinch point) policies on a set of 17 open and closed curved contours in simulation
  and 4 patterns in physical experiments with the da Vinci Research Kit (dVRK). Our
  simulation results suggest that learning to tension with Deep RL can signiﬁcantly
  improve performance and robustness to noise and external forces.
links:
- name: URL
  url: http://ieeexplore.ieee.org/document/7989275/
---
