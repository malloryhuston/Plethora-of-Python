# Plethora of Python

A list of Python 3 programming projects ranging from Beginner to Advanced. A work in progress.

## Update Repository on GitHub

```bash
git status
git add -A
git commit -m "Update README.md"
git push origin main
```

## Virtual Environment

It is recommended to run this program in a `venv` environment. First, install the following Python release via Homebrew:

```bash
brew install python@3.14
```

Next, create your own `venv` environment:

```bash
cd Plethora-of-Python
python3.14 -m venv plethora
```

Now you have to tell the system that you want to use this virtual environment, and you do that by *activating* it. Do so by using the following command:

```bash
source plethora/bin/activate
```

Check that the Python in the `plethora` virtual environment is the correct version `Python 3.14.X`:

```bash
python --version
```

## Requirements

Now that you're in the `plethora` virtual environment, run the following command:

```bash
cat requirements.txt | xargs -n 1 pip install
```

Once finished for today, exit the virtual environment `plethora` by simply running:

```bash
deactivate
```
