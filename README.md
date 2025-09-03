# AI-Bear-Body-Detection

This project was created for the **ECSE Design Competition**.
It currently uses the **Res-10 Deep Neural Network (DNN) model** for facial detection.

---

## Prerequisites

**OpenCV** is required. Install it using `pip`:

```bash
python -m pip install opencv-python
```

## How to run the app:

```bash
python main.py
```

## Mac OS Info:

For Mac OS installing python packages and running python can be weird. To install opencv and run the program I had to create a virtual environment:

```bash
python3 -m venv .venv
source .venv/bin/activate
```

---

## Things left to do:

- Trigger bear reactions (audio/movement) on face detection.
- Test with actual webcam and hardware
- Improve accuracy under different lighting + angles
