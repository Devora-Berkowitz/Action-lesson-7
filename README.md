# Action-lesson-7
name: Basic Workflow
on:
  push:
    branches: basic-workflow
jobs:
  do-things:
    name: Do Things
    runs-on: ubuntu-latest
    steps:
      - name: The Thing I've Done
        run: echo "I've done a thing!"
      - name: An Error I made
        run: |
          echo "I've made an error!"
          exit 1
