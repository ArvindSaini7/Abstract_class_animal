# Abstract_class_animal
//package Abstract_class_only;

public abstract class Animal {
	public abstract void sound();

}
//package Abstract_class_extends;
//import Abstract_class_only.Animal;
public class Tiger extends Animal {
	public void sound() {
		System.out.println("tiger sound");
	}

}

//package Abstract_class_extends;
//import Abstract_class_only.Animal;
public class Lion extends Animal {
	public void sound() {
		System.out.println("lion Sound");
		
	}
	

}

//package main_class;
//import Abstract_class_only.Animal;
//import Abstract_class_extends.Lion;
//import Abstract_class_extends.Tiger;
//public class Animal_main {

	    public static void main(String[] args) {
	        
	        Animal lion = new Lion();
	        Animal tiger = new Tiger();

	
	        lion.sound(); 
	        tiger.sound(); 
	    
	}
}


