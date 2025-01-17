### EX NO: 01 
### DATE:
# <p align="center">MDP REPRESENTATION</p>

## AIM:
To represent a Markov Decision Process(MDP) problem in the following ways.

1.Text representation

2.Graphical representation

3.Python - Dictonary representation

## PROBLEM STATEMENT:

### Problem Description

To Develop an environment contain some dirt and the agent is going to clean. The aim is to clean the dirty place.

### State Space

{Location A,Location B,Location C}

### Sample State

Location A

### Action Space


- Moving Right
- Moving Left
- Suck Dirt

### Sample Action

Moving Right

### Reward Function

- +1 - when an agent move to the right side and the dirt using vaccum
- 0 - Otherwise

### Graphical Representation

![image](https://github.com/Kayalvizhi02/mdp-representation/assets/75413726/91ecfabf-35b8-414c-8f3e-966932c018c9)

## PYTHON REPRESENTATION:
```python
# Developed by: Kayalvizhi M
# Register Number: 212220230024

P = {
    0:{
        0: [(1.0,0,0.0,True)],
        1: [(1.0,0,0.0,True)]
    },
    1:{
        0: [(1.0,0,0.0,True)],
        1: [(1.0,2,1.0,True)]
    },
    2:{
        0: [(1.0,2,0.0,True)],
        1: [(1.0,2,0.0,True)]
    }
}
```
## OUTPUT:

![image](https://github.com/Kayalvizhi02/mdp-representation/assets/75413726/df562e49-3c3b-458d-b6eb-281842f67152)

## RESULT:

Thus the given real world problem is successfully represented in a MDP form.



