//# MHS-Project

//The project stuff... Only Partially true.
import java.util.*;

public class Main {

	public static void main(String[] args) {

		//Some New Deals

		ArrayList<String> newDeals = new ArrayList<String>();
		newDeals.add("Agricultural Adjustment Act");
		newDeals.add("Civilian Conservation Corps");
		newDeals.add("Glass-Steagall Act");
		newDeals.add("Securities and Exchange Commission");

		System.out.println("There are " + newDeals.size() + " Franklin Deleanor Roosevelt's New Deal in this list. They are: ");

		for (String deals: newDeals) {
			System.out.println(deals);
		}

		//New Deal programs and definition

		HashMap<String, Integer> definition = new HashMap<String, Integer>();

		definition.put("Control Production of Agricultural products", 1931);
		definition.put("Young Men Sent to do work to help restore nature", 1932);
		definition.put("Federally insured bank deposits to prevent bank failures", 1933);
        definition.put("Regulated stock market", 1934);
                       

		for (String meaning: definition.keySet()) {
			
			if (definition.get(meaning) < 1934) {

				System.out.println(meaning + " started in " + definition.get(meaning) + ".");

			} else {

				System.out.println(meaning + " started in " + definition.get(meaning) + ".");

			}
		}

	}

}
