# A Mouse's Journey

An interactive visualization project for DSC 106 at the University of California, San Diego.

## Description

This project provides an interactive tool for analyzing trends and differences in body temperature and activity levels between male and female mice over a 14-day study. Using dynamic visualizations, users can explore distributions of activity and temperature, with additional insights into female mice's estrus cycles.

### Installation

To setup and run this project locally:

```sh
# Clone the repository
git clone https://github.com/cheese-chasers-106/mouse.git
cd mouse

# Set up a simple server (if needed)
python -m http.server 8000  # or use Live Server in VSCode
```

### Usage

Go to https://cheese-chasers-106.github.io/mouse/ or open `index.html` in a browser or local server after installation.

1. Select a measurement Temperature or Activity from the Measure dropdown.
2. Select a gender Male and Female, Male, or Female from the Gender dropdown.
3. Check the Estrus checkbox to subdivide the female distribution into each estrus state (true or false).
4. Enjoy the visualizations!
