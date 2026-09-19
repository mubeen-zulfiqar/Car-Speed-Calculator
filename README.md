# Car-Speed-Calculator

Historical computer-vision learning project from 2023, using Python and OpenCV to experiment with vehicle detection and a speed overlay on recorded video.

## Repository contents

- `Script.ipynb`: background subtraction, contour selection, and the speed-overlay experiment.
- `Car.mp4`: sample input video.

## Context and limitations

This is an early prototype. The speed calculation mixes pixel coordinates with a distance labelled in metres and uses processing wall time for recorded video. Its displayed values should not be treated as calibrated physical measurements. A validated implementation would need spatial calibration, video timestamps, and checks against known speeds.

The original code is preserved. Its notebook expects OpenCV, the sample video, and a local graphical display; the environment has not been revalidated as part of this documentation update.

## Original output

<img width="641" alt="image" src="https://github.com/mubeen-zulfiqar/Infinite-Calculator/assets/83843193/14ca6a2b-42ee-4dce-be7f-2e1385f230ab">
