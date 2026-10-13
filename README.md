<p align="center">
  <img src="assets/header.svg" width="100%" alt="gd182 — C++ developer: desktop applications and computer vision" />
</p>

<p align="center">
  <a href="https://t.me/rkt267"><img src="https://img.shields.io/badge/Telegram-@rkt267-14181D?style=flat-square&logo=telegram&logoColor=white" alt="Telegram" /></a>
  <img src="https://img.shields.io/badge/status-open_to_contracts-3B6E5A?style=flat-square" alt="Open to contracts" />
</p>

## GD182 — general description

GD182 is a C++ engineer that covers the full path of the data: from the source,
through the desktop app that displays it, to the vision or ML code that makes sense of it.
One part instead of three, no glue logic required.

## Features

- **Desktop:** Qt Widgets / QML / Charts, real-time telemetry, serial and network protocols
- **Vision & ML:** OpenCV pipelines, PyTorch / LibTorch, TensorFlow
- **Core:** C++17/20, STL, Boost, CMake, multithreading
- **Graphics:** Vulkan
- **Also supported:** embedded (ESP32, FreeRTOS)
- Field-proven: 5+ years in production, 50+ shipped projects
- Builds on Linux. Always.

## Typical applications

| Part | What it does | Stack |
| --- | --- | --- |
| [**MineAI**](https://github.com/gd182/MineAI) | CNN that learns Minesweeper through self-play. Training loop written from scratch; one set of weights plays any board size | C++17, LibTorch, CUDA |
| [**ThreadPool**](https://github.com/gd182/ThreadPool) | Thread pool with priorities, `std::future` results, runtime resizing and exception isolation | C++ |
| [**CookieBot**](https://github.com/gd182/CookieBot) | Game bot driven only by screen capture and input emulation, no access to game code | Python, CV |

Currently in development: a pipeline that turns 3D models into labeled training data,
so detectors can be trained without manual annotation.

## Supported toolchain

<p>
  <a href="https://isocpp.org" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/cplusplus-colored.svg" width="36" height="36" alt="C++" title="C++" /></a>&nbsp;
  <a href="https://www.qt.io" target="_blank" rel="noreferrer"><img src="assets/icons/qt.svg" width="36" height="36" alt="Qt" title="Qt" /></a>&nbsp;
  <a href="https://cmake.org" target="_blank" rel="noreferrer"><img src="assets/icons/cmake.svg" width="36" height="36" alt="CMake" title="CMake" /></a>&nbsp;
  <a href="https://www.python.org" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/python-colored.svg" width="36" height="36" alt="Python" title="Python" /></a>&nbsp;
  <a href="https://opencv.org" target="_blank" rel="noreferrer"><img src="assets/icons/opencv.svg" width="36" height="36" alt="OpenCV" title="OpenCV" /></a>&nbsp;
  <a href="https://pytorch.org" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/pytorch-colored.svg" width="36" height="36" alt="PyTorch" title="PyTorch" /></a>&nbsp;
  <a href="https://www.tensorflow.org" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/tensorflow-colored.svg" width="36" height="36" alt="TensorFlow" title="TensorFlow" /></a>&nbsp;
  <a href="https://huggingface.co" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/huggingface-colored.svg" width="36" height="36" alt="Hugging Face" title="Hugging Face" /></a>&nbsp;
  <a href="https://www.blender.org" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/blender-colored.svg" width="36" height="36" alt="Blender" title="Blender" /></a>&nbsp;
  <a href="https://www.vulkan.org" target="_blank" rel="noreferrer"><img src="assets/icons/vulkan.svg" width="72" height="36" alt="Vulkan" title="Vulkan" /></a>&nbsp;
  <a href="https://www.raspberrypi.com" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/raspberrypi-colored.svg" width="36" height="36" alt="Raspberry Pi" title="Raspberry Pi" /></a>&nbsp;
  <a href="https://www.postgresql.org" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/postgresql-colored.svg" width="36" height="36" alt="PostgreSQL" title="PostgreSQL" /></a>&nbsp;
  <a href="https://www.sqlite.org" target="_blank" rel="noreferrer"><img src="assets/icons/sqlite.svg" width="36" height="36" alt="SQLite" title="SQLite" /></a>&nbsp;
  <a href="https://www.docker.com" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/docker-colored.svg" width="36" height="36" alt="Docker" title="Docker" /></a>&nbsp;
  <a href="https://www.kernel.org" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/linux-colored.svg" width="36" height="36" alt="Linux" title="Linux" /></a>&nbsp;
  <a href="https://www.gnu.org/software/bash/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/gnubash-colored.svg" width="36" height="36" alt="Bash" title="Bash" /></a>&nbsp;
  <a href="https://git-scm.com" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/git-colored.svg" width="36" height="36" alt="Git" title="Git" /></a>&nbsp;
  <a href="https://code.visualstudio.com" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/visualstudiocode-colored.svg" width="36" height="36" alt="VS Code" title="VS Code" /></a>&nbsp;
</p>

## Operating notes

- Working software beats clever abstractions.
- Code explains itself; comments explain *why*.
- Ship it, measure it, then make it better.

## Revision history

| Rev | Changes |
| --- | --- |
| 5 (current) | Synthetic dataset generation for vision models. Accepting contracts |
| 1 – 4 | 5 years, 50+ projects: industrial telemetry, desktop tools, firmware, CV pipelines |

## Ordering information

Available for contract work in C++, Qt and computer vision.
Send a request via [Telegram](https://t.me/rkt267).