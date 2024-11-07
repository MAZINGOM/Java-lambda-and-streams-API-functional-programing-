## What is a Functional Interface

### An interface which contains only one abstract method 

public interface Messenger {

void notify(String msg, int count);

}


## Can be functional or Generic 


@FunctionalInterface
public interface<T,R>{

R apply(T param);

}

@FunctionalInterface

public interface Another{
String apply(String param);
}