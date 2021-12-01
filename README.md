# CP10
## 11/22/21
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

java
public class factorial {
	
	public static int factorial(int n) {
		if (n < 0) return 0; // feels good at the moment
		if (n == 0) return 1;
		return n * factorial(n - 1);
	}

	public static void main(String[] args) {
		System.out.println(factorial(8));
		

	}

}

java
import java.io.File;

public class FileSizeSum {

	public static void main(String[] args) {
		String directory = null;
		
		int s = getSize(directory);

	}

	private static int getSize(String directory) {
		// check if file -> BASE CASE
		File file = new File(directory);
		
		
		// if directory call getSize()
		return 0;
	}

}


## 11/29/21

### Technology
#### _Making, usage of, knowledge of
#### +tools, machines, techniques, crafts, systems
#### _Methods of organization to solve problem or perform a specific function
#### _Changes society for better and for worse
#### _Responsibility of Computer Scientists to create/use technology ethically
#### _Problems: law lags progress in technology
#### +Less problematic for most engineers because their laws-just like their disciplines - are older

### Good side of technology
#### _Distribute research groups:
#### +Researchers here and in Chicago work on the same problem applied to the same boot
#### _General
#### +eBay-selling and buying used goods
#### +Facebook-social connections
#### +Googles-finding information
#### +Cell phones-safety, social connections, pictures
#### +Online retailers-more variety, lower prices (Amazon?)
#### +Distance learning-accessibility
#### +Robots performing boring and dangerous jobs

### Bad side of technology
#### _Cyber stalking, cyber bullying
#### _Craigslist killings
#### _Spam
#### _Potential future employees checking Facebook, Twitter, etc.
#### _Differential ability to fully access internet
#### _Identity theft
#### _Loss of non-work life
#### _Loss of small businesses from towns
#### _Loss of privacy
#### _Group me, Respondus based exams, zyBooks based exams

### Professional Ethics
#### _Primarily a problem solving process
#### 1. Recognize that a situation has ethical implications
#### 2. Generate possible solutions
#### 3. Evaluate according to ethical theories 

### Analyze
#### _Analyze how the Code of Ethics can be applied to the problem
#### Evaluate
#### _Do you think we may have future cases that may depend on our current problem ?, etc.
#### Deontological Theories (non-consequentialist)
#### _We judge: The act itself, As well as the choice to act


## 12/1/21

### Consequentialist Theories
#### Consequentialist Theories
#### _The outcome of the act is the important thing
#### _Utilitarian is one branch of this type of theory
#### +Do the greatest good for the greatest number of people

### Natural Rights
#### _Life, liberty, property
#### _Process is important- actions are ethical if they involve
#### +Voluntary interaction
#### _Exchanges made knowingly and freely

### Negative vs Positive Rights
#### _NR (liberties): Rights of nointerference from others 
#### _PR (claim rights): imposes an obligation on others to provide the right
#### *Many issues can be viewed from both perspectives

### Law and ethics
#### _Not all laws are ethical
#### +Seizure of property
#### +Slavery
#### +Women and slaves not permitted to own property or to vote
#### _Categories of laws (not exclusive)
#### +Enforce ethical rules
#### +Rules for interacting with strangers
#### +Laws created by political influence – often not ethical..
#### _Breaking the law is not necessarily unethical
#### +If can, however, have consequences

### Other issues
#### _Just because someone is harmed, does not make an act wrong
#### _Just because an act is wrong does not imply that harm has been done

### Privacy
#### Modern perspectives
#### +Freedom from intrusion
#### +Control of information about oneself
#### +Freedom from surveilance

### Loss of privacy
#### _Many avenues
#### +Intentional use of personal information
#### +Unauthorized use/release
#### +Theft
#### +Unintentional leakage
#### +Data collection
#### +By choice


