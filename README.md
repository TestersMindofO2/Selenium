# Selenium
Important codes and concepts related to Selenium using java.

Context-Click

public static void main(String[] args) throws AWTException, InterruptedException 
{
	WebDriver driver = new ChromeDriver();
	driver.get("...<URL>...");
	WebElement link = driver.findElement(By.<LocatorName>("<...Value...>"));
	Actions action = new Actions(driver);
	action.contextClick(link).perform();
}
