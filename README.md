# Trust_Reputation_model_FIRE
## WHAT IS IT?

![Rating gif](https://cdn.dribbble.com/users/1591951/screenshots/3613845/8.gif)

This project was carried out as part of our final year of master's degree in computer science at Sorbonne University in 2018 (ANDROIDE - UE MOSIMA).

The theme was inspired by the [Nosedive](https://en.wikipedia.org/wiki/Nosedive_(Black_Mirror)) episode of the British series Black Mirror, which addresses the question of the influence of social networks on a society.

In multi-agent systems operating in open environments, it is difficult to manage interactions between them. This is due in part because agents are likely to defend personal interests and be unreliable and do not have a global vision of this environment, but also because there is no central authority controlling them.
In their article, Trung Dong Huynh, Nicholas R. Jennings and Nigel R. Shadbolt offers a model of trust and reputation, FIRE, to address this issue. This model integrates 4 different sources of information: 


  * interaction trust (IT)
  * role-based trust (RT)
  * witness reputation (WR)
  * certified reputation (CR)

FIRE is empirically evaluated and is effective in helping agents effectively select appropriate interaction partners.

The model is composed by two type of turtles: 

  * consumers which sometimes request a service
  * providers with differents profile and performance level


## HOW IT WORKS

The modelisation simulate an open world with consumers and providers which can interact once every round. Every interaction result in the evaluation of the performance of the provider. Both the consumer and the provider which participate in the interaction can then save the rate in their databases.

## HOW TO USE IT

At the beginning set the differents parameters as you want or press **Reset settings** to set the parameters at default parameters.

Once everything is selected press **Setup** to initialize the world. You can look at the 3D view to see the turtles on the spherical world.

Finally press **start** to play the number of simulation you asked for or **start once** to only play one round.

## TO-DO LIST
* develop the role-based trust model

## THINGS TO NOTICE

Every consumer when they request a service can only contact the 10 closest providers.
Every agent has a radius of operation and if a provider and a consumer are not in that radius when they interact then the performance is degraded by a linear factor.
The temperature whch set if a consumer is going to explore or exploide its database of rattings decrease linearly toward 0.

## CREDITS AND REFERENCES

Alexis DEVLILLARD - [GitHub Profile](https://github.com/Aightech)
Maëva ARLANDIS - [GitHub Profile](https://github.com/BarbeBleue)


This model is based on the following article:

* Trung  Dong  Huynh,  Nicholas  R  Jennings,  and  Nigel  R  Shadbolt.   An  integrated  trust  andreputation model for open multi-agent systems.Autonomous Agents and Multi-Agent Systems,13(2):119–154, 2006.

<!-- November-December 2018 -->
