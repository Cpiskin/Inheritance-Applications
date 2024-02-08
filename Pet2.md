public class Pet2{

  private String name;
  private String type;

  public Pet(String a, String b){
    name = a;
    type = b;
  }

  public String toString(){
    return "Name: " + name + " Type: " + type;
  }

  public void eatFood(){
    System.out.println("The pet ate");
  }
}

public class Dog extends Pet{
  private String breed;

  public Dog(String t, String n, String b){
    breed = t;
    super(n,b);
  }
  public String toString(){
    return super.toString()
  }
  public void eatFood(){
    System.out.println("The pet ate");
  }
}
