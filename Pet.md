public class Pet{

private String type;
private String name;

public String toString(){
  return "Name: " + name + ", type: " + type;
}
}

public class Dog extends Pet{

private String breed;

public Dog(String a, String b, String c){
  breed = a;
  super(b,c);
}
public String toString(){
  return super.toString() + " is a " + breed;
}

}
