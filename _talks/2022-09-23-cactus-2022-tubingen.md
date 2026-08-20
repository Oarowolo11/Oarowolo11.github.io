---
title: "Predicting the Future Trajectory of Zebrafish with Probabilistic Machine Learning"
collection: talks
type: "Symposium talk"
permalink: /talks/2022-cactus-tubingen
venue: "1st Computation and Cognition Summer Internship Symposium"
date: 2022-09-23
location: "Tübingen, Germany"
---

Abstract: Larval zebrafish is widely used in neuroscience research because it has a small transparent nervous system, allowing for cellular resolution examination of neural dynamics throughout its brain under a microscope. Recent advances in neural imaging have developed a microscopy technique that tracks the motion of freely swimming larval zebrafish and keeps its brain within the camera’s field of view. This technique utilizes model predictive control (MPC), which depends on the accurate prediction of the animal’s future position. However, larval zebrafish moves in discrete bouts making sudden, high-velocity movements that are difficult to predict. Without predictive control, tracking errors greater than 100 µm occur about 9% of the total time and 49% of the time when the fish is in motion. To reduce this error, we use a probabilistic gradient boosting prediction framework to determine the most likely region the fish can be found in the next 6 camera frames given a sequence of the fish’s coordinates and heading vector for the previous 10 frames. We use these predictions to plan the path of the tracking microscope. Compared to without prediction, we reduced the number of frames with tracking errors above 100 µm by an average of 40%. Our results demonstrate that, given a short history of previous positions, Machine Learning (ML) techniques can be used to predict the future trajectory of larval zebrafish by uncovering informative patterns in zebrafish locomotion. [Watch the talk](https://photos.app.goo.gl/DKuWMb2yHvdgZBWg7).
