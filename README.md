# U20241222859
taller de POO
//clase papel
public class Papel {
    private String color;
    private int grosor;

    // Constructor
    public Papel(String color, int grosor) {
        this.color = color;
        this.grosor = grosor;
    }

    // Getters
    public String getColor() { return color; }
    public int getGrosor() { return grosor; }

    // Setters
    public void setColor(String color) { this.color = color; }
    public void setGrosor(int grosor) { this.grosor = grosor; }

    public static void main(String[] args) {
        Papel papel = new Papel("Blanco", 2);
        System.out.println("Color: " + papel.getColor());
        System.out.println("Grosor: " + papel.getGrosor());
    }
}
