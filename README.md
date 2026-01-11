class Student {

    // private data members
    private int id;
    private String name;

    // public setter method
    public void setId(int id) {
        this.id = id;
    }

    // public getter method
    public int getId() {
        return id;
    }

    // public setter method
    public void setName(String name) {
        this.name = name;
    }

    // public getter method
    public String getName() {
        return name;
    }
}

public class EncapsulationDemo {
    public static void main(String[] args) {

        Student s = new Student();

        s.setId(101);
        s.setName("Sakshi");

        System.out.println("ID: " + s.getId());
        System.out.println("Name: " + s.getName());
    }
}
