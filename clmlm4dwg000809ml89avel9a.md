---
title: "Navigating the AWS DeepRacer Student League"
seoTitle: "The AWS AI/ML Scholarship: Unlocking Opportunities"
seoDescription: "AWS DeepRacer is a groundbreaking initiative that combines the thrill of racing with the power of reinforcement learning (RL) and autonomous driving. Partic"
datePublished: Sat Sep 16 2023 05:53:23 GMT+0000 (Coordinated Universal Time)
cuid: clmlm4dwg000809ml89avel9a
slug: navigating-the-aws-deepracer-student-league
canonical: https://www.linkedin.com/pulse/navigating-aws-deepracer-student-league-krish-gaur%3FtrackingId=rtdjCINeSi2RlHwxLoFT2w%253D%253D/?trackingId=rtdjCINeSi2RlHwxLoFT2w%3D%3D
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1694843413677/c6a1ff93-993e-4ea6-9455-21a134959c6c.png
ogImage: https://cdn.hashnode.com/res/hashnode/image/upload/v1694843542089/726dcbed-d524-4ef3-9d43-05f667eee349.png
tags: ai, aws, ml, deepracer

---

---

This article will delve into my journey, from mastering the prerequisites to competing in this thrilling event, highlighting the significance of the [***AWS AI/ML scholarship***](https://aws.amazon.com/machine-learning/scholarship/) along the way. I’m excited to share my experience in the [***AWS DeepRacer Student League***](https://student.deepracer.com/league).

### AWS DeepRacer: A Glimpse of the Future: 

AWS DeepRacer is a groundbreaking initiative that combines the thrill of racing with the power of reinforcement learning (RL) and autonomous driving. Participants train RL models to navigate a 3D simulated racetrack using AWS services. The competition serves as an engaging platform to learn and apply machine learning concepts practically.

### The AWS AI/ML Scholarship: Unlocking Opportunities: 

To qualify for the AWS DeepRacer Student League, I first completed a foundational machine learning course, equipping me with essential knowledge. Next, I demonstrated my passion and commitment by scoring over 24 points out of 30 in a challenging multiple-choice question (MCQ) test. Finally, I demonstrated the art of racing by completing three laps in under three minutes, showcasing my ability to apply machine learning concepts effectively.

But that’s not all. The machine learning algorithm that I created didn’t just meet the three-minute requirement; it also ranked among the top 100 fastest laps around the track. This emphasizes how easily the prerequisites can be fulfilled by implementing a set of effective strategies outlined in the upcoming section.

### Improving your own ML Algorithms with AWS DeepRacer parameters:

To succeed in the AWS DeepRacer Student League, it’s essential to develop and fine-tune your machine learning algorithms. AWS DeepRacer provides a unique environment for reinforcement learning, and optimizing your model can be a rewarding experience. You can view some of the default Input parameters for DeepRacer at [AWS Docs](https://docs.aws.amazon.com/deepracer/latest/developerguide/deepracer-reward-function-input.html). Here are some tips to help you get started:

* ***Hyperparameter Tuning:*** Experiment with various hyperparameters such as learning rate, exploration factor, and discount factor to find the optimal balance between exploration and exploitation.
    
* ***Reward Function:*** Craft a well-defined reward function that incentivizes your model to follow the track and make informed decisions. This is a crucial aspect of reinforcement learning.
    
* ***Simulation:*** Use AWS DeepRacer’s built-in simulation environment to train and evaluate your model efficiently before deploying it to the virtual track.
    
* ***Data Collection:*** Gather ample data by running your model in the simulator, as more data can lead to better training results.
    
* ***Iterate and Experiment:*** Don’t be afraid to iterate on your model and experiment with different techniques. Reinforcement learning is an evolving field, and continuous learning is key.
    

Here's a sample code for following the centerline algorithm which divides the track into three reward zones. The farther the car strays from the centerline, the less it’s rewarded.

```python
def reward_function(params):
    # Example of rewarding the agent to follow center line

    # Read input parameters
    track_width = params['track_width']
    distance_from_center = params['distance_from_center']

    # Calculate 3 markers that are at varying distances away from the center line
    marker_1 = 0.1 * track_width
    marker_2 = 0.25 * track_width
    marker_3 = 0.5 * track_width

    # Give higher reward if the car is closer to center line and vice versa
    if distance_from_center <= marker_1:
        reward = 1.0
    elif distance_from_center <= marker_2:
        reward = 0.5
    elif distance_from_center <= marker_3:
        reward = 0.1
    else:
        reward = 1e-3 # likely crashed/ close to off track

    return float(reward)
```

### Key Takeaways: Embracing the DeepRacer Experience

Participating in the AWS DeepRacer Student League has been a transformative journey, offering valuable lessons about the world of machine learning and life itself. Here are some key takeaways that not only apply to DeepRacer but are also universally welcome:

1. **Starting with the Simple and the Slow:** DeepRacer taught me the importance of starting with the basics. Just like in life, beginning with simple, well-understood concepts often yields the best results. It's a welcome reminder that a solid foundation is key to any endeavor.
    
2. **Small Steps Lead to Big Changes:** DeepRacer demonstrates that small, incremental progress can lead to significant improvements. This applies to both racing laps and personal growth. By consistently taking small steps forward, we can achieve remarkable transformations over time.
    
3. **Believe in Miracles, Persevere, and Achieve:** While it might take a million tries, believing in the possibility of miracles and persevering through challenges can lead to extraordinary accomplishments. DeepRacer encourages us to keep pushing our limits and believing in our potential.
    
4. **Learning from the Good and the Bad:** In machine learning, as in life, it's crucial to recognize that anything capable of learning will absorb both good and bad habits. This welcoming insight reminds us to be mindful of the influences around us and strive for positive growth.
    

In conclusion, the AWS DeepRacer Student League is not just a thrilling competition but also a welcoming educational journey that imparts valuable life lessons. These takeaways are not limited to the racetrack; they are principles that can guide us toward success and fulfillment in all aspects of life. So, whether you're interested in machine learning or simply seeking personal growth, the welcoming lessons of DeepRacer can be a beacon of inspiration and enlightenment.