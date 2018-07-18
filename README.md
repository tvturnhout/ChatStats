# ChatStats

##### This is a repo for helping to analyse Facebook groupchats

![](https://github.com/tvturnhout/chatstats/blob/master/examples/example1.png)


This package will show some cool statistics for your Facebook groupchats.

# Requirements:

Python 2.7

To install a fresh environment through Anaconda run following commands:
```sh
conda create -n py27 python=2.7 anaconda
activate py27
```
# How to obtain chatlogs from Facebook

Download your facebook chatlog, you can find it in your Facebook general account settings right here:
![N|Solid](https://i.imgur.com/LrVWagZ.png)

You will find multiple html files with all your chatlogs. You can open them in a browser to look for the one you want to analyse.
Alternatively you could go to the group in messenger and copy the group-id there:

https://www.messenger.com/t/COPY_THIS_NUMBER

# Getting started:

Once you have located your groupchat file.html use the following commands in the terminal:
```sh
git clone https://github.com/tvturnhout/ChatStats
cd ChatStats
python main.py /path/to/html/file.html

```
You can see a short summary in the terminal and under the ./plot folder you will now find the different plots.

All credits go to conor-or, this is merely a wrapper to make the library work on European time formats.

