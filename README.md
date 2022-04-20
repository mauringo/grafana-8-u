# Snap porting for Grafana 8

Check the original repo: https://github.com/grafana/grafana

## Changes 
This version of Grafana is created directly from the official grafana .deb file and include the possibility to be fully embedded in 
the ctrlX automation stack. https://github.com/boschrexroth


## Building 

1. get the recipe `git clone https://github.com/mauringo/grafana-8-u.git`
2. `cd grafana-8-u`
3. `snapcraft build`
4. `sudo snap install snapname.snap --dangerous`
