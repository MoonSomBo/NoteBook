# Notbook
#### Java
###### Extends
```java
  // Phone.java...................
    package ineritenceclassiphone;


public class Phone {
    float price;
    String IME,model,color;
    
    public Phone()
    {
        
    }
    public Phone(String IME, String model, String color, float price)
    {
     
     this.IME = IME;
     this.model = model;
     this.color = color;
     this.price = price;
    }
    public void showData()
    {
        System.out.println("ID      : "+ IME );
        System.out.println("Model   : "+ model );
        System.out.println("Color   : "+ color);
        System.out.println("Price   : "+ price);
        
    }
}
// Iphone java.....................
    package ineritenceclassiphone;

public class IPhone extends Phone {
        float price;
    public IPhone()
    {
        
    }
    public IPhone( String name, String gender, String color, float price)
    {
        super (name, gender, color, price);
        this.price = price;
    }
    public void showData()
    {
        super.showData();
        System.out.println("Price : "+ price);
        
    }
}

```
