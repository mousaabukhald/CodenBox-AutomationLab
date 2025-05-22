
✨ Codenbox Automation Lab Practice Tests

This project features **automated test cases** built using **Selenium WebDriver** and **TestNG**, designed to practice interaction with diverse web elements hosted on:

➡️ [**Codenbox Automation Lab Practice Page**](#) *(Add actual URL)*

---

## 📄 Table of Contents

* [✅ Project Setup](#-project-setup)
* [🛠️ Technologies Used](#-technologies-used)
* [🧲 Test Cases Overview](#-test-cases-overview)
* [🔍 Detailed Test Cases](#-detailed-test-cases)
* [📜 Notes](#-notes)
* [🚀 Happy Testing](#-happy-testing)

---

## ✅ Project Setup

Follow these steps to run the tests:

1. **Install Java JDK (8+)**

   * [Download Java](https://www.oracle.com/java/technologies/javase-jdk8-downloads.html)

2. **Install Apache Maven**

   * [Download Maven](https://maven.apache.org/download.cgi)

3. **Set up Project**

   * Clone this repository or copy the Java source code
   * Ensure ChromeDriver is installed and path is set correctly

4. **Add Dependencies**

   * Include the following in your `pom.xml`:

     ```xml
     <dependencies>
       <dependency>
         <groupId>org.seleniumhq.selenium</groupId>
         <artifactId>selenium-java</artifactId>
         <version>4.19.0</version>
       </dependency>
       <dependency>
         <groupId>org.testng</groupId>
         <artifactId>testng</artifactId>
         <version>7.9.0</version>
         <scope>test</scope>
       </dependency>
     </dependencies>
     ```

5. **Run Tests**

   * From IDE (e.g., IntelliJ or Eclipse) or use:

     ```bash
     mvn test
     ```

---

## 🛠️ Technologies Used

* **Java 8+**
* **Selenium WebDriver**
* **TestNG**
* **Apache Maven**
* **Apache Commons IO**

---

## 🧲 Test Cases Overview

| Priority | Test Method                      | Description                     | Status     |
| -------- | -------------------------------- | ------------------------------- | ----------- |
| 1        | RadioButton()                    | Select a random radio button    | ❌ Disabled |
| 2        | Dynamic_Dropdown()               | Select a country from dropdown  | ❌ Disabled |
| 3        | SelectTag()                      | Select an option from dropdown  | ❌ Disabled |
| 4        | CheckBoxTag()                    | Select all checkboxes           | ❌ Disabled |
| 5        | SwitchWindow()                   | Switch between windows          | ❌ Disabled |
| 5        | SwitchTab()                      | Switch between tabs             | ❌ Disabled |
| 6        | AlertTest()                      | Handle alert and confirm popups | ❌ Disabled |
| 7        | TableTest()                      | Parse and print table data      | ❌ Disabled |
| 8        | HideAndShow()                    | Test hide/show textbox          | ❌ Disabled |
| 9        | EnableDisable()                  | Enable and disable textbox      | ❌ Disabled |
| 10       | MouseHover()                     | Hover and click actions         | ❌ Disabled |
| 11       | CalenderOpen()                   | Read calendar date values       | ❌ Disabled |
| 12       | Iframe()                         | Interact within an iframe       | ❌ Disabled |
| 13       | DownloadApkFileAndScreenShot()   | Download APK & take screenshot  | ✅ Enabled  |

---

## 🔍 Detailed Test Cases

### 1.RadioButton()

* Locate all radio buttons
* Select one randomly or by index

### 2.Dynamic_Dropdown()

* Type country prefix
* Use arrow keys and Enter to select

### 3.SelectTag()

* Interact with `<select>` tag
* Choose option by visible text

### 4.CheckBoxTag()

* Locate checkboxes
* Select all available options

### 5.SwitchWindow() & SwitchTab()

* Open new window/tab
* Switch context and return
* Print window/tab titles

### 6.AlertTest()

* Fill form
* Handle alert (Accept) and confirm (Dismiss)

### 7.TableTest()

* Find table
* Print rows with keyword “Selenium”

### 8.HideAndShow()

* Hide textbox
* Reveal it again

### 9.EnableDisable()

* Scroll
* Disable, re-enable, and enter text

### 10.MouseHover()

* Hover and click sub-menu items

### 11.CalenderOpen()

* Launch calendar
* Extract and display date info

### 12.Iframe()

* Switch into iframe
* Interact with elements inside

### 13.DownloadApkFileAndScreenShot()

* Download a file
* Take screenshot (with timestamp)
* Repeats 3 times using `invocationCount=3

---

## 📜 Notes

 ✅ Only DownloadApkFileAndScreenShot() is enabled by default
 ➕ To enable other tests, set enabled = true` in the @Test annotation
 🖼️ Screenshots are saved at: src/test/ScreenShot/
 🧩 Ensure ChromeDriver version matches your installed Chrome
 ⏱️ Use Thread.sleep() with care – consider WebDriverWait for better stability

---

## 🚀 Happy Testing!


