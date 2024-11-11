class Gadget {
    private String brand;
    private String model;
    private double price;

    public String getBrand() {
        return this.brand;
    }

    public void setBrand(String brand) {
        this.brand = brand;
    }

    public String getModel() {
        return this.model;
    }

    public void setModel(String model) {
        this.model = model;
    }

    public double getPrice() {
        return this.price;
    }

    public void setPrice(double price) {
        this.price = price;
    }

    public void printDetails() {
        System.out.println("Brand: " + getBrand());
        System.out.println("Model: " + getModel());
        System.out.println("Price: " + getPrice());
    }
}

// Класс Smartphone, который наследует от Gadget
class Smartphone extends Gadget {
    private int memorySize;
    private boolean hasDualSim;

    public int getMemorySize() {
        return this.memorySize;
    }

    public void setMemorySize(int memorySize) {
        this.memorySize = memorySize;
    }

    public boolean isHasDualSim() {
        return this.hasDualSim;
    }

    public void setHasDualSim(boolean hasDualSim) {
        this.hasDualSim = hasDualSim;
    }

    @Override
    public void printDetails() {
        super.printDetails();
        System.out.println("Memory Size: " + getMemorySize());
        System.out.println("Has Dual SIM: " + isHasDualSim());
    }
}


class Laptop extends Gadget {
    private String processorType;
    private int ramSize;

    public String getProcessorType() {
        return this.processorType;
    }

    public void setProcessorType(String processorType) {
        this.processorType = processorType;
    }

    public int getRamSize() {
        return this.ramSize;
    }

    public void setRamSize(int ramSize) {
        this.ramSize = ramSize;
    }

    @Override
    public void printDetails() {
        super.printDetails(); // Вызываем метод родительского класса
        System.out.println("Processor Type: " + getProcessorType());
        System.out.println("RAM Size: " + getRamSize());
    }
}

class Tablet extends Gadget {
    private float screenSize;
    private String operatingSystem;

    public float getScreenSize() {
        return this.screenSize;
    }

    public void setScreenSize(float screenSize) {
        this.screenSize = screenSize;
    }

    public String getOperatingSystem() {
        return this.operatingSystem;
    }

    public void setOperatingSystem(String operatingSystem) {
        this.operatingSystem = operatingSystem;
    }

    @Override
    public void printDetails() {
        super.printDetails();
        System.out.println("Screen Size: " + getScreenSize());
        System.out.println("Operating System: " + getOperatingSystem());
    }
}

public class Main {
    public static void main(String[] args) {
        Gadget gadget1 = new Gadget();
        gadget1.setBrand("Apple");
        gadget1.setModel("iPhone 13 Pro Max");
        gadget1.setPrice(1200);
        
        Smartphone smartphone1 = new Smartphone();
        smartphone1.setBrand("Samsung");
        smartphone1.setModel("Galaxy S22 Ultra");
        smartphone1.setPrice(1400);
        smartphone1.setMemorySize(256);
        smartphone1.setHasDualSim(true);
        
        Laptop laptop1 = new Laptop();
        laptop1.setBrand("Dell");
        laptop1.setModel("XPS 15");
        laptop1.setPrice(2000);
        laptop1.setProcessorType("Intel Core i9");
        laptop1.setRamSize(32);
        
        Tablet tablet1 = new Tablet();
        tablet1.setBrand("Microsoft");
        tablet1.setModel("Surface Pro X");
        tablet1.setPrice(1000);
        tablet1.setScreenSize(12.3f);
        tablet1.setOperatingSystem("Windows 11");
        
        System.out.println("\nGadget:");
        gadget1.printDetails();
        
        System.out.println("\nSmartphone:");
        smartphone1.printDetails();
        
        System.out.println("\nLaptop:");
        laptop1.printDetails();
        
        System.out.println("\nTablet:");
        tablet1.printDetails();
    }
}
