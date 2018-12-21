# Security-Monitoring-Visualisation-System
This visualisation system is used to monitor the state and confirm the system's health running. All codes were wrote based on `D3.js version 3.x`.

## Introduction

This is a demo project of my work about how to visualize charts with pure d3. Current pages are loaded from one js file `integrateIndex.js`, all initialize, update and fake data generating methods are included. 

Each type of chart include `generate` and `redraw` methods, all 11 types of charts are defined in `methods` of Vue defining part. I will extract them out and then explain them briefly if someone are interested in this work.
 
## Component Methods

### Sensor Memory Monitor (Single Area Chart)

For example, you can find the function below in the file can use it to create a new instance.

```
function displayMem()
```

For complete usage of all kinds of charts, please see the complete [Docs](./DOC.md).

## DEMO
- [Weblink](https://mithileysh.github.io/Security-Monitoring-Visualisation-System/)

![DEMO 1](/assets/SSComponent-Intro-1.png 'DEMO 1')

![DEMO 2](/assets/SSComponent-Intro-2.png 'DEMO 2')

![DEMO 3](/assets/SSComponent-Intro-3.png 'DEMO 3')


Credits: Joe Jiang

