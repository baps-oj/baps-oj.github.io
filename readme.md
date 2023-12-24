# Developer Instruction

-   Clone the project with submodules

```sh
git clone --recurse-submodules git@github.com:baps-oj/baps-oj.github.io.git
```

-   Install dependencies

```sh
# create a venv (recommended)
pip install -r requirements
```

-   Start the devserver

```sh
make devserver
```

-   Navigate to http://localhost:8000

# How to create new Blog

-   First run the application
-   In the `content` folder create new markdown file.
-   It will generate `html` automaticaly
