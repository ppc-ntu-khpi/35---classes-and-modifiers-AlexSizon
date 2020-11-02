screen
https://drive.google.com/file/d/1Hmkhmr9DQNSqe4lvxgLeymkVOLkkOFn5/view?usp=sharing
adv screen 
https://drive.google.com/file/d/10F7k-UMCEO1QS04qZ5m4O24riT4lehq1/view?usp=sharing
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
