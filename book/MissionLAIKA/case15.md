# Least-squares problems: Satellite connection back online
{bdg-danger}`Python Exercise`

## Mission LAIKA: Satellite connection back online

Due to a collision with space debris, the trajectory of a satellite has been altered. To understand its movement, we need to determine its new orbit. We know the orbit will be one of three types: parabolic, elliptical, or hyperbolic. 
<img scr="../MissionLAIKA/img/case14-1.png">


The trajectory of the satellite can be described by a polar equation: 
<img scr="../MissionLAIKA/img/case14-2.png">


$$ r= b+e(r cos(\theta)) $$

$r$ distance from centre of attraction (in thousands of kilometres)

$\theta$ angular position

The parameters b and e, which define the shape and characteristics of the orbit, are currently unknown. 



## Exercise
Using observational data for $r$ and $\theta$, we can apply linear regression to estimate $b$ and $e$. With these approximations, we can determine whether the satellite's new path is parabolic, elliptical, or hyperbolic, and better predict its future trajectory. 

Try to find these approximations for $b$ and $e$ using the following observations.

| **r** | 3.00 | 2.30 | 1.65 | 1.25 | 1.01 |
|:---|---:|---:|---:|---:|---:|
| **$\theta$** | 0.88 | 1.10 | 1.42 | 1.77 | 2.14 |

<img scr="../MissionLAIKA/img/case14-3.png">


## Python exercise | Jupyter notebook 

The Google Colab notebook containing the Python exercises for this case study can be found [here](https://colab.research.google.com/github/PRIME-TU-Delft/MissionLAIKA/blob/main/PythonExercises/CaseStudy15/C15.ipynb). Source code for this Python notebook can be found [here](https://github.com/PRIME-TU-Delft/MissionLAIKA/tree/main/PythonExercises/CaseStudy15).