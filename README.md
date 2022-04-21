# SEA8 - SpringQuest - IoC & DI

## Challenge: It's not rocket science.

Create a fork of the following repository: https://github.com/WildCodeSchool/quest-spring-injection.

Mission: You take over the development of a Harry Potter fan site to improve it. The site allows the administration of the characters of the series' universe.

The database is kept in-memory and uses an _ArrayList_. You don't need to set anything up. The data is therefore not persistent: it is normal that after a server reboot, the list returns to its default value.

> You're going to start by testing the site and see how it all works.

**Be sure to take a good look at all the classes in the repository before starting the challenge!**

1. Tests that the site is working properly
2. Change the class _WizardController_ in order to retrieve the _repository_ by Dependency Injection
3. Add the necessary annotation to _WizardRepository_ so _Spring Boot_ can inject it
4. Compile and test the site to make sure that everything is still working properly.
5. Commit your changes, push it to your GitHub repository and supply the URL

Validation criterias

- In the class _WizardController_ no instance of _WizardRepository_ is created: it is injected
- In the class _WizardController_ it's the interface _WizardDao_ that is requested to be injected, not _WizardRepository_
- In the class _WizardRepository_ the annotation necessary for the consideration by Spring Boot is present
- The application works correctly
