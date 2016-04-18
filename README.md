# Xenonstack-Internship-Application
This repository contains the log file and data generated on my laptop using Elastic search and topbeat

For Elastic search:

cluster.name: my-application

node.name: node-azhar

For topbeat

input:

  # In seconds, defines how often to read server statistics
  
  period: 10

  # Regular expression to match the processes that are monitored
  
  # By default, all the processes are monitored
  
  procs: [".*"]

  # Statistics to collect (all enabled by default)
  
  stats:
    # per system statistics, by default is true
    
    system: true

    # per process statistics, by default is true
    
    process: true

    # file system information, by default is true
    
    filesystem: true

    # cpu usage per core, by default is false
    
    cpu_per_core: true
