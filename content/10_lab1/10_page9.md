+++
title = "View test results"
chapter = false
weight = 18
+++


## Test Results 

After the test completes you will see a new folder under `cfn-project` called **taskcat_outputs**
```
cfn-project
├── lambda_functions
├── templates
├── .taskcat.yml
└── taskcat_outputs/index.html < - (report)

```

To open `taskcat_outputs/index.html` in the AppStream browser, we've provided a simple 
shortcut that can be executed from the terminal:

```
open-taskcat-report
```

![fig1.3](/10_lab1/images/fig_lab1.3.png)

To see the test logs click the **View Logs** link
