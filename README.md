# Tetris

This guide explains how to set up and run a Tetris game using Python's Pygame library.

This guide provides step-by-step instructions for setting up a Tetris game project. It covers the prerequisites needed, including Python and Git. You will create a virtual environment, install necessary dependencies using either `pip` or `poetry`, and run the main file to start the game.

## Motive

The primary goal of this project is to provide a fun and engaging way to learn and practice Python programming using the Pygame library. By working on this Tetris game, you will gain hands-on experience with game development concepts, such as event handling, game loops, and rendering graphics. Additionally, this project serves as a practical example of how to manage dependencies and set up a Python development environment effectively. Enjoy the challenge and creativity of building your own game while honing your programming skills!


## Prerequisites

Before you begin, make sure you have the following installed on your system:

1. **Python**: Version 3.9 or later. You can download it from the [official Python website](https://www.python.org/downloads/).

2. **Git**: To clone the repository. You can download it from the [official Git website](https://git-scm.com/downloads).

## Get the Code

Follow these steps to set up the environment and run the Tetris game:

### Step 1: Create a Virtual Environment

A virtual environment allows you to manage dependencies separately for each project, avoiding conflicts with other projects.

1. **Navigate to Your Development Directory:**

```bash
cd ~/Dev
```

2.  **Create a New Directory for the Tetris Project:**

```bash
mkdir ~/Dev/tetris -p
```

3.  **Navigate into the Tetris Directory:**

```bash
cd ~/Dev/tetris
```

4.  **Install `virtualenv` if it is not already installed:**

```bash
python3.10 -m pip install virtualenv
```

5.  **Create a Virtual Environment in the Current Directory:**

```bash
python3.10 -m virtualenv .
```

6.  **Activate the Virtual Environment:**

```bash
source bin/activate
```

### Step 2: Install the Dependencies

You can install the required dependencies using either **pip** or **poetry**.

#### Using `pip`

1.  **Clone the Tetris Repository:**

```bash
git clone https://github.com/Arvind-4/tetris.git .
```

2.  **Install the Dependencies Listed in `requirements.txt` and `requirements-dev.txt`:**

```bash
pip install -r requirements.txt -r requirements-dev.txt
```

#### Using `poetry`

1.  **Clone the Tetris Repository:**

```bash
git clone https://github.com/Arvind-4/tetris.git .
```

2.  **Install the Dependencies Using Poetry:**

```bash
poetry install
```

### Step 3: Run the Main File

Once the dependencies are installed, you can run the Tetris game by executing the main Python script:

```bash
python app/main.py
```

Follow these instructions to successfully set up and run the Tetris game. Enjoy playing!

For any issues, please raise an issue on GitHub or contribute by creating a pull request.

## Conclusion

I have successfully set up the Tetris game using Python and Pygame. This setup ensures that all dependencies are properly managed and isolated in a virtual environment, allowing for a smooth and conflict-free development experience. If you encounter any issues or have suggestions for improvements, feel free to raise an issue on GitHub or contribute by creating a pull request. Happy coding and enjoy your game!
