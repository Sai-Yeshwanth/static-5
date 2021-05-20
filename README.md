public class Jala {
	static int id=10;
	static String name ="Sai";
	static void getdetails()
	{

		System.out.println(name + " "+id);
	}
	void call()
	{
		getdetails();
	}
	public static void main(String[] args) {
		Jala j = new Jala();
		j.call();
	}
}
