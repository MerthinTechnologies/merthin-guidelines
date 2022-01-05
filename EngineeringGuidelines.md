# Engineering Guidelines

## General

1. Take specs as exact and implement them as described.
1. Attention to details, not just to the code but to all visual elements, automated processes, written communication with clients, etc.
1. Test your work before sending it to review. Explore the edge cases, test all possible states of whatever piece you're developing and don’t wait for others to find your mistakes.
1. Use intention-revealing names. Choosing good names takes time but saves more than it takes. This applies not only to code but to any referenceable abstraction in your workflows. ([Clean Code](https://enos.itcollege.ee/~jpoial/oop/naited/Clean%20Code.pdf), Chapter 2)
1. Automate everything that needs to be automated in advance. Avoid doing things manually over and over again.
1. Don't commit with goals you can't deliver.
1. Practice extreme ownership. It's ok to ask for help but you're solely responsible for your results.
1. Solve one task at a time.

## Communication

1. Use [ubiquitous language](https://martinfowler.com/bliki/UbiquitousLanguage.html#:~:text=Ubiquitous%20Language%20is%20the%20term,language%20between%20developers%20and%20users.&text=Evans%20makes%20clear%20that%20using,and%20hence%20the%20domain%20model.) with clients and with the rest of the team.
1. Report async progress updates.
1. Communicate your blockers in async channels as soon as they emerge, along with its description, what you've tried and what you are going to try next. Help may soon arise, but try to be autonomous working with the available resources until someone can give you a hand.
1. Whenever possible, take a default action while waiting for async input. Communicate your default action on the appropriate async communication channel.
1. Use a clean handoff approach, add links and snips to clarify yourself in async communications.

## Code Principles

1. [Single-responsibility](https://blog.cleancoder.com/uncle-bob/2014/05/08/SingleReponsibilityPrinciple.html)
1. [Open–closed](http://blog.cleancoder.com/uncle-bob/2014/05/12/TheOpenClosedPrinciple.html)
1. [Liskov-substitution](https://en.wikipedia.org/wiki/Liskov_substitution_principle)
1. [Interface segregation](https://en.wikipedia.org/wiki/Interface_segregation_principle)
1. [Dependency inversion](https://en.wikipedia.org/wiki/Dependency_inversion_principle)
1. [Separation of concerns](https://en.wikipedia.org/wiki/Separation_of_concerns)

## Code

1. Leave the campground cleaner than you found it. Avoid leaving commented-out code, debug statements, unused imports, etc.
1. Use clean code to express yourself instead of comments. The proper use of comments is to compensate for our failure to express ourself in code. If you need to add a comment, check if you can refactor it with better names or if you could restructure things in a way where [each piece screams its intention](https://blog.cleancoder.com/uncle-bob/2011/09/30/Screaming-Architecture.html) by itself. ([Clean Code](https://enos.itcollege.ee/~jpoial/oop/naited/Clean%20Code.pdf), Chapter 4)
1. Choose a single name per concept and name each concept in a single way.
1. Write small functions, make each function do one thing well. ([Clean Code](https://enos.itcollege.ee/~jpoial/oop/naited/Clean%20Code.pdf), Chapter 3)
1. Write code with low coupling and high cohesion.
1. Practice consistency, choose a single way to do something and stick to it throughout the entire project.
1. DevOps go first, avoid using single environments, manual deployments and hardcoded configurations.

## Design

1. Design and design implementation will match when placed side-by-side.
1. Prefer relative units in CSS
