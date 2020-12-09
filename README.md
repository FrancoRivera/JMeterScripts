# JMeterScripts

## Requirements

- Apache jMeter (5.3 tested) [Download link](https://jmeter.apache.org/download_jmeter.cgi)
- jmeter Plugins [Download and instalation](https://jmeter-plugins.org/install/Install/)
- jpgc - Standard Set (Plugin)


## Running the tests

Clone this repostiory

```bash
git clone git@github.com:FrancoRivera/JMeterScripts.git
```

Run load test by CLI

```bash
bin/jmeter -n -t ../JMeterScripts-master/tda-load-test.jmx -l ../output -e -o ../results
```

