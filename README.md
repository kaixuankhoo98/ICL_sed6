# Creation and Dependency
In this coursework for Software Engineering Design, I demonstrate the use of a builder class to allow step-by-step construction of objects. I also demonstrate the implementation of a singleton, in which only a single instance of an object is created and all future calls to that object must call getInstance(). Included in the repository I demonstrate how I use the dependency inversion principle and made the BritishLibraryCatalogue class implement an interface Catalogue, so that the query can be reused and extended in the future. Additionally, I use JMock to test said objects in isolation using mock objects instead of a real catalogue. 