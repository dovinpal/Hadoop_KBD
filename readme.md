# Hadoop_KBD
## Knowbigdata.com

#!/usr/bin/python
import fileinput
for line in fileinput.input():
	for word in line.split():
		for letter in word.split():
			print word + "\t1"  
