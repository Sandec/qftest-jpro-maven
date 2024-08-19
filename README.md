# QF-Test Integration with JPro in Maven

This project provides a simple example on how to integrate [QF-Test](https://www.qfs.de/en/product/qf-test.html) with
[JPro](https://www.jpro.one) using Maven. It demonstrates the automation of testing JavaFX applications on both desktop
and web platforms across various operating systems and web browsers. The project is designed to be cross-platform
and supports execution on different environments, ensuring broad compatibility.

### Run the project

Browser:

```
mvn jpro:run
```

Desktop:

```
mvn javafx:run
```

### Run QF-Test

```
mvn test
```