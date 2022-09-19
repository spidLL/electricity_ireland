# Electricity Ireland

This is an example notebook to calculate and compare electricity cost of Irish Electricity provider.

It works for customer with SMART METER:
* You need to download the CSV file with the usage (it should be last 2 years)
* Configure the plan you want to compare

Requirements: 
1. You need to be able to install and run Jupyter notebook. You can use Anacoda, it should make it easier. I won't provide any support in this regards.
2. pandas (which needds matplotlib, numpy and a bunch of other stuff. Hopefully will be installed manually)

DISCLAIMER:
USE IT AT YOUR OWN RISK.

NOTE:
1. there's no support for difference in day prices. So, for example, you cannot exclude peak price from weekend, or add the "free energy" on Saturday/Sundays. I'll add it later
2. I tested it only on Electric Ireland format. I hope it's the same for other provider. I'm adding a sample CSV for comparison.
3. This does not support the standing charge. So factor it yourself.
