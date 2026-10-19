# github-final-project

## Simple Interest Calculator

A simple Bash calculator for computing simple interest. It is intended as a small, easy-to-understand example project for learning Git and GitHub collaboration.

### Inputs

- **p**: Principal amount
- **t**: Time period in years
- **r**: Annual rate of interest (percent)

### Formula

```text
Simple Interest = (p × t × r) / 100
```

### Run

Make the script executable and run it:

```bash
chmod +x simple-interest.sh
./simple-interest.sh
```

The script uses `bc` for decimal arithmetic. Install `bc` if it is not already available on your system.

### License

This project is distributed under the Apache License 2.0. See [LICENSE](LICENSE).
