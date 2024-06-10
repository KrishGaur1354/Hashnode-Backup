---
title: "My Journey with the Drupal Association in Google Summer of Code 2024"
datePublished: Sun Jun 09 2024 14:45:10 GMT+0000 (Coordinated Universal Time)
cuid: clx97li5b00000ajt5lt17d8i
slug: my-journey-with-the-drupal-association-in-google-summer-of-code-2024-69c3aaff9833
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1718038217698/ab3e58c7-ccb0-42c5-a4c5-c18350e9a4af.png

---

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1718038210942/3357681e-dff6-4401-a474-b78220abebb8.png)

Drupal Association is a part of GSoC

#### Introduction

Hello, everyone! My name is Krish Gaur, and I am thrilled to share my incredible journey with the Drupal Association as part of Google Summer of Code (GSoC) 2024. This experience has been a significant milestone in my career, allowing me to work on a fascinating project while learning from some of the best minds in the open-source community. Let me take you through my journey so far, from the anxious wait for results to the exciting start of the coding period.

#### The Waiting Game

On the 1st of May, like many students eagerly anticipating the results of the Google Summer of Code (GSoC) 2024, I found myself glued to my screen, anxiously awaiting the clock to strike 11:30 PM IST. As the time arrived, my inbox pinged with two rejection emails from organizations I had applied to. Disappointed but not defeated, I still held hope for my third application with the Drupal Association. After what felt like an eternity of waiting, I finally received the email that changed everything: I had been selected for GSoC 2024 with the Drupal Association!

Selection Email from Google Summer of Code Team

#### Elation and Gratitude

Receiving the acceptance email was a moment of pure joy and relief. My hard work had paid off, and I was thrilled to share the news with my mother. Being selected for GSoC was a significant milestone, and being chosen to work with an esteemed organization like Drupal was an honor. My project, focused on building a GPT-based Chatbot Module, promised to be an exciting and challenging endeavor.

#### Community Bonding Period

The first month of GSoC, known as the community bonding period, was crucial for establishing a strong foundation for the project. I made it a point to build a good rapport with my mentor, who had extensive experience with Drupal. She guided me through the necessary documentation and explained the Drupal architecture in detail, which was invaluable for my project.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1718038212788/bc3cb213-a4c3-49ff-a7d6-3cee61b69661.png)

Official Drupal Profile

During this period, I set up my Drupal Account and Drupal Git profile, as Drupal uses a separate Git for all its projects. Setting up a local environment was my next task. Initially, I used XAMPP and MySQL, but I soon discovered DDEV, an amazing Docker-based tool that leverages Symfony and Drush to set up a local environment efficiently. Having a background in MLOps and DevOps, I was already familiar with Docker, which made this task smoother.

#### XAMPP and DDEV

XAMPP is an open-source platform that provides an easy-to-install distribution for Apache servers, MySQL, PHP, and Perl. It’s a great tool for beginners to set up a local web server environment quickly. However, for a more advanced and streamlined workflow, especially in collaborative and containerized environments, DDEV stands out.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1718038214623/ac817b31-87f2-4c2c-bee6-b7a2bb147980.png)

DDev: Docker-based PHP development enviroment

DDEV is a Docker-based tool designed for local PHP development environments. It uses containers to create isolated environments, making it easy to manage dependencies and configurations. This is particularly useful in complex projects like those built with Drupal, where consistency across different development environments is crucial.

#### Diving into Symfony

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1718038216206/3007c7c0-351d-4fe9-a660-966cd61c4dac.jpeg)

Symfony: Free and Open-source PHP web application framework

Understanding Drupal’s infrastructure was just the beginning. To effectively build the GPT-based Chatbot Module, I needed to get comfortable with Symfony, a PHP-based framework. Symfony provides reusable PHP components and a structured environment, facilitating the development of scalable web applications.

Here’s a simple comparison of Symfony with C++ through a basic example:

*Symfony Controller Example:*

// src/Controller/DefaultController.php  
namespace App\\Controller;  
use Symfony\\Component\\HttpFoundation\\Response;  
use Symfony\\Component\\Routing\\Annotation\\Route;  
  
class DefaultController  
{  
 /\*\*  
 \* @Route("/hello/{name}", name="hello")  
 \*/  
 public function hello($name) {  
 return new Response('<html><body>Hello '.$name.'!</body></html>');  
 }  
}

*Equivalent C++ example:*

#include <iostream>  
#include <string>  
void hello(const std::string& name) {  
 std::cout << "Hello " << name << "!" << std::endl;  
}  
int main() {  
 std::string name = "World";  
 hello(name);  
 return 0;  
}

**Comparison:**  
**\- Language Structure:** PHP is designed for web development with a focus on ease of use and speed, while C++ is a general-purpose programming language known for its performance and control over system resources.  
\- **Web Integration**: Symfony provides built-in functionalities to handle HTTP requests and responses, routing, and templating, making web development straightforward. In C++, web development would require additional libraries and more complex setup.  
**\- Development Speed:** Developing web applications in PHP/Symfony is generally faster due to its higher-level abstractions and extensive documentation. C++ requires more boilerplate code and detailed memory management.

#### Gearing Up for the Coding Period

Just before the coding period commenced on May 27th, we had an introductory meeting for all GSoC mentees and mentors. It was an enriching experience to meet other talented individuals and hear from Drupal’s CTO, Hestenet. His supportive words and openness to discuss our interests, including my passion for gaming and motorsport, were truly inspiring.

#### Looking Ahead

As I move forward into the coding period, I feel well-prepared and excited to tackle the challenges ahead. The community bonding period has been instrumental in equipping me with the knowledge and tools I need to succeed. I am eager to start coding and bring the GPT-based Chatbot Module to life, making a meaningful contribution to the Drupal community.

In conclusion, my journey so far with the Drupal Association in GSoC 2024 has been a blend of anticipation, learning, and excitement. I look forward to the months ahead and the opportunity to grow both personally and professionally through this incredible experience.