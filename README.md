# **Personal Assistent (CLI)**

This project is a console application which allows:
- add, change and view contacts
- add and view birthday 
- remind about nearest birthdays (7 day)
- if the birthday falls on a weekend - move the date of congratulations to Monday

 ##  **Technologies used**
- Python 3.13.5
- Poetry (dependency managment)
- Docker (containerization)

## **How to run locally (without Docker)**

1. Clone the repository:
 ```bash
   git clone https://github.com/HannaBasova/goit-ds-hw-01.git
   cd goit-ds-hw-01
```
2. Install dependencies with Poetry:
```bash
poetry install
```

3. Run the program:
 ```bash
   poetry run python main.py
```

## **How to run in Docker**
1. Build the image:
   ```bash
   docker build -t annabasova/goit-ds-hw-01:latest
   ```
2. Run the container in interactivw mode:
   ```bash
   docker run --rm -it annabasova/goit-ds-hw-01:latest
   
