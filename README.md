# jMeter- Load and Performance Testing

> _JMeter is an open-source tool for load and performance testing, simulating multiple users to analyze system behavior under stress. It helps identify bottlenecks, measure response times, and ensure application scalability._

## GUI MODE - jMeter App
In my project on JMeter for load and performance testing, I worked in **GUI mode**, creating a **test plan** with a **thread group** to simulate multiple users. I configured **HTTP requests** using IP-based testing, set user load parameters (**threads, loop count**), and saved the test as a **.jmx file**. Additionally, I utilized **listeners**, including **View Results Tree**, to collect and analyze performance metrics.
#### Test-Plan 
![image](https://github.com/user-attachments/assets/4472f1fd-9540-4be0-a014-4f85e6d46d30)
#### Http Request 1 – Simplii-homepage
![image](https://github.com/user-attachments/assets/3ede8e99-3d16-434b-9924-83fa43c8944e)
#### Http Request 2 – Simplli-resources
![image](https://github.com/user-attachments/assets/028ecc32-0e98-477b-9d09-8c55b0cbbf84)
#### Results Tree – Listening output
![image](https://github.com/user-attachments/assets/300d5d1c-42c8-4701-802d-c8b94499e0f5)



## non-GUI MOD - command line
In my project on JMeter for load and performance testing, I also worked in **non-GUI mode** using the **command line** for efficient test execution. I used the following command to run the test:  

```bash
C:\apache-jmeter-5.4.3\bin>jmeter -n -t \apache-jmeter-5.4.3\backups\LoadTesting-Simplii-000001.jmx -l \apache-jmeter-5.4.3\backups\LoadingResults.csv
```

This executed the test plan in **non-GUI mode**, generated a **summary report**, and saved the results in a CSV file. The command output provided real-time performance data, including throughput, response times, and error rates, confirming the success of the load test.
#### Command line 
![image](https://github.com/user-attachments/assets/95d8699b-2ef0-49f4-a9ad-6cf473aa8b41)
#### Results
![image](https://github.com/user-attachments/assets/5e748d6a-d30c-43fe-adfc-6e2cdccba14f)
