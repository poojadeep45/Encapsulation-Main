public class Main { 

    // Main method
    public static void main(String[] args) {
        // Create a Person instance using the default constructor
        Person person1 = new Person(); 
        System.out.println("Person1 Age: " + person1.getAge());
        
        // Create a Person instance using the parameterized constructor with a name and age
        Person person2 = new Person("Pooja", 18); 
    
        System.out.println("Person2 Name: " + person2.getName()); 
        System.out.println("Person2 Age: " + person2.getAge());  
        
        // Set a new name and age for person2
        person2.setName("Kiran"); 
        person2.setAge(20); 
        
        // Output the updated name and age for person2
        System.out.println("Updated Person2 Name: " + person2.getName()); 
        System.out.println("Updated Person2 Age: " + person2.getAge());
    }
}
