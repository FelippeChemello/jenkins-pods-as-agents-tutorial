# jenkins-pods-as-agents-tutorial
Jenkins Pods as Agents Tutorial Sample Project

This application prints a report on our metrics to show how amazing we are!

## Requirements:

Python >= 3.7
Node >= 16

## Report

The report can be generated by running the `report_generator.py` script:
```shell
./report_generator.py
```

Afterwards, it will be available in `resources/report.json`!

## Building and Running

Build the typescript:
```shell
npm run build
```

Make sure you generated the report like explained above before running!

Run the code:
```shell
npm run start
# or
node dist/index.js
```

## Docker

We have a Docker image! Build it using:
```shell
docker build -t super-report-printer:v0.1.0 .
```

Note: you also need the report above to have been generated!
