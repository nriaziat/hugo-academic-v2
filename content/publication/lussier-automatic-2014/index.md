---
title: Automatic calibration of RGBD and thermal cameras
authors:
- Jake T. Lussier
- Sebastian Thrun
date: '2014-09-01'
publishDate: '2024-11-15T17:07:02.391889Z'
publication_types:
- paper-conference
publication: '*2014 IEEE/RSJ International Conference on Intelligent Robots and Systems*'
doi: 10.1109/IROS.2014.6942598
abstract: Reasoning about a scene’s thermal signature, in addition to its visual appearance
  and spatial conﬁguration, would facilitate signiﬁcant advances in perceptual systems.
  Applications involving the segmentation and tracking of persons, vehicles, and other
  heat-emitting objects, for example, could beneﬁt tremendously from even coarsely
  accurate relative temperatures. With the increasing affordability of commercially
  available thermal cameras, as well as the imminent introduction of new, mobile form
  factors, such data will be readily and widely accessible. However, in order for
  thermal processing to complement existing methods in RGBD, there must be an effective
  procedure for calibrating RGBD and thermal cameras to create RGBDT (red, green,
  blue, depth, and thermal) data. In this paper, we present an automatic method for
  the synchronization and calibration of RGBD and thermal cameras in arbitrary environments.
  While traditional calibration methods fail in our multimodal setting, we leverage
  invariant features visible by both camera types. We ﬁrst synchronize the streams
  with a simple optimization procedure that aligns their motion statistic time series.
  We then ﬁnd the relative poses of the cameras by minimizing an objective that measures
  the alignment between edge maps from the two streams. In contrast to existing methods
  that use special calibration targets with key points visible to both cameras, our
  method requires nothing more than some edges visible to both cameras, such as those
  arising from humans. We evaluate our method and demonstrate that it consistently
  converges to the correct transform and that it results in high-quality RGBDT data.
links:
- name: URL
  url: http://ieeexplore.ieee.org/document/6942598/
---
