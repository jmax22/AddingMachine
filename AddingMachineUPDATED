package cse360assignment02;

public class AddingMachine {
	private int total;
	private String history = "0";
	  
	  public AddingMachine () {
	    total = 0;  // not needed - included for clarity
	  }
	  /* returns the total */
	  public int getTotal () {
	    return total;
	  }
	  /* adds to the total */
	  public void add (int value) {
		  total = total + value;
		  history = history + " + " + value;
	  }
	  /* subtracts from the total */
	  public void subtract (int value) {
		  total = total - value;
		  history = history + " - " + value;
	  }
	  /* prints the history total i.e 0 + 4 - 2 + 5 */
	  public String toString () {
	    return history;
	  }

	  public void clear() {
	  }

}
