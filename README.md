# Experiment generating an NX Monorep

## Setup
```
npx create-nx-workspace nx-experiment --preset=ts
nx g @nrwl/js:library --name=hello --buildable
nx build hello
nx test hello
```

## Add a second library
```
nx g @nrwl/js:library --name=liba --buildable
```