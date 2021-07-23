# regex_reference

```
string = c("G134_E001_AX","G22_E002_12", "G3END_E003_268")
## get the first part
sub("(^[^_]+)_(.*)$","\\1",string)
## get the second part
sub("(^[^_]+)_([^_]+)_(.*)$","\\2",string)
## get the third part
sub("(^[^_]+)_([^_]+)_([^_]+$)","\\3",string)
```
