# Single-Inheritance

class Food{

	void tasty()
	{System.out.println("tasty..");
	}
}
class Chicken extends Food{
	void spicy() 
	{System.out.println("spicy....");
	}
}
class Dhal extends Food{
	void Boring()
	{System.out.println("Boring....");
	
}
}
public class SingleInheritance {

	public static void main(String[] args) {
	   Chicken f=new Chicken();
	   Dhal f1=new Dhal();
	   Food f2=new Food();
	   f.spicy();
	   f1.Boring();
       
	}

}
