- 👋 Hi, I’m @akashkanabar1998
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
akashkanabar1998/akashkanabar1998 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
package Testcase;

import org.openqa.selenium.firefox.FirefoxDriver;

public class tc_001 {
	
	public static void main(String [] args )
	{
		System.setProperty("webdriver.gecko.driver", "C:\\Users\\AKASH KANABAR\\Downloads\\Automation\\firefox driver\\geckodriver-v0.31.0-win64");
		FirefoxDriver driver = new FirefoxDriver();
		driver.get("https://www.facebook.com");
		//driver.findElementById("email").sendKeys("8866998933");
		//driver.findElementById("pass").sendKeys("8866998933A@k");
		driver.findElementById("u_0_1").click();
		driver.quit();
		
	}

}
