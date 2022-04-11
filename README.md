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

public class SingleInheritance {

	public static void main(String[] args) {
	   Chicken f=new Chicken();
	   Food f1=new Food();
	  f1.tasty();
	  f.spicy();
       
	}

}

