## QA Test Automation  

Automated test framework for functional, regression, and load testing. Primarily focused on web and API validation, leveraging Selenium, REST Assured, and JMeter for different test scenarios.  

### Features  
- Web UI testing with Selenium WebDriver  
- API automation with REST Assured  
- Performance testing using JMeter  
- Custom test reporting with Pytest HTML Reporter  
- CI/CD integration with GitHub Actions  

### Technologies  
- **Python 3.8+**: Core language  
- **Selenium WebDriver**: Web UI testing  
- **pytest**: Functional testing framework  
- **JMeter**: Load and performance testing  
- **Docker (Optional)**: Isolated test execution  

### Repository Structure  
```
QA-Test-Automation/
│── tests/
│   ├── ui_tests/           # Selenium-based UI tests
│   ├── api_tests/          # API request validation
│   ├── performance_tests/  # JMeter scripts
│── configs/                # Configuration files
│── logs/                   # Test execution logs
│── requirements.txt        # Dependencies
│── README.md               # Project documentation
```

### Setup & Execution  
1. Clone the repository  
   ```bash  
   git clone https://github.com/thomas-sdet-qa-test2/QA-Test-Automation.git  
   ```  
2. Install dependencies  
   ```bash  
   pip install -r requirements.txt  
   ```  
3. Run UI tests  
   ```bash  
   pytest tests/ui_tests/  
   ```  
4. Run API tests  
   ```bash  
   pytest tests/api_tests/  
   ```  
5. Run performance tests  
   ```bash  
   jmeter -n -t tests/performance_tests/test_plan.jmx  
   ```  

### Notes  
- For browser testing, ensure ChromeDriver is installed.  
- API tests require environment variables for authentication tokens.  
- Performance testing requires JMeter CLI setup.  

### Contribution  
Submit a pull request with well-documented changes.
