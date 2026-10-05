# ProblemSet1.java
package edu.monmouth.problemSet1;

import edu.monmouth.campusvehicle.CampusVehicle;

public class ProblemSet1 {
	
	public static void main(String[] args) {
	
		CampusVehicle myvehicle = new CampusVehicle("Car1", "Library", true);
	
		System.out.println("Vehicle 1");
		
		System.out.println("ID: " + myvehicle.getId());
		System.out.println("Location: "  + myvehicle.getLocation());
		System.out.println("Available: " + myvehicle.isAvailable());
		System.out.println();
	
		CampusVehicle vehicle2 = new CampusVehicle();
		CampusVehicle vehicle3 = new CampusVehicle();
	
	
		System.out.println("Vehicle 2");
		System.out.println("ID: " + vehicle2.getId());
		System.out.println("Location: "  + vehicle2.getLocation());
		System.out.println("Available: " + vehicle2.isAvailable());
		System.out.println();
	
		System.out.println("Vehicle 3");
		System.out.println("ID: " + vehicle3.getId());
		System.out.println("Location: "  + vehicle3.getLocation());
		System.out.println("Available: " + vehicle3.isAvailable());
		System.out.println();
	
	
		vehicle2.setId("Car2");
		vehicle2.setLocation("Spruce Hall");
		vehicle2.setAvailable(false);
    
		vehicle3.setId("Car3");
		vehicle3.setLocation("Edison");
		vehicle3.setAvailable(true);

		System.out.println("Vehicle 2");
		System.out.println("ID: " + vehicle2.getId());
		System.out.println("Location: " + vehicle2.getLocation());
		System.out.println("Available: " + vehicle2.isAvailable());
    	System.out.println();
    
    	System.out.println("Vehicle 3");
    	System.out.println("ID: " + vehicle3.getId());
    	System.out.println("Location: " + vehicle3.getLocation());
    	System.out.println("Available: " + vehicle3.isAvailable());
    	System.out.println();
	
	}
}