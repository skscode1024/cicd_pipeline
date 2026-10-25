name: Run Python


on:
  push:
    branches: [main]
  workflow_dispatch:


jobs:
  run:
    runs-on: ubuntu-latest

    steps:
      - name: Get the project file
        uses: actions/checkout@v4

      - name: Set up python
        uses: actions/setup-python@v5
        with:
          python-version: "3.12"

      - name: Run the python script
        run: python main.py
