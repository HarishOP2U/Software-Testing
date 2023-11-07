# Automation Testing

Performing the testing with the help of tools is known as Automation Testing.

-> Challenges in Manual testing 

Re-testing and regression testing.

it is very exhausting and time-consuming, and more human effort is needed in manual testing.

initially, Automation was used to overcome these 2 challenges


# Selenium

-> Selenium is Web Based Automation tool.

-> Selenium is collection of multiple components( IDE, WebDriver, Grid)
   - RC is not used anymore.
     
### Advantages

1. Open source tool and free.
   - open source means everyone can customize and add new features.
   - companies who do not wish to spend their budget use this as it's free.
2. Supports multiple Operating Systems.
3. Supports multiple Browsers.
4. Supports multiple Languages( Java, Python, C#, Ruby, Javascript etc..).
5. Integrate third-party tools into selenium.
   

### Disadvantages

1. Cannot support windows based applications( Autoit, Sikuli, Robot API).
2. Reporting is not supported( TestNG, Extent reports).
3. Cannot support Excel files( That's why we use Apache POI).
4. Graphs and captcha can't be automated.
___

## Seleniunv WebDriver

1. WebDriver is one of the component in selenium.
2. WebDriver is an java interface.

SearchContext(I): is the first interface

|

|

WebDriver(I)

- Firedoxbrowser ---- FirefoxDriver class
- Chrome browser ---- ChromeDriver class
- Edge browser ----- EdgeDriver class
- IE ---- InternetExplorerDriver (deprecated)

3. WebDriver is an API(Application programing interface)

Request --> API --> Response

>> Selenium is not a single tool, it contains multiple compoments; WebDriver, IDE, Grid.

### Setup Webdriver in Eclipse

1. Selenium client Library. (.jar)

   - client Library --> Collection of jar files contains so many no. of classes + methods.
   
2. Browser Specific drivers. (.exe)

- every browser have there own specific browsere specific driver.

4. Browsers (chrome, edge, firefox..)

## Selenium WebDriver Script

1. Launch browser
2. open url
	
 https://opensource-demo.orangehrmlive.com/

3. Provide username  - Admin
4. Provide password  - admin123
5. Click on Login button 
6. Verify the title of dashboard page   

 Exp title : OrangeHRM

7. close browser
   
--->

--->

//1) Launch browser

//webDriver drive=new ChromeDriver();

//WebDriver driver =new ChromeDriver();

//2) Open URL on the browser

Thread.sleep(5000) // 5sec in cae the browser is slow to load we use it 

driver.get("URL");

//3)Provide username - Admin

webElement ext = driver.findElement(By.name("username"));

text.sendKeys("Admin");

                        OR

driver.findElement(By.name("username)).sendKeys("Admin");

//4) Provide password - admin123

driver.findElement(By.name("username)).sendKeys("admin123");

>> xpath : address of the elements

//5) click on Login button

driver.findElement(By.xpath(" paste xpath here"))

//6) verify the title of dashboard page

String actual= driver.getTitle();

String expected= "OrangeHRM";

if(actual.equals(expected))

sout("test passsed")

else

sout("failed")

//7) close browser

driver.close();



