# Lab8-Starter

[Deployed Page](https://kevku.github.io/CSE110-Lab8-Starter/)

## Explore
Graceful Degredation and Service Workers are related because not only do service workers improve performance, it also helps with lower end devices and slow network. Suppose we have a script that does not use service workers and contains a lot of network calls. Additionally it is related to graceful degredation if the browser supports service workers, it will benefit the users, otherwise those who don't support this feature won't lose out on much. In the best possible environment with high end devices and the fastest speeds, the script may run fine, but lower end devices and slower networks will hinder the website's performance. Having service workers can help take off the load of the script (due to single-threadedness) by running some code that are not network requests while having the requests running in the background.