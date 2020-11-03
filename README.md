# screen
![](https://github.com/ppc-ntu-khpi/35---classes-and-modifiers-AlexSizon/blob/main/Solution/result.png)
# adv screen 
![](https://github.com/ppc-ntu-khpi/35---classes-and-modifiers-AlexSizon/blob/main/Solution/resadv.png)

```java
package test.domain;
public class Customer
{
   private int Id=1;
   private boolean IsNew=true;
   private float Total=1000;
   public void displayCustomerInfo()
   {
       System.out.println("Id "+Id);
       System.out.println("IsNew "+IsNew);
       System.out.println("total "+Total);
   }

    public Customer()
    {
    }
   
    public Customer(int id,boolean isNew,float total)
    {
        Id=id;
        IsNew=isNew;
        Total=total;
    }
    public int getId()
    {
        return Id;
    }

    public void setId(int Id)
    {
        this.Id = Id;
    }

    public boolean isIsNew()
    {
        return IsNew;
    }

    public void setIsNew(boolean IsNew)
    {
        this.IsNew = IsNew;
    }

    public float getTotal()
    {
        return Total;
    }

    public void setTotal(float Total)
    {
        this.Total = Total;
    }
   
}
```
