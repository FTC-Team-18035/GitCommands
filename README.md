Only use a hard reset if everything is bad and you need to discard everything. 

Use:

```git log```

to find the the commit you want to roll back to and 

Use

```git reset --hard checksum```

The checksum is the weird numbers and letters that look randomly generated after the word "commit" in the log

This will only make a change on you local computer's repo. 

To push this reset to github you'll use 

```git push -f origin master```

Please reach out to me if you need to do this and I can supervise. 
