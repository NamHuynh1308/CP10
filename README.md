# CP10
# 11/22/21
java
public class ABC {
	
	public void a() {
		b();
	}
	
	public void b() {
		c();
	}
	
	public void c() {
		System.out.println("Activation record on display");
	}

	public static void main(String[] args) {

		ABC abc = new ABC();
		abc.a();

	}

}
