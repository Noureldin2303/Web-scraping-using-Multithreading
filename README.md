# Web-scraping

**To extract data using web scraping with python using multithreading:**

1- Find the URL that you want to scrape

2-  Inspecting the Page

3- Find the data you want to extract

4-  Write the code

5-  Run the code and extract the data

6- Store the data in the required format
<br/><br/>
**Download Browser driver is using**

<table border="1" align="left">
<tbody>
<tr><td><strong>Chrome</strong>:</td>
<td><a href="https://sites.google.com/chromium.org/driver/">https://sites.google.com/chromium.org/driver/</a></td>
</tr>
</tbody>
</table>
<br/><br/><br/>

<ul>
  <li>Importing packages: from selenium import webdriver</li>
   <li>Create Chrome driver Instance: driver = webdriver.Chrome(r'Path in your computer where you have installed chromedriver')</li>
   <li>Fetch webpage: driver.get('URL')</li>
   <li>Parse webpage using Xpath: Data = driver.find_elements(By.XPATH,‘Xpath’)</li>
</ul>
