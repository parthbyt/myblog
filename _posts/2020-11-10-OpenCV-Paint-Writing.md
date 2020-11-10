---
layout: post
title: Writing OpenCV-Paint repository.
---

[Project Link](https://github.com/parthbyt/OpenCV-Paint)

[Website Link](https://parthbyt.github.io/OpenCV-Paint/)

Here is my experience in writing the OpenCV-Paint Repository.

## Common problems while writing

- **Adjusting window size**: I have created black windows using ```np.zeros()``` function of numpy. But actually at time of writing the code I didn't new how it actually worked so I adjusted window sizes by trial and error method.

## Features and problems

### Features

- Brush size and color preview.
- Image could be saved.

### Problems

- Hard to save file. Not possible to choose location and name or file type.
- If brush size is small and is moved to fast, it will draw circle insted of line.
- Can't chnage brush type.

## Problems on GitHub 

While uploading to github, I failed to use github actions. The reason was that I failed to use opencv due to its qt requirement.

## More

I am satisfied even after problems. I wrote it as a opencv practice.
