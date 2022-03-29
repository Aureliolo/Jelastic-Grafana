# Grafana JPS to install Enterprise or OSS Edition

:warning: :warning: :warning: :warning: :warning:  
THIS IS NO LONGER MAINTAINED  
NEW VERSION WHICH INCLUDES PROMETHEUS: https://github.com/Aureliolo/Jelastic-Grafana-Prometheus  
:warning: :warning: :warning: :warning: :warning:  

When you launch the JPS you have 2 Options, version and if you want a public IP + Let's Encrypt

On the version tab you can select between Enterprise and OSS Edition, see:
https://grafana.com/blog/2019/09/04/how-we-differentiate-grafana-enterprise-from-open-source-grafana/

You also have the option to install a public IP plus let's encrypt for use with your own Domain.
If you don't select this option it will enable Platform SSL and you wil have to use the jelastic Environment URL.

# Installation
Simply import this link using the Jelastic JPS Import function:
```
https://raw.githubusercontent.com/Aureliolo/Jelastic-Grafana/main/main.jps
```

Or copy the content of main.jps into the import window.


![Interface](images/interface.png?raw=true)
