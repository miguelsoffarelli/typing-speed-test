# Typing Speed Test

A simple Pygame-based typing speed test application that measures your typing speed (WPM) and accuracy against random sentences.

## Features

* Displays a random sentence for the user to type.
* Starts timing when the user clicks on the input box.
* Calculates elapsed time, accuracy (percentage of correct characters), and words-per-minute (WPM).
* Shows results with a reset button to try again.

## Table of Contents

* [Installation](#installation)
* [Usage](#usage)
* [Project Structure](#project-structure)
* [Dependencies](#dependencies)

## Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/typing-speed-test.git
   cd typing-speed-test
   ```

2. **Create a virtual environment (optional but recommended)**

   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**

   ```bash
   pip install pygame
   ```

## Usage

1. **Prepare sentences**

   * Edit or replace `sentences.txt` with your own list of sentences, one per line.

2. **Run the game**

   ```bash
   python main.py
   ```

3. **How to play**

   * Click inside the input box to start the timer.
   * Type the sentence shown on screen and press Enter.
   * View your time, accuracy, and WPM.
   * Click "Reset" to try another sentence.


## Dependencies

* [Python 3.x](https://www.python.org/)
* [Pygame](https://www.pygame.org/)

Install via:

```bash
pip install pygame
```

