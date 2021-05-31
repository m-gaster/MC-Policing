# MC-Policing
Statistical Investigation of Montgomery County, MD, Police Department for Racial Bias 

Run *Modifications to Dataset*, then *Geo Analysis for Speeding*, then *Analysis*

When writing speeding tickets, police officers (not just in Montgomery County) routinely adjust cited speeds downward so as to reduce the driver's penalty. For example, an officer may pull me over at 12 mph over the speed limit but actually cite me at 9 mph over the limit, knowing that penalties are much harsher for drivers caught in [10-19] mph over the limit compared to those cited in the [0,9] range. While this leniency is nice, it's conducted at the officer's discretion, so patterns in who receives leniency and who doesn't may reveal biases (conscious and/or subconscious) in the MCPD. 

Much of this analysis is based on the ingenious methodology devloped by Goncalves and Mello in their paper "A Few Bad Apples? Racial Bias in Policing" (https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3627809). 

NOTE: Goncalves and Mello's analysis is conducted on data which identifies the officers and the drivers - but MC data does not identify the officer or driver. This makes most of their methodology inapplicable to MC (and many other municipalities).

The aim of this project is to develop statistical methods which can detect racial bias in a police force, given completely anonymized data. As of right now, this goal has not been realized - the data are simply too weak for statistical inference using the statistical methods I have employed.

My thanks to Dr. Bruno Jedynak for his contributions to this project, and to Dr. Jonathan Graves for his supervision in the initial development of this idea.

The main dataset used in this analysis is too large to upload here, but can be downloaded from https://data.montgomerycountymd.gov/Public-Safety/Traffic-Violations/4mse-ku6q
