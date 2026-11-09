https://www.youtube.com/watch?v=IrqIJ0yKNr8



https://www.youtube.com/watch?v=5KtEX26Gi\_g













Encapsulation: we can use in POM: keeping webelements as private inside the page class and we expose only methods to interact them.

Abstraction: wrapping the method like click(), sendkeys(), getText(), test cases only call these methods without worry about the internal implementation.

Inheritance: in a base page we can setup the webdriver setup and pagefactory steup we can inheritance in multiple pages, homepage, loginpage, we can also keep the waits.

Polymorphism: we have used in payment methods to use for different payments with same method and class with interface payment





Interface: Selenium webdriver itself an interface we can use it implementinons like chromedriver, firefoxdriver





Framework: i have worked on hybrid framework which is the combination of Data driven and POM, Tech stack: i our framework we uses selenium webdriver to Java as language, TestNG for test management and maven for build management and git for version control, i followed by POM model where webpage has it own page calss, test data is maintinaing is pserate class Xcel or json, apachi poi, and i also the worked on jenkins for CI/CD, challenges that i have face while doing the automation that are flaky test cases using dynamic webelemtns, i resolved that implementing with explicit wait and cutoms wait instead of relying on thread.sleep.





I always prefer relative x-path using sibling or parent child relationship, because it's more robust and maintainable than absolute xpath which is brittle and breaks with minor layout changes.

